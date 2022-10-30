# simple_led_controller

This folder contains code to implement a very simple LED controller.

The code runs on the DA14531 module. More information on the DA14531 and how to code and upload firmware is described here: 
https://community.element14.com/technologies/open-source-hardware/b/blog/posts/easy-cost-effective-bluetooth-le-ble-with-dialog-da14531mod

To use the code, assuming that the DA145xx SDK is installed at C:\development\DA154xx_SDK, then extract the zip file in this repository to the path:

      C:\development\DA145xx_SDK\6.0.16.1144\projects\target_apps\ble_examples

Then, open the project using ARM Keil MDK (it is described at the link mentioned above) and build it and upload to the DA14531 module. How to do all of this is explained at the link mentioned earlier.

