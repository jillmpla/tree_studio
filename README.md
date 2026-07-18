# 🎄 Tree Studio: SVG Library

[**Visit Tree Studio →**](https://treestudio.xyz)

Tree Studio is a responsive web application for previewing and copying animated themed SVG trees. It was created to make it easy to add a little holiday cheer, seasonal color, or playful decoration to websites or projects throughout the entire year.

Choose a theme, preview the animation, view the generated code, and copy a portable SVG directly into another website or project.

## What It Does

- Displays 22 animated SVG tree designs
- Changes the tree, decorations, colors, background, and topper for each theme
- Lets users preview the generated SVG before copying it
- Copies portable SVG markup with the required styling and animations included
- Includes standalone preview pages with both themed-background and transparent versions
- Works across desktop, tablet, and mobile screens
- Supports reduced-motion preferences and accessible SVG descriptions
- Uses only HTML, CSS, JavaScript, and inline SVG

## SVG Designs

| Theme | Design |
|---|---|
| **4th of July** | A patriotic tree with red-and-white ribbon, stars, ornaments, and animated fireworks |
| **1990s** | A neon nostalgia tree with CDs, cassette tapes, a pager, and a corded phone |
| **Beach** | A sea-glass tree decorated with shells, flowers, sandals, and tropical details |
| **Birthday** | A party tree with balloons, cake, gifts, confetti, and celebration effects |
| **Bookish** | A cozy tree with books, tea, candlelight, bookmarks, and fluttering pages |
| **Candy** | A pastel candy-shop tree filled with lollipops, sweets, cupcakes, and donuts |
| **Classic** | A traditional evergreen with warm lights, ornaments, garland, and a glowing star |
| **Classy** | An elegant Christmas tree with champagne gold, ivory pearls, and a crystal-style topper |
| **Dancing** | A cheerful disco tree with music notes, a disco ball, and a swaying animation |
| **Easter** | A rounded spring topiary with pastel eggs, ribbons, and soft garden colors |
| **Fall** | A deciduous autumn tree with warm foliage, maple leaves, and falling-leaf animation |
| **Girly** | A pink whimsical tree with bows, makeup, handbags, and playful accessories |
| **Gothic** | A dark romantic tree with bats, candles, roses, mist, and a moon topper |
| **Halloween** | A haunted tree decorated with pumpkins, bats, ghosts, and spiderwebs |
| **Islam** | An emerald and gold Eid tree with glowing lanterns, warm lights, and a crescent + star topper |
| **Judaism** | A blue-and-silver Festival of Lights tree with Stars of David and glowing ornaments |
| **Scottish** | A windswept Highland pine with tartan details and a thistle topper |
| **Space** | A deep-space tree with planets, rockets, aliens, stars, and a moon |
| **Spring** | A flowering deciduous tree covered in colorful blossoms and bloom animations |
| **St. Patrick's Day** | A green celebration tree with shamrocks, a rainbow, a hat, and gold coins |
| **Teacher** | A back-to-school tree with apples, pencils, books, science items, and chalk effects |
| **Winter** | A quiet winter tree with snowflakes, skates, a snowman, mittens, and icy colors |

## How to Use It

1. Visit [treestudio.xyz](https://treestudio.xyz).
2. Select a tree theme.
3. Choose **View Code** to inspect the generated SVG.
4. Choose **Copy SVG** to copy it.
5. Paste the SVG directly into the HTML of another website, project, application, etc.

The copied SVG includes the selected design's colors, styling, and supported animations, so it can work independently from Tree Studio.

## Project Structure

```text
tree-studio/
├── svg-previews/
│   ├── svgpreview-4th of july.html
│   ├── svgpreview-1990s.html
│   ├── svgpreview-beach.html
│   ├── ...
│   └── svgpreview-winter.html
├── footer.html
├── index.html
└── style.css
```

### Main Files

- **`index.html`** — Application layout, SVG artwork, theme controls, and copy/export logic
- **`style.css`** — Responsive layout, theme colors, decorations, and animations
- **`footer.html`** — Reusable site footer
- **`svg-previews/`** — Standalone pages for every SVG tree design, each showing a themed-background version and a transparent version

## Run Locally

No installation or build process is required.

Because the footer is loaded with `fetch()`, run the project through a local server instead of opening `index.html` directly:

```bash
python -m http.server 5500
```

Then visit:

```text
http://localhost:5500
```

## Built With

- HTML5
- CSS3
- Vanilla JavaScript
- Inline SVG

## Purpose

Tree Studio is a small creative tool for developers, designers, educators, and anyone who wants to add animated seasonal tree art to a webpage or application without building an SVG from scratch.

From winter holidays and spring celebrations to birthdays, books, beaches, classrooms, and outer space, the goal is simple: **spread a little holiday cheer all throughout the year.**

## License

This project is available under the terms included in the [`LICENSE`](LICENSE) file.

## ⭐ Support the Project

If you find **Tree Studio** useful, consider giving the repository a star.