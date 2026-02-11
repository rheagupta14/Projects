# Letters(X) — Terminal-Based Card Game

**Course:** CMSC 14200 — University of Chicago  
**Language:** Python  
**Interface:** Text User Interface (TUI) with optional GUI extensions  
**Project Type:** Team course project

---

## Overview

Letters(X) is a Python-based card game centered on pattern recognition and
rule-based validation. Players search for valid groups of cards (“fits”)
based on shared and differing attributes, scoring points through correct
identification and strategic risk-taking.

The project emphasizes modular software design, separation of game logic
from user interfaces, and correctness through automated testing.

---

## Game Description

Each card has four attributes:

- a letter,
- a color,
- a typeface,
- and a count (number of letters displayed).

A **fit** consists of a fixed number of cards such that, for each attribute
independently, the cards are either all the same or all different.

**Letters(X)** generalizes the base game by parameterizing:

- the fit size,
- the number of attribute values,
- and the dimensions of the tableau.

Scoring scales automatically with fit size and tableau size, allowing a wide
range of valid game configurations while preserving the core rules.

---

## Project Structure

- `src/letters.py`, `card.py`, `tableau.py` — core game logic
- `src/tui.py` — terminal-based gameplay interface
- `src/gui.py` — optional graphical extensions
- `src/bot.py` — automated player logic
- `tests/` — unit tests and autograder checks

---

## My Contributions

- Implemented core game logic for validating fits across multiple card attributes
  (letter, color, typeface, and count), including generalized support for
  parameterized game variants.
- Contributed to the terminal-based user interface (TUI), enabling interactive
  gameplay and real-time validation of player actions.
- Assisted with GUI extensions and gameplay features such as automated players
  and scoring mechanics.
- Wrote and debugged unit tests to ensure correctness of game logic and edge
  cases under different configurations.
- Collaborated in a team environment using git and GitHub, integrating features
  across shared modules.

## Code Availability

This project was completed as part of a University of Chicago course.
Per academic integrity guidelines, the source code is not publicly available.

**Code available upon request.**
