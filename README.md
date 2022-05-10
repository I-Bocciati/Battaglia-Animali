VEGAS® Pro
August 2018
 
Contents
This document contains information on the following topics:
1. Welcome
2. What is new in Update 4
3. What is new in Update 3
4. What is new in Update 2
5. What is new in Update 1
6. What’s New in VEGAS Pro 16
7. Known Issues
8. System Requirements
9. Installation
10. VEGAS Pro User Manual
11. Demos
12. Technical Support
 
1. Welcome
 
Thank you for purchasing VEGAS Pro software. This document contains information about installing and using VEGAS Pro software on your computer.
 
2. What is new in Update 4
 
Bug Fixes

Crash that can happen when OpenColorIO library is not installed properly is now prevented
Incorrect values in metadata for HDR renders has been corrected
Improved handling of hardware dependent video plugins when GPU does not initialize properly
Likelihood of crash when resizing thumbnails in Project Media window has been reduced
Improved performance of thumbnail drawing within the project media window
Problem with some valid video plugins not appearing in the plugin chooser has been resolved
Crash when launching on a 2 GPU system when with one GPU disabled has been fixed
Smoothing parameter is now available in the basic mode of the Video Stabililtzation plugin
Crash when updating a grouped track that is not visible has been fixed
Crash when reading certain MP4 files is now prevented
Disabled some JDR project properties for non-HDR projects
Disabled HDR preview preference for 8 bit projects
Crash that may occur if the timeline ruler and speed controls are not visible as been resolved
Crash they may occur when beginning a render of building peaks or other similar tasks has been resolved
 
3. What is new in Update 3
 
New Features

In addition to manual refresh to keep the storyboard in sync with the timeline, an automatic refresh option has been added so the storyboard refreshes after each timeline edit
An update notification feature has been added in order to keep in better touch with users when new product updates and fixes are available
DX12 based HDR external preview support
The video stabilization plug-in now has three modes for use depending upon the level of control desired ranging from basic mode with simple one-click operation, to expert mode with a powerful set of optimization parameter controls
Automation for Video stabilization parameters enables you to make adjustments over time or to bypass stabilization during certain portions of a clip
HDR Mastering Display Metadata for rendering HDR10 content has been added to the Project Media window
A filter option in the Render As dialog box filters the render formats and templates down to just those are are 360° compatible when you've specified your project as a 360°in the Video tab of Project Properties
Mechanism is now in place to inform users when a new update of the software is available
Bug Fixes

Inconsistencies when analyzing a video for stabilization with the Static setting selected have been resolved
Closing and reopening the Project Media window no longer disengages storyboard hover scrub, and no longer resets storyboard in/out points
Stabilization works properly when the video is contained on a track that has an audio track above it on the timeline
Using the Esc key while dragging an event properly cancels the move operation rather than clearing the storyboard and causing a crash upon reopening the Project Media window
The mouse wheel works properly with OFX plug-ins even when Scroll Inactive windows is enabled in Windows
This update correctly preserves the order of effects in video effect chains that were created in VEGAS Pro 15 or earlier which involve pre-Event Pan/Crop effects and post-composite track effects
Manually adjusting the Zoom slider properly disables the Auto-zoom checkbox
Missing Aspect ratio options have been add back to the Properties dialog box
The Use Current Project Folder option has been fixed in the Advanced Save utility
Text boxes scroll correctly when Scroll inactive windows is enabled in Windows 10
Render template Frame Rate settings properly use a period or comma based on the language the application has been installed in
The Project Media window is no longer limited to showing just 100 thumbnails
Project Media thumbnails do not redraw when there are more than 49 shown and you move the mouse over them
Improved thumbnail reading in the Project Media window avoids crashing
Variable frame rate media plays back with properly synchronized audio
Fixed issue where improper thumbnail can appear for generated media in the Project Media window
Fixed issue where some MP4 files crashed the application when loaded into VEGAS
Fixed crash when loading some plugins on startup
Issue when envelopes move in the wrong direction when using the CTRL key while dragging is fixed
Audio Event FX window no longer remains open after deleting the track from which the audio effect is applied to
 
4. What is new in Update 2
 
New Features

