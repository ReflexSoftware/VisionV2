# VisionV2
Vision is an open source and advanced anticheat for 1.8.9 Minecraft Java Edition servers.

## What version of Bukkit do I need to run this?
This is made for 1.8.8 spigot servers.

## What makes this stand out against other anticheats?
### Open Source
This anticheat is fully open source, meaning there is almost no chance of getting anything malicious on your computer. It also ensures you can make forks of this anticheat.

### (Mostly) Packet Based
Vision uses packet interception for most checks. By doing this, we can make sure no players on your server modifies them.

### Free, Forever
Vision will be completely free and will never be paid (until further notice).

### Prediction Based
Our anticheat will use prediction to detect movement exploitation. What the prediction engine does is that it gets all possible positions for a given tick, and if a player doesn't move according to any of those positions, they are most likely cheating.

## Dependencies
You will need ProtocolLib 5.1.0 for this plugin to work.

## Checks (may change)
### Combat | Autoclicker - Prevents people from using autoclickers
Autoclicker (A) - Cancels actions from a player if they are clicking above a certain cps limit

Autoclicker (B) - Flags a player if they click very suspiciously in terms of consistency

### Combat | Autoblock - Stops players from using autoblock
Autoblock (A) - Cancels the attack if a player is blocking while attacking (impossible to do legit)

Autoblock (B) - Flags if a player's blocking and hits matches a specific pattern

### Combat | Aim - Prevents the use of aim related cheats
Aim (A) - Flags if a player's yaw and/or pitch move too much in one tick

Aim (B) - Flags if a player is using Killaura with modulo 360 based rotations

Aim (C) - Flags if a player's rotations match rotations used in various clients

### Movement | Prediction - Prevents many types of movement cheats
Prediction (A) - Horizontal prediction

Prediction (B) - Vertical prediction

### Movement | NoSlow - Prevents people from disabling slowdowns for sword blocking
NoSlow A - N/A

### Exploit | BadPackets - Prevents the sending of packets that crash the server and/or are not correct
?

