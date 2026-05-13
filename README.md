# Math Matcher — multiplication table trainer

A static web game: cards with math expressions (multiplication and division) and numeric answers are scattered on the board. Find every pair where the expression evaluates to the number on the other card.

## Why use it

Short play sessions help **automate recall** of the multiplication table and inverse operations (division), including larger ranges up to about 100 on the hardest level.

## Difficulty levels

1. Multiplication and division within the times table up to 10.
2. Same value shown in different forms (e.g. two different expressions with one answer).
3. Larger numbers (including up to ~100), including “big product” and division variants.

## Running locally

After cloning this repository, serve the folder with any static file server (or use the site root on GitHub Pages). The app is built as an SPA with relative asset paths (`./`).

## Publishing (short)

With `origin` configured in this repo and branch usually `main`:

```bash
git add -A
git commit -m "Deploy"
git push -u origin main
```

Exact steps depend on your host (GitHub Pages: project site from a branch or folder — match your repo settings).
