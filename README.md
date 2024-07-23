# org.pharo.PharoVM
Try to implement a Flatpak of the Pharo VM

# How to use (even though it doesn't work)
First, you need to install `flatpak` and `flatpak-builder` through the package manager of your Linux distribution.

Then do:
```console
flatpak-builder --user --force-clean buildDirectory org.pharo.PharoVM.yml
```

The direction I was taking:
* Get the libssh source code
* Get libgit2 and compile it
* Compile the vm that will download all the necessary dependencies using libgit and libssh

However, I had some issues to compile libgit so I don't know if it would work or not.

If another route was to be taken, I added `dependencies.yml` with most dependencies with their URL and SHA keys
