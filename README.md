# Houdini Turntable Lock

A lightweight Python Panel for Houdini 21+ that keeps the viewport horizon level while tumbling
Intended for use with a SpaceMouse. Works somewhat with regular mouse navigation, but is slightly nauseating.

## Features
- Lock the horizon to world +Y or +Z
- Adjustable correction strength and update interval
- Works entirely locally (no external dependencies)

## Installation
1. Copy the contents of this repo into your Houdini user preferences folder:

	Windows: %USERPROFILE%\Documents\houdini21.0
	macOS: ~/Library/Preferences/houdini/21.0/
	Linux: ~/houdini21.0/

2. Start Houdini.

3. -Open the Python Panel Editor

   -Go to: Windows → Python Panel Editor

   -TurntableLock should be accessible from the dropdown menu at the top of the window

   -Make sure these boxes are checked in the lower section:

	-Include in Toolbar Menu

	-Include in Pane Tab Menu

   -Click Apply → Accept.

4. Open **Windows → New Floating Panel → + → Python Panel → Turntable Lock**.

##  Usage
- Toggle the checkbox to enable horizon lock.  
- Adjust *Strength* and *Interval* to taste.  
- Choose **World Up: +Y** (default) or **+Z** if your scene is Z-up.  

##  Notes
- Works in the active Scene Viewer.  
- If you’re animating a camera you plan to key, disable it while keying rotation.  
- Pairs well with 3Dconnexion’s “Lock Horizon” setting.

##  Credits
Directed by Kienan-the-Barbarian
The real heavy lifting by ChatGPT because I'm not a very adept programmer. Even most of this readme is AI generated because I'm also lazy. Sue me.

##  License
MIT License — free for anyone to use or modify.
