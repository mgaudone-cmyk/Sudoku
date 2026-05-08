# Sudoku iPad Dynamic Fix

This version keeps the full working Sudoku game and fixes the iPad top clipping issue using dynamic board sizing.

## Fix

The board now calculates its size based on the real visible browser area instead of relying on fixed CSS viewport estimates. This is especially important on iPad Safari.

## Features preserved

- Real Sudoku generator
- Unique solution validation
- Difficulty levels
- Larger note numbers
- Auto notes
- Single-candidate hint
- Live conflict highlighting
- First-time onboarding flow
- Help button
- Timer
- Pause/resume overlay
- Notes mode
- Hint
- Check
- Solve
- Matching-number highlight
- Mistake tracking

## Deploy

Replace your GitHub repo files with:

- `index.html`
- `README.md`

Expected URL:

```text
https://mgaudone-cmyk.github.io/Sudoku/
```

## Best full-screen experience

On iPhone or iPad, open in Safari, tap Share, then Add to Home Screen.
