# DJ Practice Booth

Practice DJing at home, in your browser.

You get **2 Pioneer CDJ-3000 players** and a **DJM-A9 mixer** on screen, and you can load your own MP3s, just like plugging in a USB stick.

Everything is in one file: [`dj-practice.html`](dj-practice.html). You don't need to install anything or be online.

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

**Option 2: Offline**

1. On GitHub, click **Code → Download ZIP** and unzip it.
2. Right-click `dj-practice.html` → **Open with** → **Chrome** or **Edge**.

---

## Getting started

1. Click **POWER**.
2. Click **📁 USB** and pick the folder with your songs.
3. On a player, click **BROWSE**. Scroll the round knob next to the screen to move, and click it to pick a song (or just double-click the song).
4. Press **PLAY** and push up that channel's fader on the mixer.

You can also drag an MP3 straight onto a player to load it there.

---

## The player buttons

The players are laid out like a real CDJ-3000. Here's what the buttons do.

**Finding songs** (around the screen)

| Button | What it does |
|---|---|
| **BROWSE** / **PLAY LIST** | Show your folders and songs on the screen |
| **SEARCH** | Type part of a song name to find it |
| **TAG LIST** | Your shortlist of songs |
| **TAG TRACK/REMOVE** | Add a song to the TAG LIST, or take it off |
| Round knob (right of the screen) | Scroll to move, click to pick |
| **BACK** | Go back one step, or close the list |

**On the screen**

| Button | What it does |
|---|---|
| **BEAT LOOP** | Make a loop of 1/4 to 32 beats |
| **KEY SHIFT** | Move the song's key up or down |
| **BEAT JUMP** | Choose how far the jump buttons jump |
| **GRID** (under the waveform) | Fix the beat grid if it's off |
| Small waveform (bottom) | Click to jump to that part of the song |

**Cues and loops**

| Button | What it does |
|---|---|
| **A–H** pads | Hot cues. Click an empty pad to save, a saved pad to jump. |
| **CALL/DELETE** | Press it, then a pad, to delete that hot cue |
| **MEMORY** | Save the cue point as a memory cue |
| **CUE/LOOP CALL ◀ ▶** | Go to the previous / next memory cue |
| **DELETE** | Delete the memory cue you're on |
| **IN/CUE** → **OUT** | Make a loop by hand |
| **RELOOP/EXIT** | Leave the loop, or go back into it |
| **4** / **8** | 4- or 8-beat loop. While a loop plays, they make it half / double. |

**Speed and sound**

| Button | What it does |
|---|---|
| **TEMPO** slider | Down = faster, up = slower |
| **TEMPO** button | Range: ±6%, ±10%, ±16%, or WIDE |
| **TEMPO RESET** | Back to the original speed |
| **MASTER TEMPO** | Change speed without changing the key |
| **BEAT SYNC** | Match the speed and beats of the MASTER player |
| **MASTER** | Make this player the one the other follows |
| **KEY SYNC** | Match the key of the MASTER player |
| **DIRECTION** | FWD = normal, REV = backwards. Hold SLIP REV to play backwards for a moment. |
| **SLIP** | The song keeps going silently during loops and scratches, then jumps back in |
| **QUANTIZE** | Cues and loops snap to the beat |

**Jog wheel**

| Control | What it does |
|---|---|
| Top of the jog | Scratch, or hold it to stop the song (in VINYL mode) |
| Outer bumpy ring | Speed up or slow down a little (nudge) |
| **JOG MODE** | Switch between VINYL and CDJ |
| **JOG ADJUST** | Make the jog feel light or heavy |
| **VINYL SPEED ADJ.** | How slowly the song stops when you press PAUSE, like a turntable |

**Other**

| Button | What it does |
|---|---|
| **TIME MODE** | Click: show time played or time left. Hold: turn AUTO CUE on/off. |
| **TRACK SEARCH** ◀◀ ▶▶ | Previous / next song |
| **SEARCH** ◀◀ ▶▶ | Fast rewind / forward while held |

Your hot cues, memory cues, and grid fixes are saved for each song, so they're still there next time you load it.

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

- Keys don't work while you're typing in **SEARCH**, or while the **🎵 Tracks** window is open.
- The full list is also in the app: click **⌨ Help** at the top right.

---

## Using it on another computer

- **Use Chrome or Edge.** Other browsers may not play sound.
- **Your music is not on GitHub.** Bring your songs on a USB stick or in the cloud (OneDrive, Google Drive).
- **Pick your music folder every time.** The browser can't remember it.
- **Hot cues, memory cues, and grid fixes stay on that computer only.** On a new computer you'll need to set them again.
- **Headphones:** each time, click **🎧 Sound / Headphones** and pick **Split cue**. You'll hear the cue in your left ear and the main mix in your right ear.
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
- There's no mic, Bluetooth, booth output, or SD card.
- The effects sound close to the real ones, but not exactly the same.
- A mouse and keyboard don't feel like real knobs and jog wheels. The way you mix and beatmatch is the same, though.
