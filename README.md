So I picked up one of these ( https://www.ebay.co.uk/itm/125280541508 ) awesome 64 x 64 x 256 LED bags and it's better than expected, but as predicticed the app is awful, so this is my journey to understanding it and building a library to interact with it.

What do we know so far

The bag operates as it's own WiFi hotspot. The app expects your phone to connect to the bags wifi.
The auth looks pretty normal WPA, ~~then, all I can see in the air (bar probe requests) is Blank wifi frames and QoS Data. No ethernet embedded in the 802.11~~

~~My assumption at the moment that it's serial data (several people have told me they've seen similar devices with serial data shovelled over BLE) embeded in 802.11 headers~~

~~However, wifi networking isn't my strongest field, so I've just uploaded pcaps so those far more knowledgable than me can offer an opinion~~

The data is shovelled over UDP. It looks like a fair simple protocol of a 16-bit code denoting the action and then a bytestream of the actual image data. I'll upload new pcaps soon.

For working out and replicating the message format, it'll probably be easier to use the Android APK than reverse engineer it from PCAPs. https://apkpure.com/led-space/com.yj.led



Have info/questions, You can find me on most social media via https://glenn.pegden.com/findmeon 
