## Welcome to VisuALS for Windows!

Our mission is to love our neighbors by restoring independence, dignity, and hope through affordable assistive technology solutions. Specifically, VisuALS is a software package (in several versions) that enables those with debilitating conditions to use their eyes to communicate. The software works with off-the-shelf computers and eye-tracking devices to allow the patient to speak (text-to-speech), browse the web, access social networks, and use other applications.

### Not being able to communicate is tough.

When your loved one is unable to communicate because of conditions such as ALS, Stroke, or non-verbal autism, it’s easy to get frustrated and have your loved one experience a locked-inside syndrome. 

We understand what it’s like taking ten to thirty minutes to figure out what your loved one is trying to say. Also, it’s totally normal to worry about their mental health. And you’re not alone. 

### This is what you can do with a VisuALS System:

VisuALS is an assistive communication device that helps those who have lost their voice to communicate again.

#### Text-To-Speech

Using eye-tracking technology, express your needs, feelings, and communicate with our on-screen keyboard and predictive text. 

#### Notepad

Type out notes, longer thoughts, speeches, prayers, or whatever else is on their heart. They can then save it as a file and open it later.

#### Web Browser

Our unique web browser allows users to surf the internet, send emails, access social networks, and more.

#### Home Automation

Use our system with Amazon Echo Dot to turn on and off the lights, change TV channels, and so much more.


Click [here](https://github.com/Icosahunter/VisuALS_Windows/raw/master/installers/VisuALS_Windows_V2.0_Installer.exe) to download the latest installer

## Installation and Configuration

### PC Setup (recommended)

 - Update Windows software to the latest available version
	 - Go to Settings (Windows icon at lower left, then select the gear symbol), then select “Update & Security”
	 - Check for Updates; if there are Updates (Pending install will show, then Pending restart).
	 - To completely install them, Restart the computer at that point (a button should pop up at the bottom of the Updates list that says “Restart now” - click that).
	 - You may need to repeat this process several times to get all the updates.
	 - This step can easily take several hours.
 - Change computer settings to make the system easier for use by eye gaze users
	 - Not all of these options may be available on your system. If you don't see the appropriate settings, you should be fine.
	 - Remove unneeded toolbar icons
		 - Right click on icons of any applications not likely to be used and select “Unpin from toolbar”
	 -  Set power settings to “Never” so that the system will stay active (otherwise someone will need to physically push a button to wake the system up)
		 - Go to Settings,
		 - Click on System,and then on “Power & sleep”
		 - Set all screen and sleep settings to “never”
	 - Disable touch keyboard (you will use the VisuALS keyboard instead)
		 - Go to Settings
		 - Click on Devices
		 - Click on Typing
		 - Toggle “Show the touch keyboard when not in tablet mode and there’s no keyboard attached” to off
	 - Disable handwriting panel (this can block the screen when the user is trying to communicate)
		 - Go to settings
		 - Click on Devices
		 - Click on Pen & Windows Ink
		 - Make sure that the dropdown “When I tap a text field with my pen..” is set to “Only in tablet mode.”
	 - Turn off the Windows error dialogue (this can also keep the system from operating without manual intervention)
		 - Search for edit group policy in the taskbar
		 - Navigate to computer configuration
		 - Click on the administrative templates folder
		 - Click on the windows components folder
		 - Click on the windows error reporting folder
		 - Double click on prevent display of the user display interface for critical errors
		 - Click the enabled radio button
		 - Click ok
	 - Disable automatic touch keyboard (you'll be using the VisuALS keyboard)
		 - Search services
		 - Find “Touch Keyboard and handwriting…” under services
		 - Double-click on that row in “Startup Type” column
		 - Change “Startup type” (middle of window) to Disabled and then click “stop”.
		 - Click “Apply”
		 - Finally, click ok and then close the services window (X at upper right corner of window).

### Install and Setup Tobii Software

 - Plug the Tobii 4C or 5, whichever you have, into the Surface Pro.
 - Install the Tobii software
	 - Alternative 1: Go to tobii.com/getstarted and download the latest version of Tobii eye tracking core software for the appropriate Eye Tracker. 
		 - Run the installer
		 - Allow Tobii to run
		 - Review and (if appropriate) agree to terms and conditions.
		 - Click continue, and then get started. (might need to click Tobii icon in bottom toolbar)
	 - Alternative 2: Windows may automatically install the Tobii Experience for the Tobii Eye Tracker 5. Allow it to do that. 
 - Complete the calibration process.
 - Enter the user's name to create a user profile.
 - For the Tobii 4C, when the screen goes black, hit the Escape button to leave the rest of the intro. For the Tobii 5, when it gets to the home screen of Tobii Experience, either minimize it or exit out of it.

### Turn on Microsoft Eye Control

 - (On last check this worked with the Tobii 4C, but not the Tobii 5.)
 - Under Settings, select Ease of Access
 - In the left menu, select Eye Control
 - Turn on Eye Control and acknowledge
 - In the Eye Control settings (the gear in the tool bar near the top of the screen) turn on Gaze Cursor.

### Install VisuALS Software

 - Download the software [here](https://github.com/Icosahunter/VisuALS_Windows/raw/master/installers/VisuALS_Windows_V2.0_Installer.exe)
 - Double click the package to begin the install process.
 - Follow the instructions.

