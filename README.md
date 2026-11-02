# Ultimate Soundboard

A browser-based soundboard project with a large collection of sound clips and a set of playback and customisation tools.

The project was developed as part of the Astrocore work by **Figi8Cake and Geosjobbydo**. This repository is my fork, kept as part of my development history and as a place to explore the original website source.

<https://ultimatesoundboard.xyz>

## Features

- Search through the soundboard buttons.
- Play individual sound effects, or use the random and play-all controls.
- Add and remove favourite sounds, with favourites saved in browser storage.
- Adjust playback speed and volume.
- Switch between available colour themes.
- Use the browser's text-to-speech capability.
- Generate tones with the frequency control.
- Show or hide sounds marked as NSFW.
- Stop active audio playback.

Some features depend on browser support and the browser's audio and speech APIs.

## Built with

- **HTML** — page structure and soundboard controls
- **CSS** — layout and themes
- **JavaScript** — sound playback, search, favourites and settings
- **jQuery** — DOM utilities
- **Web Audio API** — tone generation
- **Web Speech API** — text-to-speech
- **HTML audio** — playback of the bundled sound files

## Repository structure

```
.
├── assets/       # Images and interface assets
├── Js/
│   └── Main.js   # Soundboard behaviour
├── sounds/       # Audio clips
├── themes/       # Stylesheets for the available themes
├── index.html    # Main soundboard page
├── .htaccess
├── LICENSE
└── README.md
```

## Run locally

There is no build step or package installation required.

1. Clone or download this repository.
2. Open `index.html` in a modern web browser.

For the best results, run it through a local static web server so browser features behave consistently. The page loads jQuery from a CDN, so an internet connection is needed for that dependency.

## Credits

The original project credits **Figi8Cake and Geosjobbydo** as its creators and was associated with [Astrocore](https://astrocore.net/).

This repository is a fork of the [Astrocore Team source repository](https://github.com/astrocore-team/astrocore-team.github.io). Credit for the original project and its assets remains with their respective creators.

## License

See the [LICENSE](LICENSE) file for the licence included with this repository.
