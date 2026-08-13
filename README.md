# cs499-eportfolio

Static ePortfolio for SNHU CS 499 Computer Science Capstone.

Published at `https://sireniklas.github.io/cs499-eportfolio/`.

## Structure

```
index.html         professional self-assessment and outcome ledger
code-review.html   code review video and written summary
artifacts.html     three enhancements with narratives and commit links
assets/styles.css  single stylesheet, no build step
.nojekyll          serve files as-is, skip Jekyll processing
```

## Before submitting

- [ ] Replace `REPLACE_WITH_VIDEO_ID` in `code-review.html` (two places)
- [ ] Replace every `commit permalink` href in `artifacts.html` with a real SHA URL
- [ ] Fill and delete every `<div class="todo">` block
- [ ] Confirm no `todo` class remains: `grep -rn 'class="todo"' .`
