# zMail
Rexx program to send emails from z/OS batch jobs supporting html tags and file attachments. This is for example useful for sending automated reports generated in a previoius JCL step. 
The logic is not using NJE nor requireing any SMTP task running on z/OS but are using TCP sockets to connect directly to any SMTP server/gateway to deliver emails. 
