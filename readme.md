# Advanced Behaviour Tracker

An advanced version of my Website Behaviour Tracker, built as one HTML file in vanilla JavaScript with no libraries. The demo page is a fictional shop, **Northward Supply Co.**, and the tracker is a docked console at the bottom of the page with 5 tabs.

## Features

- **Click tracking** with dead-click and rage-click detection
- **Cursor, scroll, keyboard, form, selection and dwell tracking**, recording key categories only
- **Session replay** with a ghost cursor, a scrubbable timeline and speeds from ×0.5 to ×4
- **Canvas overlays:** heatmap with adjustable radius, scatter, trail and zones
- **Analytics:** engagement index (0–100), session funnel, event-rate chart, and a live event stream with filters and search
- **Export** as JSON, CSV or a text report, plus save and restore with `localStorage`

## How to Run

1. Open the HTML file in a browser. No server is needed.
2. Interact with the page, and the console records everything live.
3. Use the tabs to replay, visualise and export your session.

## Quick Demo

1. Click on headings to trigger **dead clicks**.
2. Spam a button to trigger **rage clicks**.
3. Drag the **Cold Index** slider.
4. Submit the form.
5. Play the session in the **Replay** tab.
6. View the **Heatmap**.
7. Export your data from the **Data** tab.

## Privacy

Typed characters and form values are never recorded. All data stays in the browser.

## Built With

HTML, CSS and vanilla JavaScript
