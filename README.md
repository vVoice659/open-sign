# Open Sign

A small browser game. One night street, one shop, one sign.

Flip the sign to open the door. The door takes whoever reaches it first, so you
can't cherry-pick the customer you want. Each type of visitor pays differently
and remembers a different amount of your face. Five nights. Rent is due at dawn.
Run out of money, or become too well known, and the run ends.

Play: [itch.io](https://lowlightgames.itch.io/open-sign) / [github.io](https://vvoice659.github.io/open-sign)

## Controls

- Click anywhere, or press Space, to flip the sign.
- Nothing else.

## Shifts

Every shift is its own room: a different crowd, a different rent, and a
different amount of warning before the window fills.

- **EASY** — cap 46, a slower street, and a poorer crowd (mostly regulars and
  quiet types) that pays 0.9x. Rent 72c, and the warning comes six faces out.
- **MEDIUM** — cap 40, the standard crowd, standard pay. Rent 108c.
- **HARD** — cap 38, a busier street, and a richer crowd (more spenders) that
  pays a 1.12x premium. Rent 125c, and the warning comes only three faces out.

The less a room pays, the less the night costs. Rent is not the same bill on
every shift; it is priced to the crowd you get.

## Design note

The whole game is one exchange: letting someone in costs you a face, and a face
is the thing that ends the run. You never see who's worth what before you
commit. Every later decision (the fast flip-to-flip door cycle, the window glass
that brightens as the town learns you, the rent that tracks each shift's crowd)
exists to keep that one exchange honest.

## Files

- `index.html` — the entire game (canvas, no dependencies).
- `manifest.json` — iLands playable wrapper metadata.

MIT licensed.
