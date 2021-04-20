# JDownloader-Launcher-M1-ARM64
Alternative Launcher for JDownloader to use Azul-JDK (native apple silicon java jdk) to launch app natively

PRE-REQUISITES
Install Azul OpenJDK (JAVA) specified for Mac M1 Apple Silicon from here
https://www.azul.com/downloads/zulu-community/?os=macos&architecture=arm-64-bit&package=jdk
Choose latest version (.dmg) and install it

Download JDownloader from is own site and install as usual
It will install crappy (not so fast for me)
Install in default bin folder (simply don't change nothing and click next everytime)

After install JDownloader, extract the released binary from this repo in Application Folder (or wherever you want)
https://github.com/mccoy88f/JDownloader-Launcher-M1-ARM64/releases/download/0.1/JDLauncher.M1.v0.1.zip

Simply Launch it and Works!

As you can see in Monitoring App it will use native JDK and not the JDK for intel included in JDowloader app

Know Issue:
· Adding premium account seems do not open ui for adding, you can adding it with the old launcher, save, close and reopen with M1 launcher and it works.
· There's not icon on dock (because use java launcher, you will see that icon)

For other problem open issue just to share.
I will not resolve it beacuse this isn't an app, is a trick 🤟
We hope JDownloader will soon fix creating a native M1 APP
Greetings from Italy
