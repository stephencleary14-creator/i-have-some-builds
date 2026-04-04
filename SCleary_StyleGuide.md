# CLAUDE.md

This file provides guidance to Claude Code when working with code in this repository.

## What This Repository Is

A single-file HTML personal brand style guide for **stephenjcleary**. Open `index.html` directly in a browser — no build step, no package manager, no server required.

## Running & Developing

```
open index.html
```

## File Conventions

Single file: inline `<style>` block → HTML markup → inline `<script>` block at the bottom. All CSS, markup, and JS live in `index.html`. External dependencies are limited to Google Fonts (loaded via `<link>`).

**Do not introduce** bundlers, npm, external JS libraries, or multi-file structures.

## Brand Tokens

```css
--cream:       #EDE0C4;  /* warm ecru — primary background */
--cream-light: #F7F2EA;  /* lighter cream — section backgrounds, cards */
--red:         #C8102E;  /* deep crimson — primary accent */
--red-deep:    #A00E24;  /* darker red — hover states, emphasis */
--dark:        #1C1C1C;  /* near-black — primary text */
--mid:         #5C5247;  /* warm brown-grey — muted/secondary text */
--font:        'Inter', 'Segoe UI', sans-serif;
```

## Tone of Voice

Full tone of voice guidance — voice characteristics, sentence patterns, vocabulary, format rules, and annotated real examples — is in `SCleary_ToneOfVoice.md`.

## Typography Rules

- **Typeface**: Inter (Google Fonts), weights 400 / 500 / 600 / 700
- **Headlines & titles**: Title Case — First Letter Of Each Word Is Capitalised
- **Body copy**: Sentence case — only the first word is capitalised
- **Never** use all-caps anywhere in the brand
