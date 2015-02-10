# Pushbullet Notifier - readme under construction
*Pushbullet Notifier for Smartthings*

"If I have seen further than others, it is by standing upon the shoulders of giants." - Isaac Newton *Thanks, @625Alex, for the work you did in* https://github.com/625alex/SmartThings/blob/master/devices/Pushbullet.groovy *to get me here.*

SmartApps and device type to push messages through Pushbullet (www.pushbullet.com) to specific devices.

### Features

* Setup a Pushbullet device to recieve notifications on.
* Choose from a variety of capabilities to get notified about:
	* Acceleration
	* Contact
	* Motion
	* Presence
	* Smoke
	* Switch
	* Water
	* Temperature (can set a threshold to get notified if it goes above or below a certain temperature.)
* Choose multiple device with the same capability.
* Watch for just one attribute or every event from the device. (ex. Presence can notify you when someone arrives only, leaves only, or both)
* Choose multiple Pushbullet Devices to push to.
* Set a user defined message.
* Show the message in the title or leave it as the app label. (The title shows on the lock screen when you recieve a notification)
* Set a minimum number of minutes between notifications (So you don't get notified every time that motion sensor changes state!)

## Instalation

### Pushbullet.com

First you need to go to www.pushbullet.com, sign up for an account, and install Pushbullet on the device(s) that you want to get notified on.

### Device Service Manager

You need to have a Pushbullet device to use the notifier. The Pushbullet Connect app will help set up the device and is available in the "My Apps" section of the Shared
Smart Apps in [SmartThings IDE](https://graph.api.smartthings.com).

1. Go to "My SmartApps" section and click on the "+ New SmartApp" button on the
right.
2. On the "New SmartApp" page, fill out mandatory "Name" and "Description"
fields (it does not matter what you put there).
3. Click the "Create" button at the bottom.
4. When a new app template opens in the IDE, click on the "Browse SmartApps"
drop-down list in the upper right corner and select "Browse Shared SmartApps".
A list of shared SmartApps will appear on the left side of the editor window.
5. Scroll down to "My Apps" section and click on it.
6. Select "Pushbullet Connect" app from the list and click the red "Overwrite" button
in the bottom right corner.
7. Click the blue "Save" button above the editor window.
8. Click the "Publish" button next to it and select "For Me". You have now
self-published your SmartApp.
9. Open SmartThings mobile app on iPhone or Android and go to the Dashboard.
10. Tap on the round "+" button and navigate to "My Apps" section by swiping
the menu ribbon all the way to the left.
11. "Pushbullet Connect" app should be available in the list of SmartApps that
appears below the menu ribbon. Tap it and follow setup instructions.
12. When it asks for your API key, you can find it at http://www.pushbullet.com/account

### App

Pushbullet Notifier app is available in the "My Apps" section of the Shared
Smart Apps in [SmartThings IDE](https://graph.api.smartthings.com).

*You can set up multiple instances of the app to use multiple devices with different capabilities or to have different messages*

Follow steps 1-5 from service manager installation.

* Select "Pushbullet Notifier" app from the list and click the red "Overwrite" button
in the bottom right corner.

Follow steps 7-10 from service manager instalation.

* "Pushbullet Notifier" app should be available in the list of SmartApps that
appears below the menu ribbon. Tap it and follow setup instructions.


