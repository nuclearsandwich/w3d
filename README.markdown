# w3d

Load JavaScript and CSS files in `~/.w3`, based on their filename via Chrome Extension.

## Requirements

- Python3+ is needed to serve the files under ~/.w3 via `python -m http.server` command.
- Chrome or Chromium.

## Installation

1. Hit <chrome://extensions>
2. Enable developer mode
3. Load unpacked extension
4. Navigate to your local .w3 folder and select the chrome-ext subfolder
5. Add .w3/bin/w3d to your user startup scripts.

## Customization

If for some reason you really really need port 3132 for something, you can
specify a different port by changing the port in both
[chrome-ext/w3.js](chrome-ext/w3.js) and [bin/w3d](bin/w3d).


## Runnin'

Start w3d and add some stuff to your `~/.w3/` directory.

# Credits

[@azer](https://github.com/azer) for the original .w3 scripts and extension.

Inspired from and based on [defunkt/dotjs](http://github.com/defunkt/dotjs) and [stewart/dotcss](https://github.com/stewart/dotcss/).
