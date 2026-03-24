# Terminal Voice Recorder

A lightweight and interactive command-line application for recording and managing audio directly from your terminal. Built with Python and `pyaudio`, this tool offers a fluid interface with robust file management, making it perfect for quick voice memos, podcast drafting, or system audio testing.

## ✨ Features

* **Interactive CLI:** A clean, constantly updating text-based interface.
* **Quality Presets:** Choose between High (48 kHz stereo), Medium (44.1 kHz stereo), and Low (44.1 kHz mono) recording formats.
* **Live Previews:** Listen to your current recording before deciding to save or discard it.
* **Pause & Resume:** Seamlessly pause and resume your active recording sessions.
* **File Management:** Play, rename, and sort your saved `.wav` files by date, name, or duration.
* **Trash/Recycle Bin:** Safely discard recordings to a hidden `.trash` folder with the ability to restore them or empty the bin permanently.
* **Persistent Configuration:** Automatically saves your preferred quality and save directory to `~/.config/terminal_recorder.json`.

## 🛠️ Prerequisites & Installation

This application requires Python 3 and the PortAudio system library to interface with your microphone.

### 1. Install System Dependencies

**For Ubuntu/Debian:**
```bash
sudo apt update
sudo apt install portaudio19-dev python3-pyaudio