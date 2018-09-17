Icons for your favorite Terminal Apps like [Hyper](https://hyper.is) or [iTerm](http://www.iterm2.com)
=========================================================

Like Visual Studio Code? Checkout https://github.com/dhanishgajjar/vscode-icons

### Dracula by [@zenorocha](https://github.com/zenorocha)

<a href="https://draculatheme.com/visual-studio-code/"><img src="svg/dracula.svg" title="Dracula" width="128"/></a>

### Cobalt2 by [@wesbos](https://github.com/wesbos)

<a href="https://marketplace.visualstudio.com/items?itemName=wesbos.theme-cobalt2"><img src="svg/cobalt2.svg" alt="Cobalt 2" title="Cobalt2 by Wes Bos" width="128"/></a>

### Monokai Pro by [@Monokai](https://github.com/Monokai)

<a href="https://marketplace.visualstudio.com/items?itemName=monokai.theme-monokai-pro-vscode"><img src="svg/monokai-pro.svg" alt="Monokai Pro themed iTerm icon" title="Monokai Pro by Monokai" width="128"/></a>

## How to Contribute

 - Download the sample icon sketch file. Change the colors and create your icon, without changing any dimensions.
 - Select the artboard and export a `svg` file.
 - Select the artboard again and export a `png` file, but @0.25x (256 x 256)
 - Download the [Image2Icon](http://www.img2icnsapp.com) App
 - Drop the svg as source and export a .ICNS for macOS
 - If you can afford pay for in-app purchases, so you can also export to .ico. If not then find an alternative way to create a .ico file from a `svg`
 - Send pull request for icon files only, DO NOT commit the sample sketch icon file

## How to Install

**Mac OS:**

Easiest way to change the icons is by using https://freemacsoft.net/liteicon/. Just Drag and Drop the custom icon and hit `Apply Changes`.

Copy the `.icns` file you'd like to use. Find VS Code in your Applications folder, right click the icon and select `Get Info`. Click the icon in the top right corner so that a blue highlight appears around it. `⌘ + V` to paste the new icon in. It may take a few restarts of VS Code for the icon to take.

If for some reason that doesn't work, then dragging the `.icns` to the icon (in the top left) of the info pane, until you see the green plus sign and then dropping it works.

**Windows:**

Right click on the shortcut App Icon, select properties and then shortcut tab and then `change icon` button.

**Linux:**

I think this works, but not sure https://bluesabre.org/projects/menulibre/

*Gnome3*

This example installs the `cobalt2` variant. Replace `cobalt2.png` with `dracula.png` for the dracula icon. Replace `cobalt2.png` with `monokai-pro.png` for the Monokai Pro icon.
```bash
$ xdg-icon-resource install --novendor --size 128 ./linux/cobalt2.png
```

Update the icon for the application you wish to use it with. This file is most likely in `/usr/share/applications/` or `~/.local/share/applications` and ends with `.desktop`.  For example, I have replaced deepin-terminal icon with the cobalt2 icon.

* edit (sudo) `/usr/share/applications/deepin-terminal.desktop`
* modify `Icon=deepin-terminal` -> `Icon=cobalt2`
* save/exit

> You may have to restart your desktop environment

---

You can get in touch with me at Twitter: [@dhanishgajjar](https://twitter.com/dhanishgajjar)

I post awesome stuff at
Instagram: [@dhanishgajjar](https://instagram.com/dhanishgajjar)
