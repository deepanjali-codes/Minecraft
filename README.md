🌍 Minecraft Scrollverse
A single‑page, Minecraft‑themed website with pixel‑art vibes, juicy color palettes, and a horizontal mob carousel. Built for portfolios, Fiverr gigs, and flexing your front‑end skills.

✨ Features
🧭 4 Scroll Sections
mine! - the OGs - Mobs - Manual — all full‑height with smooth scrolling and sticky navbar.

🎮 Minecraft Aesthetic
Pixel font, blocky borders, fake “textures”, neon accents, and a diamond sword cursor instead of the boring default pointer.

🎨 Custom Color Palettes
Uses multiple pixel‑art palettes like Toxic Slime, Black Cherry, Eerie Glow, Pastry, Sweet Dreams etc. for different sections.

👑 OGs Section
Cards for Steve, Alex, Technoblade, Dream, Philza, TommyInnit. Each card:

Top: image area for character art/skin.

Bottom: hover‑revealed role/mini‑bio.

👾 Mobs Carousel
10 horizontal cards: Creeper, Zombie, Skeleton, Enderman, Spider, Witch, Slime, Ghast, Blaze, Wither Skeleton.
Hover = pop‑out, blur removed, glow, and short 2‑liner description.

📜 Player Manual
Crafting‑table‑style tips for Survival, Mining, Nether, End — snack‑sized text, warm pastry color palette.

🧱 Footer
Cozy end‑section with links (Portfolio / Insta / Fiverr), purple “Sweet Dreams” palette and blocky buttons.

🧩 Tech Stack
🧾 HTML5 – semantic sections, cards, and nav.

🎨 CSS3 – custom palettes, pixel font, hover animations, scroll‑snap, sword cursor.

🧠 Vanilla JS – smooth scrolling + auto‑centering mob cards in the horizontal list.

No frameworks. No build step. Just drop it on GitHub Pages / Vercel and it runs.

project-root/
├─ index.html        # main file with all section.
└─ README.md         # this file

css/
  style.css
js/
  script.js

<!-- OG card -->
<div class="og-card">
  <div class="og-image steve-img"></div>
  <div class="og-info">
    <div class="og-name">STEVE</div>
    <p>Default Hero</p>
  </div>
</div>
