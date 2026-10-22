# PROGRAMMING IN JAVA — NPTEL Exam Prep

A standalone, responsive MCQ practice site with a separate dashboard and practice workspace.

## Run locally

1. Extract the ZIP.
2. Open `dashboard.html` for your study overview or `index.html` to practice MCQs.
3. No build step or package installation is required.

## Pages

- `dashboard.html`: Overall completion, accuracy, correct answers, review queue, and week-by-week progress cards.
- `index.html`: Focused MCQ practice page with week navigation, practice/mock mode, search, review markers, answer feedback, and per-week progress. `?week=1` through `?week=12` opens a selected week.

## Progress storage

Both pages use the same browser storage key (`java-nptel-mcq-lab-v3`) so progress is shared when hosted on the same origin (for example on GitHub Pages or Vercel). Browser handling of `file://` storage can vary; for reliable cross-page progress sync, serve both files from the same local server or deploy them to the same site.

## Question sources

- Weeks 1–6 are based on the NPTEL/SWAYAM assignment screenshots already supplied. Some small or blurry code text was reconstructed into readable examples.
- Weeks 7–12 use the supplied question-and-answer material and screenshots, reconstructing a few unreadable snippets as equivalent practice examples.

This is an independent study tool and is not affiliated with NPTEL or SWAYAM. Progress is stored in your browser and is not synced between devices.

## UI updates
- Dark theme uses background `#10141F`, foreground `#E4E4E4`, and accent `#003C9C`.
- Practice mode displays all matching questions in one scrollable page.
- Mock mode displays one question at a time, with submit-to-check behaviour.
- Built by Hrithik Burnwal.