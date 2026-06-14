# Online Gaming Website - Instructions

## 1. Project Overview
Build a complete front-end online gaming website for **Moonpack Relay**, a browser-based tile-routing puzzle game. The player guides a moon-wolf courier through glowing forest route tiles, collects moon tokens, avoids shadow tiles, and reaches the den before the move counter or timer runs out.

The website must feel like a real online game page, not just a static mockup. It must include a playable mini demo, game instructions, character/world section, score display, mock leaderboard, responsive layout, and documentation.

## 2. Client Details

| Field | Value |
| --- | --- |
| Client name | LunaTrail Games |
| Project type | Online browser game website |
| Category | Web Development |
| Game name | Moonpack Relay |
| Audience | Casual browser game players and puzzle game fans |
| Build style | Front-end website with playable JavaScript demo |
| Delivery type | Source code and documentation |

## 3. Game Concept
Moonpack Relay is a cozy fantasy route puzzle. Each level shows a small grid. The player must create or rotate a safe route from the start tile to the den tile. Some tiles hold moon tokens for bonus points. Some tiles are shadow tiles that block or penalize the route.

The game should be simple, readable, and quick to play. It should not include violence, betting, real-money mechanics, crypto, NFTs, or account systems.

## 4. Required Output Folder
Submit one website project folder named `MoonpackRelay_OnlineGamingWebsite`.

```text
MoonpackRelay_OnlineGamingWebsite/
├── index.html
├── css/
│   └── styles.css
├── js/
│   └── game.js
├── assets/
│   ├── logo_placeholder.png
│   ├── courier_placeholder.png
│   ├── moon_token_icon.png
│   └── forest_background_placeholder.png
├── README.md
└── source_notes.txt
```

If the freelancer uses a different file organization, the README must explain the structure clearly and the site must still run locally.

## 5. Required Website Sections

### 5.1 Landing Section
The landing section must include the game title, tagline, short game summary, hero visual area, and a clear Play Demo button.

### 5.2 Playable Game Demo
The demo must include at least five playable levels. Each level must include a start point, den goal, route tiles, at least one moon token opportunity, and at least one shadow tile or blocked tile hazard.

### 5.3 Game Rules and UI
The demo must show score, current level, move counter or timer, restart control, and next-level control. The game must provide a visible win state and a visible retry or lose state.

### 5.4 How to Play Section
The page must explain the objective, controls, scoring rules, moon tokens, shadow tiles, and goal tile.

### 5.5 Character and World Section
The website must include a short section explaining the moon-wolf courier, moon tokens, shadow tiles, and forest den goal.

### 5.6 Mock Leaderboard
The leaderboard must show at least five sample player names and scores. It may optionally show the current local score using browser storage.

### 5.7 Responsive Design
The site must be usable on desktop and mobile widths. The game board and buttons must remain readable and tappable on smaller screens.

## 6. Technical Requirements
- Use HTML, CSS, and JavaScript.
- The website must run locally without paid hosting or backend setup.
- CSS should be organized and responsive.
- JavaScript should be readable and include comments for the main game logic.
- The game should not depend on a private API or paid external service.
- External fonts or libraries are allowed only if listed in source notes.

## 7. README Requirements
README.md must explain:
- How to open or run the website
- File structure
- Game rules
- Controls
- How the levels work
- How scoring works
- Any known limitations
- Browser compatibility notes

## 8. Source Notes Requirements
source_notes.txt must list all fonts, icons, images, libraries, starter code, AI tools, or external resources used. If all code and visuals are created for this project, state that clearly.

## 9. Scope Boundaries
Do not build login, payment, real-money gaming, betting, loot-box purchases, crypto mechanics, NFT mechanics, real multiplayer, chat, account profiles, external leaderboard database, private data collection, captcha bypass, auto-downloaders, or server-side user tracking.
