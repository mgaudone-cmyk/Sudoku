# Sudoku Notes Upgrade

This version restores the full Sudoku app and improves notes.

## New upgrades

- Larger note numbers inside cells
- Auto notes button
- Single-candidate hint button
- Live conflict highlighting when the same number conflicts in a row, column, or box
- Existing features preserved:
  - Real Sudoku generator
  - Unique solution validation
  - Difficulty levels
  - Timer
  - Pause/resume overlay
  - Notes mode
  - Hint
  - Check
  - Solve
  - Matching-number highlight
  - Mistake tracking

## How notes work

- Notes OFF: numbers entered are final answers.
- Notes ON: numbers entered are pencil marks/candidates.
- Auto notes fills possible candidates based on the current board.
- Single hint finds a cell with only one possible candidate, when available.

## Deploy

Replace your GitHub repo files with:

- `index.html`
- `README.md`

Your expected GitHub Pages URL:

```text
https://mgaudone-cmyk.github.io/Sudoku/
```

## Best mobile experience

Open in Safari, tap Share, then Add to Home Screen.
