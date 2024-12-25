# Ideas-for-future
My ideas to implement someday - feel free to make one of these but please open source 🙃

1. 2024-12-25: (oversimplified TLDR: xinput over webrtc and probably electron) On client side (eg. mobile device) you scan QR code generated on "host" device (eg. PC on which gaming happen). It opens website on client and client connects to server as directly as possible (eg. by peer to peer via WebRTC). On client is shown gamepad, and clicking keys on that gamepad sends them to server.

On mobile, client should be touch friendly; also it should make use of accelerometer/gyroscope and vibration motor (and think about other sensors). Ultimately remapping should be possible, and also connecting other gamepad to phone (for some reason). Think about wired usecases: eg. someone connects laptop as a client and map keyboard keys to gamepad buttons, but wants to use touchpad to control analog sticks.

On server side, if possible it should be as minimal as possible. Probably it isn't possible to create virtual system-wide xinput device only by opening website, so I guess some installation would be required. I guess the easiest way would be to make electron app. 

Maybe at the end it should hve also possibility to passthrough xinput and other events directly. Also, maybe creation of devices other than xinput (so eg. playstation gamepads) should be possible.

Some "references": blymp.io, sharedrop, snapdrop, https://github.com/TobiasMelen/acthung-webrtc.
