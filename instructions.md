## Panopticon: We Never Turn Back

Panopticon uses AR to put eyes on the back of your head --- or rather, your canr.


Requirements:
  * An Android phone
  * A Wi-Fi network covering the area you intend to drive. (A mobile hotspot suffices; only LAN connections will be used.)
  * A Magic Leap One headset.
  * A car.

Instructions

  1. Set up your phone for streaming. Download CamOn from the Play Store, https://play.google.com/store/apps/details?id=com.spynet.camon&hl=en_US and begin streaming. Connect phone to the hotspot.
  2. Affix the phone to the car, facing rear. The car used for our demo had a "fin" on the roof, which made it easy to get a reasonably secure mount using nothing but duct taape.
  3. Connect the Magic Leap to the same network. Open the Helio browser. Place the window in a reasonable place (we used directly in front of the driver). Set it to "Following."
  4. Let "x" be the streaming URL shown in the CamOnn app. Then, in Helio navigate to "x/video/mjpeg". For example, if the URL is http://10.189.80.50:8080, navigate to http://10.189.80.50:8080/stream/mjpeg

## Challenges

We spent much of the first day getting stuff to run on the Magic Leap, and familiarizing ourselves with the device.

We then encountered two bugs in Magic Leap which burnt the bulk of our remaining time. The first bug was that the Magic Leap browser, Helio, is by default configured to not access LAN, and would not prompt for permission upon accessing a LAN URL. The second bug, more serious, is that the Magic Leap Media Plaper is evidently unable to load videos from LAN, even with permissions properly configured. A Magic Leap employee confirmed this bug and filed it internally on our behalf.

This meant that, in order to view the camera feed with good bandwidth, we could only view it in-browser. With hopes of a software hack smashed, we instead focused on rigging up a car.