# ubunsys
=============================================

<img src="https://raw.githubusercontent.com/adgellida/ubunsys/master/images/ubunsys.ico" width="80">

Configurable app referent to packages, updates and configurations.

<img src="http://i.imgur.com/1SJR6Af.png" width="500">

<img src="http://i.imgur.com/VbZ6eeb.png" width="500">

<img src="http://i.imgur.com/TPPM5vN.png" width="500">

<img src="http://i.imgur.com/SrJCFeE.png" width="500">

If you want to use PPA
=============================================

* Not updated to latest version yet

`sudo add-apt-repository -y ppa:adgellida/ubunsys`

`sudo apt-get -y update`

`sudo apt-get -y install ubunsys`

What this program do
=============================================

You can select a lot of apps and install them clicking only a button.

You can configure, repair... system with a few options.

Be careful! These initial versions has a lot of bugs and disabled functionalities.

If you want to help on this dev, say to me.

If you need help about compilation and packaging I have basic notions, ask me.

Tutorial
=============================================

Recommended steps:

1. Push on 'Update scripts' button.

Near the program version (green up arrow).

2. Push on 'Backup sudoers file'.

3. Then push on 'Enable sudo without pass'.

This way you can execute commands without questioning your sudo pass each time. More quick so.

You always can go to default pushing 'Import sudoers file' and selecting your backuped file before.

TO DO
=============================================

* Search box.

* Save selection.

* When package selection installed, unselect all boxes or hold them? By now, hold. Unselection commented.

* Implement code to generate new apps automatically to save a bunch of code lines.

* Load saved configurations of personalized user installations.

* Snap, AppImage, PPA (updated).

* Uninstall packages.

* Regroup files to clean main directory.

* First add all selected ppas. Then apt-fast -y update and finally install all selected packages. So, more quick.

DONE
=============================================

Download updated database about ppas each time you open app independent of app version. You push "update scripts button" and it does it.

Be care
=============================================

I'm not a senior programmer, nor junior. I program as a hobby. So I'm not following professional coding practises.

I know that my code is horrifying and not good implemented. With patience I'll go to improving it.

All experienced help are welcome.

Credits
=============================================

[Bernar Novalyi](https://thenounproject.com/bernar.novalyi/) from Noun Project that creates the app [icon](https://thenounproject.com/term/terminal/715962/) used here. Beautiful!

Release notes
=============================================

You can check it [here](https://github.com/adgellida/ubunsys/releases)
