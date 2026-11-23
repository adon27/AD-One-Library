# AD ONE Library

Book idea cards for the Reading Corner of AD ONE, a personal Android app.
The app checks `index.json` here once a week (only when the reader has switched updates on) and downloads packs that are new or newer.

Each card is an original short summary of one idea from a book, written in our own words; no text is copied from the books.

Format and rules: see `tools/reading_packs.py` in the app's repository. Every pack listed in `index.json` must match its `bytes` and `sha256` exactly, or the app refuses it.
