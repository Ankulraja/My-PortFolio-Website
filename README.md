# My-PortFolio-Website

Live :- https://my-port-folio-website-seven.vercel.app/

Personal portfolio website for Ankul Raja Patel.

**What this project is**

- A static HTML/CSS/JS portfolio site (no build tools).
- Includes: Home, About, Projects, Services (Skills) and Contact sections.
- Added a DSA (LeetCode / Codeforces / CodeChef / Codolio) visual section and responsive improvements.

**Recent changes**

- Added a `DSA` section with links to:
  - LeetCode: https://leetcode.com/u/ankulraja2002/
  - Codeforces: https://codeforces.com/profile/Ankulraja
  - CodeChef: https://www.codechef.com/users/ankulraja2002
  - Codolio: https://codolio.com/profile/Ankul
- Improved responsiveness for portfolio and services cards (grid layout, equal-height cards).
- Fixed navbar anchor for `Skills` to point to `#services`.
- Added an optional background/overlay for the `DSA` section. Place your screenshot at `images/dsa-bg.png` to enable it (see Notes below).
- Hid the rotating profession visual on small screens to avoid overlapping the Home section.

**How to run locally**

1. Open a terminal and change to the project folder:

```bash
cd /Users/ankulrajapatel/Desktop/My-PortFolio-Website
```

2. Start a simple HTTP server (Python 3):

```bash
python3 -m http.server 8000
```

3. Open your browser to:

```
http://localhost:8000
```

(Or use VS Code Live Server extension or `npx serve` if you prefer.)

**Where to put the DSA screenshot (optional)**

- If you want the screenshots you attached to appear as the background in the DSA section, copy one into the project at:

```
My-PortFolio-Website/images/dsa-bg.png
```

The CSS expects the background path relative to `css/style.css` as `../images/dsa-bg.png`.

**Notes & next steps**

- Images: Large screenshots slow page load — consider resizing/compressing before adding them to `images/`.
- Icons: I used favicons / simple logos for the DSA cards — we can replace these with SVG icons for sharper visuals.
- Live stats: I can fetch and embed live numeric stats (rating, solved counts) for LeetCode/CF/CC, but that requires network requests and sometimes scraping or using public APIs.
- Accessibility: Add `alt` text where missing and ensure color contrast for light/dark modes.

If you want, I can:

- add the screenshot you attached into `images/dsa-bg.png` now,
- fetch live platform stats and render small badges, or
- convert some badges to SVG icons for a crisper UI.

— I can continue with any of these next steps; tell me which you'd like.
