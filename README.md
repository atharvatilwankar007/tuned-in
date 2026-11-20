# Tuned In

A free spectrum-guessing party game that runs in the browser. No app or APK to install, and no sign-up.

**Play:** https://atharvatilwankar007.github.io/tuned-in/

## How to play

1. The **psychic** picks one of two spectrums (for example *Underrated skill ⟷ Overrated skill*) and secretly sees where the target sits on the dial.
2. They give a clue that lands on that spot.
3. Their team drags the needle and locks it in.
4. The other team calls whether the target is **left or right** of the needle, for 1 point.
5. Reveal: bullseye 4, next ring 3, outer ring 2. First team to the goal wins.

## Modes

- **Online room:** create a room and share the invite link or the 4-letter code. The host's browser runs the game, so the host keeps the tab open until the game ends. Players connect directly through [PeerJS](https://peerjs.com/).
- **One phone:** pass a single device around. This also works with screen sharing on a video call.

There are 387 built-in spectrums. Cards you've seen go to the back of the deck, and you can add your own.

Everything is in `index.html`. To edit the spectrums, change the `DECK_TEXT` list at the top of the script, with one `Left|Right` pair per line.
