# Home-Assistant---Control4

These files will enable you to use the Control4 (4) Zone Matrix Amplifier and Control4 tuner in Home Assistant without the need of the Control4 Controller itself. I no longer use the Control4 system (with the exception of the AMP and Tuner which I like).

These files are written specifically for my setup, but can be modified easily to accomidate your setup. This is based on a Control 4 (4) Zone Matrix Amplifier and Control4 Tuner (Tuner 1, Tuner 2, and XM radio), but since I've never used XM I have no writeup for that. This is based on what Matt from Smart(ish)Home orginally did with OpenHab and Home Assistant (this wouldn't have been possible without his work), and a few others who gave me pointers and fixes (thanks Walrus_Parka).

***** 0.92 Break Change Fix *****

Stop Home Assistant<br>
Remove/Rename/Delete c4_services.py<br>
Copy the c4_services folder into the custom_components folder<br>
Start Home Assistant<br>

If successful, a __pycache__ folder will be automatically created registering the c4_services.<br>

Response is a little slower (icon indicator) for the booleen switches as now it's using the new hass services.

<img src="https://github.com/kmakar89/Home-Assistant---Control4/blob/master/ha_c4.png">



