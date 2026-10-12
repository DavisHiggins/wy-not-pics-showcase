<p align="center">
  <a href="https://wynotpics.vercel.app"><img src="assets/hero.svg" width="100%" alt="wy_not_pics: Wyatt Bullock Photography. Animated cover with the title in serif type beside a camera viewfinder where autofocus locks onto the wy_not_pics badge and the shutter fires." /></a>
</p>

<h1 align="center">wy_not_pics</h1>

<p align="center"><strong>A portfolio website for Charlotte photographer Wyatt Bullock: sports, portraits, and lifestyle work moved off a social feed and into a site that reads as a brand.</strong></p>

<p align="center">
  <a href="https://wynotpics.vercel.app"><img src="assets/btn-open.svg" height="44" alt="Visit the site" /></a>&nbsp;
  <a href="https://www.higginsd.com/work/wy-not-pics"><img src="assets/btn-case.svg" height="44" alt="Case study" /></a>&nbsp;
  <a href="https://davishiggins.com"><img src="assets/btn-dh.svg" height="44" alt="Davis Higgins" /></a>
</p>

<p align="center"><sub>Live · Client project for Wyatt Bullock (@wy_not_pics) · Designed and built by Davis Higgins</sub></p>

---

## See it in motion

<p align="center">
  <img src="assets/demo.gif" width="720" alt="Screen recording of wynotpics.vercel.app: from the home page hero to Prices & Packages with session cards, then the contact page." />
</p>

<p align="center"><sub>Real capture of the live site's booking path: home, pricing, contact. <a href="assets/demo.png">Static frame</a></sub></p>

## What it does

- **The work, in its own frame.** Portfolio sections for sports, portraits, and lifestyle use a masonry grid that keeps each photo's own shape, with a full-screen lightbox, instead of square feed crops.
- **Clear starting points.** A pricing page lays out session packages (portraits, sports coverage, lifestyle and brand, custom) so a prospective client knows where to begin.
- **A direct line.** Every page leads to contact: direct email and the Instagram handle the brand grew from.

## The brief

Wyatt's photography was strong, but its presentation lived in a social feed: a grid of square crops in someone else's interface, with no simple way to book a shoot. The site needed to put the photographs first, keep everything else quiet, and turn interest into an inquiry. It also needed to belong to Wyatt rather than to a platform.

## What I built

- The site's structure: home, portfolio with sports, portraits, and lifestyle sections, about, pricing, and contact
- An editorial visual system: deep ink-blue surfaces, ivory text, cyan and amber accents, Cormorant Garamond with Inter and JetBrains Mono, and a film-grain texture
- The masonry gallery and lightbox, portfolio sub-tabs, a custom cursor, and page transitions
- Easy-to-update galleries and pricing, so new work or new packages never require a redesign

<details>
<summary><strong>How it's put together</strong></summary>

<br />

```mermaid
flowchart TB
    G[Gallery collections<br/>sports · portraits · lifestyle] --> L[Masonry grid + lightbox]
    R[Session packages] --> K[Pricing page]
    L --> C[Contact: email + Instagram]
    K --> C
```

| Decision | Why |
|---|---|
| **Every photo keeps its composition** | Portrait and landscape frames are laid out at their real proportions instead of being cropped to squares. |
| **A real page for every collection** | Each portfolio section has its own address, and older links keep working. |
| **Updates without redesigns** | New shoots and new packages drop into place without touching the layout. |

</details>

## Screens

<table>
  <tr>
    <td width="62%"><img src="assets/screenshot-home.jpg" alt="wy_not_pics homepage: 'Wyatt Bullock Photography' over a photo of Wyatt holding a camera by the water, with the round photography badge." /></td>
    <td rowspan="2" width="38%" align="center"><img src="assets/screenshot-mobile.jpg" width="300" alt="Contact page on a phone: 'Tell me what you need photographed.'" /></td>
  </tr>
  <tr>
    <td><img src="assets/screenshot-pricing.jpg" alt="Prices & Packages page with Portrait Session from $350 and Sports Coverage from $600." /></td>
  </tr>
</table>

<sub>Homepage · Pricing · Contact on mobile</sub>

## Technology

| Layer | Technology |
|---|---|
| App | React, Vite |
| Motion | Framer Motion |
| Styling | CSS |
| Hosting | Vercel |

---

<p align="center">
  <a href="https://wynotpics.vercel.app"><img src="assets/btn-open.svg" height="44" alt="Visit the site" /></a>&nbsp;
  <a href="https://github.com/DavisHiggins"><img src="assets/btn-more.svg" height="44" alt="More of my work" /></a>
</p>

<p align="center"><sub>© 2026 Davis Higgins. The wy_not_pics name, badge, and all photographs belong to Wyatt Bullock.</sub></p>
