# Bathysphere — Reading Comprehension Question Sets

A browser-based tool that presents reading-comprehension questions for classic
books across four levels of cognitive demand — **Literal, Inferential,
Analytical, and Evaluative** — in two formats you can toggle between:

- **Open-Ended** — each question with an answer key and two follow-up questions.
- **Multiple Choice** — a four-option quiz with instant correct/incorrect feedback.

Every question carries an aligned **CCSS ELA (Reading: Literature)** standard.

This is a **static proof of concept**: it runs entirely in the browser with no
login and no API key. Choose a book, pick a format, and it displays a ready-made
question set.

## Features
- Classic public-domain books, organized by grade band:
  **K–1, 1–2, 3–4, 5–6, 7–8, 8–9, 9–10, 11–12**
- Toggle between **Open-Ended** and **Multiple-Choice** formats
- Four cognitive levels per book
- Open-ended items include an answer key and two follow-up questions
- Multiple-choice items give immediate feedback and reveal the correct answer
- A CCSS ELA Reading: Literature standard on every question
- No account, no API key — open the page and use it

## Roadmap
An AI-powered version (built separately) connects live to Project Gutenberg's
~70,000 free books and generates fresh questions from any book — or any pasted
passage — using the Claude API and a small backend.

## License
MIT — see [LICENSE](LICENSE).
