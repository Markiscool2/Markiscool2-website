# Mark Ratsko portfolio

Static portfolio site for Mark Ratsko. Plain HTML and CSS with no build step, served by GitHub Pages from the root of `main`.

Live preview: https://kihsomray.github.io/mark-ratsko-portfolio/

## What's here

| Path | What it is |
| --- | --- |
| `index.html` | The whole page |
| `css/site.css` | All styles |
| `img/` | Project images, WebP, two sizes each |
| `fonts/` | Bricolage Grotesque and Instrument Sans, under the SIL Open Font License |
| `cascadia/` | The Cascadia Collection site, linked from its project entry |
| `og.png`, `favicon.*`, `apple-touch-icon.png` | Link preview image and icons |
| `404.html` | Not found page |

## Editing

Each project is one `<section class="case">` block in `index.html`. Copy a block to add a project, delete one to remove it, and keep the list in the hero in step.

The coloured panel behind each project takes its colour from `style="--tint: ..."` on the `.stage` element.

The page follows the visitor's light or dark setting. The button in the header switches it and remembers the choice.

Images are listed in `srcset` at two widths. Export new ones as WebP at roughly 1600px and 800px wide and keep the `width` and `height` attributes in step with the larger file.

## Before moving this to Mark's own address

- Remove `<meta name="robots" content="noindex">` from `index.html` and the pages in `cascadia/`. It is there so this preview copy stays out of search results.
- Update `og:url` and `og:image` in `index.html` to the new address.
- `404.html` uses absolute `/mark-ratsko-portfolio/` paths. Change them to match the new location.

## Still needed from Mark

- A photo and a résumé PDF for the About section.
- One line per project on what came of it. The current text only covers what the project was and what Mark did.
- Figma files renamed before sharing: the Anthem Church file is called "Untitled".
- Confirmation of which projects were client work and which were concepts, so they can be labelled.
