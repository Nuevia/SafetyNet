SafetyNet
==============
SafetyNet is a wireless, multi-user proximity monitoring system. A parent or group chaperone carries a pocket-sized base unit that wirelessly communicates with a secure smartphone/web application and can monitor up to 25 bracelets equipped with wireless remote "check-in" capability.

The concept of a "zone" is central to SafetyNet operation.  A zone consists of a base unit, a smartphone running the SafetyNet app, and 1-25 bracelets configured for that zone.

Bracelet
--------

Each bracelet has 2 configuration settings:  

- Zone Id (default 1) : Which zone this bracelet is assigned to
- Checkin Delay (default 8):  How many seconds between each check-in


Base Unit
---------
The base unit has 3 primary functions:

- receive bracelet check-in messages for a particular zone
- report those checkins to the SafetyNet mobile app via short-range bluetooth connection
- wirelessy reprogram a bracelet's Zone Id or Checking Delay
