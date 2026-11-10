# Corporate Finance & Game Theory: quiz prep

Live site: https://pulkitmangal09.github.io/CF-and-Game-Theory/

## Layout

```
index.html                     home page, lists every course and quiz
corporate-finance/
  quiz-1/index.html            Quiz 1 formula sheet + past papers
  quiz-2/                      (later)
  end-term/                    (later)
game-theory/
  quiz-1/  quiz-2/  end-term/  (later)
```

## Adding a quiz

1. Put the page at `<course>/<quiz>/index.html` (e.g. `game-theory/quiz-1/index.html`).
2. In the home page `index.html`, set `ready: true` for that quiz in the `COURSES` list.
3. Keep the `← All courses` link (`href="../../"`) at the top of the quiz page.
