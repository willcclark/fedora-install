# fedora-install

A basic get-up-and-running Fedora install script.

## RUN AS YOUR USER!

Seriously, this changes usersettings. root for the entire script will NOT work.
It may require you due to the time it takes to enter your password multiple times.

## For a free, open source only install run it using

``` bash
sudo dnf install -y wget && wget "https://git.furworks.de/tobias/fedora-install/raw/branch/master/install.sh" && chmod +x ./install.sh && ./install.sh
```

## To also get nonfree extensions, like rpmfusion nonfree upstream or steam flatpak run it this way instead

``` bash
sudo dnf install -y wget && wget "https://git.furworks.de/tobias/fedora-install/raw/branch/master/install.sh" && chmod +x ./install.sh && ./install.sh --nonfree --steam
```
