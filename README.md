# PROGRAMMING IN JAVA — NPTEL Exam Prep

A colourful papercraft-inspired welcome page with a focused MCQ practice app and a separate study dashboard.

## Run locally

1. Clone or download this repository.
2. Open `index.html` for the welcome page.
3. Open `dashboard.html` to see your study progress.
4. Open `practice.html` to practise MCQs.
5. No build step or package installation is required for the static pages.

## Pages

- `index.html`: Welcome homepage, study navigation, exam schedule, certification rules and certificate details.
- `dashboard.html`: Overall completion, accuracy, correct answers, review queue and week-by-week progress.
- `practice.html`: Week-by-week MCQ practice, scrollable Practice mode, one-question-at-a-time Mock mode, search, review markers and answer feedback. `practice.html?week=1` through `practice.html?week=12` opens a selected week.

## Progress storage

The dashboard and practice page use the same browser storage key (`java-nptel-mcq-lab-v3`) so progress is shared when hosted on the same origin (for example on Vercel). Browser handling of `file://` storage can vary; for reliable cross-page progress sync, serve the files from one local server or deploy them to the same site.

## Question sources

- Weeks 1–6 are based on the NPTEL/SWAYAM assignment screenshots supplied. Some small or blurry code text was reconstructed into readable examples.
- Weeks 7–12 use supplied question-and-answer material and screenshots, reconstructing a few unreadable snippets as equivalent practice examples.

This is an independent study tool and is not affiliated with NPTEL or SWAYAM. Study progress is stored in the browser and is not synced between devices.

## UI details

- Study pages use a dark theme with background `#10141F`, foreground `#E4E4E4` and accent `#003C9C`.
- The homepage uses a colourful, layered papercraft theme and Lucide icons.
- Practice mode displays all matching questions on one scrollable page.
- Mock mode displays one question at a time, with submit-to-check behaviour.
- Built by Hrithik Burnwal.

## Exam information

The homepage reflects the course/exam details supplied for October 25, 2026. Check official NPTEL course announcements and the published registration form for updates, fee payment instructions, exam centres and conditions.
