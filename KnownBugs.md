# Known Bugs #
The following is a list of known bugs in the Source Engine Automatic Demo Saver, sorted by version discovered.  Any information you can provide as to the circumstances of discovered bugs (screenshots, exception text, operating system and privileges, etc.) are of great help for me to debug the problems.  I've included error logging; when a problem occurs, a log.txt file should be created or added to in your "C:\...\SEADS\Source Engine Automatic Demo Saver\" folder.  Providing this log file or the contents in your email will help me immensely.


---

## Bugs: Version 3.23 ##

---


**Type:** _SEADS crashes on startup._

**Encountered:** When launching SEADS.

**Possible User Fix:** Delete the config file located at "C:\Users\$USER$\AppData\Local\Mo\_Steel\".

**Fix Status:**  Investigating.


---

## Bugs: Version 3.22 ##

---


**Type:** _SEADS causes my autoexec.cfg file for Left 4 Dead 2 to stop functioning._

**Encountered:** When playing Left 4 Dead 2.

**Possible User Fix:** Delete any autoexec.cfg files in the DLC folders in your Left 4 Dead 2 directory.

**Fix Status:**  Should be fixed in Version 3.23, pending testing.


---

## Bugs: Version 3.21 ##

---


**Type:** _"Save Now" button in the Configuration Window doesn't work._

**Encountered:** When trying to manually save recorded demos.

**Possible User Fix:** Run a Source Engine game for a few minutes, then exit and the demos should be saved properly.

**Fix Status:**  Should be fixed in upcoming Version 3.22, straightforward coding error.

---

**Type:** _Error box appears when trying to change keybinds saying log.txt access denied._

**Encountered:** When trying to save custom keybinds.

**Possible User Fix:** Right-click the SEADS shortcut, click Properties, click the Compatibility tab, and near the bottom check the box "Run this program as an administrator", then close the SEADS program and try again.

**Fix Status:**  Looking into it.


---

## Bugs: Version 3.20 ##

---


**Type:** _SQL-related error occurs._

**Encountered:** Opening the Demo Browser.

**Fix Status:**  Resolved with version 3.20 BETA 1.

---

**Type:** _Unable to use the View or Convert buttons on Left 4 Dead 2 recorded demos._

**Encountered:** Demo Browser: attempts failed.

**Fix Status:**  Will be fixed in version 3.21.  Uninstalling the Left 4 Dead 2 Demo should resolve the issue.


---

## Bugs: Version 3.10 ##

---


**Type:** _Program creates folders even when not needed._

**Encountered:** Testing for future features.

**Fix Status:**  Released 3.11 for minor fix.  Uninstall 3.10 and Install 3.11 to fix.

---

**Type:** _Unable to find file seads.cfg in Windows/system32/ folder._

**Encountered:** Configuration changes at startup..

**Fix Status:**  Released version 3.13 as potential fix (found problems with coding).


---

## Bugs: Version 3.0 ##

---

**Type:** _Unhandled Exception - Object reference not set to an instance of an object._

**Encountered:** During installation with three checkboxes checked: Startup, Minimized, Left 4 Dead.

**Fix Status:**  Problem should be resolved in Version 3.10; awaiting additional feedback.

---

**Type:** _Win32 Exception - Error box appears - process related._

**Encountered:** During usage of SEADS to record. (WinXP)

**Possible User Fix:** None currently; a potential coding fix is being tested.

---