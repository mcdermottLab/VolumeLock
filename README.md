# VolumeLock
OS X Objective-C Status Bar app that locks the currently set audio volume level

The app works by reading audio device properties, and setting up listeners for changes. If a user changes the volume setting, VolumeLock immediately changes it back to the locked setting.

Once locked, an Administrator authentication is required to unlock the volume setting again.

(Initial commit in this repository was built in 2013, and was targeting OS X 10.7)


## Installation

Click "Latest Release" and download VolumeLock.app.zip.

Open the zip and move VolumeLock.app to Applications

When starting for the first time, you'll see this message:

![1](https://github.com/mcdermottLab/VolumeLock/assets/2054545/332e15b8-8b63-4fb7-87a2-2114e0491428)

Click "OK" and then open System Settings —> Privacy & Security

![2](https://github.com/mcdermottLab/VolumeLock/assets/2054545/04742833-cce7-43f0-b777-6266c4543297)

Scroll down to the message about VolumeLock and click "Open Anyway" 

Finally,on the next dialog, click "Open"  

![3](https://github.com/mcdermottLab/VolumeLock/assets/2054545/9e63116e-3138-42c6-b1d0-7d3e1c70e121)




