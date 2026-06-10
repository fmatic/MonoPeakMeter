# FM-DX Webserver Mono Peakmeter

![Release](https://img.shields.io/github/v/release/fmatic/MonoPeakMeter?display_name=tag&style=flat-square)
![Platform](https://img.shields.io/badge/platform-browser-green?style=flat-square)
![Version](https://img.shields.io/badge/version-0.5.0-00c8ff?style=flat-square)

[![Support my work](https://img.shields.io/badge/Support-My%20Work-333333?style=flat-square&logo=buymeacoffee&logoColor=white)](https://buymeacoffee.com/jannedx)

![Mono Peakmeter Demo](docs/IMG_5430.GIF)

A modern RF/audio peak meter plugin for FM-DX Webserver inspired by professional broadcast monitor equipment and classic studio peak meters.

Designed especially for FM-DX monitoring with smooth animations, peak hold indicators and lightweight canvas rendering.

---

## Features

- Live RF signal meter
- Live audio modulation meter
- Peak hold indicators
- CLIP warning indicator
- Smooth interpolation and animations
- Broadcast style gradient meters
- Lightweight canvas rendering
- Native FM-DX Webserver UI integration
- Compact Mode
- Full-size detailed meter mode
- Theme aware colors
- Responsive layout support

---

## Screenshot

- Full-size broadcast monitor style mode
- Compact lightweight mode for smaller layouts

---

## Installation

1. Download the latest release from the Releases page
2. Extract the plugin into your FM-DX Webserver `plugins` directory
3. Restart FM-DX Webserver

---

## Compact Mode

Enable lightweight compact mode:

```js
const COMPACT_MODE = true;

Enable full-size broadcast monitor mode:

```js
const COMPACT_MODE = false;

## Planned Features

* Stereo / mono detection
* Stereo pilot detection
* Additional meter skins
* Vintage broadcast processor themes
* Tune Panel integration
* More responsive layouts
* Advanced peak algorithms


## Support

If you like this project and want to support development:

[Buy Me a Coffee](https://buymeacoffee.com/jannedx)

## License

MIT