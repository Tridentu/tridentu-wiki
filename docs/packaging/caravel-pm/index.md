

# Caravel-PM


## What is Caravel PM?

Caravel PM is a package manager made specifically for Tridentu 2. It aims to package optional programs and libraries instead of going all in.

## How does it work?

Caravel-PM uses the xz format via libarchive to create the package. The package is also filled with a manifest and  custom uninstaller/installer scripts (Lua) that the user provides.

## How do I use Caravel?

to install packages, run the following command:

```
sudo caravel-pm install-package [package-name]
```

replace [package-name] with the name of the package you want to install.

To uninstall packages, run:

```
sudo caravel-pm uninstall-package [package-name]
```

Again, replace [package-name] with the name of the package you want to uninstall.
