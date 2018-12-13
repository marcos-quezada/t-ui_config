# T-UI Linux CLI Launcher personalised configuration

This is a repository to share my theme for th android T-UI laucher, details:
[T-UI Linux CLI Launcher Homepage](https://github.com/fAndreuzzi/TUI-ConsoleLauncher)

There's also a separate folder for the wallpaper I'm using. To create it I relied on the following tools and resources:
- [Linux Pics](https://gitlab.com/jstpcs/lnxpcs)
- [Image Magick](https://www.imagemagick.org/script/index.php)

  Example conversion command:

```bash
convert path/to/original-image.png -gravity northeast -resize "324x576" -background "#0D3642" -extent "1080x1920" ~/destination/image.png
```

**IMPORTANT NOTES!**

- The display, model and font used in your phone, might get you a result different to the screenshot.
- You will need to play around with the spacing, fonts and other variables to adjust to your device.
- Keep in mind that, to get a similar result as the one in the screenshot, you must have the latest beta version, which can be found in the previous link.


![alt text][screenshot]

[screenshot]: https://github.com/marcos-quezada/t-ui_config/blob/master/t-ui_marcos_theme.png

Feel free to take this as an initial configuration, and modify it to your taste.
