cfPostMarkApp
=============

A ColdFusion Component for interacting with the PostmarkApp API.

The cfPostMarkApp service is used to send E-mail through the PostMarkApp.com API rather than through cfmail.

PostMarkApp (http://postmarkapp.com/) is a web based email service provider. E-mail is handled through a REST request to their API, as opposed to standard SMTP protocols. It includes message identification, bounce back APIs and webhooks to track mail delivery.

This version features the capability to add file attachments to outgoing E-mail, including multiples. Mime-types are determined 'on the fly'. There is no limit to the number, type or size of attachments, other than those restrictions imposed by PostMarkApp.

This app extends earlier work by Jonathan Lane and Robert Rawlins, with thanks to Ben Nadel.

Further instructions and information are available in the header of the cfc. An example file is included in the zip.

Requirements:
An account with PostMarkApp.com and ColdFusion 8+ 
