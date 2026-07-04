# 📖 Wikipedia Paul

A fully interactive fake Wikipedia article built as a Fourth of July gift for a friend who doesn't trust Wikipedia - complete with a Talk page argument, a sockpuppet accusation, and a revision history he can't win.

![License](https://img.shields.io/badge/license-MIT-blue)
![GitHub Pages](https://img.shields.io/badge/hosted-GitHub%20Pages-222?logo=github)

- 🕵️ **Opens on a fake Google search first** - tap the one real result to "discover" the article, exactly like stumbling onto it for real
- 📜 **Full mobile-Wikipedia styling** - collapsible sections, Table of Contents, infobox, citations, and a Talk page argument that ends in a sockpuppet accusation
- 🥩 **Grounded in real facts** - his actual novella, his actual naturalization post, his actual LinkedIn bio, all cited like sources

## Features

### Core Article
- 📖 **Full mock-Wikipedia layout** - infobox, Table of Contents, collapsible sections, category footer
- 🔍 **Fake Google search landing page** - the reveal moment before the article loads
- 🗣️ **Talk page argument** - includes a sockpuppet accusation and a thread debating whether brisket meets the notability threshold
- 🕓 **Revision history** - edit wars, a deletion attempt, and the subject's own reverted correction attempt

### Easter Eggs
- 🖱️ **"Edit" button** returns a fake permissions error
- 🔎 **Two hidden HTML comments** only visible via View Source / DevTools
- 🔝 **Self-referential redirect link** - scrolls back to the top of the page, a redirect that redirects to itself

## Live Demo

https://ohsusannamarie.github.io/wikipedia-paul

## Tech Stack

| Layer | Tech |
|---|---|
| Frontend | Vanilla HTML/CSS/JS, single file |
| Image | Base64-embedded PNG, no external assets |
| Styling | Custom CSS mimicking Wikipedia's mobile Vector skin |
| Hosting | GitHub Pages |

## Setup

```bash
git clone https://github.com/ohsusannamarie/wikipedia-paul.git
cd wikipedia-paul
open index.html
```

## License

[MIT](LICENSE) - use freely, attribution appreciated.

## Built With

No external APIs or libraries - handcrafted HTML, CSS, and vanilla JavaScript.

---

For every friend who's ever said "I don't trust Wikipedia" without realizing they were about to become an article on it.
