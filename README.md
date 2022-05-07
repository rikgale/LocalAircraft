# LocalAircraft
LocalAircraft.txt for use with Virtual Radar Server.

If civil aircraft are incorrectly flagged as Military in Virtual Radar Server and visa-versa, this will fix it.

Please post additions as Issues.

# Usage

Download ``LocalAircraft.txt`` Place file in configuration folder of VRS and wait until the nightly refresh of the standing data. Don't expect this to work striaght away.

- Windows 
  - Go to ``Help | About`` and click the link to the configuration folder. Place ``LocalAircraft.txt`` in this folder. 
  - Or put ``%LOCALAPPDATA%\VirtualRadar`` in the address bar of Windows Explorer. This should take you direct to the required folder. Place ``LocalAircraft.txt`` in this folder. 

- Linux - varies dependant on where/how VRS was installed, but look for ``~.local/share/VirtualRadar`` or run a search for StandingData.sqb and place ``LocalAircraft.txt`` in the same location as this database.
