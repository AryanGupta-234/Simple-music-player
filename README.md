# Simple Music Player

A Tkinter desktop MP3 player with playlists, search and a recently played panel.

## What it does

- Opens a single MP3 file or a whole folder as a playlist (falls back to your Music folder if none is chosen).
- Play, pause, stop, next and previous controls, a position slider with elapsed and total time, and a volume slider.
- A search box that filters the playlist as you type.
- Keeps a recently played history in local text files and lets you jump back to recent songs.
- Light, dark and blend themes, plus keyboard shortcuts: Space (play/pause), Ctrl+O (open file), Ctrl+P (open folder as playlist), Ctrl+S (focus search).

## Built with

- Python 3
- Tkinter (GUI)
- pygame `mixer` (playback)
- mutagen (MP3 length)
- pyautogui (pop-up alerts)

## Run it

1. Install Python 3 (with Tkinter) and the dependencies:

       pip install pygame mutagen pyautogui

2. Start the player:

       python "mp3 player.pyw"

   On Windows you can also double-click the `.pyw` file.

The app writes small history files (`last.txt`, `recently played*.txt`) to the folder it is run from.

## Project status

Early learning project, written for Windows.

## License

Released into the public domain under [The Unlicense](LICENSE).

---

Part of [Aryan Gupta's projects](https://github.com/AryanGupta-234). Building [NOBAD](https://nobad-platform.aassworld99.workers.dev/): software with a point of view.
