Party API Classifications
===============

Category of Individuals
--------------
Defines category of individual customer, based on its residential status or age or some other differentiation that bank needs.

Literal 					| Code	| Description
----------------------------|-------|------------------------
`resident-individuals`		| 00001	| Resident Individuals
`non-resident-individuals`	| 00002	| Non-Resident Individuals
`minors`					| 00003	| Minors


Customer Lyfecycle Status
--------------
Identifies the state of a Customer within a lifecycle model.

Literal					| Code 	| Description
------------------------|-------|------------------------
`rejected`				| 00001	| Identifies a Customer Life Cycle Status in which the object <Involved Party> has sought to initiate an active relationship with the subject Involved Party (the seller of a product or service), but the seller has refused to establish the active relationship.
`declined`				| 00002	| Identifies a Customer Lifecycle State in which the subject <Involved Party> has been contacted by the object <Involved Party> (the seller of a product or service) in order to establish an active Customer Relationship, but the Prospective <Customer> has rejected the offer and has opted not to establish an active relationship.
`dormant`				| 00003	| Identifies a Customer Lifecycle Status in which the <Involved Party> has previously accepted and acquired the goods or used the services offered by the modeled organization, but has not acquired goods or used services for a specified period of time.
`potential`				| 00004	| Identifies a Customer Life Cycle State in which the 'subject' <Involved Party> (the <Customer>) has been identified as a possible participant in an active customer relationship with the object Involved Party but in which the modeled organization has not contacted the subject Involved Party.
`active`				| 00005	| Identifies a Customer Lifecycle Status in which the <Customer> has accepted and is using a product or service offered by the modeled organization.
`former`				| 00006	| Identifies a Customer Lifecycle Status in which the <Involved Party> (the <Customer>) previously had an active customer relationship with the modeled organization but currently is inactive with no open <Product Arrangement>s in force.
`prospective`			| 00007	| Identifies a lifecycle state where an <Involved Party> (the <Customer>) has been identified as a possible active customer by the modeled organization and has been contacted by the modeled organization.


Primary Identification Document
--------------
Acceptable primary proof of identity entered from original or certified documents with full name and date of birth.

Literal							| Code 	| Description
--------------------------------|-------|------------------------
`passport`						| 00001	| Passport
`driving-licence`				| 00002	| Driving licence
`personal-identification-card`	| 00003	| Personal identification card


Registration Number
--------------
Kind of identification number of individual customer.

Literal 							| Code 	| Description
------------------------------------|--------|------------------------
`national-identification-number`	| 00001 | National identification number
`tax-identification-number`			| 00002	| Tax identification number
`social-security-number`			| 00003	| Social security number
`driver-licence-number`				| 00004	| Driver licence number
`passport-number`					| 00005	| Passport number
`identity-card-number`				| 00006	| Idenitity card number

Employment Status
--------------
Employment status of the individual customer.

Literal				| Code 	| Description
--------------------|-------|------------------------
`employed`			| 00001 | Employed
`not-employed`		| 00002	| Not Employed
`retired`			| 00003	| Retired
`shop-owner`		| 00004	| Shop Owner
`farmer`			| 00005	| Farmer
`leave-of-absence`	| 00006	| Leave of absence
`part-time-job`		| 00007 | Part-time job

Arrangement Category
--------------
Identifies the type associated with an <Arrangement>. This type may be hierarchical.

Literal 				    | Code 	| Description
----------------------------|-------|------------------------
`bank-transit-account`		| 00001 | Bank Transit Account
`cash-drawer`				| 00002 | Cash Drawer
`local-currency-card`		| 00003 | Local Currency Card
`deposit-card`				| 00004 | Deposit Card
`dedicated-account`			| 00005 | Dedicated Account
`non-resident-account`		| 00006 | Non-resident Account
`deposit-account`			| 00007 | Deposit Account

Contact Usage
--------------
Usage type of the contact.

Literal 		| Code 	| Description
----------------|-------|------------------------
`seasonal`		| 00001 | Seasonal
`assistant`		| 00002	| Assistant
`work`			| 00003	| Work
`home`			| 00004	| Home
`default`		| 00005	| Default
`business`		| 00006	| Business
`legal`			| 00007	| Legal

Contact Address Category
--------------
Category of the contact address of the individual customer.

Literal						| Code 	| Description
----------------------------|-------|------------------------
`postal-address`			| 00001 | Postal address
`telecommunication-number`	| 00002	| Telecommunication number
`electronic-address`		| 00003	| Electronic address

Telecommunication Number Category
--------------

Telecommunication number category.

Literal 			| Code 	| Description
--------------------|-------|------------------------
`phone`				| 00001 | Phone
`mobile-phone`		| 00002 | Mobile Phone
`fax`				| 00003 | Fax

