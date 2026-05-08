# Sudoku Stable iPad Layout

This version fixes the iPad clipping problem by changing the layout strategy.

## What changed

- The app no longer hard-locks the page with `overflow:hidden`.
- The board size is calculated from the real visible screen area.
- iPad landscape now shrinks the board before cutting off controls.
- iPad portrait and Home Screen web-app mode use safer top spacing.
- If the browser leaves too little room, the page can scroll slightly instead of clipping the board or controls.

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
