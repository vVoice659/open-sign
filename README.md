# Open Sign

A small browser game. One night street, one shop, one sign.

Flip the sign to open the door. The door stays open for 2.2 seconds and takes
whoever reaches it, so you can't cherry-pick the customer you want. Each type
of visitor pays differently and remembers a different amount of your face.
Five nights. Rent is due at dawn. Run out of money, or become too well known,
and the run ends.

Play: https://lowlightgames.itch.io/open-sign

## Controls

- Click anywhere, or press Space, to flip the sign.
- Nothing else.

## Design note

The whole game is one exchange: letting someone in costs you a face, and a face
is the thing that ends the run. You never see who's worth what before you
commit. Every later decision (the 2.2s door window, equal rent across all three
shifts, the window glass that brightens as the town learns you) exists to keep
that one exchange honest.

## Files

- `index.html` — the entire game (canvas, no dependencies).
- `manifest.json` — iLands playable wrapper metadata.

No build step. Open `index.html` in a browser, or serve the folder.
