DJ DU BEAM MUSIC BINGO — STARTER BUILD

FILES
- index.html = player phone screen
- host.html = DJ/host dashboard
- logo.jpeg = DJ DU BEAM logo
- songs.js = editable 75-song starter bank
- styles.css = black/gold styling

QUICK TEST (FREE)
1. Unzip this folder on a laptop.
2. Open index.html to test a player card.
3. Enter any name and game code (example DUBEAM-01).
4. Open host.html to test the host song tracker.

IMPORTANT
This starter build generates different player cards and lets the host track songs, but it does NOT yet sync player claims to the host across different phones. True live multi-phone syncing needs a free cloud database (for example Firebase or Supabase) plus free web hosting. config.js is included as the placeholder for that next step.

NEXT BUILD STEP
Connect a free realtime database, add host-created game codes, player list, live BINGO claim alerts, server-side validation against songs actually played, and generate the permanent QR code after the site has its final public URL.

EDITING SONGS
Open songs.js in a text editor. Keep each entry inside quotes and separated by commas. Use the format:
"Song Title — Artist"

BINGO RULE IN THIS STARTER
5 marked squares across, down, or diagonal. The center FREE SPACE starts marked.
