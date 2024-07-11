This file is SPECIFIC to the: Project Lazarus (EMU) EverQuest server.
-
MQ2EasyFind is a plugin that helps get you around EverQuest, and while the heavy lifting and actual character movement is provided by the Nav plugin, EasyFind tells it where to go.

EasyFind provides two main categories of functionality:
Finding locations in the current zone.
Navigating to other zones.

You can interact with this plugin in the following ways:
Ctrl+click on items in the Find window (opens with Ctrl+F by default)
The /easyfind command - find locations in the current zone
The /travelto command - travel to another zone

You can also access settings for EasyFind through /mqsettings
--
Note:
--
The configuration file (ZoneConnections.yaml) is used to bypass the default server configurations for Zonelines / Translocators / Switches / Doors, this is needed
on EMU servers, as there might be specific content ( Server specific Translocators or locations ). 

When using the plugin via the LUA interface (/EasyFind UI) you MUST go into the Settings TAB and ENABLE (Ignore ZOne COnnection Data).
This will force the plugin to USE the (ZoneConnections.yaml) file and ignore server data.
