This is the yaml for my current P1S HA dashboard.
I borrowed heavily from @WolfwithSword dashboard template but customized his code to meet my requirements (mobile view with as much control as possible with no scrolling). 
It's inspired by his template but I made a lot of chabges over time to make it work for me. See his awesome template below:

https://www.wolfwithsword.com/bambulab-home-assistant-dashboard/



Amongst other things, this dashboard pulls it data from the Hacs integration for Bambu Labs printers found here:

https://github.com/greghesp/ha-bambulab




Below are some of the changes I made to WolfwithSword's awesome dashboard template.

**Edited both photos**
- AMS pic - made all the filament spools look the same (lighter)
- P1S pics - removed picture of ptfe tubing at the top

**Uses the following custom cards**

HACS Integration
- browser_mod
  
HACS frontend
- mushroom cards
-	card-mod
-	Hass Hue Icons(spool icons)
-	frigate-card (for camera pop)

**2 input_boolean helpers used to show/hide info**
-	one to show/hide the stop,pause,play print buttons (input_boolean.3d_printer_print_controls)
-	one to show/hide air quality sensor (Govee) (input_boolean.3d_printer_aq_toggle)
