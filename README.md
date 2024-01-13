[![Twitter URL](https://img.shields.io/twitter/url/https/twitter.com/deanthecoder.svg?style=social&label=Follow%20%40deanthecoder)](https://twitter.com/deanthecoder)
# ZX Speculator
ZX Speculator is a ZX Spectrum 48K emulator, written in C#. It leverages the [Avalonia](https://avaloniaui.net/) library for cross-platform capabilities. Initially developed on Mac, but has seen limited testing on Windows.

![Main UI](img/MainUI.png?raw=true "Main UI")

## Features
- **Platform Independent**: Built using [Avalonia](https://avaloniaui.net/), ensuring compatibility across various platforms.
- **File Format Support**: Compatible with .z80, .bin, .scr, .tap, and .sna files.
- **Integrated Debugger**: Comes with a built-in debugger for examination of the Z80 CPU state, including:
  - Instruction stepping.
  - Breakpoints.
  - Instruction history.
- **Sound Libraries**: Utilizes [OpenAL](https://www.openal.org/) on Mac and Windows for sound emulation.
- **Display**: Optional CRT TV effect.
- **Joysticks**: Kempston and Cursor joystick support.

## Development and Testing
Developed on a Mac environment, ZX Speculator is also tested on Windows, albeit with limited scope, and passes all the ZEXDOC tests and FUSE emulator tests.

![Jetpac published by Ultimate Play the Game](img/Jetpac.png?raw=true "Jetpac")

## Getting Started
### Prerequisites
- .NET compatible IDE, such as [JetBrains Rider](https://www.jetbrains.com/rider/) or [Visual Studio 2022](https://visualstudio.microsoft.com/vs/).
- Basic knowledge of C# and emulation concepts.

### Setup
The project is provided as C# source code:
1. Clone the repository from GitHub.
2. Open the project in your preferred IDE.
3. Build and run the application.

### Loading .tap Files
1. Type `Load ""` in BASIC.
2. The File->Open dialog will automatically open, allowing a .tap file to be specified.
3. Enjoy the loading experience.

### Keyboard
Move the mouse pointer to the small keyboard icon at the top-right of the screen to see a representation of the ZX Spectrum keyboard.
![Keyboard](img/Keyboard.png?raw=true "Keyboard")
Many keys on a modern keyboard are automatically mapped to their ZX Spectrum equivalent.  For example, backspace, square brackets, braces, math symbols etc.

The left shift key maps to **CAPS SHIFT** on the Spectrum, and the right shift key maps to **SYMBOL SHIFT**.

ESCape will reset the machine.

## Contribution and Improvements
ZX Speculator is an ongoing project and contributions are welcome. Whether it's improving emulation accuracy, testing on different platforms, or enhancing existing features, your input is valuable (although I can't always promise a fast response, as this is a side project).

## Limitations
- Emulation is not 100% accurate in terms of memory cycles and other specifics.
- Limited testing on Windows; there may be undiscovered issues - Sound support is known to be a bit sketchy.

## Future Plans
- Further testing.
- Refinement of emulation accuracy and performance.

---

Feel free to follow me on Twitter for more updates: [@deanthecoder](https://twitter.com/deanthecoder)
