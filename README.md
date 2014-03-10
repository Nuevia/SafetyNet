SafetyNet
==============
SafetyNet is a wireless, multi-user proximity monitoring system. An administrator (parent or group chaperone, for example) carries a pocket-sized base unit that is able to receive wireless "check-in" messages from bracelets within a given range (25-250 meters depending bracelet model and configuration).  When any bracelet fails to check in, the base unit can be configured to notify the administrator with vibration, alert tone, or optionally through the SafetyNet smartphone app via bluetooth.

Zone
-----
The concept of a "zone" is central to SafetyNet operation.  

A base unit defaults to Zone 1, and automatically establishes that zone when it is powered on.  The SafetyNet mobile app can be used to set a base unit to a different zone, although only one zone at a time is allowed per base unit.

Bracelets default to Zone 1 as well, and automatically join and begin checking in to that zone when they are powered on.  

The range of the system will vary, depending on the bracelet model used, battery charge, and obstructions like buildings, hills, dense woods, etc.  Maximum, unobstructed range should be in the neighborhood of 50-75 meters.

Bracelet
--------

Each bracelet has 2 configuration settings:  

- Zone Id (default 1) : Which zone this bracelet is assigned to
- Checkin Delay (default 8):  How many seconds between each check-in


Base Unit
---------
The base unit has several purposes:

- receive bracelet check-in messages for a particular zone
- notify administrator of failed checkins with vibration/sound alerts
- if synced to a smartphone, send all checkin activity to smartphone for logging and notifications
- wirelessy reprogram a bracelet's Zone Id or Checking Delay