You can now set any preset of the Titles and Text media generator as the default for the Insert Subtitles from Files and Insert Subtitles from Regions functions
You can now create subtitles by importing SRT files with the Insert Subtitles from files feature
Video scopes can now be set to display the NITS scale for HDR work, including for 8-bit projects
VEGAS now warns you if no track has been armed for recording when you start recording and enables you to specify which existing track or tracks you want to record to, or to create a new track and record to that
Replacing media in the Main Storyboard timeline now updates the project timeline
The user now has the ability to "pin" another video event to a motion tracked event
Custom frame rates can now be set when encoding using AMD and VCE render templates in the MAGIX AVC/HEVC formats
The Main Timeline storyboard no longer automatically reacts to changes on the timeline. A Refresh Storyboard button has been added to the Project Media window when viewing a storyboard which enables you to manually match the storyboard to the timeline
A Red background for the Main Timeline storyboard alerts the user when the storyboard is out of sync with the project timeline and must be manually updated
A dialog box warns the user that the Main Timeline storyboard cannot be altered until it is updated to be in sync with the main timeline
A Red warning bar at the edge of storyboard thumbnails indicates when the timeline event is longer than the media it holds
You can now set in/out points in the storyboard for audio-only files
You can now set in/out points in the storyboard for still-image files
The Storyboard now properly recognizes L and J cuts and orders itself appropriately
Added support for time stretched/compressed events hover scrub in and out point trimming, and storyboard refresh
A new OFX plug-in enables you to add video stabilization to 360° video
Bugfixes

The Neat Video (and other temporal effects) now works properly when placed before Pan/Crop in an event FX chain
MTS files now render properly at 25p or lower framerates
The Internet HD 720p 29.97 fps (AMD VCE) template now yields the proper framerate
Reordering items in the storyboard no longer causes media in and out points to be reset
Audio recorded using Quicktime on a Macbook Air no longer get corrupted by so4compoundplug
The stabilization tool's Zoom parameter now properly persists through project save, close, and reload
The Render As dialog box no longer gets hidden off screen in a dual monitor set up which would cause the appearance of VEGAS freezing
Media in and out points are now properly honored when adding an unassociated storyboard bin to the timeline
The Insert Subtitles from File operation now properly recognizes commas in the subtitle text
The Add at Project Frame Rate operation now works properly when the media frame rate does not match the project frame rate
The audio meter context menu properly appears as expected again
The Scene Rotation plug-in has been optimized and should no longer cause occasional crashes at start up
The AutoSave function no longer triggers the creation of an unwanted duplicate storyboard which could occur in some cases
Crash has been resolved when using video stabilization and motion tracking with an AMD Phenom II card
Double-clicking Color Correction custom tab parameters now properly sets the parameters to their defaults
Overwriting files when rendering with AMD VCE templates now properly reports file size
Deleting storyboard placeholders no longer cause crashes as they did in certain instances
Replacing a generated placeholder with a clip no long crashes the application as was the case in certain scenarios
Moving generated media in the storyboard now follows expected behavior
External preview now works properly through Decklink cards in 32-bit projects
Fixed potential inconsistencies caused by replacing a generated placeholder with a video clip
Moving a generated media thumbnail to the end of the storyboard no longer causes an unwanted duplicate thumbnail
Sync Cursor to Media Timeline again works properly when user clicks on a keyframe in the FX automation section
Unwanted extra generated media thumbnails are no longer created in the storyboard when changing the order of thumbnails
Importing bins from one project into another no longer causes a crash
Importing media from one project into another now works properly
The BattleCompVintage VST and other plug-ins now work properly
32-bit projects created in older versions of VEGAS now open properly as 32-bit in VEGAS Pro 16
Dragging a media generator to the Main Timeline Storyboard no longer causes a crash
The render destination folder is now used for temporary file creation during the render process to avoid inadvertently filling up the user's C: drive
Certain specific MOV files no longer cause a crash when stabilization is applied
Switching through presets no longer disables stabilization in any case
Event Pan/Crop animation now works properly on events that hold still images
Color samplers in the Parameters and Custom tabs of the Color Corrector OFX plug-in are now correct and consistent
Stabilization of video clips that contain zooms now works properly
The Auto Zoom option now works more exactly to eliminate black borders
Right Alt+z and Shift+Right Alt+z now properly give users of the Polish localized version ż and Ż
Color Curve channel behavior has been improved so that changing the channel on one changes only that one and no others, and new curves are always added with the default settings instead of the settings from the previous curve worked with
All files now retain Markers & Regions in Trimmer
Timeline performance problems caused by automatically updating the Main Timeline storyboard during a timeline edit have been resolved
 
