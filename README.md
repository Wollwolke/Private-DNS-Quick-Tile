# Private DNS Quick Tile

> Private DNS Quick Tile - toggle and configure your Private DNS settings on Android 9+ from the comfort of your quick settings panel.

This fork adds the ability to switch the Private DNS feature on / off with app shortcuts.  
These enable automation of the settings using routines on Galaxy Smartphones.

## Setup

To modify the Private DNS settings, the app needs the `WRITE_SECURE_SETTINGS` permission.
This can only be granted using ADB:  

```bash
adb shell pm grant com.jpwolfso.privdnsqt android.permission.WRITE_SECURE_SETTINGS
```
