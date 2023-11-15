*In compliance with the [GPL-3.0](https://opensource.org/licenses/GPL-3.0) license: I declare that this version of the program contains my modifications, which can be seen through the usual "git" mechanism.*  


2022-05  
Contributor(s):  
Jyers  
>Upload tititopher's latest source  
- - - - - - - - - - - - - - - - - - - - - - - - - - - 


2022-02  
Contributor(s):  
Jyers  
>Merge remote-tracking branch 'upstream/bugfix-2.0.x' into bugfix-JyersUI  
- - - - - - - - - - - - - - - - - - - - - - - - - - - 


2021-11  
Contributor(s):  
Jyers  
>Merge remote-tracking branch 'upstream/bugfix-2.0.x' into bugfix-JyersUI  
>v2.0.1  
>Filament Load/Unload Fix  
- - - - - - - - - - - - - - - - - - - - - - - - - - - 


2021-10  
Contributor(s):  
Jyers  
>v2.0.0  
>Merge remote-tracking branch 'upstream/bugfix-2.0.x' into Upstream_JyersUI  
>Bring Back Display Firmware Folder  
- - - - - - - - - - - - - - - - - - - - - - - - - - - 


2021-09  
Contributor(s):  
Jyers  
>Ender 3 V2 Default Configs  
- - - - - - - - - - - - - - - - - - - - - - - - - - - 


2021-08  
Contributor(s):  
Jyers  
>Merge remote-tracking branch 'upstream/bugfix-2.0.x' into Ender_3_V2_JyersUI  
>Merge Fixes  
>Restore Default Configs  
- - - - - - - - - - - - - - - - - - - - - - - - - - - 


2021-07  
Contributor(s):  
Jyers  
>Merge remote-tracking branch 'upstream/bugfix-2.0.x' into Ender_3_V2_JyersUI  
>Merge Cleanup  
>Big Merge Fix  
>Fixing Regression  
>Revert "Merge Cleanup"This reverts commit 91641f4d7d2982c38895ea921cff404a83a764ec.  
- - - - - - - - - - - - - - - - - - - - - - - - - - - 


2021-06  
Contributor(s):  
Jyers  
>Fixed Build Version String  
- - - - - - - - - - - - - - - - - - - - - - - - - - - 


2021-05  
Contributor(s):  
Jyers  
>Default Config  
>Another Default Config Fix  
>Organized Display Firmware  
>Merge Cleanup  
>The Big Move Part 2  
>Merge remote-tracking branch 'upstream/bugfix-2.0.x' into Ender_3_V2_Extensible_UI  
>Temporary Purge More Fix  
>Added Purge More Option to Filament Change  
- - - - - - - - - - - - - - - - - - - - - - - - - - - 


2021-04  
Contributor(s):  
Corben Eastman  
Jyers  
>Added LCD backlight brightness control* Added LCD backlight brightness control

* Move LCD backlight menu items to better locations

* Format and Function Modifications

Co-authored-by: Jyers <jyers.m@gmail.com>  
>Fixed Default Config Compile Issue  
>Merge remote-tracking branch 'upstream/bugfix-2.0.x' into Ender_3_V2_Extensible_UI  
>Display Brightness Touchups  
>v1.3.0  
- - - - - - - - - - - - - - - - - - - - - - - - - - - 


2021-03  
Contributor(s):  
Jyers  
Henri J. Norden  
>G420 -> M420  
>Fixed Config Commit  
>Merge Leftovers  
>Stockify Default Configs  
>UI Framework and Menu Additions* UI framework changes, menu additions/fixes

Framework:
* Add Draw_Checkbox and Redraw_Menu methods
* Draw_Menu_Item custom icon support
* Draw_Float NaN support
* Status area negative Z value fix
* Draw_Popup keeps selection value for Confirm mode
* Clear_Screen documentation
* Replace active menu if block with switch in Value_Control

Menus:
* Add probe control to Move menu
* Add cold extrude temperature limit and power loss recovery control to Control/Advanced
* Add print statistics to Control/Info
* Auto Home moves extruder tip to Z_SAFE_HOMING position when finished
* Fix 'more' setting for menu items

* Update configuration files to include CREALITY_DWIN_EXTUI_CUSTOM_ICONS

* Display firmware with new icons

* Bugfix

* Add support for dual-row label to Draw_Menu_Item, refactor Info menu to use Draw_Menu_Item

* Fixed Custom Icon System

* Formatting and Menu Fixes

* Change custom icon defaults

* Fix strlen(NULL) check in Draw_Menu_Item

* The Great Indent

* Improved Check Mark

* Utilize Redraw_Menu and Draw_Checkbox

* Fix a few checkbox calls

* Z Offset and Manual Level Fixes

Co-authored-by: Jyers <jyers.m@gmail.com>  
>Fixing Config Commit  
- - - - - - - - - - - - - - - - - - - - - - - - - - - 


2021-02  
Contributor(s):  
Scott Lahteine  
Jyers  
>Slight Changes and Updates  
>Added Status Bar Scrolling  
>Merge remote-tracking branch 'origin/bugfix-2.0.x' into Ender_3_V2_Extensible_UI  
>Configuration Overhaul  
>Fixed User Confirm Prompts  
>Config Changes  
>Bugfixes and M117 in Menus  
>Added Manual Mesh Bed Leveling  
>Build #1.1  
>New Display Define  
>Build 1.1  
>Added Resume Fan After Pause  
>Fixed Negative Z Pos Issue  
>Configuration Updates  
>Add Host Action Support to Templates  
>Beeper Fix  
>Major Fixes  
>Extui Default in Configs  
>Enable HOST_PROMPT_SUPPORT  
>Merge Conflicts  
>Merge remote-tracking branch 'upstream/bugfix-2.0.x' into pr/20983  
>Oops Wrong Config  
>Enabled Nozzle Park  
>Extensible UI Base  
>Fixed Default Config  
- - - - - - - - - - - - - - - - - - - - - - - - - - - 


2021-01  
Contributor(s):  
Roxy-3D  
Jyers  
>Add Host LCD Progress Support  
>Added Preheat Settings  
>Revert "Adding custom move feedrate for G26 (#20729)"This reverts commit 14567f3459d23f6cad0ab055a839b8f2652de979.  
>Print Screen Fixes  
>Changed Config to E3V2  
>DWIN Rewrite  
>Big Bugfix/Feature Update  
- - - - - - - - - - - - - - - - - - - - - - - - - - - 


2018-09  
Contributor(s):  
Scott Lahteine  
>Fit task code for updated Max7219  
- - - - - - - - - - - - - - - - - - - - - - - - - - - 


2018-07  
Contributor(s):  
Scott Lahteine  
>Max7219 RTOS changes  
>Add M101 command for RTOS  
- - - - - - - - - - - - - - - - - - - - - - - - - - - 


2018-05  
Contributor(s):  
Roxy-3D  
>Marlin on RTOS  
- - - - - - - - - - - - - - - - - - - - - - - - - - - 

