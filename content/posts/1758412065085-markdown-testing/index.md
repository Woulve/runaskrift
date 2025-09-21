---
title: "Markdown Testing"
date: 2025-09-20
draft: false
description: "Comprehensive markdown styling test for Hugo static site generator"
tags: ["markdown", "testing", "hugo", "styling"]
---

# Markdown Styling Test

This post contains various markdown elements to test styling in Hugo.

## Headings

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

## Text Formatting

**Bold text** and __also bold__

*Italic text* and _also italic_

***Bold and italic*** and ___also bold and italic___

~~Strikethrough text~~

`Inline code` with backticks

## Links

[External link to Hugo](https://gohugo.io/)

[Internal link](#code-blocks)

<https://example.com> - Automatic link

## Lists

### Unordered Lists

- Item 1
- Item 2
  - Nested item 2.1
  - Nested item 2.2
    - Deep nested item 2.2.1
- Item 3

### Ordered Lists

1. First item
2. Second item
   1. Nested numbered item
   2. Another nested item
3. Third item

### Task Lists

- [x] Completed task
- [ ] Incomplete task
- [x] Another completed task

## Blockquotes

> This is a blockquote
> 
> It can span multiple lines

> Nested blockquotes
> 
> > This is nested
> > 
> > > And this is deeply nested

## Code Blocks

### Inline Code

Here's some `inline code` in a sentence.

### Fenced Code Blocks

```javascript
function greet(name) {
    console.log(`Hello, ${name}!`);
}

greet('World');
```

```python
def fibonacci(n):
    if n <= 1:
        return n
    return fibonacci(n-1) + fibonacci(n-2)

print(fibonacci(10))
```

```css
.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
}

.button {
    background-color: #007bff;
    color: white;
    border: none;
    padding: 10px 20px;
    border-radius: 4px;
}
```

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Test Page</title>
</head>
<body>
    <h1>Hello World</h1>
    <p>This is a test paragraph.</p>
</body>
</html>
```

### Code Block Without Language

```
This is a code block without syntax highlighting
It preserves formatting and spacing
    Including indentation
```

## Tables

| Column 1 | Column 2 | Column 3 |
|----------|----------|----------|
| Row 1, Col 1 | Row 1, Col 2 | Row 1, Col 3 |
| Row 2, Col 1 | Row 2, Col 2 | Row 2, Col 3 |
| Row 3, Col 1 | Row 3, Col 2 | Row 3, Col 3 |

### Table with Alignment

| Left Aligned | Center Aligned | Right Aligned |
|:-------------|:--------------:|--------------:|
| Left | Center | Right |
| Text | Text | Text |
| More | More | More |

## Horizontal Rules

---

***

___

## Images

![Alt text for image](featured.png "Optional title")

## Line Breaks

This is a line with two spaces at the end  
This creates a line break

This is a paragraph.

This is another paragraph with a blank line above.

## Escape Characters

\*This text is not italic\*

\`This is not code\`

\# This is not a heading

## HTML Elements

<div style="background-color: #f0f0f0; padding: 10px; border-radius: 5px;">
This is HTML content within markdown
</div>

<details>
<summary>Click to expand</summary>

This content is hidden by default and can be expanded.

- Item 1
- Item 2
- Item 3

</details>

## Footnotes

Here's a sentence with a footnote[^1].

Another sentence with another footnote[^note].

[^1]: This is the first footnote.
[^note]: This is a named footnote.

## Definition Lists

Term 1
: Definition 1

Term 2
: Definition 2a
: Definition 2b

## Abbreviations

*[HTML]: Hyper Text Markup Language
*[CSS]: Cascading Style Sheets

The HTML specification is maintained by the W3C.

## Math (if supported)

Inline math: $E = mc^2$

Block math:
$$
\sum_{i=1}^{n} x_i = x_1 + x_2 + \cdots + x_n
$$

## Special Characters

© ® ™ § ¶ † ‡ • … ‰ ′ ″ ‴ ※ ‼ ⁇ ⁈ ⁉ ⁏ ⁗ ‖ ‗ ' ' ‚ ‛ " " „ ‟

## Emojis

:smile: :heart: :thumbsup: :rocket: :fire: :100:

😀 😃 😄 😁 😆 😅 😂 🤣 😊 😇

## Mixed Content Test

Here's a paragraph with **bold**, *italic*, `code`, and a [link](https://example.com).

> A blockquote with **bold text** and `inline code`
> 
> - List item in blockquote
> - Another item

1. Ordered list with `code`
2. **Bold item**
3. *Italic item*

---

This comprehensive test covers most markdown elements to help you verify styling in your Hugo theme.