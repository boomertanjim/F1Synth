# F1Synth

F1Synth is a 3kb drum sequencer capable of running in the browser

## Description

F1Synth is a digital replica of the [Orbita by Playtonica](https://shop.playtronica.com/pages/new-device-orbita?srsltid=AU7gw4UXi7a3Y20xtRgwd-ixSaXxkbYBjw_thDXzKmVfv9UJunpiqhLW) that plays kicks, snares and hi-hats based on a circle's position in an orbit. This project is roughly 3034 bytes and can be run completely in a browser.

### Screenshots

<img width="1896" height="873" alt="image" src="https://github.com/user-attachments/assets/7aa35ef4-9bf8-496e-87e9-feb3f1e0eab1" />

## How To Use

- Copy the text from `dist/uri.txt` and paste it in the browser search bar

- There are three orbitals and each of them represent kick, snare and hi-hat from the smallest to largest

- Each of these orbital can have smaller circles of different colors to them and they spin around the orbital

- When these circles go past the gray line on the left of the orbitals, they play kick, snare or hi-hat based on the orbital

- Circles can be added by simply clicking anywhere in the orbitals

- In the same way, they can be deleted by clicking them

- Grey button on the right plays/pauses the spinning

- Slider below the orbitals control circle spinning speed

TL-DR:
Copy text from `dist/uri.txt`, Paste it in a browser search bar, Click Grey Button, Circles move, they play notes when passing grey line, Click orbital to add new circles, click circles to delete them.

## Building from Source

First, download Node.js from [the official website](https://nodejs.org/en/download/current)

Install Terser

```bash
npm install --save-dev terser
```

Download the `src` folder with the `index.html` file inside.

Download and put the `build.mjs` next to the `src` folder.

Run this code

```bash
node build.mjs
```

The URI file and the shrunken `index.html` file will be made in the `dist` folder

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
