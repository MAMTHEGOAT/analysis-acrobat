# Analysis Acrobat

A single-file browser app for practising **Cambridge IGCSE First Language English (0500)** extended language analysis — Paper 1, Question 3(d) (pre-2027: Question 2(d)). Built around the house "3D" analysis scaffold (opening effect → three ideas, each with a technique, a literal *Move 1* and an implied *Move 2*).

**Live app:** <https://mamthegoat.github.io/analysis-acrobat/>

## What it does

A two-column home screen:

- **Learn** — Instructions, Exam strategy (with an annotated model answer), and Techniques explained.
- **Practice** — Explicit and implied meaning, Identifying techniques, Unpacking imagery, Building analytical paragraphs, and Writing a complete response (a full exam-style answer with deterministic, no-AI feedback).

The whole thing is one self-contained `index.html` (the logo is embedded; no external files, no build step), so it runs from any host that serves static files.

## Run locally

Open `index.html` in a browser, or serve the folder:

```
pwsh ./serve.ps1   # http://localhost:8765
```

## Editing the content

`SPEC.md` is the authoring spec and standards; `validate.ps1` checks the content banks for errors; `CLAUDE.md` holds build instructions. The app's content is original (no copyrighted exam material).
