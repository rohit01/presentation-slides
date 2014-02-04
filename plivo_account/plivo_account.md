Plivo Account
=============
<center>
<br />
<br />
<br />
<br />
<br />
<br />

** Rohit Gupta **
<br />
<br />
** Developer @plivo **
<br />
<br />
** @rohit01 **
<br />
<br />
</center>

---
Create an Account
=================

- Register: [https://manage.plivo.com/accounts/register](https://manage.plivo.com/accounts/register/)
- Free Trial:
    - Call and send SMS messages
    - Claim your free local US number
    - No credit card required

---
Dashboard
=========

- Sub Accounts
- Applications
- Numbers
- Endpoints
- Carriers (BYOC)
- Logs
- Payments

---
Sub Accounts
============

- Enables hierarchical management of your resources
- Properties:
    - Name *
    - Enabled *

Once created, a Sub Account generates Auth Id and Auth Token. This can be used for all API calls except search or rent numbers.

---
Application
===========

- Handle Inbound calls and SMS
- Properties:
    - Application name *
    - Sub account
    - Answer url *
    - Answer method *
    - Fallback_answer url
    - Fallback method

---
Application
===========

- Properties (contd...)
    - Hangup url
    - Hangup method
    - Message url
    - Message method
    - Default number app
    - Default endpoint app
    - Public uri

---
Numbers
=======

- Virtual phone numbers: Receive calls & SMS
- Types: Local, National, Tollfree, Custom Carrier
- Features: Voice Enabled, SMS (Available for few Countries)
- Properties:
    - Plivo Application: Decides incomming call flow
    - Sub Account: Groups for managing and tracking resources
    - Alias: Human readable Identifier

---
Endpoints
=========

- Create sip Users
- Plivo SIP Domain: phone.plivo.com
- Properties:
    - Username *
    - Password *
    - Alias
    - Plivo App: Usually a [direct dial](https://github.com/plivo/directdial) application *
    - Sub Account

Once created, full sip address will be of format:

- sip:&lt;username&gt;${creation_timestamp}@phone.plivo.com

---
Carriers (BYOC)
===============

- Incomming Carrier: Name, Enabled, IP Set
- Outgoing Carrier (Available through API only):
    - name *
    - address *
    - failover_address
    - prefix
    - failover_prefix
    - suffix
    - retries
    - retry_seconds

---
Logs
====

- Calls: Successful call summary logs
- Messages: Successful messages summary logs
- Recordings: Call/Conference recordings
- Debug: Detailed Call and SMS logs
    - All
    - Error

---
Payments
========

- Recharge: Credit Card, Coupon Recharges
- Usage: Monthly Invoice
- History: Payment history
- Recurring Charges: Usually number rentals

---
Questions
=========
