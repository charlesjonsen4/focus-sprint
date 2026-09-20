# Focus Sprint

A small, single-file focus timer. Pick one thing, run a sprint, take a break.

## Run it

There is nothing to install or build. Open `index.html` in any modern browser.

## Features

- **Timer** with 15, 25, or 50 minute focus sprints, followed by a 5 minute break.
- **One thing** field to name what you're working on for the current sprint.
- **Task list** ("Up next") to queue tasks, tick them off, and send one to the focus field.
- **Sprint log** of today's completed sprints, with a running total shown in the header.
- **Chime** when a sprint or break ends.
- **Light and dark themes**, following your system setting.

## Controls

| Control | What it does |
| --- | --- |
| Start / Pause / Resume | Runs or pauses the timer. `Space` does the same. |
| Reset | Returns the current timer to its full length. |
| Skip | Switches between focus and break. |
| Clear log | Deletes all logged sprints. Click twice to confirm. |

The focus length can't be changed while a focus sprint is running.

## Your data

Everything stays in your browser's `localStorage` under the key `focusSprint.v1`. Nothing is sent anywhere, and clearing your site data resets the app.
