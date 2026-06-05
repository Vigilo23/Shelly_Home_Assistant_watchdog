# Shelly_Home_Assistant_watchdog

Ein watchdog für einen shelly PlugS Gen3. (sollte aber auch auf anderen Shellys funktionieren)
Der Shelly wird mit der Stromversorgung des Home Assistant Servers verbunden und prüft regelmässig ob der Home Asssitant erreichbar ist.
Sollte dieses zu oft hintereinander nicht funktionieren, wird die Stromversorgung getrennt um dadurch den Home Assistant neuzustarten.

---------------------------------------------------------------------------------------------------

A watchdog for a Shelly Plug S Gen3. (should also work on other Shelly devices)
The Shelly is connected to the power supply of the Home Assistant server and regularly checks whether Home Assistant is reachable.
If this fails too often in a row, the power supply is disconnected to restart Home Assistant.
