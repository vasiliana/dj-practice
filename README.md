# DJ Practice Booth

Practice DJing at home, in your browser.

You get **2 Pioneer CDJ-3000 players** and a **DJM-A9 mixer** on screen, and you can load your own MP3s, just like plugging in a USB stick.

Everything is in one file: [`dj-practice.html`](dj-practice.html). You don't need to install anything or be online.

> The app's own text is in Greek. Button names in this guide are written exactly as they appear on screen.

---

## How to open it

**Option 1: Online (easiest)**

Open this link in **Chrome** or **Edge**:

```
https://<username>.github.io/<repo-name>/dj-practice.html
```

To turn this link on (one time only):
1. On GitHub, go to your repo → **Settings** → **Pages**.
2. Under **Source**, pick **Deploy from a branch**.
3. Pick branch **main** and folder **/ (root)**, then click **Save**.
4. Wait 1–2 minutes. The link appears at the top of the **Pages** screen.

> GitHub Pages is free only for **public** repos.

**Option 2: Offline**

1. On GitHub, click **Code → Download ZIP** and unzip it.
2. Right-click `dj-practice.html` → **Open with** → **Chrome** or **Edge**.

---

## Getting started

1. Click **POWER**.
2. Click **📁 USB** and pick the folder with your songs.
3. On a player, click **BROWSE** and double-click a song.
4. Press **PLAY** and push up that channel's fader on the mixer.

---

## Keyboard controls

You don't need the mouse for the main buttons. The keys work even when your keyboard is set to Greek.

### Players

| What it does | Player 1 (left) | Player 2 (right) |
|---|---|---|
| **CUE** | `Z` | `N` |
| **PLAY / PAUSE** | `X` | `M` |
| Nudge slower / faster | `A` / `S` | `K` / `L` |
| Hot Cues A, B, C, D | `1` `2` `3` `4` | `7` `8` `9` `0` |
| Delete a Hot Cue | `Shift` + hot cue key | `Shift` + hot cue key |
| 4-beat loop | `Q` | `U` |
| Exit / restart loop | `W` | `I` |
| Beat Sync on/off | `E` | `O` |
| Jump back / forward | `D` / `F` | `H` / `J` |

### Mixer

| What it does | Key |
|---|---|
| Crossfader left / right (hold) | `←` / `→` |
| Beat FX on/off | `Space` |

### How CUE works (same as a real CDJ)

- **When paused:** press CUE to set a cue point where the track is right now.
- **Hold CUE** on the cue point: the track plays while you hold it and jumps back when you let go.
- **While holding CUE**, press PLAY to keep playing.
- **While playing:** press CUE to jump back to the cue point and stop.

### Good to know

- Keys don't work while the song list (**BROWSE**) is open or while you're typing in search.
- The full list is also in the app: click **⌨ Οδηγίες** (Help) at the top right.

---

## Using it on another computer

- **Use Chrome or Edge.** Other browsers may not play sound.
- **Your music is not on GitHub.** Bring your songs on a USB stick or in the cloud (OneDrive, Google Drive).
- **Pick your music folder every time.** The browser can't remember it.
- **Beat grid fixes stay on that computer only.** You may need to fix some grids again on a new computer.
- **Headphones:** each time, click **🎧 Ήχος / Ακουστικά** (Sound / Headphones) and pick **Split cue**. You'll hear the cue in your left ear and the main mix in your right ear.
- **No sound?** Check that you clicked **POWER**, the channel fader is up, **MASTER LEVEL** is up, and your computer's volume is on.
- **Work or school computer?** If you can't pick a folder, drag the MP3 files onto the page.

---

## Don't upload your music

- Most songs are **copyrighted**, and a public repo lets anyone download them.
- GitHub doesn't accept files **bigger than 100 MB**.

The [`.gitignore`](.gitignore) file already blocks music files from being uploaded by accident.

---

## Updating the app

After you change `dj-practice.html`:

```bash
git add dj-practice.html
git commit -m "What I changed"
git push
```

The online version updates in 1–2 minutes. If you still see the old version, press **Ctrl + F5**.

---

## How it's different from the real thing

- The mixer has **2 channels** (the real DJM-A9 has 4). Player 1 is CH 1 and Player 2 is CH 2.
- There's no mic, Bluetooth, booth output, memory cues, or touch screen browser.
- The effects sound close to the real ones, but not exactly the same.
- A mouse and keyboard don't feel like real knobs and jog wheels. The way you mix and beatmatch is the same, though.
