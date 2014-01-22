#RPITools#

Simple script that handles commons admin tasks on a Raspberri Pi.

#Alpha project#

This project is a very young one and need a lot of work.

#Installation#

Type the following line on a raspberry pi console :

 `sudo curl https://raw.github.com/christophemaillot/rpitools/master/rpitools -o /usr/local/sbin/rpitools`
 
#Using#
 
Please note that RPITools is at a very early development stage, and has a very short command list for now.

`rpitools install_script <script name>` : install a script. See the script list below.

#Script list#

`rpi_keep_wlan0` : check the internet connection on a regular basis and issue a ifdown / ifup sequence on wlan0 if Internet seems to be down.
 
 
 