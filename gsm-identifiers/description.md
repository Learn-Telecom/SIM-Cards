---
description: >-
  SIM cards have to main categories CDMA / GSM here i am focus on GSM SIM cards.
  This cards have two types of charging system PREPAID and POSTPAID.
---

# Description

The format of the ICCID is: MMCC IINN NNNN NNNN NN C x&#x20;

MM = Constant (ISO 7812 Major Industry Identifier)&#x20;

CC = Country Code&#x20;

II = Issuer Identifier&#x20;

N{12} = Account ID ("SIM number")&#x20;

C = Checksum calculated from the other 19 digits using the Luhn algorithm.&#x20;

x = An extra 20th digit is returned by the 'AT!ICCID?' command, but it is not officially part of the ICCID.

**PREPAID**

Prepaid cards already have a tax plan assigned to them

**POSTPAID**

#### SIM Card Structure

***

SIM cards hold a profile mapped by the network operator, these cards have a storage capacity 8k,16k,32k128k,etc...

MF - Master Files

DF - Dedicated Files

EF - Elementary Files

Standards : GSM 11.11 - [3GPP 51.011](https://www.etsi.org/deliver/etsi\_TS/151000\_151099/151011/04.15.00\_60/ts\_151011v041500p.pdf)

#### SIM Card Profile

***

Network Requirements

* MCC / MNC
* IMSI
* ICC-ID
* SMS Parameters&#x20;

Marketing Requirements

* Phonebook
* Number of Short Messages
* Service Dialing Number (Customer Care Numbers
* Mailbox Number

Business Requirements

* Roaming Partner List
* PIN Handling

**ICC-ID**

***

ICC&#x20;

* **SIM** - Single IMSI or Dual IMSI
* **RUIM** - Single CDMS or Combo CDMA+GSM

ICC-ID is defined by **ITU-T E.118**

The ICC-ID has 19 digits and calculated using Luhn algorithm.

89-91-15-100-000000011-8

89 - Tele

91 - CC

15 - MNC

100 - Vendor

000000011 - Serial Number

8 - Checksum

**IMSI**

***

**I**nternational **M**obile **S**ubscriber **I**dentity

The IMSI has 15 digits and is unique across all globe and indicates the home network of the subscriber.

MCC + MNC + MSIN = IMSI

MNS + MSIN = NMSI

**SIM Keys**
