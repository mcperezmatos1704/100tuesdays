# 100 Tuesdays / 100 Martes

A bilingual research project collecting anonymous answers to one question:
"Describe a Tuesday that felt like a good life."
Spanish: "Describe un martes que se sintió como una buena vida."

Goal: 100 submissions, then published findings.

## Stack
Plain HTML and CSS. No framework, no build step.

## Rules
- Every page works in English and Spanish.
- No JavaScript unless a feature actually requires it.
- Copy stays plain and specific. No inspirational filler, no "journey."
  Short sentences.
- Never use em dashes in site copy.
- Ask before adding any dependency.
- Explain what you're about to do before you write files.
- Never edit copy in copy.md or on the site. Copy is written by hand
  and changes only when explicitly asked.

  ## Design
- Palette (ColorBrewer PuOr): paper #F7F7F7, orange #F1A340, lavender #998EC3, plum ink #2A1F3D. All live as variables in :root in styles.css.
- Headline: Newsreader (Google Fonts, approved by me). Body: system font.
- Signature details: orange marker on Tuesday/martes, italic good life/buena vida, pill button with orange arrow, 100-dot counter.
- Counter update: change -n+X in styles.css plus the number in both language blocks.