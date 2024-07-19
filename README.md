# org.pharo.PharoVM
Try to implement a Flatpak of the Pharo VM

# How to use (even though it doesn't work)
First, you need to install `flatpak` and `flatpak-builder` through the package manager of your Linux distribution.

Then do:
```console
flatpak-builder --user --force-clean buildDirectory org.pharo.PharoVM.yml
```
