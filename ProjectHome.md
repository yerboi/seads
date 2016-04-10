
---

# About SEADS #

---

The **Source Engine Automatic Demo Saver** (_SEADS_) allows users to easily record and save demos in Source Engine games.  All Source Engine games and mods should now be supported and automatically have SEADS installed to work for them.

**Current Version:** 3.24 _(Updated 04/20/11)_  **[Click here](http://seads.googlecode.com/files/SEADS_3_24_1.zip)** to download. (.ZIP)

**Want to stay up to date?**  [Subscribe to the SEADS mailing list!](MailingList.md)

http://seads.googlecode.com/files/seads3_22.JPG

_Special thanks to "Something Awful" and "Strength and Honour" for their assistance in testing and creating SEADS._


---

# Additional Information #

---

## INSTALLATION INSTRUCTIONS ##

SEADS utilizes a two-stage automated installer; extract and run SEADS\_Setup.msi, then follow the instructions to choose an installation folder for SEADS.  After SEADS has been installed, it will automatically scan for available Source Engine games and enable SEADS support.


## RECORDING AND SAVING INSTRUCTIONS ##

  1. Make sure SEADS is running (an icon will be visible in the tray of a floppy disk.)
  1. Begin playing a Source Engine game (TF2, L4D, SourceForts, etc.)
  1. To record a demo, press the NUMPAD ENTER key (default).  To start a new demo, press NUMPAD ENTER again.
  1. When you're done, exit the game.
  1. When saving is completed, a window will appear showing how many demos were saved by SEADS.


## WHERE ARE MY DEMOS SAVED ##

In a subfolder of the game they were recorded from.  For example, Team Fortress 2 demos would be at:

> "C:\...\team fortress 2\tf\saved\_demos\~date~\xxxxx\_saved\_demo01.dem"

You can also jump to the last saved demo; right-click the tray icon and select "Go To Last Saved Demo".



## CONFIGURING SEADS ##

To configure SEADS, right-click the tray icon and select "Configure Settings".

**< General >**

This tab displays general program options and information:
  * Scan For Source Games - Checks for newly installed Source Engine games and enables SEADS support for them.
  * Save Recorded Demos - Checks for recorded demos that were not saved automatically and saves them.
  * Launch Options - Allows you to enable/disable "Run at Startup" and "Run Minimized" options.

**< Recording Options >**

This tab contains two primary option categories:
  * Keybind Options - Allows you to change keybinds used to start recording, stop recording, and create markers.
  * Naming Options - Allows you to enable/disable renaming demos with the map name.

**< Demo Browser >**

This tab contains options for the Demo Browser
  * Highlight Demos - Customize which demos are highlighted in the Demo Browser (Date - Red, Size - Orange, Markers - Green).
  * Recycle Demos - Customize which demos are automatically recycled by the Demo Browser.

## THE DEMO BROWSER ##

http://seads.googlecode.com/files/demobrowser4.JPG

The Demo Browser simplifies saved demo management for users.  To access the Demo Browser, right-click the SEADS tray icon and select "Open Demo Browser".  The Demo Browser will then open and look for any demos saved by SEADS.

**< Renaming Demos >**

To rename a demo in the Demo Browser, click inside the name box for the demo you want to rename, type the new name, and hit Enter.  A message will ask if you are sure you want to rename the demo.  NOTE:  Demo files cannot contain some characters, including spaces.  SEADS will automatically replace spaces with underscores and append .dem to maintain file types if you do not manually add .dem to the end when renaming.

**< Viewing Demos >**

To view a demo, select it in the Demo Browser list, then click on "Watch Selected Demo".  SEADS will then launch the game through Steam and begin playback of the demo file.

**< Converting Demos >**

There are two conversion options available in SEADS currently: Convert to HD AVI, and Convert to TGA.  Convert to HD AVI launches the selected demo through Steam and then prompts you to select a codec (some codecs may not function properly) to begin converting a demo to an AVI file.  When you are finished converting, open the console and type "endmovie" to stop recording the new AVI file.  AVI files are saved the initial game directory (i.e. - /team fortress 2/ or /left 4 dead/, not /tf/ or /left4dead/ ).  Convert to TGA launches the selected demo through Steam and then converts it to a sequence of TGA files that need to be combined in an external application such as VirtualDub to create a video.

Both options launch the game in 1280x720 for HD conversion by default.

**< Deleting Demos >**

You can delete multiple saved demos at once by highlighting as many as you like and clicking on "Delete Selected Demos".  A message will appear asking if you are sure.  Deleted demos will be moved to the Recycle Bin; this may take some time depending on the size and number of demos selected.


## DEMO MARKERS ##

Demo Markers are a new feature introduced in Version 3.21, and enables users to easily mark a demo in specific locations.  Demo Markers are multiple purpose tools depending on user goals.  This feature has no default keybind, and must be configured in "Recording Options" before it can be used.

**< Mark For Deletion >**

Demo Markers can be used to mark a demo for automatic deletion by the Demo Browser if the user decides the demo is not worth keeping.  This option can be configured in the "Demo Browser" tab.

**< Mark For Importance >**

Demo Markers can be used to mark a demo as important.  Simply press your chosen Demo Marker keybind at the end of a map to mark the demo, and it will be highlighted by default in the Demo Browser.

**< Mark Location in Demo >**

Demo Markers send the command "demo\_pause" to the Source Engine when created in the demo recording, which forces the game to pause playback.  In this way, Demo Markers can be used alongside high-speed playback to locate a marked location in a demo file without user intervention.  For example...


As a Sniper in TF2, I manage to single-handedly stop the opposing team's advance before being killed in the middle of a round.  I press the Demo Marker keybind I specified in the options menu ("P" for me), and a marker is created.  When I'm done playing the demo is saved as normal.  Two days later I open the Demo Browser to locate that clip to record for a video.  In the Demo Browser that demo is highlighted in green; I click "Watch Selected Demo", press Shift+F2 once the playback starts, and set the speed to 600%.  In a minute or two, the demo playback has paused at the location I made the marker; from there I can use the Go To Tick option to jump back 1,000 or 2,000 ticks and start recording there.


A big thank you to Steam User **rezOnance** for the idea behind Demo Markers.



---

# Questions?  Comments?  Bugs?  Suggestions? #

---


  * Email me:  neschampion AT gmail DOT com
  * On Steam:  http://steamcommunity.com/id/mo_steel
  * On Youtube:  http://www.youtube.com/user/mookalokka