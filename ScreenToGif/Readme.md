﻿# ScreenToGif  

This is the current project of ScreenToGif.  

_VS 2019 and .Net 4.8 or newer required._


## What's new? (Version 2.24)

• [Installer] Added the option to install the shortcut to all users.  
• [Installer] When installing, the UAC prompt will only appear if necessary (for example, when installing the shortcut to all users).  
• Added the option to force the update to run with elevated privileges.  
• Updated the default parameters for exporting with FFmpeg (click on the reset button to load the new ones).  

### Fixed:

♦ When trying to insert an image with a different DPI than the project, it would import it with the incorrect size.  
♦ Added a warning when trying to import multiple images with different DPIs.  
♦ The app could crash when rendering a character which had a broken glyph (while using the caption feature).  
♦ The app was crashing when applying the 'Reduce Frame Count' while selecting the last frames.  
♦ It was not allowed to add a preset with a name already in use in a preset from another video type.  
♦ (Experimental) Added a workaround for the 'Not enough quota...' crash. It can be disabled on Options > Application.  

### Known Bugs:

♠ When importing multiple images with different sizes at the same time, the app does not ask to resize all images to the same size.   
♠ When exporting with FFmpeg, the last frame may be out of sync with the timmings of the project.  
♠ Cancelling a encoding of FFmpeg will result in a crash (file in use).  
♠ Keystrokes has a 1 pixel transparent border at the bottom-right sides when using a high DPI screen.  
♠ It's impossible to capture snapshots with the DirectX method.  
♠ When capturing with the DirectX, the recording will crash if the recording area is outside of the screen.  