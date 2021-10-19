# impishgdm

_**This script assumes that the Installation of Ubuntu 21.10 is a fresh install. If you tried to change the GDM background with someother scripts, you first need to reset those changes. Other scripts may have the option --reset.**_

Change the login screen background for Ubuntu 21.10 only.

this script is to change the login screen background of Ubuntu 21
º.10 only.


you can download the `impishgdm` file via command line

    wget -qO - https://github.com/dtalens/impishgdm/archive/TrailRun.tar.gz | tar zx --strip-components=1 impishgdm-TrailRun/impishgdm

Once you downloaded the script `focalgdm3`. cd to the downloaded script file.

to set the background with Image  
`sudo ./impishgdm /absolute/path/to/image`

to set the background with color  
`sudo ./impishgdm \#aAbBcC` replace `#aAbBcC` with any vaid hex color code..

to reset everything that the script made..  
`sudo ./impishgdm --reset`

![result of Image](https://i.stack.imgur.com/ssYjj.png)

![result of Image with OSK](https://i.stack.imgur.com/xcpwT.png)

![result of color](https://i.stack.imgur.com/KmliD.png)

![result of color with OSK](https://i.stack.imgur.com/TFWP5.png)
