# Web Practical Programs

A complete front-end web development practical submission covering **HTML**, **CSS** and
**JavaScript** — 257 hands-on experiments in total, built with plain HTML5, CSS3 and vanilla
JavaScript. No frameworks, no build tools, no Node.js/npm packages, and no server are required.

## Student Details

| Field | Value |
|---|---|
| **Name** | Sudha Akhil Eswar Reddy |
| **Roll Number** | 250200369 |
| **University** | Sai University |
| **Program** | B.Tech CSE |

## Project Structure

```
Web-Practical-Programs/
│
├── index.html                 Root project dashboard
├── README.md                  This file
│
├── html/                      15 HTML experiments
│   ├── index.html              Directory / search page
│   ├── html-01.html ... html-15.html
│   ├── html-11-style.css       External stylesheet used by HTML 11
│   ├── sample-audio.mp3        Bundled sample audio (HTML 06)
│   └── sample-video.mp4        Bundled sample video (HTML 06, CSS 44)
│
├── css/                        75 CSS experiments
│   ├── index.html               Directory / search page
│   ├── css-01.html ... css-75.html
│   └── css-01-style.css         External stylesheet used by CSS 01
│
└── javascript/                 167 JavaScript experiments
    ├── index.html                Directory / search page
    └── js-001.html ... js-167.html
```

## Experiment Counts

| Section | Experiments | Status |
|---|---|---|
| HTML | 15 | Complete |
| CSS | 75 | Complete |
| JavaScript | 167 | Complete |
| **Total** | **257** | **Complete** |

### JavaScript breakdown by category

| Category | Range | Count |
|---|---|---|
| Mini Projects | js-001 – js-017 | 17 |
| DOM Manipulation | js-018 – js-052 | 35 |
| Events | js-053 – js-082 | 30 |
| Forms & Validation | js-083 – js-122 | 40 |
| Browser Objects & Features | js-123 – js-142 | 20 |
| Web Storage | js-143 – js-167 | 25 |

## How to Run

This project requires **no installation** beyond a code editor and a browser.

1. Open the `Web-Practical-Programs` folder in **Visual Studio Code**.
2. Install the **Live Server** extension (by Ritwick Dey) if you don't already have it.
3. Right-click `index.html` in the file explorer and choose **"Open with Live Server"**.
4. Use the dashboard to navigate into the HTML, CSS and JavaScript sections. Each section has its
   own searchable, filterable directory page, and every experiment links back to its section
   directory and the main dashboard, plus (for JavaScript) Previous/Next navigation.

Opening `index.html` directly by double-clicking it also works for browsing, but a couple of
experiments (iframes referencing sibling pages, and the fetch()-based API demos) behave most
reliably when served over `http://` via Live Server rather than the `file://` protocol.

## Notes

- Two experiments (JS 006 – Weather App, JS 016 – Currency Converter) call free, key-free public
  APIs (Open-Meteo and open.er-api.com) and require an internet connection. If the network is
  unavailable, both show a clear, graceful error message instead of breaking.
- HTML 14 (Bootstrap Demonstration) loads Bootstrap 5 from a public CDN and needs an internet
  connection to render fully styled; every other page in the project works completely offline.
- No Node.js, npm, or any build tooling is used or required anywhere in this submission.
