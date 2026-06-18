# Terminal Voice Recorder

A lightweight and interactive command-line application for recording and managing audio directly from your terminal. Built with Python and `pyaudio`, this tool offers a fluid interface with robust file management, making it perfect for quick voice memos, podcast drafting, or system audio testing.

## Features

* **Interactive CLI:** A clean, constantly updating text-based interface.
* **Quality Presets:** Choose between High (48 kHz stereo), Medium (44.1 kHz stereo), and Low (44.1 kHz mono) recording formats.
* **Live Previews:** Listen to your current recording before deciding to save or discard it.
* **Pause & Resume:** Seamlessly pause and resume your active recording sessions.
* **File Management:** Play, rename, and sort your saved `.wav` files by date, name, or duration.
* **Trash/Recycle Bin:** Safely discard recordings to a hidden `.trash` folder with the ability to restore them or empty the bin permanently.
* **Persistent Configuration:** Automatically saves your preferred quality and save directory to `~/.config/terminal_recorder.json`.

## Prerequisites & Installation

This application requires Python 3 and the PortAudio system library to interface with your microphone.

### 1. Install System Dependencies

**For Ubuntu/Debian:**
```bash
sudo apt update
sudo apt install portaudio19-dev python3-pyaudio

## License

MIT License — Copyright (c) 2025 nodefive

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
