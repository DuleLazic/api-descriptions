---
visibility: public
---
Electronic Access Arrangements API Classifications
===============

Arrangement Statuses
---

Enumeration that distinguishes between current status of the electronic access arrangement
according to the arrangement lifecycle.

Literal          | Description
-----------------|------------
`effective`      | Effective, active
`canceled`       | Canceled, cannot be activated again


Electronic Access Channel
---

Electronic Access Channels.

Literal         | Description
----------------|---
`web`           | web channel
`mobile`        | mobile channel
...           | ...   


Contact Medium
---

Enumeration that distinguishes between mediums for the contact  for the
delivery of the communication.  

Literal          |Description                                        
-----------------|---------------------------------------------------
`smartphone-push`|Contact expects push notification on the Smartphone
`email`          |Email message                                      
`virtual-inbox`  |Virtual Inbox                                      
`sms`            |SMS notification     
...           | ...   


Limit Types
---

Limit Types.  

Literal              |Description                                        
---------------------|---------------------------------------------------
`transfer-limit`     |Transfer Limit                                     
`authorization-limit`|Authorization Limit                                
...           | ...   


Bank Services
-----

List of bank services allowed by mandates and tracked by limits.  These are groupings of more granular operations.

Literal         | Code  | Description
----------------|-------|------------
`any`           | 00001 | Any
`transfers`     | 00002 | Transfers
`exchanges`     | 00003 | Exchanges
`mandates`      | 00004 | Mandates
`maintenance`   | 00005 | Maintenance
`balances`      | 00006 | Balances
`statements`    | 00007 | Statements
`payments`      | 00008 | Payments
`withdrawals`   | 00009 | Withdrawals
`turnover-inq`  | 00010 | Turnover Inquiries
...             | ...   



Limit Channels
-----

Channels for which mandates and limits can be set 

Literal       | Description
--------------|------------
`online`      | Online self-service eg. direct banking, digital branch, mobile, home banking
`branch`      | Branches
`call-center` | Call Center
`atm`         | ATM
`pos`         | Point of Sales (PoS)
`vpos`        | Virtual PoS 
`any`         | Any
...           | ...  



User Roles
-----

User Roles

Literal       | Description
----------------|------------
`inputer`       | Inputer
`authorizer`    | Authorizer
`consent-giver` | Consent Giver
...           | ...  


Authentication Device Kinds
-----

Authentication Device Kinds

Literal          | Description
-----------------|------------
`mobile-token`   | Mobile Token
`hardware-token` | Hardware Token
...           | ...  