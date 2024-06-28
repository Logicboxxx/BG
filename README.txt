	Thanks for downloading and checking out conky BG system monitor theme.  I know its a pretty basic concept for a conky and that there is more than 
a dozen of these already out there. I just wanted one slightly different but mainly wanted to design one to fit with other conky's I am actively
working on. When I say working on I mean that they’re done I’m just not OK enough with them to release them yet. Got a port monitoring/connections
monitoring one, a network conky with some helpful and what I  find to be extremely useful bells and whistles that others don’t have. 
At least none that I’ve seen so far.
	There are some additional files that you will need to download to run this conky properly.
Nothing too crazy, just a few tools that most likely already have on your system, at least a few of theme. Below is a list of the required dependencies 
for this conky and how to download them from your terminal. 
    • Curl		sudo apt-get install curl
    • wmctrl		sudo apt-get install wmctrl
    • xrandr		sudo apt-get install xrandr
    • lm-sensors	sudo apt-get install lm-sensors


	If you've not already done it, run "sudo sensors-detect" after you install lm-sensors assuming it wasn't already installed on your system and setup.
You will perhaps need to edit the file on line 104. There you’ll see ${diskio_read /dev/nvme0n1} and ${diskio_write /dev/nvme0n1}. 
Unless your HDD is labeled the same in your system, you’ll have to replace the dev/nvme0n1 with whatever yours is. You cane type “lsblk” or 
“ lsblk -o NAME,LABEL” in your terminal to find yours, just remember to put /dev/ in front of it.

	Feel free to contact me at logicbox@tuta.io 
	Check out my github for updates and new stuff  https://github.com/Logicboxxx
	
	Buy me a coffee. God knows i need the extra stimulation, im not shaking enough yet. XD
	buymeacoffee.com/logicbox                
