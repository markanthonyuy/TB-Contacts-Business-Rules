# TB-Contacts-Business-Rules

| FEATURE	(view, add, edit, delete)	| ROLE (reports, banking, admin) | CONTACT TYPE (contact, officer, member, vendor) | CURRENT USER |
|---|---|---|---|
| 1. Contact |
|   1.1  View All Contact	|	All					|officer, member|				Yes |
|   1.2  Add Contact			|Admin					|N/A						|	N/A	|		
|   1.3  Edit Own Contact		|All					|officer, member					|	Yes|
|   1.4  Edit All Contact		|Admin					|N/A						|	N/A|
|   1.5  Delete Contact			|Admin					|N/A						|	N/A|
|   *** FIELD SPECIFIC ***  |
|   1.6  Edit Contact Type		|Admin					|N/A						|	N/A|
|   1.7  View Contact Type		|Admin					|N/A						|	N/A|
|   1.8  Edit Contact Type		|Admin					|N/A						|	N/A|
|   1.9  Add Officer			|Admin					|N/A						|	N/A|
|   1.10 Edit Officer			|Admin					|officer, member				|		N/A|
|   1.11 Add Officer Term		|Admin					|N/A						|	N/A|
|   1.12 Edit Officer Term		|Admin					|officer, member					|	N/A|
| 2. Login |
|   2.1 View All User Can Login		|Admin					|N/A						|	N/A|
|   2.2 View Profile			|reports, banking			|officer, member						|Yes|
|   2.3 Add User Can Login		|Admin					|N/A							|N/A|
|   2.4 Edit Own User Login		|Admin					|N/A						|	N/A|
|   2.5 Edit All User Login		|Admin					|N/A						|	N/A|
|   2.6 Delete/Revoke User Login		|Admin					|N/A							|No|
|   *** FIELD SPECIFIC *** |
|   2.7 Edit Active			|Admin					|N/A							|No		|
|   2.8 Edit Roles			|Admin					|N/A							|No	|
|   2.9 Add Approver			|Banking, admin				|N/A							|No|
