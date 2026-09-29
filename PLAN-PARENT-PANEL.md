# The parent panel: a plan

The parent card lives in the README and in [parent-guide.html](parent-guide.html), away from the game. This
plan puts the few lines for the game he is in behind the parent dial, so a parent sitting with him can
glance at them without leaving the app.

The recommendation in one line: **hold the dial, and a quiet panel opens with the level and the card for
this game. A tap anywhere closes it.** No new button on his screen.

## What changes for him

Nothing he can see. The dial stays where it is, the same size and colour, still behind a press and hold of
about a second. It now shows in ✖️ too (it was hidden there because it did nothing).

## What the parent sees

Hold the dial: the orange fill grows as today, then a panel covers the game.

```
  ┌───────────────────────────────────────────────┐
  │  ➕ How many?                                  │
  │                                               │
  │  Say     "3 and 2 make 5."                    │
  │  Ask     "How did you know?"                  │
  │          "What if one more came?"             │
  │  Watch   After a miss, count along with him   │
  │          out loud.                            │
  │                                               │
  │  (A · up to 5) (B · 6 to 10)  Tap anywhere to │
  │                                        close  │
  └───────────────────────────────────────────────┘
```

- **One card per game**, three or four short lines, taken from parent-guide.html: what to say, what to
  ask, one thing to watch for. Play shows its own short card (talk while he moves them).
- **The level, in ➕ and ➖ only:** two buttons at the bottom left, far from the dial's corner, labelled
  with what they mean ("A · up to 5", "B · 6 to 10"), the current one lit. A tap on the other one switches
  the level with the quiet tok (never the ting, his reward sound), closes the panel and deals a fresh sum.
  Play has no level and ✖️ has one, so there the panel has only the card.
- **Close:** a tap anywhere else on the panel. Taps in its first 300 ms are ignored, so the end of the hold,
  or a copied second tap on the same spot, does nothing.
- **It only opens while the game is still:** no sum arriving, no count, tidy or read-back playing. Checked
  when the hold starts and again when it ends. Otherwise the orange fill does not start.

## If he opens it

Make it harmless and dull rather than impossible:

- Text he cannot read yet, no sounds, no animation, no stars. Nothing to come back for. Because it only
  opens while the game is still, no read-back or fanfare plays under it.
- Nothing is lost: the sum on screen stays as it was, the stars stay, his place in the sums stays.
- No links in it, so he cannot leave the app.
- The level only changes with a separate tap on the other letter, never on the way out.
- The pointing hand does not appear while the panel is open.

## What stays the same

- The hold time (about 0.9 s) and the orange fill.
- He will copy the parent's hold one day. He then finds a quiet card, and his next tap on the same spot
  closes it.
- The dial shows the level letter of the game he is in (in Play, the addition level). In ✖️ it shows `A`.
- Everything the game does is unchanged.

## Tech

- One `#parent` overlay inside `#app`, above `#layer` and `#trophy`, below `#turn`. Sized in `--u` so it
  fits a phone on its side and an iPad.
- The cards are a small object keyed by mode at the top of the script, next to `SETS` and `FOODS`.
- The dial's hold opens the panel instead of flipping the level. The flip moves to the A/B buttons, with
  the same code (`save`, `resetSeq`, `setMode`) and `sfx.tok` in place of `sfx.ting`.
- `still()`: in ➕ not busy, `Q.pending` 0 and not tidying; in ➖ and ✖️ also `asked`. Play always.
- The panel closes on `pointerdown`, like every game handler, so the release never reaches the game.
- Text: `max(15px, .34u)`, so it stays readable on a phone on its side.
- `setMode` no longer hides the dial in ✖️.
- The hand's timer skips while the panel is open.
- README: the dial paragraph mentions the panel.

## Reviewed

A second agent read this plan against the code. Its changes, all taken: A/B far from the dial and labelled,
the tok and not the ting, no A/B in Play (a level switch there would wipe his tray for nothing), open only
while the game is still (checked twice), the 300 ms guard, the font floor, and the hand's timer check.
