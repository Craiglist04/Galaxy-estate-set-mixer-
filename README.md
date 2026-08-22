# Galaxy Estate Field Set Mixer

A simple website for pickup ball at Galaxy Estate Field: paste player names and randomly group them into sets of 3.

## How to use

1. Open `index.html` in any phone or laptop browser.
2. Type or paste names (one per line, or separated by commas).
3. Keep **3 (default)** if you play three people per set.
4. Tap **Mix sets**.
5. Tap **Shuffle again** for a new mix.
6. Tap **Copy for WhatsApp** to send the groups.

## How grouping works

- 15 players → 5 full sets
- 12 players → 4 full sets
- 9 players → 3 full sets
- 6 players → 2 full sets
- Extra names that do not fill a full set go to **Bench / next rotation**

## House rule

If these names are in the list, they always go into the same set:

- Usman or Uthman (either spelling)
- Kingsley or Kingley
- Neymar

With sets of 3, those three fill one set by themselves.

You can also switch set size to 2, 4, 5, or 6 if the game format changes.

Names stay in the browser only. Nothing is uploaded.

## Deploy on Render

1. Create a GitHub repo and upload `index.html` plus `render.yaml`.
2. Go to [https://dashboard.render.com](https://dashboard.render.com) and sign in.
3. Click **New +** → **Static Site**.
4. Connect GitHub and select the repo.
5. Use these settings:
   - **Build Command:** `echo "No build needed"`
   - **Publish Directory:** `.`
6. Click **Create Static Site**.

Render will give you a live URL like `https://galaxy-estate-field-set-mixer.onrender.com`.
