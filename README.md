# VolumeLock
MacOS Objective-C Status Bar app that locks the currently set audio volume level.

VolumeLock works by reading audio device properties, and setting up listeners for changes. If a user changes the volume setting, VolumeLock immediately changes it back to the locked setting.


## New Features

With Version 1.2 the locked volume setting will be saved in User Preferences. The saved setting and lock status will be restored when VolumeLock is restarted.

## Installation

1. Click "Releases" and from the Latest release, download VolumeLock.app.zip

2. Open the zip and move VolumeLock.app to Applications

    —  When starting for the first time, you'll see this message:

    ![1](https://github.com/mcdermottLab/VolumeLock/assets/2054545/332e15b8-8b63-4fb7-87a2-2114e0491428)

3. Click "OK" and then open System Settings —> Privacy & Security

    ![2](https://github.com/mcdermottLab/VolumeLock/assets/2054545/04742833-cce7-43f0-b777-6266c4543297)

4. Scroll down to the message about VolumeLock and click "Open Anyway" 

5. Finally,on the next dialog, click "Open"  

    ![3](https://github.com/mcdermottLab/VolumeLock/assets/2054545/9e63116e-3138-42c6-b1d0-7d3e1c70e121)

   
## Usage and Options

- When you first start VolumeLock it will be in the Unlocked state.  Set the system Sound volume to the desired level you wish to lock it to and then click "Lock" from the VolumeLock status bar item menu 


   ![1](https://github.com/mcdermottLab/VolumeLock/assets/2054545/2aa48c7f-c0d4-4b66-91f5-d14489690ff5)


- When locked, an Administrator authentication is required to unlock the volume setting or to quit VolumeLock.

   ![2](https://github.com/mcdermottLab/VolumeLock/assets/2054545/af09a5ce-92fd-4afa-95bc-83e331862d5a)


- If you quit VolumeLock while it is locked, when restarted it will automatically lock the system Sound volume to the previously locked setting.





