EXAMPLE 3: MOBILE BANKING/ONLINE SYSTEM DOWN<br />

- Intake<br />
Karen Jones sent in a ticket saying the Mobile Bank system is down and that customers are receiving an Error 404 message when trying to visit the web site.

- Assignment and Communication<br />
System Administrator Scot Blair looks over the ticket and decides to address the issue himself.  He upgrades the ticket priority to "Emergency" due to its business impacting nature, changes the SLA plan to Sev-A, and files it under the "Business Critical Outage" help topic.  Scot then reaches out to Karen to express sympathy for the situation, and explains that a server on his end recently failed and is currently being replaced, but shouldn't take too long to do.

  Once the new server is installed, Scot contacts Karen again to let her know, so that she may try revisiting the website.  Karen responds by saying the error message is gone, but the site still fails to load, so Scot asks her to try other web pages as well.  Karen says that the mobile website is the only one that seems to not be working.

- Working the Issue<br />
Scot remembers that a new server carries a new IP address, and the website is likely still trying to connect to the old one.  Scot gets the IP address of Karen's pc and Remote Desktop's in.
<br />![VirtualBox_Windows 10_24_06_2024_09_30_40](https://github.com/ScotBlair/Example-3/assets/171102023/97fe4ec6-ce40-4f68-837b-c2a4e4e18840)<br />

  He opens up Command Prompt and types in "ipconfig /displaydns" to confirm his hunch.
<br />![1](https://github.com/ScotBlair/Example-3/assets/171102023/310101c7-cf44-4a41-90ff-43c6c34b34f2)<br />

  After noting the listed DNS address, he types in "ipconfig /flushdns" to flush the local DNS.
<br />![VirtualBox_Windows 10_24_06_2024_09_34_28](https://github.com/ScotBlair/Example-3/assets/171102023/68dec572-6fa2-4354-b5ad-9ec1b2a7e1e3)<br />

- Resolution<br />
Scot contacts Karen once more to ask her to try the website again.  Karen responds by saying that the website is back online.  Scot thanks her for contacting IT support, then closes the ticket.
<br />![Screenshot_24-6-2024_94128_localhost](https://github.com/ScotBlair/Example-3/assets/171102023/6f3cfd5b-aea4-440b-94fb-63fddcc7c54a)<br />

