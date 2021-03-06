Additional Code Examples
========================


Here are additional plug-ins from the community. The long videos one are all based on the 
`THETA Sample Plug-in: Camera API <https://github.com/theta360developers/theta-plugin-camera-api-sample>`_
project listed above.



.. index:: accelerometer, compass, sensors

THETA Motion Sensors
--------------------
* Use THETA internal accelerometer and magnetic field sensors to trigger events such as taking a picture.
* `GitHub <https://github.com/theta360developers/theta-motion-sensor>`_
* `Discussion <https://community.theta360.guide/t/howto-use-theta-motion-sensors/4145?u=codetricity>`_

.. index:: opencv, hdr

HDR2EXR by Kasper Oerlemans
---------------------------
* Create HDR file inside the camera using OpenCV
* `GitHub <https://github.com/iamagod/HDR2EXR>`_
* `Discussion <https://community.theta360.guide/t/hdr-plugin-to-automatically-create-exr-file-for-vfx-use/4132?u=codetricity>`_

.. index:: live streaming, WebRTC

Skyway THETA Plug-in Example
----------------------------
* Uses WebRTC and a Skyway signaling server to establish two-way P2P communication for 
  video and audio.
* `GitHub <https://github.com/theta360developers/skyway_theta_plugin_example>`_
* `Documentation and Discussion <https://community.theta360.guide/t/theta-live-streaming-360-video-with-webrtc-direct-from-camera/4082?u=codetricity>`_

.. index:: M5Stack, ESP32, Arduino

M5Stack (ESP32 Arduino) Sample Serial Code
------------------------------------------
* Sample code to connect the THETA V to the M5Stack ESP32 Arudino with the USB port of the THETA. Take pictures, displays QRcode
* `GitHub <https://github.com/theta360developers/theta-plugin-m5-serial-remote-sample>`_
* `Documentation and Discussion <https://community.theta360.guide/t/m5-stack-esp32-and-ricoh-theta/4102?u=codetricity>`_

.. index:: OpenCV

OpenCV Plug-in
--------------
* NDK to use the OpenCV library inside the THETA.
* `GitHub <https://github.com/theta360developers/opencvsample>`_
* `Documentation and Discussion <https://community.theta360.guide/t/ricoh-blog-post-running-opencv-in-your-ricoh-theta/4084?u=codetricity>`_

.. index:: WebRTC

WebRTC Plug-in Sample Picture Shooting Only
-------------------------------------------
* Uses WebRTC to provide remote shutter function.
* `GitHub <https://github.com/theta360developers/theta-plugin-webrtc-sample>`_
* `Documentation and Discussion <https://community.theta360.guide/t/create-a-webrtc-p2p-shooting-app-with-the-theta-plug-in/4050/2?u=codetricity>`_


.. index:: user interface, GUI

Web GUI Sample
--------------
* Uses NanoHTTPd to build a web server for THETA Plug-is. Stores preferences using SharedPreferences.
* `GitHub <https://github.com/theta360developers/webgui-sample>`_
* `Documentation and Discussion <https://community.theta360.guide/t/creating-a-webui-for-your-theta-plug-in/4054?u=codetricity>`_

.. index:: microphone, audio

THETA Microphone
----------------
* Record audio from the THETA microphone. Use the THETA as a dedicated audio recorder
  without video.
* `GitHub <https://github.com/theta360developers/theta-microphone>`_
* `Documentation and Discussion <https://community.theta360.guide/t/how-to-record-using-a-microphone-with-the-ricoh-theta-plug-in/3733?u=codetricity>`_

.. index:: messaging

Messaging plugin
----------------
* Use messaging API from LINE to send a message from the RICOH THETA to a mobile phone. 
  Good for event notification. Can be adapted to any REST API messaging system.
* `GitHub <https://github.com/theta360developers/ricoh-theta-messaging-plugin>`_
* `Documentation and Discussion <https://community.theta360.guide/t/ricoh-blog-post-theta-plug-in-development-sending-love-with-theta/3327?u=codetricity>`_

