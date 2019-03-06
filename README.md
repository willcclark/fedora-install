# fedora-install

A basic get-up-and-running Fedora install script.

This was purposefully re-worked from my best-effort own setup script as a help and base for interested users taking part in the fedora os challenge but will be kept updated after as well.


It supposed to give you an easy starting point, with quite a few good tools and a better looking/usable theme, or simple things like reenabling the maximize/minimize buttons for gnome.

These are of course by nature my opinions for how to go about it, to save newcomers twenty pages of clicking in guis that you'd have to do to achieve the same.

If you have Improvements or Issues, contact me!:

https://t.me/wolfshappen



(So no, this is not "a random script". :P)


## RUN THIS AS YOUR USER!

Seriously, this changes usersettings. root for the entire script will NOT work.
It may require you due to the time it takes to enter your password multiple times.

## For a free, open source only install run it using

``` bash
#installs wget, gets the script, makes it executable and runs it
sudo dnf install -y wget && wget "https://git.furworks.de/tobias/fedora-install/raw/branch/master/install.sh" -O ./install.sh && chmod +x ./install.sh && ./install.sh
```

## To also get nonfree extensions, like rpmfusion nonfree upstream or steam flatpak run it this way instead

``` bash
#installs wget, gets the script, makes it executable and runs it with steam and nonfree repos added for things like nvidia drivers
sudo dnf install -y wget && wget "https://git.furworks.de/tobias/fedora-install/raw/branch/master/install.sh" -O ./install.sh && chmod +x ./install.sh && ./install.sh --nonfree --steam
```
