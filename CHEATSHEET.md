# 📝 Markdown Cheat Sheet

Each example shows what you type, then what it looks like. Leave a **blank line** between
headings, paragraphs, lists, and images, or they run together.

## Headings

Start a line with `#`. More `#` symbols make a smaller heading. Use one `#` heading at the
top, then `##` for each section.

```markdown
# Hi, I'm Dave 👋
## Professionally
### My first job
```

## Paragraphs and Line Breaks

Separate paragraphs with a blank line. Pressing <kbd>Enter</kbd> once doesn't start a new
line on GitHub.

```markdown
I live in Florence, KY.

I've been a web developer for over 10 years.
```

## Bold and Italic

```markdown
I'm a **Senior Front-End Engineer**.
I graduated from *UC Blue Ash*.
This is ***both***.
```

I'm a **Senior Front-End Engineer**.
I graduated from *UC Blue Ash*.
This is ***both***.

## Lists

Start each line with `-` for a bulleted list, or a number and a period for a numbered list.
Indent two spaces to nest a list.

```markdown
- Hiking
- Photography
  - Mostly landscapes
- Video games

1. Learn HTML
2. Learn CSS
3. Build my portfolio
```

- Hiking
- Photography
  - Mostly landscapes
- Video games

1. Learn HTML
2. Learn CSS
3. Build my portfolio

## Links

Put the text in square brackets and the URL in parentheses.

```markdown
I'm studying at [UC Blue Ash](https://www.ucblueash.edu).
```

I'm studying at [UC Blue Ash](https://www.ucblueash.edu).

## Images

Like a link, with a `!` in front. The text in the square brackets is the **alt text**: a
short description of the image for people who can't see it.

```markdown
![Dave smiling in a green plaid shirt](me.jpeg)
```

The path is relative to this file, so `me.jpeg` means the `me.jpeg` file in the same
folder as `README.md`. Paths are case-sensitive: `Me.JPEG` and `me.jpeg` are different
files.

To set the size, use an HTML `<img>` tag instead:

```html
<img src="me.jpeg" alt="Dave smiling in a green plaid shirt" width="300">
```

## Quotes

```markdown
> The best way to learn is to build something.
```

> The best way to learn is to build something.

## Code

Wrap short code in single backticks. For several lines, put three backticks on the lines
above and below, and name the language after the first three.

````markdown
My favorite tag is `<main>`.

```html
<h1>Hello, world!</h1>
```
````

My favorite tag is `<main>`.

```html
<h1>Hello, world!</h1>
```

## Horizontal Line

Three dashes on their own line, with a blank line above them.

```markdown
---
```

---

## Tables

```markdown
| Class | Semester |
| --- | --- |
| Web Design 1 | Fall |
| Web Design 2 | Spring |
```

| Class | Semester |
| --- | --- |
| Web Design 1 | Fall |
| Web Design 2 | Spring |

## Emoji

Paste an emoji directly (👋 🎨 💻), or use a shortcode like `:wave:` → :wave:.

## Learn More

- [Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
  (GitHub Docs)
- [Markdown Guide: Basic Syntax](https://www.markdownguide.org/basic-syntax/)
- [Markdown in WebStorm](https://www.jetbrains.com/help/webstorm/markdown.html) (JetBrains)
