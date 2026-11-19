# Rooftop Protocol

A pixel-art platformer/shooter that runs entirely in the browser: a single HTML file, nothing to install and no build step.

You are **VERDE-7**, the last maintenance unit still running in Neo-Verdana. Cross four worlds, unlock new abilities and take down the bosses that have seized the city.

## How to play

Open `index.html` in a browser (Chrome, Edge or Firefox), or serve it locally:

```bash
python3 -m http.server 8000
```

then visit http://localhost:8000.

The file can also be shared as-is (for example as a document on WhatsApp): on desktop and Android it opens in the browser. An internet connection is only needed to load the fonts. Saves and achievements stay in each player's browser.

## Controls

| Action | Keyboard | Controller |
|---|---|---|
| Move | Arrows / A D | Stick / D-pad |
| Jump (double jump) | Space / W | A |
| Shoot (hold for a charged shot) | X / J | X / RT |
| Dash | Shift / K | B / RB |
| Bomb | E | LB |
| Secondary weapon | Q | Y |
| Interact (vendor, telescope) | R | Up |
| Inventory | I / Tab | Back |
| Pause | P / Esc | Start |
| Audio | M | |
| Fullscreen | F | |

On phones a touch pad appears below the game screen.

## Content

- **4 worlds:** Rooftops of Neo-Verdana, Gardens of Flora, The Foundations, Unity Castle. Each has collectibles, a miniboss, a vendor and a boss.
- **Bosses:** Armored Colossus, Mother Flora, OBLIVION, Unity, plus the secret bosses Bonez, the Royal Mechanic, and Tramezzino.
- **Boss Hell:** every boss in a row inside a great colosseum. It ends with a surprise.
- **Achievements:** 30 goals, some of them secret.
- **4 languages:** Italian, English, Spanish, French.
- **4 difficulty levels:** from Maintenance to Total Meltdown.

## Version

The current version is shown in the bottom-right corner of the title screen and is defined by the `VERSION` constant in `index.html`. Update it with every release.
