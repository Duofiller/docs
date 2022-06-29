---
order: 108
---

# Getting started

This guide is for both the Mono and Duofiller. 

- Place a drip tray under the filler. Always use a drip tray to collect spills under the filler.
- Make sure the filler is connected to a keg with cold water and keg pressure approximately 1 bar. 
- Connect CO~2~ to the filler and make sure CO~2~ pressure is below 3psi/0.2 bar.
- Power up the filler by connecting the plug from the power supply into the socket.

When filler starts up first time the LED will light green. This indicates that the filler is in timer mode. For first time use we want to have it in sensor mode for calibration and function test. Hold push button 2 seconds and release. Led shall switch to solid blue, indicating it's switched to sensor mode. (If the led instead starts to blink green you probably held the button to long. Hold button 4-5 seconds and it should be back in timer mode; try to set it in sensor mode again.)

## Sensor mode fill level programming
When in sensor mode hold button for 4 seconds and release. The led starts to blink blue. This inducates that the filler is in sensor mode programming mode. 
To program the filler we want to start a fill and stop it at the desired fill level. Place a glass or can under the fill head and start a fill by pressing the push button. Fill sequence will begin by first purging and then switch to beverage fill. Pay attention to the fill level. When at desired level press the push button a short press and it will stop. The led goes green, which means it successfully saved the fill level. The fill level will not be stored if the fill level is set at 25mm or less. If the fill level is not stored successfully it blinks red and stays in fill level program mode. On successfull fill level save it will jump back to sensor mode automatically after the can is removed.

Start a new fill and it will stop at the saved fill level. 

Go back to sensor mode programming and repeat a few times until you are familiar with the programming. 

If you have the Duofiller do the same for the second fill head.

## Timer mode fill level programming
Go back to timer mode (hold button 2 seconds and release). When in timer mode hold button for 4-5 seconds and release to go to Timer Mode fill level programming. The green led will start to blink, indicating that it's in Timer Mode fill level programming is active. Use a glass, can or bottle to do the programming. Programming is done exactly the same way as in sensor mode. Start a fill and stop it at the desired fill level. The only difference is that on successful fill level save, it will not jump automatically back to Timer Mode. To go back to Timer Mode hold push button for 4-5 seconds and release. 

Start a fill and verify it stops at the programmed fill level.

Since Timer Mode measures the exact time used to fill to the desired fill level it's important to keep that in mind before the fill level is programmed. Set the keg pressure, flush/prime beverage tubing, etc. before Timer Mode programming is done.

## First time cleaning
1. Flush through the filler with lukewarm water with detergent. Start a fill in Timer Mode programming mode to do the flushing, the beverage valve will stay open until manually aborted. For first-time clean we recommend using PBW or a dishwasher detergent (at recommended concentration) and flush for 10 minutes.
2. Flush through an acid-based sanitizer for beverage equipment (we recommend StarSan, SureSan or equivalent) at its recommended concentration. Contact time 3 minutes or more
3. Gently spray (with a spray bottle) or soak the outside of the stainless fill tubes with an acid-based sanitizer. Use goggles. Contact time 3 minutes.

## Beverage fill
After first time cleaning the filler is ready to use. Connect a keg with beverage. Repeat fill level calibrations using the beverage. Don't expect programmed fill level done with water to be similar to actual fill level with beverage. Many factors play a role; in sensor mode the fill level is affected by SG, carbonation level (amount of bubbles) and flow. In Timer Mode the fill level is mainly affected by keg pressure and beverage viscosity. If you have a stable keg pressure then Timer Mode will be the most accurate fill mode. If you experience inconsistent fill level with Timer Mode then switch to Sensor Mode filling.

## Purge time programming
Default, recommended and factory set purge time is 6 seconds. If you want to change the purge time; make sure that you are in either Sensor Mode or Timer Mode. Hold the push button for more than 6 seconds and release. LED will turn off, indicating that it's in purge time programming mode.  When in purge time programming mode a short press on the button will skip the purge time +1 second forward. For each step, the led will blink red. When the purge time is 5 seconds the led will blink green instead of red. When at 10 seconds the next step will be 0 seconds. When at 0 seconds the led blinks blue (0 seconds = purge disabled). Hold push button more than 6 seconds and release to exit purge time programming mode.

If you have the Duofiller purge time is set individually for each fill head.

Purge time is set globally for both Timer Mode and Sensor Mode. For Timer Mode purge can be disabled but for Sensor Mode, it's recommended to use at least 1 second purge time to ensure the CO~2~ tube is free of liquid before each fill sequence.

## Web interface
Default, on each boot the filler starts an accesspoint (AP) with **SSID "Duofiller" and password "duofiller"**. Use a phone, tablet or computer to connect to that AP. On successful connection enter http://192.168.4.1 or http://duofiller.local in the browser address field. It will take you to the web-interface menu. In the web interface you can adjust fill level for sensor mode, fill time for timer mode and purge time. There is also a fill counter that is handy to use to easily count how many fillings has been done. 

Fill time for Timer Mode can be set in milliseconds and fill level for sensor mode can be set in millimeters. Please note that the intention is to have the possibility to fine-tune the already set fill level. Don't expect to dial in the exact fill level in millimeter with the web interface. But for adjusting the fill level 1-2-5-10 mm up or down it works great. Fill level in millimeter indicates the measured fill level above the tip of the CO~2~ tube using non carbonated water. With carbonated beverage the actual fill level will be slightly different, depending on the carbonation level and SG (specific gravity).

In the connection setup menu you can input your home wifi SSID and password. After reboot the filler will connect to your home network and you can control it using any device connected to the same network. You can find the filler menu by typing address http://duofiller.local or it's assigned IP address. Find IP address either by using a network scanner (look for a device "Duofiller" or sometimes "espressif") or log in to your router and find the filler in the DHCP lease list. Make sure your phone, tablet or computer is connected to the same wifi as the filler.

You can change each fillers AP SSID (and password) to differentiate between more than one filler. The hostname of the filler will be the same as the AP SSID. For example if you have more than one Duofiller it's possible to rename them to for example "Duofiller1", "Duofiller2", etc. Connect to each filler by using duofiller1.local, duofiller2.local, etc. 

Web interface also has a "disable wifi" option. The filler works perfectly fine without wifi and if you don't use it it's possible to disable the wifi radio. To re-enable wifi, reset network settings.

## Factory reset

**Power off filler, press push button and power up while holding the button:**

Hold push button for 5 seconds and release to reset network settings. 5 seconds is indicated by a blue led. 

Hold push button for 10 seconds and release to reset all settings to factory default. 10 seconds is indicated by a red led. 

To abort the reset, hold for more than 15 seconds and release.

## Firmware upgrade

The web interface has an "update firmware" option. Select the firmware file (*.bin file) and press upload. Please never unplug the filler while the firmware upgrade is in progress. When the upgrade is complete it will be indicated by a solid green light in the led indication that it's back in timer Mode. It's not necessary to reboot the filler after the firmware upgrade.

![](/static/firmware.png)

### Details

For details please see the quick reference :icon-arrow-down: [!ref Quick Reference](/quickreference.md) 