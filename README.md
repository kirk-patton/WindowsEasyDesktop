# WindowsEasyDesktop
Simplified Windows Desktop Settings 

## Seniors Difficulty With Windows

Windows has a good deal of functionality that many people find confusing and are unlikely to use.

* Drag & Drop
* Minimize / Maximize
* Double Click & Right Click
* Menus upon menus and settings...

When setting up Windows for my mother, the things I would consider simple are often the most challenging for her.
A good example is the Right-Click menu and the Double-Click(launch) vs. Single click(select).  My mom really just wants
to read and write e-mail, and all the other features in Windows end up causing her grief.  

## Restricted Setup - Less Is More

Git rid of Windows distractions that cause confusion and disable or simplify features. 

* Restrict the User account(NonAdmin) - Don't let applications be installed

* Don't Require a Login Password - Not good security practice though...
  * For this to work, a local account may be required (Not a MS Cloud Account)

* Set Windows Task bar to AutoHide

```
Right Click empty area of taskbar and select "Taskbar Settings" => "Automatically Hide Taskbar in Desktop Mode"
```

* Install [Nexus Program Launcher](http://www.winstep.net/)
  * Remove Default Icons
  * Drag & Drop Limited Set Of Programs To Launcher (Email/Web/Remote Support)
  * Set Position Left Side (Preferences Position)
  * Always on Top (Preferences Behavior)
  * Auto Hide After Short Delay (Behavior)
    1000ms (Auto Hide Settings)
  * Auto Hide For Maximized Applications (Behavior)
  * Lock Icons And Prevent Dragging (Behavior)

### Set Programs To Maximize By Default

Multiple open windows can be very confusing for seniors.  This is especially try if the program was opened by accident.  By reducing the number of programs the user can choose from, this problem can be reduced.  If we go a step further and maximize each of the programs and then close it, windows will remember that setting.  The next time the program is opened it will be maximized.

Combined with the Nexus launcher settings, the user will be presented with a maximized instance of each program they launch.

## Remote Desktop

Google makes an easy to use [remote desktop](https://remotedesktop.google.com/access/) solution.
The chrome browser is required at both ends.  The user sharing there desktop generates an access code that is shared with 
the person connecting.

