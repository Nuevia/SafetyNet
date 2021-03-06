SafetyNet
==============
SafetyNet is a wireless, multi-user proximity monitoring system. An administrator (parent or group chaperone, for example) carries a pocket-sized base unit that is able to receive wireless "check-in" messages from bracelets within a given range (25-100 meters depending bracelet model and configuration).  When any bracelet fails to check in, the base unit notifies the administrator using the SafetyNet mobile app.

Zone
-----
The concept of a "zone" is central to SafetyNet operation.  

A base unit defaults to Zone 1, and automatically establishes that zone when it is powered on.  The SafetyNet mobile app can be used to set a base unit to a different zone, although only one zone at a time is allowed per base unit.

Bracelets default to Zone 1 as well, and automatically join and begin checking in to that zone when they are powered on.  

The range of the system will vary, depending on the bracelet model used, battery charge, and obstructions like buildings, hills, dense woods, etc.  Maximum, unobstructed range should be in the neighborhood of 50-100 meters.

Bracelet
--------

Each bracelet has 2 configuration settings:  

- Zone Id (default 1) : Which zone this bracelet is assigned to
- Checkin Delay (default 8):  How many seconds between each check-in


Base Unit
---------
The base unit has several purposes:

- receive bracelet check-in messages for a particular zone
- if synced to a smartphone, send all checkin activity to smartphone for logging and notifications

SafetyNet smartphone app
--------
Monitoring and configuration of the base unit(s) and bracelets is done from the mobile app.

- Displays status of base unit and configured bracelets for Zone 1
- Notifies administrator of any failed checkins
