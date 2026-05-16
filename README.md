# CSS Bento Grid Layouts

A collection of **bento-style UI layouts** built with pure HTML and CSS, organized by difficulty level. Each layout is a pixel-perfect recreation of a design challenge — great for practicing CSS Grid, Flexbox, and component composition.

## Previews

### Easy — Butusic Art Gallery
![Easy layout preview](Screenshot%20(391).png)

### Medium — Designer Portfolio
![Medium layout preview](Screenshot%202026-05-12%20192428.png)

### Hard — Jon Daniel Portfolio
![Hard layout preview](Screenshot%202026-05-17%20003407.png)

---

## Structure

```
├── Easy/        # Butusic art gallery & NFT marketplace UI
├── Medium/      # Designer personal portfolio bento grid
└── Hard/        # Jon Daniel — full portfolio layout with sidebar nav
```

Each folder contains:
- `index.html` — markup
- `style.css` — all layout and styling
- `img*.png` — assets used in the layout

## Difficulty Breakdown

| Level  | Layout Style | Key Concepts |
|--------|-------------|--------------|
| Easy   | Multi-panel bento grid | CSS Grid, Flexbox, image placement |
| Medium | Asymmetric card grid | Grid areas, icon fonts, responsive cards |
| Hard   | Full-page portfolio layout | Complex grid, sidebar nav, overlapping elements |

## Tech Stack

- HTML5
- CSS3 (Grid + Flexbox)
- [Remix Icon](https://remixicon.com/) (Easy)
- [Font Awesome 7](https://fontawesome.com/) (Medium, Hard)

## How to Run

No build step needed. Just open any `index.html` directly in your browser:

```bash
# Example
open Easy/index.html
```

Or use a local server like [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) in VS Code for the best experience.