Electronic Address Category
--------------

Electronic address category

Literal 			| Code 	| Description
--------------------|-------|------------------------
`email-address`		| 00001 | E-mail address
`uri`				| 00002	| Uri
`facebook`			| 00003	| Facebook

Redisential Status
--------------

Residential status of the individual customer.

Literal 			| Code 	| Description
--------------------|-------|------------------------
`resident`			| 00001 | Resident
`non-resident`		| 00002	| Non-resident

Gender
--------------

Gender of the individual customer.

Literal 		| Code 	| Description
----------------|-------|------------------------
`male`			| 00001 | Male
`female`		| 00002 | Female
`unknown`		| 00003 | Unknown

Record Status
--------------

Gets or sets the created, updated, deleted record status.

Literal 		| Code 	| Description
----------------|-------|------------------------
`created`		| 00001 | Created record status
`updated`		| 00002 | Updated record status
`deleted`		| 00003 | Deleted record status

Customer Taxonomies
----

Classifies customers according to taxonomy defined by bank.

Literal 		| Code 	| Description
----------------|-------|------------------------

Customer Statuses
----

Identifies the state of a customer within a lifecycle model.

Literal 		| Code 	| Description
----------------|-------|------------------------

Customer Segments
----

Classifies the customers into segments according to bank requirements.

Literal 		| Code 	| Description
----------------|-------|------------------------

Contact Purposes
----

Purposes for which party does not allow to be contacted.

Literal 		| Code 	| Description
----------------|-------|------------------------

Legal Structures
----

Classifies organizations based on their legal form or structure.

Literal 		| Code 	| Description
----------------|-------|------------------------

Organization Purposes
----

Distinguishes between organizations according to their purpose or format.

Literal 		| Code 	| Description
----------------|-------|------------------------

Party API Enumerations
===============

Party Kinds
------

Literal 		| Description
------------|------------------------
individual		| Individual (human)
organization		| organization (legal entity)

Party Statuses
------

Status of the Party during lifecycle of existence in the system.

Literal 		| Description
------------|------------------------
potential| Potential
prospective| Prospective
active| Active
dormant| Dormant
former| Former
declined| Declined
rejected | Rejected

Identification Kinds
------

Kinds of identification numbers, based on type of identification origin.

Literal 		| Description
------------|------------------------
registration-number|Registration Number
tax-id-number|Tax-ID Number
personal-id-number|Personal-ID Number
identity-card-number|Identity Card Number
passport-number|Passport Number
driver-license-number|Driver License Number
social-security-number|Social Security Number

Legal Competencies
----

Enumeration that distinguishes whether individual has any legal limitation on their ability to transact business with bank

Literal 		| Description
------------|------------------------
incompetent-minor| Has a level of incompetency (minor or because of other reasons)
competent-adult| Fully competent

Marital Statuses
----

Literal 		| Description
------------|------------------------
divorced| Divorced
common-law-marriage| Common Law Marriage
married | Married
single | Single
widowed | Widowed

Party Relationship Kinds
----

Literal 		| Description
------------|------------------------
marriage	|	Marriage
family	|	Family
ownership	|	Ownership
representation	|	Representation
employment	|	Employment

Party Relationship Roles
----

Literal 		| Description
------------|------------------------
spouse	|	Spouse
child	|	Child
parent	|	Parent
sibling	|	Sibling
cousin	|	Cousin
owner	|	Owner
owned	|	Owned
representative	|	Representative
represented	|	Represented
employer	|	Employer
employee	|	Employee

Contact Point Methods
----

Literal 		| Description
------------|------------------------
postal	|	Postal
pstn	|	PSTN
gsm	|	GSM
fax	|	Fax
facebook	|	Facebook
email	|	Email
web	|	Web

Contact Point Usages
----

Literal 		| Description
------------|------------------------
default	|	Default
home	|	Home
business	|	Business
work	|	Work
seasonal	|	Seasonal
assistant	|	Assistant
delivery	|	Delivery
legal	|	Legal

Address Kinds
----

Literal 		| Description
------------|------------------------
postal-address	|	Postal Address
phone-number	|	Phone Number
email-address	|	Email Address
facebook-account	|	Facebook Account
web-url	|	Web URL

Identification Document Kinds
----

Literal 		| Description
------------|------------------------
passport|Passport
national-id-card|National ID Card
drivers-license|Drivers License

Identification Document Statuses
----

Literal 		| Description
------------|------------------------
active | Active
annulled | Annulled
expired | Expired

Registration Profiles
----

Literal 		| Description
------------|------------------------
contact|Contact
prospect|Prospect
customer|Customer
