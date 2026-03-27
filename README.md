# web-portofolio-projects

> [!Warning]
> "In movies, hacking is speed. In reality, hacking is observation."
> 
> *This design is a fan-made reinterpretation and is not affiliated with Valve Corporation.*


<img width="1109" height="604" alt="Screenshot 2026-01-30 204508" src="https://github.com/user-attachments/assets/d1f4c048-d277-4629-a82a-89265e94afac" />

<div align="center" style="line-height: 1;">
  <a href="https://github.com/nhx0x1"><img alt="GITHUB" src="https://img.shields.io/badge/License-Modified_MIT-f5de53?&color=f5de53"/></a>
</div>

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Status](https://img.shields.io/badge/status-active-success.svg)

> [!Note]
> [Reference-UI](https://www.ui-layouts.com/), [Color Scheme](https://github.com/tokyo-night/tokyo-night-vscode-theme), [Fonts](https://www.jetbrains.com/lp/mono/), [Hyprland](hyprland.org), [CORS](https://developer.mozilla.org/en-US/docs/Web/HTTP/Guides/CORS), 

<details>
  <summary>STEAM-VIEW</summary>
## STEAM
  
<img width="811" height="337" alt="Screenshot 2026-01-31 at 03-59-23 Steam Profile Web Design - Kimi" src="https://github.com/user-attachments/assets/ad1eb8c6-5487-40fa-bdb1-61e231dc4ed1" />

An interactive profile interface with a Steam aesthetic, using glassmorphism and modern animations.

## Features
Elements adopted:
- Profile card layout with background artwork
- Glassmorphism/panel transparency (Steam overlay style)
- Badge showcase system (Steam Badges)
- Recent Activity showcase section
- Color palette: Dark navy (#0a0a0a), Steam blue accent, glass white
- Typography: Arial/Helvetica with shadow for readability in the background image

Original modifications:
- Added interactive Spotlight effect (CSS radial-gradient mouse tracking)
- Randomized text animation (inspired by a cyberpunk/glitch aesthetic)
- Marquee badge scroll for efficient space consumption
- 
- **Glassmorphism Effect** - Blurred transparency with smooth edges
- **Spotlight Cards** - A glowing effect that follows the cursor on each card
- **Random Text** - Animated random text on usernames
- **Marquee Badge** - Infinite scroll for icon badges
- **Fixed Layout** - Optimized for a 1920x1080 viewport

## Structure Layout
```
background-container (1920x1080)
├── Container 1 (Left Top) - Fixed
│   ├── Card 1: Photo (185x177)
│   └── Card 2: Description (681x106)
├── Container 2 (Left Bottom) - Fixed
│   ├── Card 4: Showcase 01 (881x110)
│   ├── Card 5: Showcase 02 (881x110)
│   └── Card 6: Showcase 03 (881x110)
└── Container 3 (Right) - Adjustable
├── Card 3: Music (308x48)
└── Card 7: Badge + Social (308x565)
```
## Skets

<img width="1261" height="732" alt="Screenshot 2026-01-28 115710" src="https://github.com/user-attachments/assets/63f501e1-17bd-407c-b1be-105da9c732d6" />
<img width="1919" height="934" alt="Screenshot 2026-01-28 155917" src="https://github.com/user-attachments/assets/1c5e1a90-4fb3-4ad5-bb8f-12cdf216b36f" />

# View

<img width="1919" height="940" alt="Screenshot 2026-01-30 111837" src="https://github.com/user-attachments/assets/d15e003e-5b4b-49df-8faa-301284697e12" />

# My Case

<img width="1919" height="947" alt="Screenshot 2026-01-30 083758" src="https://github.com/user-attachments/assets/2e1215e2-0ce3-4802-8854-aca9796254d5" />
<img width="1203" height="78" alt="Screenshot 2026-01-30 084006" src="https://github.com/user-attachments/assets/9c92856a-218e-4e6f-a077-418588dbc0f0" />


</details>

<details>
  <summary>Linux Desktop View</summary>
<img width="1648" height="765" alt="Screenshot 2026-01-31 at 04-16-25 Website Portofolio Desktop - Kimi" src="https://github.com/user-attachments/assets/25b9ad74-39e3-47c2-afc5-1d13fec40acf" />

```
├── full-build/                 
│   ├── assets/
│   │   ├── fonts/             
│   │   └── icons/             
│   ├── files/
│   │   ├── certificate/       
│   │   └── terminal/
│   │       ├── fastfetch.txt  
│   │       └── hack.txt       
│   ├── wallpapers/            
│   └── dsx.html              
└── raw/
└── dsk.html              # Development/backup
```
  <img width="1919" height="943" alt="Screenshot 2026-01-31 003731" src="https://github.com/user-attachments/assets/1d93cc35-d5bd-47e1-bad1-1ac8c6dc493f" />

  ```
:root {
    --accent: #7aa2f7;        /* Blue accent */
    --success: #9ece6a;       /* Green */
    --error: #f7768e;         /* Red */
    --warning: #e0af68;       /* Yellow */
    --purple: #bb9af7;        /* Purple */
    --cyan: #7dcfff;          /* Cyan */
}
  ```
| Shortcut                 | Action             |
| ------------------------ | ------------------ |
| `Enter` (on lock screen) | Unlock             |
| `Ctrl + Q` (in terminal) | Close window       |
| `Ctrl + L` (in terminal) | Clear screen       |
| `Ctrl + C` (in terminal) | Cancel input       |
| `↑ / ↓` (in terminal)    | Command history    |
| `Super + Enter`          | Open terminal      |
| `Super + E`              | Open file manager  |
| `Escape`                 | Close context menu |

## LOCAL <--- if ur script doesnt works.cuz CORS 

```
python -m http.server 8000
or
npx serve .
or
php -S localhost:8000
```

```
full-build/
├── dsx.html          ← Website A (origin: file:// atau localhost:8000)
└── files/
    └── terminal/
        └── fastfetch.txt   ← Resource B
```
    

</details>

