# WebOS

**A tiny operating system that runs entirely in your browser. One HTML file, no installs, no dependencies.**

Boot it, log in, open windows, browse files, play games, watch videos and see other players' cursors in shared lobbies, all from a single `os.html`.

<!-- Add screenshots here: desktop, a few windows open, Multiplayer lobby with cursors -->

## Versions

| Version | Status | What it is |
|---|---|---|
| **Alpha** | Current | The first playable build. Everything lives in one file and new features are being added one at a time, so expect rough edges and changes between updates. |
| **Remaster** | Planned | A future remaster of WebOS. Details to be announced. |

## What's inside

### The system
- Boot screen and lock screen, with an optional password
- Start menu with app search, a taskbar with open-window buttons, clock, network and battery indicators
- Windows you can drag, resize, minimize, maximize and close
- Right-click desktop menu, switchable wallpapers, restart and shut down
- A virtual file system (Documents, Downloads, Pictures, Trash) that is saved in your browser

### Apps
| App | What it does |
|---|---|
| **Files** | Browse, create, rename and delete files and folders. Deleted items go to the Trash |
| **Terminal** | `ls`, `cd`, `cat`, `mkdir`, `cp`, `mv`, `rm`, `open`, `ps`, `kill`, `neofetch` and more (type `help`) |
| **Notepad** | Open and save text files, with Ctrl+S and an unsaved-changes warning |
| **Browser** | A simple web browser with back, forward and reload, plus a button to open pages in a real tab |
| **YouTube** | Paste a video or playlist link and watch in the built-in player, with a recent list. Optional in-app search if you add your own API key |
| **Multiplayer** | Public and private lobbies where every player gets a custom cursor with their name on top (see below) |
| **Task Manager** | See running windows and end them |
| **Calculator**, **Settings**, **Trash** | The basics: wallpapers, password, and reset |

### Games
- **Gloom**: an original Doom-style first-person shooter with its own raycasting engine, two kinds of demons, a shotgun and touch controls. Move with WASD, turn with the arrow keys or mouse, fire with Space or click.
- **Snake**, **Tic-Tac-Toe** (with an unbeatable hard mode) and **Minesweeper**

### Multiplayer
Join one of six public lobbies (up to 8 players each) or create a private lobby and share its 5-character code. Once you're in, everyone sees everyone else's cursor on their own screen, in each player's chosen color with their name on top. Clicks send a ripple, and positions scale between different screen sizes.

Lobbies run through free public servers, so there is nothing to host. You can point WebOS at your own server in the app's settings.

## Getting started

1. Download `WebOS.html`.
2. Open it in any modern browser.

That's it. You can also host it on any static site (for example GitHub Pages). Hosting it over `https` is recommended because the YouTube player works best from a normal web address.

## Privacy and notes

- Your files, settings, name and color are stored locally in your browser. **Settings → Reset WebOS** erases everything.
- In Multiplayer, your name, color and cursor position are visible to everyone in the lobby and to anyone listening on the public server. Private lobbies are unlisted, not secret. There is no chat, on purpose.
- YouTube plays through YouTube's embedded player. Some videos can't be embedded, and the ↗ button opens them on YouTube instead.
- Gloom is an original game. It is not Doom and does not use any id Software code or assets.
- WebOS is an independent project. YouTube is a trademark of Google LLC and Doom is a trademark of id Software. Neither company is affiliated with this project.

## Known limitations (Alpha)

- Many websites refuse to load inside the Browser app. Use the ↗ button for those.
- Your cursor doesn't update for other players while your pointer is inside an embedded page (YouTube or Browser).
- Multiplayer depends on free public servers, which can be slow or unavailable.
- Gloom has a single level.

## Roadmap

- **Alpha:** keep adding apps and features one by one, and fix what breaks along the way.
- **Remaster:** a planned future rebuild. More details soon.

## Feedback

Found a bug or have an idea? Open an issue.

NOTE: THIS APP/GAME IS VIBECODED