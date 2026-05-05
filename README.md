# Light Crime Audio Player

A Winamp-inspired macOS audio player with a flat, 90s cyber aesthetic.

## About Light Crime

The 90s and early 00s were an era of personal computing, self-expression, rapid technical expansion, the web. We were barreling forward at the speed of innovation and culture, and for a brief period, the utopia of new media and self-expression were fueled by the imagination. And then... it stopped. Hotline, KaZaa, Lime Wire, Napster, Tumblr, ICQ, AOL Messenger, IRC, Usenet, Winamp... remember WinRAR? All became irrelevant really quickly, either due to legal restrictions or gutting of communities and platforms. Many artists have reflected on this, but I feel at this moment in time we're seeing that passion creep back through the cracks of the corporate chokehold on open web.

Light Crime aims to create modern software with a cozier personal computing approach. Spotify is great. Apple Music is meh but no ICE ads, and yet... they still separate you from your media and personal space. All the tools and technologies still exist, sitting dormant, but maybe people have moved on, or recessed to small corners of the web.

When I started coding it was with BASIC and Visual Basic 3. What a joy! But now, with the advent of paired programming with tools like Claude Caude, I don't have to worry about the labor intensive time suck of building something that cuts against the grain of modern technology. What I would have said "eh who is going to use that?" is replaced with "Who cares, I can spend an afternoon and be done with it." So I'm going through my backlog of software and art work I want to see in the world. And am no longer stuck in the mind trap of wondering how it fits into the current culture of social media and people's relationship to software.

*ahem* ... Anyways, I think curating your music on your computer is fun. Making playlists is fun. And generally, just enjoying your computer rather than a terminal to SaSS platforms is refreshing in 2026. Enjoy. - chris

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

## Screenshots: Main Player, Playlist Editor, Status Bar & Combined

<img width="356" height="578" alt="mainplayer" src="https://github.com/user-attachments/assets/65764112-e8df-483a-9f48-7c9506c1192f" />
<img width="356" height="546" alt="playlisteditor" src="https://github.com/user-attachments/assets/ee050de4-df23-475b-9bb0-c1e606105269" />
<img width="609" height="473" alt="allwindows" src="https://github.com/user-attachments/assets/f8c02574-b38f-4b2b-b2d2-a0c1eb086053" />

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

```
██▓     ██▓  ▄████  ██░ ██ ▄▄▄█████▓    ▄████▄   ██▀███   ██▓ ███▄ ▄███▓▓█████
▓██▒    ▓██▒ ██▒ ▀█▒▓██░ ██▒▓  ██▒ ▓▒   ▒██▀ ▀█  ▓██ ▒ ██▒▓██▒▓██▒▀█▀ ██▒▓█   ▀
▒██░    ▒██▒▒██░▄▄▄░▒██▀▀██░▒ ▓██░ ▒░   ▒▓█    ▄ ▓██ ░▄█ ▒▒██▒▓██    ▓██░▒███  
▒██░    ░██░░▓█  ██▓░▓█ ░██ ░ ▓██▓ ░    ▒▓▓▄ ▄██▒▒██▀▀█▄  ░██░▒██    ▒██ ▒▓█  ▄
░██████▒░██░░▒▓███▀▒░▓█▒░██▓  ▒██▒ ░    ▒ ▓███▀ ░░██▓ ▒██▒░██░▒██▒   ░██▒░▒████▒
░ ▒░▓  ░░▓   ░▒   ▒  ▒ ░░▒░▒  ▒ ░░      ░ ░▒ ▒  ░░ ▒▓ ░▒▓░░▓  ░ ▒░   ░  ░░░ ▒░ ░
░ ░ ▒  ░ ▒ ░  ░   ░  ▒ ░▒░ ░    ░         ░  ▒     ░▒ ░ ▒░ ▒ ░░  ░      ░ ░ ░  ░
  ░ ░    ▒ ░░ ░   ░  ░  ░░ ░  ░         ░          ░░   ░  ▒ ░░      ░      ░   
    ░  ░ ░        ░  ░  ░  ░            ░ ░         ░      ░         ░      ░  ░
                                          ░
```

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
