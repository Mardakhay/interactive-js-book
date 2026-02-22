# Interactive JavaScript Book

> An interactive single-file HTML JavaScript book — built from personal Notion notes — covering 27 topics from basics to advanced, with a live code editor, quizzes, and progress tracking.

---

## Demo

Just download and open `js_interactive_book.html` in any browser. No server, no install, no internet required.

---

## Features

- **Live code editor** — edit and run JavaScript directly in the browser on every topic
- **Quizzes** — instant correct/wrong feedback to test your understanding
- **Progress tracker** — sidebar fills up as you complete each section
- **Live DOM & Event demos** — interact with real elements, no code needed
- **Previous / Next navigation** — move through topics in order
- **Dark theme** — easy on the eyes during long study sessions
- **Zero dependencies** — pure HTML, CSS, and JavaScript, one file

---

## Contents

### Basics
| # | Topic |
|---|-------|
| 1 | Introduction & Console |
| 2 | Variables & Data Types |
| 3 | Operators |
| 4 | Conditionals (if/else, switch, ternary) |
| 5 | Functions (declarations, expressions, arrow) |
| 6 | Scope |
| 7 | Arrays & Array Methods |
| 8 | Loops (for, while, do...while) |
| 9 | Iterators (map, filter, reduce, forEach…) |
| 10 | Objects (methods, getters/setters, this) |
| 11 | Classes & Inheritance |

### Intermediate
| # | Topic |
|---|-------|
| 12 | Promises |
| 13 | Async / Await |
| 14 | Fetch API & HTTP Requests |
| 15 | Errors & Debugging |
| 16 | Modules (CommonJS & ES6) |

### Advanced
| # | Topic |
|---|-------|
| 17 | Destructuring (array & object) |
| 18 | Spread & Rest Operators |
| 19 | Optional Chaining `?.` & Nullish Coalescing `??` |
| 20 | Maps & Sets |
| 21 | Closures |
| 22 | Prototypes & Prototypal Inheritance |
| 23 | call() / apply() / bind() |
| 24 | Generators & Iterators |
| 25 | DOM Manipulation |
| 26 | Events |
| 27 | Memory Management |

---

## Usage

1. **Download** `js_interactive_book.html`
2. **Open** it in any modern browser (Chrome, Firefox, Edge, Safari)
3. **Learn** — read the explanation, edit the code, run it, answer the quiz
4. **Track** your progress in the left sidebar

No Node.js, no npm, no build step. Just one file.

---

## Project Structure

```
js_interactive_book.html   ← Everything in one file
README.md
```

---

## How It Works

The entire book is a self-contained HTML file with:

- **CSS** — dark-themed responsive layout with sidebar navigation
- **HTML** — 27 lesson sections, each with explanations, code blocks, editors, and quizzes
- **Vanilla JS** — sandboxed code runner (redirects `console.log` to on-page output), quiz logic, progress tracking, and section navigation

Code in the editor runs inside a sandboxed `new Function()` scope so it cannot affect the page itself.

---

## Source

This book was generated from personal **Notion notes** on JavaScript, covering both fundamentals (`JavaScript.pdf`) and advanced topics (`Advanced_JS.pdf`).

---

## Contributing

Feel free to fork and add:
- More topics (e.g. TypeScript, Web APIs, Node.js)
- More quiz questions
- Code challenges with expected output validation

---

## License

MIT — free to use, share, and modify.
