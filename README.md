# Steam Autumn Sale Landing Page (Replica)

A static HTML and CSS replica of the Steam store landing page during the Autumn Sale, built as a group coursework activity. It is a student project and is not affiliated with or endorsed by Valve.

## Preview

Open `index.html` in any modern browser. No build step or server needed.

If GitHub Pages is enabled, the live page is at:
`https://<username>.github.io/<repo-name>/`

## Project structure

```
steam-landing/
├── index.html   # Page markup
├── style.css    # All styling (design tokens live in :root)
└── README.md
```

## What's included

- Header with logo, main navigation, Install Steam button, and sign in / language links
- Store sub-navigation with search bar
- Autumn Sale banner
- Featured carousel (3 cards, arrow buttons, swipe on mobile)
- "All-time greats" deals row
- Discounted games grid
- Responsive layout (desktop, tablet, phone)

## Design notes

- All colors, spacing, and radii are CSS variables in `:root` at the top of `style.css`. Change them there, not inside individual rules.
- Font: Figtree (Google Fonts, needs internet). Falls back to Tahoma offline.
- Game art and the sale mascot are CSS/SVG placeholders. Replace them with real images before final submission (put them in an `img/` folder and use relative paths).
- Accessibility: visible keyboard focus, aria-labels on icon buttons, and reduced-motion support.

## Known limitations

- No real game images yet.
- Carousel dots are decorative and don't track the current slide.
- Colors were matched by eye from photos, not pixel-matched.
- Prices and titles are placeholder content copied from the reference screenshots.

## Team workflow

1. Pull before you start: `git pull origin main`
2. Work on your own branch: `git checkout -b <section-name>` (for example `header`, `banner`, `carousel`)
3. Commit small and often: `git commit -m "Describe the change"`
4. Push the branch and open a pull request. Don't push straight to `main`.
5. Run `git status` before every commit to make sure only project files are staged.

## Team

| Name | Section |
|------|---------|
|Serillano, Jerry S. II | BSCPE 3B |
| _Add name_ | _Add section_ |


