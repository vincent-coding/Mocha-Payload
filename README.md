# Mocha Payload
Mocha Payload is a modified version of payload.elf allowing to launch the wiiu exploit.<br />They allow you very simply to launch the Mocha CFW Mocha directly instead of the Homebrew Launcher.<br /><br />This program is based on [GaryOderNichts](https://github.com/GaryOderNichts/configurable-payload)' code.

## WARNING
With this file, MochaCFW is launched instead of the Homebrew Launcher, which makes the Homebrew Launcher inaccessible by the browser.
You must therefore have the Homebrew Channel installed.<br /><br />The mocha.elf must also be located at this location on the SD card.<br />
```java
sd:/wiiu/apps/mocha/mocha.elf
```
## Additional information.
Test with and without the __"Skip this menu on launch"__ option.<br />Console used for testing:
- EUR: WiiU 5.5.4
- USA WiiU 5.5.4
<br /><br />Tested site:
- [u.wiidb.de](http://u.wiidb.de/) [Working]
- [wiiuexploit.xyz](http://wiiuexploit.xyz/) [Working]
- [Indexiine](https://gbatemp.net/threads/indexiine-load-cfw-during-boot-and-offline-without-a-vc-ds-title.553681/) [Not Working]
- [wiiubru.com](http://wiiubru.com/flump/) [Working]
