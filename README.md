# Ethan11San.github.io
This repository contains the `QuizMaker` web app and its data file `quizData.json`.

When loaded, `QuizMaker.html` will attempt to fetch quiz data from a local API
(`http://localhost:5001/api/quizData`). If that fails, it falls back to the
bundled `quizData.json`. If the JSON file cannot be loaded locally (for example
when opening the page directly from the file system), a final fallback fetches
`quizData.json` from the GitHub repository.

## Changing folder colors

Right-click any folder name to quickly choose a custom color. Double-clicking now opens a dialog where you can edit the folder's name and color together.
