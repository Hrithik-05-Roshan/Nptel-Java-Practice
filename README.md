# Programming in Java — NPTEL Exam Prep

A lightweight, browser-based revision tool for the NPTEL Programming in Java course. Practise 120 multiple-choice questions across 12 weeks, review mistakes, and track your progress without creating an account or installing a framework.

<p align="center">
  <a href="https://nptel-java-practice-fawn.vercel.app/"><strong>Open Study Hub</strong></a>
  ·
  <a href="https://nptel-java-practice-fawn.vercel.app/practice.html"><strong>Start Practising</strong></a>
  ·
  <a href="https://nptel-java-practice-fawn.vercel.app/dashboard.html"><strong>View Dashboard</strong></a>
</p>

## At a glance

- **120 MCQs** organised into **12 weeks**.
- **Practice mode:** answer questions on a scrollable page and get immediate feedback.
- **Mock mode:** work through one question at a time and submit your answer to check it.
- **Progress dashboard:** review completion, accuracy, correct answers, and week-by-week activity.
- **Revision tools:** search questions, filter unanswered or incorrect questions, and mark questions for review.
- **Local-first progress:** answers are saved in your browser, with no account required.
- **Static site:** HTML, CSS, and JavaScript. No package installation or build step.

## Live pages

| Page | What it does |
| --- | --- |
| [Study hub](https://nptel-java-practice-fawn.vercel.app/) | Course overview, quick navigation, progress summary, and exam information |
| [MCQ practice](https://nptel-java-practice-fawn.vercel.app/practice.html) | Select a week, answer questions, filter/search, and review explanations |
| [Progress dashboard](https://nptel-java-practice-fawn.vercel.app/dashboard.html) | See saved performance and progress across the 12-week track |

## Screens and workflow

1. Open the [Study Hub](https://nptel-java-practice-fawn.vercel.app/).
2. Choose a week or jump straight to the [practice page](https://nptel-java-practice-fawn.vercel.app/practice.html).
3. Use **Practice mode** for instant answer feedback, or **Mock mode** to check answers after selecting them.
4. Mark difficult questions for review and use the filters to revisit unanswered or incorrect questions.
5. Open the dashboard to check progress and accuracy.

### Open a specific week

Append a `week` query parameter from 1 to 12:

- `practice.html?week=1`
- `practice.html?week=6`
- `practice.html?week=12`

Example: [Open Week 1](https://nptel-java-practice-fawn.vercel.app/practice.html?week=1).

## Run locally

No Node.js, dependencies, or build command are required.

### Option 1: open the files

1. Clone or download this repository.
2. Open `index.html` in your browser.
3. Open `practice.html` for questions or `dashboard.html` for progress.

Browser restrictions can make storage behaviour for directly opened `file://` pages inconsistent. Use a local server for reliable progress sharing between pages.

### Option 2: serve the folder locally

```bash
git clone https://github.com/Hrithik-05-Roshan/Nptel-Java-Practice.git
cd Nptel-Java-Practice
python -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

## Progress and privacy

- Practice and dashboard pages use the same localStorage key: `java-nptel-mcq-lab-v3`.
- Progress is saved in the browser on the current device and browser profile.
- Progress is **not** synced across devices and is not stored in a remote database.
- Clearing site data or browser storage can delete saved progress.
- For cross-page sync to work as expected, open the pages from the same origin (for example, the deployed Vercel site or one local server).

## Question bank and accuracy notes

The question bank was assembled from assignment screenshots and question/answer material supplied for study preparation. Some small or blurry code snippets were reconstructed as readable, equivalent examples.

Treat this as a **revision aid**, not an official answer key. Check course materials and official NPTEL/SWAYAM announcements if an answer, interpretation, exam rule, or date matters to your preparation.

## Exam information

The study hub includes exam and certification details supplied for the **October 25, 2026** exam. Exam dates, sessions, fees, eligibility rules, centres, and registration instructions can change. Verify the latest details through official NPTEL/SWAYAM course announcements before making exam arrangements.

## Tech stack

- HTML5
- CSS3
- Vanilla JavaScript
- Browser localStorage for progress
- Lucide icons
- Vercel for deployment

## Project structure

```text
.
├── index.html       # Study hub and exam information
├── practice.html    # 12-week, 120-question MCQ practice app
├── dashboard.html   # Progress and performance dashboard
└── README.md        # Project documentation
```

## Limitations

- No account system or cloud sync.
- Saved progress belongs to the current browser/device.
- Question wording may differ from the official assignment if an image was unreadable and had to be reconstructed.
- This project is independent and is **not affiliated with NPTEL or SWAYAM**.

## Author

**Hrithik Burnwal**

- GitHub: [@Hrithik-05-Roshan](https://github.com/Hrithik-05-Roshan)
- Repository: [Nptel-Java-Practice](https://github.com/Hrithik-05-Roshan/Nptel-Java-Practice)

---

Built for focused Java revision. Good luck with the exam.