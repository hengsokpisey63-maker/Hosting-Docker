# FluentPath — English Study App

A responsive five-page English learning demo.

## Pages
1. Home dashboard (`#/home`)
2. Vocabulary (`#/vocabulary`) — 20 words, search, level/topic filters, Khmer translations, favorites, learned status, flashcards.
3. Grammar (`#/grammar`) — 10 lessons with examples and quick checks.
4. Practice (`#/practice`) — reading, listening, writing, speaking prompts, and a five-question quiz.
5. My Progress (`#/progress`) — learned words, completed lessons, quiz scores, milestones, and weekly activity.

## Run
No install is needed. Extract the ZIP and open `index.html` in a browser.
For a local server, run `python -m http.server 8000` in this folder, then open `http://localhost:8000`.

## Notes
Progress is saved in this browser using localStorage. This demo has no login, server database, or cross-device sync. Listening and speaking prompt playback use browser text-to-speech where available; speaking is not recorded or automatically evaluated.
