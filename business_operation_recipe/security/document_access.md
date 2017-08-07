# Document access

This document describes the ways in which we protect access to documents for Convivio staff, its contractors and customers. The document forms part of our alignment to the ISO 27001 Information Securit Management System standard.

## Documents in Google drive

We mostly use Google Drive to store our project documents. The information is stored across many data centres owned by Google, these are across Europe and the US which prevents any undue loss of data and is protected against fire and server failure. Google documents however cannot be backed up automatically and require manual download at intervals to make sure that all company information remains backed up.

Information stored by Google is protected by their ISO 27001 accreditation. Google Drive includes dozens of critical security features specifically designed to keep data safe and secure. These include encryption in transit as data moves from mobile devices to Google, as it moves between Google’s data centers and when it is stored on any mobile device.

###Confidential documents

Confidential documents should be marked with the word “confidential” on every page to ensure that it is a recognisable as a non distributable document. Confidential documents should not be printed or photocopied unless prior authorisation has been agreed. If a confidential document is printed or photocopied the disposal of all duplicates should be done in a secure fashion through means of secure shredding or incineration. 

## Public documents

Information regarding Convivio that is publically available is available within this cookbook. This is a publically available intranet containing information about Convivio, its practises, project management processes and also other helpful information. Any public documents should undergo peer review before they are published to minimise any incorrect information being released.

## Staff leaving Convivio

When a member of staff or a contractor no longer work for Convivio, access to the following systems is removed:

* Google account
* GitHub
* Slack
* Contactually

Before the user account is removed from Google, the contents of the Google Drive for that individual must be transferred to another current user to remain accessible within the system to do this :

Sign in to the Google Admin console.
Click Google Apps > Drive. Where is it?
Click Transfer ownership.
Complete the Document ownership transfer section:

In the From field, enter the user name of the current owner and select the user’s domain.
In the To field, enter the user name of the new owner and select the user’s domain.
Tip: If the transfer involves a very large number of documents, you may want to notify the new owner and check that they have enough storage capacity to accommodate the transferred documents. (You can see the amount of storage used and available at the bottom left corner of Google Drive on the web.)

Click Transfer documents to save.
All of the transferred documents are automatically organized in a single new folder — titled with the previous owner’s email address — in the new owner’s Drive.

The administrator and the new and previous owners receive email about the transfer as soon as the process completes.

If there were any problems with the transfer (e.g. the new owner’s quota is exceeded, which prevents the transfer of some documents), the email notification describes what happened. To fix the problem, you might purchase more storage for Google Drive for the new owner, transfer ownership of the documents to a different user, or redistribute ownership of documents one at a time to different users.

If you intend to delete the original owner of the transferred files, make sure to wait until the transfer finishes.

The removal of these accounts and their access is managed by administrators.

##Git Hub 

We store our codebase in Github repositories from where Convivio administrators can control access. Access to Github is password controlled with users passwords being no less than 16 alphanumeric and punctuation characters.

When access is provided to the repositories the user can edit, clone, branch code with every change being version controlled and trackable. This prevents any loss of code or irreversible errors. All changes are automatically communicated in a Slack channel.