5. What is new in Update 1
 
New Features

You can now split tangents on the Bézier Masking OFX plug-in so you can create curved masks with perfect accuracy
You can now preview HDR using the 10-bit OpenGL pixel format
A new script enables users to create text that is "pinned" to a motion tracked object
An improved interface makes the stabilization plug-in more intuitive and easy to use
It is now possible to automatically create subtitles based upon named regions in your project
Bugfixes

A proper error message appears if the user attempts to insert subtitles from a file without actually choosing a valid file
All QuickStart window buttons are now active when the user opens a project that already has media on the timeline
Stabilization now more properly handles accurate mode
Stabilization now recognizes black initial frames and works properly regardless of a black frame's presence
The Live Save function no longer conflicts with Master fader operation
Crosshair interacts for position parameters in OFX plugins now works as intended
The Stabilization plug-in's avoid Black Borders option now works more effectively
Bézier Masking Edit Mode is now properly limited to only one mask at a time
When you copy an event that has Video FX on it, then paste event attributes onto an event of a different resolution, the target event's Pan/Crop settings are properly handled
HEVC files rendered through the MAGIX HEVC QSV encoder now play back more efficiently
 
6. What's New in VEGAS Pro 16
 
New Features

Video stabilization has been completely redeveloped in house to provide far better stabilization results
Motion tracking enables the user to follow the motion of on-screen objects and apply video FX and filters to the moving area
Bezier Masking OFX plug-in provides complete flexibility in creating multiple masks with simple to complex shapes, apply masks to the media or video FX, and use a motion track to have the mask follow selected objects in the video
Project Media thumbnails now feature hover scrub so you can easily review media files without first adding them to the timeline or Trimmer
The user can mark in and out points on each clip in the Project Media window, then preview just the material between the two points and add just that material to the timeline
In and out points can be marked separately on the same media in different bins–especially important in the new storyboard bins
Project Media thumbnails can now be resized in order to see more detail in the thumbnail
You can now preview multiple files sequentially in the Project Media window (including the new storyboard bins) either by selecting no files (in which case they will all preview one after the other) or by selecting specific files (in which case, just those files will preview)
Significant workflow improvements have been added to the Project Media bin system in the Project Media window
You can now drag a project media bin (including the new Storyboard bins) to the timeline to add all of the contents of that bin sequentially to the timeline
More logically centralized tools for adding media to your project through the Project Media window
Quick Start dashboard provides quick access to major workflow operations
Added color swatches to the Device Preferences to provide a visual indication of the Interface Type preference
Tiny Planet OFX plug-in for creative treatment of regular and 360 footage
You can now easily add a missing audio or video stream back to your project automatically synchronized and grouped with its partner stream
A button has been added to the Render As dialog box to instantly set the render to location to match the project file location
Robust auto-save and backup options have been added so the user can specify how often they want their project saved or backups created
The user can generate automatic subtitle events on a new subtitle track from TXT and CSV files, including support for timecode in and out information in a CSV file so that the subtitles end up in the exact desired position
A new menu item allows the user to remove gaps between selected events
The user has an option to export HDR metadata in HEVC 32 bit projects which can then be ready by sites such as YouTube
Bugfixes

Multiple project media bin bugs have been resolved
Ctrl+Z and Ctrl+Y functionality has been restored in the tree view of the Project Media window
RAM usage is now managed properly and efficiently in complex projects
Double-clicking on a media generator thumbnail now properly adds the generator to the timeline
You can now properly directly access the context menu for Text parameter keyframes and keyframes properly receive focus in all click cases
A blank window no longer appears when the "Swap for" folder contains no compatible files
Non-functional Help button no longer appears in Edit Visible Button Set dialog box
VEGAS no longer crashes when a group track is removed via scripting
The Render As dialog has been refined so that it no longer shows incorrect options of some file formats
Export to Media Composer/Pro Tools AAF no longer fails when the video track contains a still image
Export to Davinci Resolve now delivers tracks in the proper order
The Video scopes now properly reflect ACES color-managed output
The Render As dialog no longer becomes hidden in certain circumstances
The Internet HD 720p 29.97 fps (AMD VCE) template for the MAGIX AVC/AAC MP4 file format now correctly renders at 29.97 fps as expected
For scripting, the ExpandTrackGroup method in the TrackGroup class no longer incorrectly collapses a group if it already expanded
The LUT filter and other OFX plug-ins now properly recognize special characters in folder names
 
