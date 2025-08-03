# Ethan11San.github.io
This repository contains the `QuizMaker` web app and its data file `quizData.json`.

When loaded, `QuizMaker.html` will attempt to fetch quiz data from a local API
(`http://localhost:5001/api/quizData`). If that fails, it falls back to the
bundled `quizData.json` or the copy hosted on GitHub.

Any edits you make are stored in your browser's local storage. Use the
**Copy Local Changes** button to copy the entire JSON to your clipboard and
send it for inclusion in `quizData.json`. When the repository version matches
your local copy, the saved changes are cleared from the browser automatically.

## Changing folder colors

Right-click any folder name to quickly choose a custom color. Double-clicking now opens a dialog where you can edit the folder's name and color together.
