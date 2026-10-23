# Reader's Guide — system-design-primer

## What this project is

**The System Design Primer** is a structured course for **learning how to
design large-scale systems and preparing for system design interviews**. It
organises a sprawling subject — scalability, availability, databases,
caching, load balancing and the rest — into a study guide with explanations,
diagrams, trade-off discussions, and worked solutions to the classic
interview questions.

## How the content is organised

- [`README.md`](README.md) — the course itself (this guide was written from
  its section outline and the repository tree; the README is long). Its flow:
  - **Motivation**, **Anki flashcards**, **Contributing** — why the primer
    exists and how to memorise it.
  - **Index of system design topics** and a **Study guide** — the suggested
    order of attack depending on how much time you have.
  - **How to approach a system design interview question** — the method to
    apply before any specific question.
  - **System design interview questions with solutions** and
    **Object-oriented design interview questions with solutions** — the
    practice sets, linking into `solutions/`.
  - **System design topics: start here** — the concept chapters:
    Performance vs scalability, Latency vs throughput, Availability vs
    consistency, Consistency patterns, Availability patterns, Domain name
    system, Content delivery network, Load balancer, Reverse proxy,
    Application layer, Database, Cache, Asynchronism, Communication,
    Security — plus an **Appendix** of further material.
- `solutions/system_design/` and `solutions/object_oriented_design/` — the
  worked solutions (discussions, architectures, code) for the question sets.
- `resources/flash_cards/` — the Anki flashcard decks; `resources/` also
  holds the study-guide diagram sources.
- `images/` — the diagrams used throughout the README.
- Translations live alongside the English original (`README-ja.md`,
  `README-zh-Hans.md`, `README-zh-TW.md`); `TRANSLATIONS.md` tracks the many
  more in progress. `generate-epub.sh` builds an ebook edition.

## How to use it

1. Read **How to approach a system design interview question** first — the
   framework matters more than any single answer.
2. Work through **System design topics: start here** in order, using the
   **Study guide** to pace yourself.
3. Practise with the question sets, compare against `solutions/`, and drill
   the weak spots with the Anki decks in `resources/flash_cards/`.

## About this standalone edition

This repository is a standalone edition of
[donnemartin/system-design-primer](https://github.com/donnemartin/system-design-primer),
converted from a fork into its own repository and enhanced in place. See
[`ENHANCEMENTS.md`](ENHANCEMENTS.md) for what this edition adds and
[`CHANGELOG.md`](CHANGELOG.md) for its version history (v1.0.0 upstream
baseline, v1.1.0 enhancements). All original work belongs to Donne Martin and
the upstream contributors; licence in `LICENSE.txt`.
