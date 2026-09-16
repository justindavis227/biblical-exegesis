# Better One, or Two? — podium card

## Presenting with the TV (presenter mode)

1. Plug in the TV. In macOS **System Settings → Displays**, make sure it's **extended**, not mirrored.
2. Open **`presenter.html`** in Chrome (Safari works too). Press **F** if you want it full-screen on the laptop.
3. Click the red **Audience window — off** button. A second window appears — **drag it onto the TV.** The button turns green and reads *live* once it's connected.
4. **Click once inside the audience window.** That fills the TV and turns on the phoropter sound. (Browsers only allow fullscreen and sound after a click *in that window* — that's why this step exists.)
5. Come back to the presenter window. Your clicker and arrow keys drive both screens from here.

The presenter shows: what the room sees (live, with the animations), your notes, the next frame, time-in-talk, and the practice countdown. Along the bottom is a **timeline of all 54 slides — click any one to jump straight to it**, which is the fast way to skip or double back. It reflows for a half-screen window, so it can sit beside Craft.

The audience window shows the slide and nothing else. Before you start it may warn you that sound isn't armed or that it isn't filling the screen; both disappear once you click inside it and it goes full-screen.

**Notes** — your Craft outline, one entry per frame, lives in `notes.js`. Click the notes box and type to override it for that frame.

*Where your typing goes:* it saves into this browser the moment you stop typing (the label reads **edited here · saved**) and always beats `notes.js`, so it survives reloads, new builds and pushes. What it does **not** survive: a different browser, another Mac, or switching between the local file and the hosted link — those are separate stores. Press **Save notes** in the header to download a `notes.js` containing every note with your edits merged in; drop that file in the deck folder (replacing the old one) and your edits are permanent everywhere.

To undo an edit on one slide, click **revert** next to the label — it asks first.

**If the presenter window ever reloads or crashes:** reopen `presenter.html`. It finds the audience window on its own within two seconds — the TV never goes dark.

## Keys

Press **?** or click **Keys** in the presenter for this list on screen.

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
