# Focus Desk / 番茄工位

A browser-based Pomodoro timer and focus journal for study topics and projects.

## Run locally

Open `index.html` in a modern browser, or serve the repository with a static web server. For example, run `python -m http.server 8000` from the repository root and open `http://localhost:8000`.

There is no build step. The app can be hosted on any static host.

## Features

- A configurable focus timer, five-minute breaks, and optional ticking sound.
- Categories and individual items, with duplicate item detection within each category.
- Daily totals, editable history, manual time entries, and weekly and monthly trends.
- Learning notes that are drafted during focus and saved with the time record.
- English by default, with a Simplified Chinese language selector.

Records, notes, settings, and active timers are stored in browser local storage. They are scoped to the browser profile and site address.

## Making changes

Use a branch for each change, test it in a browser, and commit it with a descriptive message. Open a pull request against `main` for review. Deploy from a specific commit so the deployed version can be traced back to Git history.

## License

[MIT](LICENSE)
