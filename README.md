# Pushbullet Notifier - readme under construction
*Pushbullet Notifier for Smartthings*

"If I have seen further than others, it is by standing upon the shoulders of giants." - Isaac Newton *Thanks, @625Alex, for the work you did in* https://github.com/625alex/SmartThings/blob/master/devices/Pushbullet.groovy *to get me here.*

SmartApps and device type to push messages through Pushbullet (www.pushbullet.com) to specific devices.

*If you find this useful and feel so inclined, please donate.*

[![PayPal](https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=M93LDK4QJSSUS)

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

### Device Type

You need to have a Pushbullet device to use the notifier. To use the service manager, you first have to install the device type in [SmartThings IDE](https://graph.api.smartthings.com).

1. Go to the "My Device Types" section and click on the "+ New SmartDevice" button on the right.
2. Click on "From Code" and copy/paste the code from the "pushbullet_device.groovy" and click "Create".
3. Click the blue "Save" button above the editor window.
4. Click the "Publish" button next to it and select "For Me". The device type is now installed.

### Device Service Manager

The Pushbullet Connect app will help set up the device. You can use a new instance of the app for each Pushbullet device you want to push to.

1. Go to "My SmartApps" section and click on the "+ New SmartApp" button on the
right.
2. Click on "From Code" and copy/paste the code from the "pushbullet_connect.groovy" and click "Create".
3. Click the blue "Save" button above the editor window.
4. Click the "Publish" button next to it and select "For Me". You have now self-published your SmartApp.
5. Open the SmartThings mobile app on iPhone or Android and go to the Dashboard.
6. Tap on the round "+" button and navigate to "My Apps" section by swiping the menu ribbon all the way to the left.
7. The "Pushbullet Connect" app should be available in the list of SmartApps that appears below the menu ribbon. Tap it and follow the setup instructions.
8. When it asks for your API key, you can find it at http://www.pushbullet.com/account (Pro tip: Use pushbullet to get the API key from your computer to your mobile device without having to enter it.)

### App

The Pushbullet Notifier app is where you create your notifications.

*You can set up multiple instances of the app to use multiple devices with different capabilities or to have different messages*

1. Go to "My SmartApps" section and click on the "+ New SmartApp" button on the right.
2. Click on "From Code" and copy/paste the code from the "pushbullet_connect.groovy" and click "Create".
3. Click the blue "Save" button above the editor window.
4. Click the "Publish" button next to it and select "For Me". You have now self-published your SmartApp.
5. Open the SmartThings mobile app on iPhone or Android and go to the Dashboard.
6. Tap on the round "+" button and navigate to "My Apps" section by swiping the menu ribbon all the way to the left.
7. The "Pushbullet Notifier" app should be available in the list of SmartApps that appears below the menu ribbon. Tap it and follow the setup instructions.


