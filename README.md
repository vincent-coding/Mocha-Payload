# Mocha Payload
Mocha Payload is a modified version of payload.elf allowing to launch the wiiu exploit.<br />They allow you very simply to launch the Mocha CFW Mocha directly instead of the Homebrew Launcher.<br /><br />This program is based on [wiiu-env](https://github.com/wiiu-env/homebrew_launcher_installer)' code.

## WARNING
With this file, MochaCFW is launched instead of the Homebrew Launcher, which makes the Homebrew Launcher inaccessible by the browser.
You must therefore have the Homebrew Channel installed.<br /><br />The mocha.elf must also be located at this location on the SD card.<br />
```java
sd:/wiiu/apps/mocha/mocha.elf
```
And the payload.elf file must be here:
```java
sd:/wiiu/payload.elf
```
## Recommended configuration
Thanks to **niekniek** for giving it to me.<br />
This configuration is recommended because it launches Mocha CFW directly, with the possibility of launching the Homebrew Launcher Channel.<br />
You can find the configuration file, named `config.ini` in the `MochaCFW` folder, provided you have changed the basic configuration of MochaCFW.
```
[MOCHA]
viewMode=0
directLaunch=1
launchImage=1
noIosReload=0
launchSysMenu=1
redNAND=0
seeprom_red=0
otp_red=0
syshaxXml=0
```

## Additional information.
Test with and without the __"Skip this menu on launch"__ option.<br />Console used for testing:
- EUR: WiiU 5.5.4
- USA WiiU 5.5.4
<br /><br />Tested site:
- [u.wiidb.de](http://u.wiidb.de/) [Working]
- [wiiuexploit.xyz](http://wiiuexploit.xyz/) [Working] *even with the new version.*
- [Indexiine](https://gbatemp.net/threads/indexiine-load-cfw-during-boot-and-offline-without-a-vc-ds-title.553681/) [Working]
- [wiiubru.com](http://wiiubru.com/flump/) [Working]
