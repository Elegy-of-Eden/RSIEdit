<h1 align="center">
  <img src="https://user-images.githubusercontent.com/10968691/125787499-7da697e2-5f7f-4d83-a9b0-995bbd23d032.png">
</h1>

RSIEdit is a GUI application for creating and editing [RSI files](https://hackmd.io/@ss14/rsis) and converting existing DMI files to the RSI format. 

It replaces the old [RSI Editor](https://github.com/space-wizards/RSI-editor) with this project and [RSI.py](https://github.com/space-wizards/RSI.py) with [RSI.NET](https://github.com/space-wizards/RSI.NET).


## Installing
The latest release for your OS can be downloaded [here](https://github.com/space-wizards/RSIEdit/releases/latest).

You can find every previous release [here](https://github.com/space-wizards/RSIEdit/releases).

### Arch Linux
You can find an (unofficial) installation package on the [AUR](https://aur.archlinux.org/packages/rsiedit-bin/):
```
paru -S rsiedit-bin
```
or
```
yay -S rsiedit-bin
```
Note that this package is not maintained by us. Read the PKGBUILD and then proceed at your own risk.

## Building
1. Clone this repo.
2. Run `git submodule update --init` to init submodules and download the importer.
3. Compile the solution.
