StikDebug requires a specialized "pairing file" to communicate with your device "remotely". This pairing file is device-specific and required to use StikDebug; otherwise, StikDebug won't work. 

> [!WARNING]
> Caution: Because of iOS/iPadOS limitations, if you reset or change the passcode on your Apple Device, the pairing file will expire, and you will need to replace it.

# Method 1: On-device
This method uses StikDebug's built-in pairing menu and can only pair devices on iOS/iPadOS 27+ or tvOS 14+ (tvOS pairing does not work in LiveContainer yet).
In StikDebug, navigate to Settings → Pair a Device → Pair iPhone or iPad. Follow the in-app instructions to pair.

# Method 2: Computer
This method utilizes [iloader](https://iloader.app) running on a computer to generate and place the pairing file. Requires a computer and USB cable.

## Prerequisites
### On your Mac
1. Download and install iloader for [Mac](https://github.com/nab138/iloader/releases/latest/download/iloader-darwin-universal.dmg).

### On your Windows PC
1. Download and install [iTunes](https://apple.co/ms).
2. Download the iloader installer ([exe](https://github.com/nab138/iloader/releases/latest/download/iloader-windows-x64.exe) or [msi](https://github.com/nab138/iloader/releases/latest/download/iloader-windows-x64.msi) [recommended]).
3. Run the installer.

### On your Linux machine
1. Download and install `usbmuxd` (may be preinstalled for your distro, otherwise install with your package manager).
2. Download and install iloader for your distro ([Debian/Ubuntu](https://github.com/nab138/iloader/releases/latest/download/iloader-linux-amd64.deb), [Fedora/openSUSE](https://github.com/nab138/iloader/releases/latest/download/iloader-linux-x86_64.rpm), [other](https://github.com/nab138/iloader/releases/latest/download/iloader-linux-amd64.AppImage)).

## Generating/placing the pairing file
1. For best results, connect your device to your computer via a USB cable, but if your device appears wirelessly, that should work too.
2. Click `Manage Pairing File`.
3. To the right of "StikDebug" and any other apps you wish to pair, click `Place`. "Pairing file placed successfully!" should appear in green.
