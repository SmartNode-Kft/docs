# Release Notes
# SMSEagle 

This document lists the changes, improvements, and bug fixes for each version of the module.

## v1.1.0 - 2025-12-03 (Latest)
### ✨ New Features 
* **Queue datas:** Added Queue to store messages at niagara side.
* **Retry logic:** Added retry logic if niagara or SMSEagle hardvare loses connection. 
* **Ack Messages:** Added alarm acknowledge functionality to filter messages.
* **Low Limit, High Limit:** Added low limit, high limit support.

## v1.0.5 - 2025-11-13
### ✨ New Features 
* **Round robin:** Added round robin support to the module, it can be configured via admin SMSEagle page.

### 🐛 Bug Fixes
* **User block:** Fix user datatype so you can rename it for what you want.

## v1.0.4 - 2025-08-21
* 

## v1.0.3 - 2025-07-17

## v1.0.2 - 2025-06-30

### 🐛 Bug Fixes
* **Group, Contact:** Fixed multiple group and contact error.

## v1.0.1 - 2025-06-11
### ✨ New Features 
* **Alarm handling:** Connect Niagara alarm database so all of the messages pass through the module if it is enabled. 
* **AlarmDemux:** action slot to connect through the alarm class.

### 🐛 Bug Fixes
* Fixed no message sent when trigger an alarm.
* Fixed SSL certificate validation error when connecting via HTTPS.

## v1.0.0 - 2025-05-28
### Initial Release
* Core blocks: Call, Sms, User
* Solving call sending problem.




