# my-microsoft365-prep
This project is done to learn admin skills in the M365 ecosystem- sharepoint, one drive, outlook, entra ID. The first thing I wanted to learn was how to increase productivity in Outlook.

# Microsoft Outlook

## Shared mailboxes
You can create a shared mailbox in outlook and add members to it. Here i created an itsupport mailbox so that incoming tickets are easier to track:

<img width="539" height="415" alt="Screenshot 2026-03-31 005820" src="https://github.com/user-attachments/assets/fae6f9cd-5306-4bc5-b838-40695acc0405" />


In outlook once you are added to a shared mailbox you can see it by clicking profile> add a mailbox
I verified the mail is coming in
<img width="700" height="309" alt="project1" src="https://github.com/user-attachments/assets/1f361bdc-bc05-47a6-a9e6-0ab1cc093a03" />

## Distribution Lists

A distribution list provides a way to send mail to one address and have everyone in that list receive it. 
For example, if i create an all managers list communication that needs to be sent to managers can be managed through a distribution list. Go to admin. exchange > groups > group type > dynamic distribution list
<img width="637" height="110" alt="Screenshot 2026-05-10 130859" src="https://github.com/user-attachments/assets/f78a7d98-3883-4dfe-86ac-bce5e7078782" />




<img width="618" height="412" alt="Screenshot 2026-05-10 131825" src="https://github.com/user-attachments/assets/ec51769d-b81f-4352-b7d9-fa2e5b2b7c77" />

## Retaining mailboxes
Problem: When a user leaves an organization it is important to be able to retain their emails and block access. For example, if Mike in Sales leaves
the org we need to protect their data.

Solution: I will change Mikes mailbox into a shared mailbox, give Mikes manager permission. Deleting licenses for Mike is okay, but we cannot delete the user object or the mailbox is lost.



## Blocking external emails

message trace,defender 
