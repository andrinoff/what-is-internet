# Latex Doc Template

A minimal Markdown-to-HTML document template with LaTeX math support. Write your content in a single Markdown file and get a clean, readable website.

## Features

- **LaTeX math** - Inline (`$...$`) and block (`$$...$$`) equations via KaTeX
- **Syntax highlighting** - Automatic code highlighting for 190+ languages
- **Dark/light mode** - Toggle with sun/moon button, respects system preference
- **Table of contents** - Expandable sidebar, auto-generated from headings
- **Reading stats** - Estimated read time, word count, last modified date
- **Reading progress** - Progress bar at the top of the page
- **Copy code** - One-click copy button on code blocks
- **Customizable footer** - Configure via frontmatter (author, license, contribute link)
- **Print-friendly** - Clean print styles
- **Responsive** - Works on mobile and desktop

## Usage

1. Edit `content.md` with your content
2. Serve the directory:
   ```bash
   python -m http.server 8000
   ```
3. Open http://localhost:8000

## Frontmatter

Configure the footer by adding YAML frontmatter at the top of `content.md`:

```yaml
---
author: Your Name
contribute_url: https://github.com/user/repo/edit/main/content.md
contribute_text: Edit this page
license: MIT License
license_url: https://opensource.org/licenses/MIT
footer_text: Made with latex-doc-template
---
```

All fields are optional. Omit the frontmatter block entirely to hide the footer.

## Math

Inline math uses single dollar signs:

```
The formula $E = mc^2$ is well known.
```

Block math uses double dollar signs:

```
$$
\int_{-\infty}^{\infty} e^{-x^2} dx = \sqrt{\pi}
$$
```

## Code

Fenced code blocks with language hints get syntax highlighting:

````
```python
def hello():
    print("Hello, world!")
```
````

## Deployment

This is a static site. Deploy by copying `index.html` and `content.md` to any static host:

- GitHub Pages
- Netlify
- Vercel
- Any web server

No build step required.

## License

MIT
