# Arduino Tool For Wiremod
 (No longer in development.) Tool for Wiremod that allows users to connect their physical Arduino to the addon. Please note that this addon is experimental and is not intended to be used like the normal Wiremod tools. Also, it probably goes without saying but this only provides you with the virtual half. You will obviously need a physical Arduino and at least a small amount of C++ experience in order to do anything with this addon.

# Requirements
 - Wiremod, which can be downloaded [here.](https://steamcommunity.com/sharedfiles/filedetails/?id=160250458)
 - My Arduino Gmod Interface module, which can be downloaded [here.](https://github.com/LambdaGaming/ArduinoGmodInterface)
 - A physical Arduino and at least a small amount of C++ experience, as stated above.

# How To Use
 Using the tool is fairly simple. You can find it in the "Chips, Gates" category. Once you have it selected, you can change various settings that include:
 - Whether or not it should be enabled on spawn. If disabled, the virtual Arduino will not be able to transmit or receive any data until turned on through a virtual input.
 - Whether or not the virtual Arduino should convert all strings sent by the physical Arduino to numbers. This is useful for communicating with Wiremod entities that only accept numbers for certain inputs.
 - The name of the serial port the physical Arduino is connected to. This is required to make the virtual Arduino function properly.
 - The model of the virtual Arduino. Model options are the same as the Wiremod CPU.

 Once you spawn it in, you can get to work connecting things as inputs, outputs, or both depending entirely on what you want to do, and then writing code for your physical Arduino to react to those inputs/outputs.

# Contributing
 - This project has been archived and is no longer accepting pull requests, but feel free to create your own fork.