7. Known Issues
 
If you are printing a rendered file to HDV tape, the file must precisely conform to the target HDV device and file type requirements, or the print-to-tape operation will fail. Rendering using the provided HDV MPEG-2 render templates—unmodified in any way—is required to successfully print to HDV tape.
VEGAS Pro templates for rendering multichannel audio in .wav/.wav64, .avi, and .mxf formats may be visible in other VEGAS applications that do not support multichannel audio. Using these templates in other applications will not produce the desired result and should be avoided.
Under some uncommon conditions on multiprocessor machines, you may encounter stability problems when using some Waves 5.2 plug-ins. In most cases, the stability issues can be resolved by clearing the Enable track buffering check box in VEGAS Pro (Options > Preferences > Audio Device).
You may not be able to render files larger than 4 GB using some combinations of settings in the Sony AVC encoder.
If you have multiple VEGAS or MAGIX applications (such as ACID, Sound Forge, CD Architect, etc.) installed, uninstalling other applications may cause your audio plug-ins to be removed from VEGAS Pro. To restore your audio plug-ins, uninstall and reinstall VEGAS Pro.
When the Show Video Monitor button in the Trimmer window is selected, video that you preview from the VEGAS Explorer and Media Manager windows is played back in the Trimmer. Because the Trimmer is placed in the same window dock as the Explorer and Media Manager, you will not see your video preview. To preview Explorer and Media Manager video, you can drag the Trimmer to a new dock group, or you can turn off the Show Video Monitor button to preview in the Video Preview window.
The Step Forward and Step Backward buttons in the Capture window are not supported by all HDV devices.
If your project contains still-image sequences, segmented .r3d files, or P2 MXF files, do not select the Copy media with project check box in the Save As dialog. Some frames or segments may not be saved when this check box is selected.
Installing driver 2.21 for the PDW-UI XDCAM drive can prevent VEGAS from starting. Uninstalling the driver or upgrading to version 2.3 will resolve the issue.
If you're running two instances of VEGAS Pro, external control devices are available only to the first instance of the software.
When using the Stereoscopic 3D Graphic Card as your preview device with an nVidia 3D Vision for Quadro or 3D Vision Pro setup on a Windows Vista machine, the 3D output may stop when opening another window (such as a video FX property page). If this occurs, please make sure you have the latest graphic card driver and 3D Vision USB driver installed. If installing the latest drivers does not fix the problem, try switching the primary and secondary monitors. There is also a known issue where content on the main window will flicker. This can be fixed by moving another window over the portions of the window that are flickering and then closing the overlapping window.
We recommend Windows 7 for nVidia 3D Vision for Quadro setups.
Rendering CineForm Neo3D files requires CineForm NeoHD, Neo4K, or Neo3D 5.1 (or newer) or GoPro-CineForm Studio, Studio Premium or Studio Professional. The CineForm Neo Player is not compatible with other CineForm products. Do not install Neo Player if you have another CineForm product installed.
CEA608 and CEA708 closed captions are supported over HD-SDI on AJA cards only. Line 21 captions are supported on AJA and DeckLink cards.
Right-clicking a media file and choosing Edit Source Project fails to load the project path saved in the media file for media rendered using the following settings: MainConcept AVC/AAC and Sony AVC (Memory Stick templates only).
In order for some devices to appear in the Device Explorer window, you may need to change the device’s USB Connect setting from Automatic or MTP to Mass Storage.
The Tools > Burn Disc > DVD with Menus and Tools > Burn Disc > Blu-ray Disc with Menus commands are unavailable if DVD Architect Pro is not installed.
If you want to use RAW camera files in your project, the Microsoft Camera Codec Pack will allow you to view RAW camera files and add them to the timeline.
When previewing through an SDI video preview device, audio and video quality issues may occur when previewing 720p video.
When using an AJA SDI device, AJA driver version 10.1 is required for audio and video preview. Do not use driver version 10.3.
For best results when previewing audio through an SDI video preview device, please turn off Video Preview on External Monitor before loading a project or changing project formats.
24p pulldown removal is not currently available for Panasonic P2 files.
Some MOV files recorded by devices running Apple iOS 6 may fail to read correctly when using QuickTime 7.7.2. Updating to QuickTime 7.7.3 resolves the issue.
When using some source files with highly saturated colors, you may notice color variations after rendering when the Project Properties > Video > Pixel Format is set to 8-bit. Change the setting to 32-bit floating point (video levels) to prevent IRE levels from clipping.
When using AMD Catalyst 13.4, Video Preview on External Monitor does not work correctly when using a display that is rotated into portrait mode.
Shot marks are not read correctly when copying DVCAM clips directly from an XDCAM Station. The shot marks are displayed correctly when you use the VEGAS XDCAM Explorer to import clips.
Only 4:2:0 10-bit HEVC rendering is supported.
Storyboards do not handle multiple instances of the same media.
Replacing a piece of media in a storyboard does not replace it on the timeline.
Using import media function to import media directly main timeline storyboard does not update the main timeline.
Auto-scrolling does not work within the storyboard.
Reordering media in the storyboard resets the in/out points to beginning/end.
Checkerboard artifacts may be visible in HDR external preview when preview quality is set to "Best" with certain kinds of footage; please switch to "Good" quality in such scenarios; this does not affect the actual rendered output
 
