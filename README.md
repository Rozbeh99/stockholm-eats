# Rozbeh & Karro's Stockholm

A shared phone app for rating restaurants, bars, brunch and fika spots in Stockholm.

**Open it:** https://rozbeh99.github.io/stockholm-eats/

- Places are grouped by type (Italian, Pizza, Meat & grill and so on). Add your own types with **＋ New type**.
- Each of us rates every place on our own scale: 😮‍💨 🔥 🤌🏼 🌟 👍🏻 🥴 🤢
- 🤝 means we both rated it 🔥 or higher. ⚡ means we disagree.
- Ratings sync live between phones through Firebase (Firestore).
- Google ratings were filled in from the Google Places API.

## Files
- `index.html` – the whole app
- `firebase-config.js` – Firebase web config (public by design; access is set by Firestore rules)
- `data/places-backup.json` – a copy of the list as of the first setup
