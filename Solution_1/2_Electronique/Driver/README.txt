https://learn.sparkfun.com/tutorials/samd21-minidev-breakout-hookup-guide/hardware-setup#driver-install

Windows Driver Installation

After plugging the board in, Windows will try – and fail – to search the Internet for drivers. Click the button below to download the drivers.

Then follow the steps below to install the drivers:

    1) After downloading, extract the ZIP folder and copy down the location of the sparkfun.inf and sparkfun.cat files.
    
	2) Open your Device Manager
        - In Windows 8 or 10, simply search for "Device Manager" and select the Windows app
        - See Window's resources for Windows 7.
        -(Start > Run > "devmgmt.msc", should work on almost any version of the OS.)

    3) In the Device Manager, expand the "Other devices" tree -- you should see an entry for "Unknown Device", Right-click and select Update Driver Software...
    Screenshot: Navigating the Device Manager
    
	4) Select Browse my computer for driver software. On the next screen
    Screenshot: Browse your computer for the driver
    
	5) Paste the directory location of your sparkfun.inf and sparkfun.cat files into the search location. Then hit "Next".
    Screenshot: Setting the driver location
    
	6) Click "Install" when the next pop-up questions if you want to install the driver.
    
	7)The driver installation may take a moment, when it's done you should be greeted with a "successfully updated your driver software" message!

Mac and Linux

Mac and Linux users shouldn’t need to download any drivers. The device should show up as a serial port as soon as it’s plugged in to your computer.