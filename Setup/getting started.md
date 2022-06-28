# Getting started

This guide is for both the Duofiller and the Duofiller Mono. 

- Make sure the filler is connected to a keg with water or sanitizer and keg pressure approximately 1 bar. 
- Connect CO~2~ to the filler and make sure CO~2~ pressure is below 3psi/0.2 bar.
- Power up the filler by connecting the plug from the power supply into the socket.

When filler starts up first time the LED will light green. This indicates that the filler is in timer mode. For first time use we want to have it in sensor mode for calibration. Hold push button 2 seconds and release. Led shall switch to solid blue, indicating it's switched to sensor mode. (If the led instead starts to blink green you probably held the button to long. Hold button 4 seconds and it should be back in timer mode and try to set it in sensor mode again.)

## Sensor mode programming
When in sensor mode hold button for 4 seconds and release. The led starts to blink blue. This inducates that the filler is in sensor mode programming mode. 
To program the filler we want to start a fill and stop it at the desired fill level. Place a glass or can under the fill head and start a fill by pressing the push button. Fill sequence will begin by first purging and then switch to beverage fill. Pay attention to the fill level. When at desired level press the push button a short press and it will stop. The led goes green, which means it successfully saved the fill level. On successfull fill level save it will jump back to sensor mode automatically. Start a new fill and it will stop at the saved fill level. If you have the Duofiller do the same for the second fill head.

Go back to sensor mode programming and repeat a few times until you are familiar with the programming. 

## Timer mode programming
Go back to timer mode (hold button 2 seconds and release). When in timer mode hold button for 4 seconds and release. The green led will start to blink, indicating that it's in timer mode programming mode. Programming is done exactly the same way as in sensor mode. Start a fill and stop it at the desired fill level. The only difference is that on successful fill level save, it will not jump automatically back to timer mode. To go back to timer mode hold push button for 4 seconds and release.


## Purge time programming
To enter purge time programming mode first make sure that you are in either sensor mode or timer mode. Hold push button for 10 seconds and release. LED will turn dark, indicationg you are in purge time programming mode. Default, recommended and factory set purge time is 6 seconds. To change it push the button once to step one second forward. Each push moves the purge time +1 seconds. When at 10 seconds next step will be 0 seconds. Each step is indicated by a red blink in the led. On 0 seconds the led blinks green and on 5 seconds the led blinks blue. When at desired purge time exit purge time programming mode by holding the push button 10 seconds and release.

## Web interface
On first boot the filler starts an accesspoint (AP) with SSID "Duofiller" and password "duofiller". Use a phone, tablet or computer to connect to that AP. On successful connection enter "http://192.168.4.1" or "http://duofiller.local" in the browser address field. It will take you to the web-interface menu. In the web interface you can adjust fill level for sensor mode, fill time for timer mode and purge time. there is also a fill counter that is handy to use to easily count how many fillings has been done. 

In the connection setup menu you can input your home wifi SSID and password. After reboot the filler will connect to your home network. Make sure your phone, tablet or computer is connected back on home wifi. You can find the filler menu by typing address "http://duofiller.local" or it's assigned IP address. Find IP address either by using a network scanner (look for a device "Duofiller" or sometimes "espressif") or log in to your router and find the filler in the DHCP lease list.

The hostname of the filler can be changed in the menu. For example if you have more than one Duofiller it's possible to rename them to for example "Duofiller1", "Duofiller2", etc. Connect to each filler by using duofiller1.local, duofiller2.local, etc. You can also change each fillers AP SSID to differentiate between more than one filler.

Web interface also has a "disable wifi" option. The filler works perfectly fine without wifi and if you don't use it it's possible to disable. To re-enable wifi, reset network settings.

## Factory reset
Power off filler, press push button and power up while holding the button. 

Hold push button for 5 seconds and release to reset network settings and 10 seconds and release to reset all settings to default.

## Firmware upgrade

The web interface has an "update firmware" option. Select the firmware file (*.bin file) and press upload. Please never unplug the filler while the firmware upgrade is in progress. When the upgrade is complete it will be indicated by a solid green light in the led indication that it's back in timer Mode. It's not necessary to reboot the filler after the firmware upgrade.

![](/static/firmware.png)