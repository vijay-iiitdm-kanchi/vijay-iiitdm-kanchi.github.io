---
title: "Introduction to Data Science for Engineers"
collection: teaching
type: "Undergraduate Course"
permalink: /teaching/intro-data-science-engineers
venue: "Department of CSE, IIITDM Kancheepuram"
date: 2026-07-01
location: "Chennai, India"
---

A working introduction to data science for engineering students — building from Python's object model up to fitting and evaluating models on real data. The emphasis throughout is on *running* things rather than reading about them, so most modules ship with an interactive tool that executes Python directly in the browser.

**Prerequisites:** basic programming exposure in any language. No prior Python assumed.

---

## Course Map

| # | Topic | Materials | Status |
|---|-------|-----------|--------|
| 1 | Datatypes, Strings & Collections | [Interactive lecture](/files/cs3006-l34/) | Available |
| 2 | Control Flow & Functions | — | Coming soon |
| 3 | NumPy: Arrays & Vectorised Thinking | — | Coming soon |
| 4 | pandas: Tabular Data & Cleaning | — | Coming soon |
| 5 | Visualisation & Exploratory Analysis | — | Coming soon |
| 6 | Probability & Descriptive Statistics | — | Coming soon |
| 7 | Regression | — | Coming soon |
| 8 | Classification | — | Coming soon |
| 9 | Model Evaluation & Overfitting | — | Coming soon |
| 10 | End-to-End Case Study | — | Coming soon |

---

## Module 1 — Datatypes, Strings & Collections

The foundation the rest of the course stands on: **everything in Python is an object**, and identity (`id()`) explains behaviour that otherwise looks arbitrary.

* **Datatypes & Identity** — `int`, `float`, `str`, and `bool` as objects with an address, a type, and a value.
* **Mutable vs Immutable** — why an integer gets a *new* address when reassigned, while a list keeps its address after modification.
* **Strings** — slicing, cleaning, and f-strings, all consequences of strings being unmodifiable in place.
* **Collections** — choosing between `list`, `tuple`, `set`, and `dict` based on ordering, uniqueness, and mutability.
* **The Aliasing Trap** — why `b = a` on a list does not give you an independent copy.

**[▶ Open the interactive lecture](/files/cs3006-l34/)**

74 interleaved cards: teaching slides, 29 predict-the-output exercises, and 6 concept questions, with a live Python scratchpad built in. Python runs locally in your browser via WebAssembly — nothing to install, and no internet needed after the first load.

*Controls:* `Space` / `→` next · `←` previous · `R` run the snippet · `A` reveal the answer · `S` scratchpad · `F11` full screen.

**Practice before the lab:**

1. After `x = 5; y = x; x += 1`, what does `id(y)` reveal about how assignment works?
2. Why does `s.upper()` return a value instead of modifying `s`, and what happens if you discard the return value?
3. You need to count unique words in a document, then report them by frequency. Which two collection types, and in what order?
4. Given `a = [1, 2, 3]` and `b = a`, predict `b.append(4); print(len(a))`. Now predict it again for `b = a[:]`.

---

> **Note to students:** The predict-the-output cards only work if you commit to an answer *before* pressing `R`. Being wrong on record and then finding out why teaches considerably more than guess-and-check.
