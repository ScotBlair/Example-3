EXAMPLE 3: MOBILE BANKING/ONLINE SYSTEM DOWN<br />

<br />- Intake<br />
Karen Jones sent in a ticket saying the Mobile Bank system is down and that customers are receiving an Error 404 message when trying to visit the web site.

<br />- Assignment and Communication<br />
System Administrator Scot Blair looks over the ticket and decides to address the issue himself.  He upgrades the ticket priority to "Emergency" due to its business impacting nature, changes the SLA plan to Sev-A, and files it under the "Business Critical Outage" help topic.  Scot then reaches out to Karen to express sympathy for the situation, and explains that a server recently failed and is currently being replaced, but shouldn't take too long to do.<br />

Once the new server is installed, Scot contacts Karen again to let her know, so that she may try revisiting the website.  Karen responds by saying the error message is gone, but the site still fails to load, so Scot asks her to try other web pages as well.  Karen says that the mobile website is the only one that seems to not be working.<br />


<br />- Working the Issue<br />
Scot remembers that a new server carries a new IP address, and the website is likely still trying to connect to the old one.  Scot gets the IP address of Karen's pc and Remote Desktop's in.  He opens up Command Prompt and types in "ipconfig /displaydns" just to satisfy his curiosity.  

<br />- Resolution<br />

