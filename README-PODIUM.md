# Better One, or Two? — podium card

## Presenting with the TV (presenter mode)

1. Plug in the TV. In macOS **System Settings → Displays**, make sure it's **extended**, not mirrored.
2. Open **`presenter.html`** in Chrome (Safari works too). Press **F** if you want it full-screen on the laptop.
3. Click **Open audience window**. A second window appears — **drag it onto the TV.**
4. **Click once inside the audience window.** That fills the TV and turns on the phoropter sound. (Browsers only allow fullscreen and sound after a click *in that window* — that's why this step exists.)
5. Come back to the presenter window. Your clicker and arrow keys drive both screens from here.

The presenter shows: what the room sees (live, with the animations), the next frame, notes, a wall clock, time-in-talk, and the practice countdown. It reflows for a half-screen window, so it can sit beside Craft.

**Notes** — your Craft outline, one entry per frame, lives in `notes.js`. Click the notes box to type over it for that frame (saved on this Mac only; the label turns to *edited here*). Click *edited here* to go back to the file's text.

**If the presenter window ever reloads or crashes:** reopen `presenter.html`. It finds the audience window on its own within two seconds — the TV never goes dark.

## Keys (work in the presenter window; most also work in the audience window)

| Key | Does |
|---|---|
| → · Space · PgDn · clicker forward | next |
| ← · PgUp · clicker back | back |
| **B** or **.** | black screen on the TV (press again to return) |
| **M** | mute / unmute the phoropter clicks |
| **t** | countdown start / pause |
| **Shift+T** | countdown reset (to whatever you last set) |
| **+** / **−** | add / remove a minute |
| **E** or click "in talk" | reset the talk clock to 00:00 — do this right before you start; it begins counting on your first advance |
| click the time in the presenter | type a new time (`10` or `12:30`), Enter |
| **F** | fullscreen the window you're in |
| Home / End | first / last frame |

Sound plays **only in the audience window**, so the laptop never doubles it.

## Presenting without a second screen (solo mode)

Open **`index.html`**, press **F**, press any key to arm sound. Same keys. **Shift+P** switches to presenter mode from here.

## Jumping to a frame

Add `#20` to the address bar (frame numbers, not labels). The phoropter run is frames 16–23; the practice timer is frame 38.

**Do not** edit `index.html` by hand. Content changes go through Claude Design → re-export → rebuild.
