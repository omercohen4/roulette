# Roulette

European single-zero roulette to play with friends: a shared leaderboard, PIN-locked players,
groups with invite links, and a Lucky Wheel when you run out of chips. Play money only.

- `index.html` is the whole game. Wheel images and app icons live in `assets/`.
- `firebase-config.js` holds the Firebase web app settings (public identifiers, not secrets).
- `firestore.rules` holds the database rules. Paste them into Firebase console > Firestore Database > Rules.

The site is served by GitHub Pages from the `main` branch, so every push to `main` goes live within a few minutes.
