# Auto-Terminal-ON
ubuntu

sudo nano .bashrc

lxterminal 


sudo nano /etc/profile

A Script Without End

You will only be returned to the command line when your script is complete. If your script contains an endless loop then you may want to 

use this line in the profile file instead :

sudo python /home/pi/myscript.py &


This will allow the script to run in the background but you will not see any text output from it.


