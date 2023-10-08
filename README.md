
## Fork Info

This is identical to the parent except for two lines, which puts Window's focus on the task bar before switching desktops, then unfocuses the taskbar afterwards. The result is [preventing an annoying issue](https://stackoverflow.com/a/70201208) where taskbar icons flicker after changing desktops.

To compile this, you will have to use [an old version of AutoHotkey](https://github.com/AutoHotkey/AutoHotkey/releases/tag/v1.1.29.01), specifying Unicode 64-bit. 

# Windows 10 Virtual Desktop Enhancer

**Warning:** I am officially no longer maintaining this project due to lack of time and interest. Thanks for using it and for all of your work towards helping me improve it. -sdias

## Introduction

Windows 10 Virtual Desktop Enhancer is a [AutoHotkey](https://autohotkey.com/) script which adds some useful features to Windows 10 Virtual Desktops, like:

- Extra customizable keyboard shortcuts to switch or move a window to a different desktop
- Customizable keyboard shortcuts to pin a window or a program to all desktops
- Setting a custom wallpaper for each virtual desktop (either a picture or a solid color)
- An indicator in the tray area customizable with various icon packs showing the number of the current desktop
- Assigning custom desktop names to each desktop
- Fully customizable tooltips showing the desktop name when switching desktops

## Main resources

- [Installation](docs/installation.md)
- [Customization](docs/settings.md)
- [Known issues](docs/known-issues.md)
- [Request assistance](docs/issue-page.md)

## Installation

Windows 10 Virtual Desktop Enhancer is extremely easy to install: you just have to download and extract the latest version of the script.

Please read [the installation page](docs/installation.md) for more detailed instructions.

## Customization

Windows 10 Virtual Desktop Enhancer is built to be customizable and to adapt to your needs: learn how to personalize your experience [here](docs/settings.md).

## License

Windows 10 Virtual Desktop Enhancer is licensed under the [MIT license](https://github.com/sdias/win-10-virtual-desktop-enhancer/blob/master/LICENSE).  
This means you are free to modify and redistribute this program as you wish, but you must include the license and this notice in your version.

## Credits

Thanks to GioBonvi (Giorgio Bonvicini) for all of his contributions to this project, and his active role as collaborator.

Thanks to Ciantic (Jari Pennanen) for his library and sample AHK script, which can be found [here](https://github.com/Ciantic/VirtualDesktopAccessor).

Thanks to engunneer for his AHK library, which can be found [here](http://www.autohotkey.com/board/topic/21510-toaster-popups/#entry140824).

Thanks to the creator of the ReadINI AHK library, found [here](https://autohotkey.com/board/topic/33506-read-ini-file-in-one-go/).

Thanks to the artists that created the packed wallpapers, whom I lost track of. Sorry.

Thanks to rob3110 on Reddit for the extra white icon theme.

Thanks to several people on reddit.com/r/windows10 and in the project's Github page for their suggestions.

Thanks to mlabaj (Martin Labaj) for his code for the window pinning functionality.

Thanks to chpock for his fixes related to the Windows 10 1803 update.
