# Word Formation — Studio v2

Public word-formation reference and study environment in American English, designed for teachers and students.

## Features

- **Library:** search across 40 manually curated word families (183 documented forms) and 27 prefix/suffix entries
- **Family map:** visually explore each family's nouns, verbs, adjectives and adverbs, with selected derivation paths where verified
- **Compare:** view any two entries from the same family side by side, with definitions, examples and pronunciation
- **Practice:** contextual fill-in prompts drawn from attested examples; reveal a model answer and meaning; avoid falsely marking alternative natural answers as wrong
- **My list:** save words in the current browser, copy study notes and practice saved words
- **American English pronunciation:** built-in browser speech synthesis with en-US preference; output quality depends on the available voice
- **Definitions:** English by default, optional Portuguese for comprehension
- **Deep links:** share a family or affix through URL fragments (`#word=rely`, `#affix=un-`)
- **Copy:** copy family summaries, examples and comparisons for lessons

## Content policy

This is a reviewed starter reference, **not an exhaustive dictionary**. Word forms have been entered individually. The site does not combine arbitrary prefixes and suffixes, because a morphologically possible string may be unnatural, uncommon or change meaning unexpectedly. Affix meanings are approximate and may vary by word and history.

The study list and practice progress are stored **only in this browser** using localStorage. They are not synchronized between devices or associated with student accounts. The site requires no server, paid API, login or database.

## Hosting

Deployed from `main` at repository root through GitHub Pages. Files: `index.html`, `styles.css`, `app.js`, `studio.js`, `data.js`, `.nojekyll`.

## Maintenance

- Lexicon: `data.js`
- Visual style: `styles.css`
- Reference search/details: `app.js`
- Additional tools: `studio.js`
- Layout and navigation: `index.html`

Review definitions, American usage and contextual examples before expanding entries. Verify desktop and mobile accessibility and the browser's pronunciation quality before teaching.
