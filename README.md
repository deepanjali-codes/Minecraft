This project is a single-page, Minecraft‑themed fan site with heavy pixel‑art vibes and interactive scrolling sections.

Project vibe
Full Minecraft aesthetic: pixel font, blocky borders, fake “textures,” neon‑green accents, and a custom diamond‑sword cursor.

Built as a single index.html file using plain HTML, CSS and a tiny bit of vanilla JS for smooth scrolling and mob scroll‑snap.

Designed for portfolio / Fiverr demo use: everything is client‑side and easy to drop on Netlify, Vercel, or GitHub Pages.

✨ Features & Aesthetics
🧭 Layout & Navigation
Sticky top navbar with links: mine!, the OGs, Mobs, Manual.

Smooth scroll behavior between four full‑screen sections.

Pixel‑art inspired font (e.g. Press Start 2P or similar), all‑caps headings, chunky spacing.

🎮 Minecraft Aesthetic
Diamond sword cursor used globally for the page and all interactive elements.

Square/“block” borders, no rounded corners, with offset box‑shadows to mimic pixel blocks.

Backgrounds based on Minecraft‑style palettes:

Greens and teals for “Toxic Slime” / overworld grass vibes.

Reds/purples for “Black Cherry” OG section.

Teal/gray “Eerie Glow” for mobs (moody hostile‑mob energy).

Warm browns (“Pastry”) for the Manual (cozy crafting‑table energy).

Soft purples (“Sweet Dreams”) in the footer for a chill, end‑of‑page vibe.

Optional image slots ready for custom textures, skins and mob renders.

👤 Section 1 – mine! (Notch + Mojang)
Short intro about Notch and Mojang + the origins of Minecraft.

Two‑column layout:

Text column with lore paragraphs styled like in‑game tooltips.

“Mojang” block on the side: a floating card using the red palette, animated up/down for a subtle idle motion.

🧱 Section 2 – the OGs
Grid of six “OG” cards:

Steve

Alex

Technoblade

Dream

Philza

TommyInnit

Each card:

Top half reserved for an image (player skin / fanart).

Hover state: background color shift + subtle slide/scale.

Bottom half reveals name + a short, punchy role/label (PvP god, chaos boy, etc.).

👾 Section 3 – Mobs
Horizontal scroll area with 10 mob cards:

Creeper, Zombie, Skeleton, Enderman, Spider, Witch, Slime, Ghast, Blaze, Wither Skeleton.

Each card:

Top area reserved for a mob image.

Hover: card pops out, blur effect removed, border + shadow glow, subtle rotation.

Two‑line mob description written in short, meme‑style text.

Scroll‑snap helper JS: after scrolling, the closest card auto‑centers for a clean carousel feel.

📜 Section 4 – Manual
“Player Manual” / survival guide section.

Grid of cards with short, high‑signal tips:

Survival basics

Mining & gear

Nether

End/Dragon

Warm pastry‑brown palette, big blocky boxes like recipe books.

Hover: card lifts slightly with stronger shadow and lighter background.

🧱 Footer
Purple “Sweet Dreams” palette.

Title like “Crafted with Code” / “GG WP”.

Social‑style buttons (Portfolio, Instagram, Fiverr, etc.) with blocky hover states.

project-root/
├─ index.html        # main file with all section.
└─ README.md         # this file

css/
  style.css
js/
  script.js
