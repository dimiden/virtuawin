VWDesktopIcons v1.4 - Steven Phillips

Description:

This  VirtuaWin  module  enables the user to select  which  desktop  icons are
visible and set their position on each VirtuaWin desktop. This module requires
VirtuaWin version 3.0 or above.


Installation:

NOTE: This  module  cannot be used with  Windows  'Auto  Arrange' or 'Align to
Grid' desktop icon options,  these options must be disabled  first. To disable
them right  click on the  desktop  and in the context  menu that opens  select
'Arrange Icons By' to access the sub-menu containing these options.

Copy VWDesktopIcons.exe into the VirtuaWin modules directory.

To use the unicode version instead, copy  VWDesktopIcons_unicode.exe  into the
modules directory and rename the program to VWDesktopIcons.exe


Configuration:

To configure a desktop's icons:

1.  Use normal VirtuaWin navigation to go to the required desktop
2.  Using  the  VirtuaWin  Setup ->  Modules ->  Configure  button to open the
    VWDesktopIcons configuration dialog 
3.  To hide an icon,  select  the icon from the right  'shown'  list and press
    Hide button to move them to the left 'hidden' list. Multiple  icons can be
    selected using standard window modifier keys (e.g. pressing Control).
4.  Use the Show  button  to move  icons that have been  hidden  back into the
    shown list.
5.  Pressing  the  Reset  button  will  make all icons  visible  and set their
    position to their default Windows location.
6.  When the 'Show new icons on this desktop'  checkbox is disabled, new icons
    created on other desktops will not be shown on the current desktop.
7.  When the  'Auto-up-date  this  desktop'  checkbox is disabled  the current
    desktop will not be  automatically  up-dated on a desktop change (i.e. the
    icon layout is fixed). If enabled the  position of icons is  automatically
    updated.
8.  The Store button can be used to store the current  position of all visible
    icons, this button must be used to change icon  positions when the current
    desktop is not automatically up-dated.
9.  The Align to Grid button will move all shown icons to a grid location, the
    size of the grid is set via the Size setting.
10. If   'Auto-align  to  grid  this  desktop'  is  enabled  then  icons  will
    automatically be aligned to grid on desktop change.
11. The Copy and Paste buttons can be used to copy the icon configuration from
    one desktop to another. 
12. Once the Shown and Hidden lists are correct press OK.

Copyright:

VWDesktopIcons is a freely distributed program and is licensed under the GNU
General Public License.

Copyright (c) 2006-2011 VirtuaWin (virtuawin@home.se)


HISTORY

Ver 1.4 - 2011/03/17

* 3182977 Fixed module to find desktop icon window on Windows 7.

Ver 1.3 - 2010/03/15

* Implemented windows 64bit support

Ver 1.2 - 2008/06/03

* Changed cfg file format and file name
* Added Show new icons and Auto-up-date desktop options
* Changed Restore to Reset and added Store button.
* Added multi-select support in icon lists.
* Added Align to Grid feature.

Ver 1.1 - 2007/08/01

* Added auto storing of icon positions per desktop
* Added Restore, Copy and Paste features.
