~LaunchCold~

App Launcher for openbox, based on Gabriel Sabillon's MyLaunchpad (https://github.com/gaboelnuevo/mylaunchpad) with the "slingscold" look and feel.

~ Dependences:

gnome-menus2
pygtk
python-lxml
python-cairo
python-imaging 
python-distutils-extra

How to install:

~ Create folder "~/user/.launchcold"

~ Copy files into "~/user/.launchcold"

Use:

	Use default configuration:
    		$python2 /path-to/launchcold
	
	An specific xdg-menu (i.e. lxde-applications)
    		$python2 /path-to/launchcold lxde-applications
    		
	Or modify your "conf" file in section:
    		# Use custom menu like xfce-applications or lxde-applications
    		xdg-menu = desired-applications


For more configuration options and information you can check:
https://github.com/gaboelnuevo/mylaunchpad

Preview:

![alt tag](https://github.com/earvingad/LaunchCold/blob/master/LaunchCold-prev.png)
