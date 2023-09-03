# caffeine-ng-autostart
This is a fork to make `caffeine-ng` actually autostart.

As it turns out, the new versions of `caffeine-ng` already do this, but AUR just doesn't have them, so you have to build from source...

## dev preinit
git branch -M master
git remote add upstream <url>

## dev pull
git fetch upstream
git merge upstream/master

## dev push
git push

## dev install
sudo pacman -S dbus-python
make build
sudo make install
sudo glib-compile-schemas /usr/share/glib-2.0/schemas