.. index:: deep learning, tensorflow, ai, voice recognition

TensorFlow THETA
----------------
* Modified TensorFlow example for THETA V (Android). Object recognition,
  artistic style application, voice recognition, object detection
* `GitHub <https://github.com/theta360developers/tensorflow-theta>`_
* `Developer Documentation <https://medium.com/theta360-guide/howto-build-tensorflow-apps-for-ricoh-theta-1b64da06a0bd>`_
* `User Documentation <https://medium.com/theta360-guide/running-tensorflow-on-ricoh-theta-v-e9ca512174cf>`_
* `Discussion <https://community.theta360.guide/t/how-to-build-tensorflow-apps-for-ricoh-theta/3808?u=codetricity>`_


.. index:: user interface, GUI

Meowshot
--------
* Get a cat's attention by a voice, and take a picture. Kotlin
  example. Uses NanoHTTPd for webgui.
* `GitHub <https://github.com/theta360developers/meowshot>`_

Long 2K Video
-------------
* Bypasses 25 minute video recording limitation to record 1 hour and 24 minutes 
  of 2K video with spatial audio
* `GitHub <https://github.com/theta360developers/long-2k-video>`_
* `Discussion and Documentation <https://community.theta360.guide/t/theta-v-long-video-plug-in-recording-beyond-25-minutes/3483?u=codetricity>`_

Long 4K Video
----------------------------------------------------------------------
* Tested to 1 hour 24 minutes of 4K 30fps video with mono audio and 48 minutes 
  with spatial audio and default encoding.
* `GitHub <https://github.com/theta360developers/4k-long-video>`_
* `Discussion and Documentation <https://community.theta360.guide/t/theta-v-long-video-plug-in-recording-beyond-25-minutes/3483?u=codetricity>`_

Surveillance 2K
---------------
* 10 hour 55 minute saved to internal storage. 2K, 10fps
* `GitHub <https://github.com/theta360developers/surveillance-2k>`_ 
* `Discussion and Documentation <https://community.theta360.guide/t/theta-v-long-video-plug-in-recording-beyond-25-minutes/3483?u=codetricity>`_

.. index:: live streaming

Live Streaming Plug-in Sample for RICOH THETA
---------------------------------------------
* Sample application using WebRTC SFU to live stream spherical video to the 
  RICOH Cloud with the `RICOH Live Streaming API <https://api.ricoh/products/live-streaming-api/>`_
  for their cloud. 
* Author: Ricoh
* `GitHub <https://github.com/theta360developers/theta-plugin-ricoh-live-streaming-sample>`_


Cloud Upload 
------------
* Upload automatically from THETA to Google Photos for 360 and VR viewing
* Author: Ricoh
* `GitHub <https://github.com/theta360developers/theta-cloud-upload-plugin>`_
* Status: No longer works


.. index:: live streaming

Wireless Live Streaming
-----------------------
* 4K equirectangular live streaming from THETA direct to YouTube and Facebook using RTMP
* Author: Ricoh
* `GitHub <https://github.com/theta360developers/theta-wireless-live-streaming-plugin>`_

Automatic Face Blur
-------------------
* Automatically detect and blur the faces of people to protect privacy
* Author: Ricoh
* `GitHub <https://github.com/theta360developers/theta-automatic-face-blur-plugin>`_


FastCV Plug-in Sample for RICOH THETA
-------------------------------------
* Image processing via FastCV
* Author: RICOH
* `GitHub <https://github.com/theta360developers/theta-plugin-fastcv-sample>`_ 

GPS/GNSS Receiver Plug-in Sample for RICOH THETA
------------------------------------------------
* Receives GPS / GNSS data and updates position information in the camera
* Author: RICOH
* `GitHub <https://github.com/theta360developers/theta-plugin-gnssreceiver-sample>`_ 


THETA Sample Plug-in: WebAPI Capture Plugin
-------------------------------------------
* Great sample application to use the WebAPI from the plug-in
* Author: Shohara
* `GitHub <https://github.com/theta360developers/theta-plugin-web-api-sample>`_ 