8. System Requirements
 
The following lists the minimum system requirements for using VEGAS Pro software:
A 64-bit operating system: Microsoft® Windows 7, Windows 8.1, or Windows 10
2.5 GHz 4-core processor (3 GHz and 8 cores recommended for 4K)
1.5GB hard-disk space for program installation
Solid-state disk (SSD) or high-speed multi-disk RAID for 4K media
8 GB RAM minimum (16 GB recommended; 32 GB recommended for 4K)
OHCI-compatible IEEE-1394DV card (for DV and HDV capture and print-to-tape)
USB 2.0 or faster connection (for importing from AVCHD, XDCAM EX, NXCAM, or DVD camcorders)
NVIDIA

For hardware rendering (NVEnc) GeForce 900 series or higher with 4GB

AMD/ATI

AMD/ATI® Radeon with 4GB and VCE 3.0 or higher (Radeon Pro series with 8GB for HDR and 32 bit projects)

Intel

Intel Skylake or newer processor required for QSV accelerated 8-bit HEVC/AVC decoding and encoding, Intel KabyLake or newer processor required for QSV accelerated 10-bit HEVC encoding and decoding
Windows-compatible sound device
Supported CD-recordable drive (for CD burning only)
Supported DVD-R/-RW/+R/+RW (for DVD burning only)
Supported BD-R/-RE drive (for Blu-ray Disc™ burning only)
Microsoft .NET Framework 4.0 (included on application disc) or 4.5
Additional 4K recommendations
Proxy workflow can be used to expedite 4K editing on all machines.
When the Preferences > Preview Device > Wait for vertical sync check box is selected, your frame rate will be limited if using HDMI 1.4 (HD: 60 fps; QFHD: 29 fps; 4K: 24 fps). The frame rate is not limited when using fully HDMI 2.0 compliant hardware.
 
9. Installation
 
The install utility creates any necessary folders and copies all files required by VEGAS Pro software to your computer.
 
Installing from a boxed product
Place the VEGAS Pro application disc in the drive. The setup screen is displayed (if AutoPlay is enabled for your optical drive).
If you have turned off the drive's AutoPlay feature, click the Start button and type D:\setup.exe, where D is the drive letter of your optical drive, and follow the on-screen prompts to complete the installation.
Click Install, and then follow the on-screen prompts to install the appropriate version of VEGAS Pro for your computer.
Installing from the Web
Download the install utility from our Web site.
Double-click the file, and then follow the on-screen prompts to install the appropriate version of VEGAS Pro for your computer. 
 
10. VEGAS Pro User Manual
 
The VEGAS Pro application disc includes a User Manual in Adobe Acrobat (PDF) format. The Acrobat format allows easy viewing and printing of the text. The manual is located in the Manual folder on the application disc.
In order to view the manual, you will need to install Adobe Reader. You can download the latest version of Adobe Reader from http://get.adobe.com/reader/.

 
10. Trials and Demos
 
If you would like information or trial/demo versions of other products from VEGAS, please visit our Web site. You will always find the latest technical information, trials, demos, and product announcements from VEGAS there.
 
12. Technical Support
 
If you experience problems or have questions while using VEGAS Pro, our technical support department is always ready to help you. Additional support and information can be found at http://www.vegascreativesoftware.com.
For a detailed list of Technical Support options, please visit our web site.