So I picked up one of these ( https://www.ebay.co.uk/itm/125280541508 ) awesome 64 x 64 x 256 LED bags and it's better than expect, but as predicticed the app is aweful, so this is my journey to understanding it and building a library to interact with it.

What do we know so far

The bag operates as it's own WiFi hotspot. The app expects your phone to connect to the bags wifi.
The auth looks pretty normal, then, all I can see in the air (bar probe requests) is Blank wifi frames and QoS Data. No ethernet embedded in the 802.11

My assumption at the moment that it's serial data (several people have told me they've seen similar devices with serial data shovelled over BLE) embeded in 802.11 headers

However, wifi networking isn't my strongest field, so I've just uploaded pcaps so those far more knowledgable than me can offer an opinion

Have info/questions, You can find me on most social media via https://glenn.pegden.com/findmeon 
