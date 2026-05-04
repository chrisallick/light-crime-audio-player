# Light Crime Audio Player

A Winamp-inspired macOS audio player with a flat, 90s cyber aesthetic.

## Features

- Plays MP3, FLAC, AAC, M4A, WAV, AIFF, CAF, MP4, MOV (audio extracted automatically)
- Parses M3U, M3U8, PLS, and XSPF playlist files
- Winamp-style scrolling marquee for long track/artist names — hover a queue row to marquee its title
- Bitrate + sample rate readout
- Custom borderless window with drag-anywhere chrome
- Lives in the menu bar — Dock icon hides when window is closed
- Hardware media key support (play/pause/next/prev F-keys)
- Now Playing integration (lock screen, Control Center)
- Shuffle with Fisher-Yates, previous-track restart threshold
- Drag-and-drop folders or files to add music
- Missing file detection — tracks turn red if moved, tap to re-link
- Playlist manager — create, load, and edit named playlists
- Persistent library and playlists across restarts

## Requirements

- macOS 13.0 (Ventura) or later

## Screenshots: Main Player, Playlist Editor

<img width="732" height="1156" alt="mainplayer" src="https://github.com/user-attachments/assets/65764112-e8df-483a-9f48-7c9506c1192f" />
<img width="732" height="1092" alt="playlisteditor" src="https://github.com/user-attachments/assets/ee050de4-df23-475b-9bb0-c1e606105269" />

## Install (I didn't want to pay for Apple Developer account yet lol!)

1. Download the latest `.dmg` from [Releases](../../releases)
2. Open the DMG and drag **Light Crime Audio Player** to your Applications folder
3. Try to open the app — macOS will block it with a Gatekeeper warning
4. Go to **System Settings → Privacy & Security**
5. Scroll down to the Security section — you'll see a message about Light Crime Audio Player being blocked
6. Click **Allow Anyway**
7. Try opening the app again — click **Open** on the confirmation dialog

This is a one-time step per machine. The app runs normally after that.

## Usage

| Action | How |
|---|---|
| Add music | Drag folders/files onto the window, or click **Add Music** |
| Play / Pause | Click the button, press **Space**, or use media keys |
| Next / Prev | Click arrows, press **← →**, or use media keys |
| Seek | Drag the scrubber bar |
| Shuffle | Click the shuffle icon in the transport row |
| Playlists | Click **Playlists** in the toolbar |
| Hide to menu bar | Click **×** — audio keeps playing |
| Show player | Click the waveform icon in the menu bar |

## Coming soon!

1. Theme editor for skinning: background images
2. Visualizer
3. Internet radio support.

## Not Yet Supported

- OGG Vorbis, Opus, WMA, APE
- These formats are detected and reported gracefully rather than crashing

## License

[Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/)

You may share and adapt this work for non-commercial purposes with attribution. Commercial use is not permitted.
