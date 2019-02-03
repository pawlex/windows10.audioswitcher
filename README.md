# windows10.audioswitcher
Task bar audio switcher

===== Description =====
Uses NIRCMD to switch audio device.
Arbitrary number of devices allowed.
Create new folder somewhere on the User/$USER filesystem.  I use a folder called "quickie".  Name is arbitrary
Create a 'toolbar' on your windows 'taskbar' and point it to "quickie"

===== For each device you want to quickly switch to: =====
 * Open "Sound properties" and go to "Device properties"
 * Rename each device to their appropriate function:
   * Speakers
   * Headset
   * Headphones
   * etc.

Create appropriate .cmd files within "quickie" appropriate for your setup.




===== NIRCMD =====
http://www.nirsoft.net/utils/nircmd.html

