# Release Notes
# SMSEagle 

This document lists the changes, improvements, and bug fixes for each version of the module.

## v1.3.6 - 2025-12-08 (Latest)
### 🐛 Bug Fixes
* **Version number:** Fix version numbers.
* **Alarm ack messages:** Fix alarm ack messages.

## v1.3.5 - 2025-12-04
### ✨ New Features 
* **Queue datas:** Added Queue to store messages at niagara side.
* **Retry logic:** Added retry logic if niagara or SMSEagle hardvare loses connection. 
* **Ack Messages:** Added alarm acknowledge functionality to filter messages.
* **Low Limit, High Limit:** Added low limit, high limit support.

## v1.1.4 - 2025-11-10
### 🐛 Bug Fixes
* **Round robin:** Fix round robin nullable.
 
## v1.2.3 - 2025-11-08
### ✨ New Features 
* **Round robin:** Added round robin support to the module, it can be configured via admin SMSEagle page.

### 🐛 Bug Fixes
* **User block:** Fix :user datatype.

## v1.1.2 - 2025-06-30
### 🐛 Bug Fixes
* **Alarm timestamp:** Fix alarm timestamp format. Add timezone.
* **Group, Contact:** Fixed multiple group and contact error.
* Fixed no message sent when trigger an alarm.

## v1.1.1 - 2025-06-11
### ✨ New Features 
* **Alarm handling:** Connect Niagara alarm database so all of the messages pass through the module if it is enabled. 
* **AlarmDemux:** action slot to connect through the alarm class.
* **PresentValue, SourceName, Timestamp, SourceState, AckState, Priority, AlarmClass, MsgText, Uuid**

* Fixed SSL certificate validation error when connecting via HTTPS.

## v1.0.0 - 2025-05-28
### Initial Release
* Core blocks: Call, Sms, User
* Solving call and sms sending problem.






