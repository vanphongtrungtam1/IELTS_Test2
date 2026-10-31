IELTS ACADEMIC MOCK TEST 02 — GITHUB PAGES
========================================

1. Create a NEW GitHub repository (e.g. IELTS_TEST2) to preserve Test 01.
2. Upload all contents of this ZIP to the repository ROOT (no subfolders).
3. In Settings > Pages, set Deploy from a branch > main > /(root).
4. Open the public site after deployment.

FILES
- index.html, style.css, app.js, exam-data.js, sheet-config.js
- logo-cfl.jpg and logo-35-years.jpg (provided original logos)
- listening-library-plan.svg and listening-exchange-rate-flow.svg
- writing-chart.png (sharpened crop of ORIGINAL image from Writing Task 1 PDF)

CONNECT TO GOOGLE SHEETS
- Set up the separate TEST 02 Apps Script with the provided Code.gs and
  SpeakingAudio.gs. This project writes Test02_Submissions/Test02_Answers
  into the same spreadsheet as Test 01, without changing Test 01 sheets.
- Paste its NEW /exec deployment URL into sheet-config.js. The default value
  is empty; Test 02 submission to Google Sheets will NOT work until configured.
- Current backup submission folder link and result Google Sheet link are already
  set to the supplied URLs.

LISTENING AUDIO — INCLUDED AND CONNECTED
- Part 1: LISTENING_PART_1.mp3 — 05:36
- Part 2: LISTENING_PART_2.mp3 — 06:00
- Part 3: LISTENING_PART_3.mp3 — 06:07
- Part 4: LISTENING_PART_4.mp3 — 05:55
- Files were copied directly from your four MP3 uploads without re-encoding.
- Audio filenames are already configured in exam-data.js; do not rename files.
- All MP3s must be uploaded at the repository ROOT alongside index.html.
- The audio is not automatically played; click Play for the relevant Part.

THE EXAM
- Listening: 4 parts, Q1–40, original table/map/flow and answer inputs.
- Reading: 3 passages, Q1–40, independent scroll columns and answers.
- Writing: Task 1 original enhanced source image, Task 2 prompt, 2 independent
  scrollable panels and word counts.
- Speaking: Part 1–3, one continuous microphone recording, notes, ZIP export.
- Review: candidates confirm all answers, submit to Sheet, 30-second check,
  and receive a ZIP with recordings; Drive audio links require valid Apps Script.

Do not expose this website as an official IELTS testing platform or assume it
is a secure proctored exam. Candidate answers live in the browser until sent.
