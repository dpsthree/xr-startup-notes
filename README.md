# XR Startup Notes
Initially Authored by Paul Spears (@theevergreendev) on 12/20/21

# Development modes
There are 3 environments to develop apps in for an Oculus
Quest 2
* Web
* Unity
* Unreal Engine

# Web
For web development there is a collection of APIs, WebXR, 
that are designed to provide ease of development
support for AR and VR devices. I don't yet know exactly which 
APIs are required to put an application into
"VR" mode.

Instead, I've done my initial research with a web/VR 
framework called A-Frame(https://aframe.io/). To test such an 
app on the headset, you will need to deploy it to the web and
access it via the Oculus Browser. To aid in the process for
development I used ngrok (https://ngrok.com/) for tunneling.

This was the fastest way to get started as a web developer 
and required the least amount of Oculus setup.

# Notes on non-web development
There are three different ways to test a native application
on the Oculus.
1. side loading
2. Oculus Link
3. marketplace deployment

Side loading involves the creation of a local app apk bundle
that is then loaded onto the Oculus.

The Oculus Link approach involves the installation of an 
application on the development PC. The Oculus can then 
connect to this running environment through a USB C 3.0 
compatible cable. The Link application has the ability to
inform you if your cable is compatible. The Oculus will then
allow you to access the "Link Mode" "app" from the Oculus
menu. This environment replaces the default Quest UI and 
environment and allows applications to be loaded into it 
through the PC.

Marketplace deployment requires building the application,
creating a marketplace entry and seeking Meta approval for 
publication. I have not yet gone through these steps

## Setting up for side loading
In order to side load an app you will need to first create an 
Oculus development account. You can use your existing 
facebook account for this, but you will need to indicate that 
you would like to be an Oculus developer and create an 
organization on the Oculus store. I find this easier to do 
through the mobile app by following the directions that 
appear when attempting to put the Oculus into developer mode. 

Once the developer account is created, you will need to put 
the Oculus into developer mode. After plugging the Oculus 
into your development machine, you will also need to confirm, 
on the Oculus, that it is OK to share data with the connected 
device.

Follow the directions for your development tool of choice for 
how to load the app.

## Setting up for Oculus Link
Before you can use the Oculus link approach you will first 
need to download and install the Oculus Link application on 
your development machine. This is a large download so be sure 
to allow for plenty of time.

After connecting to the PC with a compatible USB C 3.0 cable 
you will need to confirm on the Oculus that it is OK to share 
data with the connected device. To start link mode, open the 
Oculus option menu. Link mode should be one of the top level 
options.

Once in Link Mode, follow the directions for your development 
tool of choice for how to load the app.

# Unreal Engine
Coming Soon!

# Unity
I used the following tutorial to get started
https://www.youtube.com/watch?v=JyxbA2bm7os
It includes direction for side loading or using the Oculus 
Link for deployment.

It also includes some quick basics for getting up free 3d 
assets.
