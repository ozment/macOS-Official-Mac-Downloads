# macOS-Official-Mac-Downloads
Download different versions of macOS via official Apple directories. 
Original Author: u/ChrisWayg
From: r/hackintosh

When trying to download various versions of macOS (including older ones), I noticed, 
that it did not always work as expected. So i took some notes and put together this guide for reference.

Via App Store links or Apple direct download links.
You can download HIGH SIERRA, MOJAVE and CATALINA via App Store links:

# macOS Catalina ------------------->

    How to upgrade to macOS Catalina - Apple Support:
        https://support.apple.com/en-us/HT201475
    Get macOS Catalina - App Store URL:
        https://itunes.apple.com/us/app/macos-catalina/id1466841314?ls=1&mt=12

# macOS Mojave ---------------------->

    HOW TO upgrade to macOS Mojave - Apple Support:
        https://support.apple.com/en-us/HT210190
    APP STORE LINK - Get macOS Mojave:
        https://itunes.apple.com/us/app/macos-mojave/id1398502828?ls=1&mt=12
        
# macOS High Sierra ------------------> 

    HOW TO upgrade to macOS High Sierra - Apple Support:
        https://support.apple.com/en-us/HT208969
    APP STORE LINK - Get macOS High Sierra:
       	https://itunes.apple.com/us/app/macos-high-sierra/id1246284741?ls=1&mt=12


# For El Capitan and macOS Sierra Apple provides the direct download links instead of the App Store links in its own documentation. 
# The App Store links will only work on High Sierra and below, as Mojave and Catalina will refuse to download these older versions.


# macOS Sierra ------------------------------->

    HOW TO upgrade to macOS Sierra - Apple Support:
    https://support.apple.com/en-us/HT208202
    APP STORE LINK - macOS Sierra: 
    https://apps.apple.com/ph/app/macos-sierra/id1127487414?mt=12
    DIRECT DOWNLOAD LINK - macOS Sierra: 
    http://updates-http.cdn-apple.com/2019/cert/061-39476-20191023-48f365f4-0015-4c41-9f44-39d3d2aca067/InstallOS.dmg        

	- The installer will copy Install macOS Sierra into /Applications

# OS X El Capitan ------------------------------>

    HOW TO upgrade to OS X El Capitan - Apple Support:
    https://support.apple.com/en-us/HT206886
    
    APP STORE LINK - Get OS X El Capitan
    https://apps.apple.com/ph/app/macos-sierra/id1127487414?mt=12

    DIRECT LINK - Download OS X El Capitan
    http://updates-http.cdn-apple.com/2019/cert/061-41424-20191024-218af9ec-cf50-4516-9011-228c78eda3d2/InstallMacOSX.dmg
   
   	- The installer will copy Install OS X El Capitan into /Applications

# OS X Yosemite ---------------------------------->

    HOW TO upgrade to OS X Yosemite - Apple Support
    https://support.apple.com/en-us/HT210717

    DIRECT LINK - Download OS X Yosemite
    http://updates-http.cdn-apple.com/2019/cert/061-41343-20191023-02465f92-3ab5-4c92-bfe2-b725447a070d/InstallMacOSX.dmg

    - The installer will copy Install OS X Yosemite into /Applications


## For even OLDER VERSIONS try here:
	Title: How can I download an older version of OS X/macOS? - Ask Different
	URL: https://apple.stackexchange.com/questions/309399/how-can-i-download-an-older-version-of-os-x-macos


## Some of the problems relating to downloading macOS have been covered in this article:
	Title: How to download macOS Catalina, Mojave or High Sierra Full Installers
	URL: https://mrmacintosh.com/how-to-download-macos-catalina-mojave-or-high-sierra-full-installers/



## gibMacOS for Downloading macOS Recovery Image or Creating a Full Installer:
	https://github.com/corpnewt/gibMacOS

## The gibMacOS python script runs on Windows, Linux or macOS and is used in this Guide:

	Title: Downloading the Recovery HD image - /r/Hackintosh macOS Internet Install
	URL: https://internet-install.gitbook.io/macos-internet-install/preparing-your-installer.../untitled-1

	For example to get the Yosemite Recovery Image run in the Terminal ./gibMacOS.command --recovery -v 10.10 -m 10.10 (replace 10.10 with the version you need: 		(10.09 to 10.15)

	gibMacOS has a script to create the whole installer from the parts downloaded. 
	You can only get the Full Installer of the latest supported OS's by Apple (like High Sierra, Mojave and Catalina).

    ~ get the gibMacOS script

    ~ run the script in Terminal ./gibMacOS.command

    ~ select the appropriate entry

    ~ let it download and wait (when finished type 'q' to quit)

    ~ run ./BuildmacOSInstallApp.command

    ~ drag the appropriate download folder onto the Terminal window (press enter and wait)

    ~ the "Install macOS {MacOS Version}.app" will be in the same folder
    
 <img>https://preview.redd.it/8ddm1o37xt641.png?width=467&format=png&auto=webp&s=e2d81a22d3af4bc350c56b741ced191032ed9a9b</img>

r/hackintosh - How to download macOS from Apple's official download locations (3 methods)

More details here:
Title: Preparing macOS for Installation.
URL: https://fewtarius.gitbook.io/laptopguide/prepare-install-macos/preparing-the-usb-media#preparing-macos-for-installation
Thanks to u/midi1996 and u/fewtarius who provided additional instructions for gibMacOS.


## DOSDUDE1 PATCHERRS  -------------------------------------------------------->
@@ http://dosdude1.com

Each GUI App has a macOS downloader included: u/DOSDUDE1 or a hackintosh, 
you do not need to use any of the other features. 
The App downloads the full macOS installer from: swcdn.apple.com (checked with my firewall).

## macOS Catalina Patcher -------------------> 
    
    (Download macOS Catalina Patcher 1.3.0):
    OFFICIAL PAGE - http://dosdude1.com/catalina
    DIRECT URL  -   https://ipfs.io/ipfs/Qmdw4cRrrzBWGJXNhMpBx1QfVZ3kiUbKk1eWLPnw9XxZXt/macOS%20Catalina%20Patcher.dmg
       
       - - - > Download macOS: Continue > Continue > Download a Copy

## macOS Mojave Patcher -------------------> 

    (Download macOS Mojave Patcher 1.3.7):
    OFFICIAL PAGE - http://dosdude1.com/mojave
    DIRECT URL  -   https://ipfs.io/ipfs/Qmds4TpDcAXszxMMACdBYK7XA8ih2kBoiuV2ZWejebgzgY/macOS%20Mojave%20Patcher.dmg
       
       - - - > Download macOS: Continue > Continue > Download a Copy
       
## macOS High Sierra Patcher -------------------> 

    (Download macOS High Sierra Patcher 2.7.0):
    OFFICIAL PAGE - http://dosdude1.com/highsierra
    DIRECT URL  -   https://drive.google.com/open?id=1W992CqAjQa0A1gmWubnUeUarb4B4Jo-w
       
       - - - > Download macOS: Continue > Continue > Download a Copy
    
  <IMG>https://preview.redd.it/sf912vjzwt641.png?width=677&format=png&auto=webp&s=1d113d886c1fb599edad6882107762f83ad6533f</IMG>
       
## Related Links:

        Combo Updates for old versions (example): 
        https://support.apple.com/downloads/mavericks

        How to download old Mac OS X and macOS versions:
        https://www.macworld.co.uk/how-to/mac-software/download-old-os-x-3629363/
##
