# VisuALS for Windows

Our mission is to love our neighbors by restoring independence, dignity, and hope through affordable assistive technology solutions. Specifically, VisuALS is a software package (in several versions) that enables those with debilitating conditions to use their eyes to communicate. The software works with off-the-shelf computers and eye-tracking devices to allow the patient to speak (text-to-speech), browse the web, access social networks, and use other applications.

The main differentiators of VisuALS over commercially available eye-tracking based augmentative and alternative communications devices are:

- **Affordability:** this free software combined with commercially available off-the-shelf hardware is much less expensive than packaged solutions.
- **Ease-of-Use:** most commercially available products have focused so much on adding features that the systems have become overly complex. VisuALS focuses first on speech generation and second on web and e-mail communications.

This is specifically the VisuALS package for patients (as opposed to the version designed for clinics and other institutional settings) that works on Windows computers (as opposed to the Android version).

## Getting Started

These instructions will get you a copy of the VisuALS software up and running on your local machine. 

### Prerequisites

There are three main components required for an integrated VisuALS system:
* This software
* A Windows personal computer
* Eye tracking hardware and related software

Additionally, a complete solution likely requires some kind of mounting solution and possibly a case to hold the computer and eye tracking hardware together.

#### Windows PC
The current requirements to support eye tracking include:
* Windows 10 RS3 or newer
* 6th generation Intel Core (i3/i5/i7-6xxx) and later, or equivalent AMD 64 bit processor, minimum 2GHz
* 8GB RAM
* USB port

If you want to be able to use the VisuALS system while on the go, you will probably want a tablet PC, like the Microsoft Surface Pro.

#### Eye Tracking Hardware
VisuALS works with Tobii eye trackers. The software works best with the most recent version, which currently is the [Tobii Eye Tracker 5](https://gaming.tobii.com/product/eye-tracker-5/). These devices come with drivers and other software that will need to be installed for VisuALS to work.

#### Mounting Solutions
The mounting solution for you will depend on where you want to use the system (at home or on the go) and the type of computer you are using. We have found [The Joy Factory](https://thejoyfactory.com/product-line/?_bc_fsnf=1&product_type=Mounts) to provide quality mounts at a good value.

#### Tablet Case
Tobii eye trackers don't easily mount to tablet computers.  [Tobii sells a solution.](https://us.tobiidynavox.com/products/eyemobile-mini-bracket)  


## Deployment
To begin using the VisuALS software, follow these steps:

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

## Authors

The original VisuALS software evolved out of student projects by Electrical and Computer Engineering students at Oklahoma Christian University. These original authors include:

* **Allison Chilton** 
* **Daniel Griffin**
* **Drew Harris**
* **Josh Bilello**
* **Aubrey Gonzalez**
* **Preston Kemp**
* **Tyler Sriver**

A company was then formed, VisuALS Technology Solutions, LLC, to productize and commercialize the software. The developers who furthered the software into the version that has been released here include:

* **McKenna Gameros**
* **Brendan McKinley**
* **Addison Schwamb**
* **Preston Seaman**
* **Russell Bian**
* **Nathaniel Markham**
* **Austin Merritt**
* **Andrew Ash**
* **Ian Robison**
* **Zachary Walden**

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project. **update link**

## License

This project is licensed under the GPLv3 License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Special thanks to Ash Srinivas for originally identifying the need for VisuALS and for working with the original student team.
* Thanks also to Steve Maher, Russ McGuire, Austin McRay, Jevon Seaman, Kevin McGuire, Seth Reiter, and all the other non-developers who helped make VisuALS a reality.
* We also thank the original investors in VisuALS Technology Solutions, LLC who funded the development, and Oklahoma Christian University which continues to provide support for the VisuALS project.
* We dedicate VisuALS to the memory of Weyton, Carl, Steve, and the other early users of VisuALS who provided the inspiration and feedback for making this the best solution it can be.



> Written with [StackEdit](https://stackedit.io/).
