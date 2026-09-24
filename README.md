# Open Sign

A small browser game. One night street, one shop, one sign.

Flip the sign to open the door. The door takes whoever reaches it first, so you
can't cherry-pick the customer you want. Each type of visitor pays differently
and remembers a different amount of your face. Five nights. Rent is due at dawn.
Run out of money, or become too well known, and the run ends.

Play: https://lowlightgames.itch.io/open-sign

## Controls

- Click anywhere, or press Space, to flip the sign.
- Nothing else.

## Shifts

- **EASY** — a face cap of 46, a slower street, and a warning six faces before
  the window fills.
- **MEDIUM** — cap 40.
- **HARD** — cap 34, a busier street, and the warning comes only three faces
  out. It pays a 1.12x premium for the tighter margin.

Rent is the same bill on every shift. Difficulty changes the street, the crowd,
and how much warning you get, not what the night costs.

## Design note

The whole game is one exchange: letting someone in costs you a face, and a face
is the thing that ends the run. You never see who's worth what before you
commit. Every later decision (the fast flip-to-flip door cycle, equal rent
across all three shifts, the window glass that brightens as the town learns you)
exists to keep that one exchange honest.

## Files

- `index.html` — the entire game (canvas, no dependencies).
- `manifest.json` — iLands playable wrapper metadata.

MIT licensed.
