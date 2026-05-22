# Kingmaker War — Owlbear Rodeo Extension

An army combat tracker for PF2e Kingmaker war encounters.

## Features
- Army stat cards with condition-modified stats
- Attack, Maneuver, Morale, and Scout rolls with auto DC resolution
- Click attack → click target token → auto damage applied
- Shot tracking for ranged armies
- Rout check prompts at end of each round
- Turn tracker with round counter
- Friendly/enemy army distinction — players only see friendly cards
- All conditions with mechanical effects applied automatically

## Setup — GitHub Pages

1. **Create a new GitHub repository** called `kingmaker-war`
2. **Upload all files** from this folder into the repository root
3. Go to **Settings → Pages**
4. Under Source select **Deploy from a branch**
5. Select **main** branch and **/ (root)** folder
6. Click Save — GitHub will give you a URL like `https://YOUR_USERNAME.github.io/kingmaker-war/`

## Installing in Owlbear Rodeo

1. Open your Owlbear room
2. Click the **puzzle piece** icon (Extensions)
3. Click **Add Custom Extension**
4. Paste your manifest URL: `https://YOUR_USERNAME.github.io/kingmaker-war/manifest.json`
5. Click Add

## Usage

### Adding Armies
1. Open the extension panel
2. Go to the **+ Add** tab
3. Select a preset (Infantry/Cavalry/Skirmisher/Siege) or enter custom stats
4. Choose Friendly or Enemy
5. Click Add Army

### Marking Tokens as Friendly/Enemy
- Place a token on the board
- Right-click the token → **Toggle Friendly** to mark it as friendly
- Friendly tokens can be interacted with by players
- Enemy tokens are GM-only

### Running a Battle
1. Add all armies in the **+ Add** tab
2. Roll Scouting checks and enter initiative values in each army card
3. Click **Start** in the Battle tab
4. Use **Next Turn** to advance through initiative order
5. Click an army's **Attack/Maneuver/Morale** button then click a target token on the board
6. Results apply automatically — HP subtracted, conditions applied, rout checks prompted

### Conditions
Click condition buttons on any army card to toggle them on/off. Conditions with values (Shaken, Weary, Mired) cycle through 0–4. Effects apply automatically to all rolls:
- **Shaken** — penalty to Morale checks
- **Weary** — penalty to AC, Maneuver, all checks
- **Mired** — penalty to Maneuver
- **Outflanked** — −2 AC
- **Fortified** — +4 AC, +4 Morale to rally

## Important — Replace YOUR_USERNAME
Before uploading, do a find-and-replace of `YOUR_USERNAME` with your actual GitHub username in `manifest.json`.
