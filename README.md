# test.quarto.website

A scratch Quarto website for debugging Quarto problems.
It is not a template and not a course site: nothing depends on it, and nothing is published from it.

Use it, or a branch of it, to reproduce a Quarto problem in a small project before changing a real site
([Morrison-Lab/ai-config#4274](https://github.com/Morrison-Lab/ai-config/issues/4274)).
Its sibling for books is [`quarto.test.book`](https://github.com/Morrison-Lab/quarto.test.book).
To start a real site, use the template [`qwt`](https://github.com/Morrison-Lab/qwt) instead.

## What is here

- Two pages, `index.qmd` and `about.qmd`.
- `_quarto.yml`, a website project with `revealjs` and `html` formats.
- An `renv` project (`renv.lock`), for pages that run R.

## Working here

- Put each experiment on its own branch, named for what it tests.
- Say what the branch showed, in its pull request or in an issue, before leaving it.
