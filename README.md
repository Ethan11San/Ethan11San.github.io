# Ethan11San.github.io
This repository contains the `QuizMaker` web app and its data file `quizData.json`.

When loaded, `QuizMaker.html` will attempt to fetch quiz data from a local API
(`http://localhost:5001/api/quizData`). If that fails, it falls back to the
bundled `quizData.json` or the copy hosted on GitHub.

Any text edits you make are stored in your browser's local storage. Images
added to questions are kept separately in IndexedDB and referenced by a content
hash. Use the **Copy Local Changes** button to either copy the JSON diff to
your clipboard or, if you provide a GitHub token when prompted, automatically
upload your changes and any new images directly to this repository.
When the repository version matches your local copy, the saved changes are
cleared from the browser automatically.

## Changing folder colors

Right-click any folder name to quickly choose a custom color. Double-clicking now opens a dialog where you can edit the folder's name and color together.
