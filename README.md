# ptt.py
Made to repurpose my old AVERMedia C985 button as a makeshift push-to-talk foot pedal when I'm using a joystick playing games.

  invoke via command line
  ```
  python.exe ptt.py
  ```

Since this was just quick for personal use (but hey, maybe someone else will find it useful) I "hardcoded" the PTT key as '`'
you can change that just by going to line 23 - there's a link above it to the complete list of hexidecimal keycodes.

** Tested on **
* Teamspeak
* Ventrilo
* OBS

Mumble does something weird with how it registers global key input, which makes it
not function with this script. If I ever update this, that will probably be the update.

** Required  **
 * Python 2.7+ 	https://www.python.org/downloads/
 * pywinusb		https://pypi.python.org/pypi/pywinusb/ (or python.exe -m pip install pywinusb (2.7.9+))
 * pywin32		http://sourceforge.net/projects/pywin32/files/pywin32/
