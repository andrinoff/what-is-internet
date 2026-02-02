---
author: Drew Smirnoff
contribute_url: https://github.com/andrinoff/latex-doc-template/edit/main/content.md
contribute_text: Edit this page
license: MIT License
license_url: https://opensource.org/licenses/MIT
---

# My Document

This is a sample document with **Markdown** and LaTeX support. Edit this file to write your content.

## Inline Math

The quadratic formula is $x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$. You can also write things like $e^{i\pi} + 1 = 0$ inline.

## Block Math

$$
\int_{-\infty}^{\infty} e^{-x^2} dx = \sqrt{\pi}
$$

Maxwell's equations:

$$
\nabla \times \mathbf{E} = -\frac{\partial \mathbf{B}}{\partial t}
$$

## Code Examples

Here's some Python with syntax highlighting:

```python
def fibonacci(n):
    """Generate Fibonacci sequence up to n."""
    a, b = 0, 1
    while a < n:
        yield a
        a, b = b, a + b

for num in fibonacci(100):
    print(num)
```

And some JavaScript:

```javascript
const fetchData = async (url) => {
  const response = await fetch(url);
  const data = await response.json();
  return data;
};
```

## Lists

- Item one with **bold** text
- Item two with *italic* text
- Item three with `inline code`

1. First ordered item
2. Second ordered item
3. Third ordered item

## Blockquotes

> This is a blockquote. It can contain multiple paragraphs and other elements.
>
> Like this second paragraph with some math: $a^2 + b^2 = c^2$

## Tables

| Language   | Typing     | Paradigm        |
|------------|------------|-----------------|
| Python     | Dynamic    | Multi-paradigm  |
| Rust       | Static     | Systems         |
| Haskell    | Static     | Functional      |
| JavaScript | Dynamic    | Multi-paradigm  |

## Links and Images

Visit [GitHub](https://github.com/andrinoff/latex-doc-template) for more information.

---

That's it! Start editing this file to create your own document.
