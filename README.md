# AP Special TET — Topic Options & A–D Practice

**గంగలపూడి భాస్కర్ రెడ్డి · Gangalapudi Bhasker Reddy**

## Files to upload

- `index.html` — complete standalone practice website.
- `.nojekyll` — GitHub Pages static-file marker.
- `README.md` — these instructions.

Extract the ZIP first. Upload the extracted files, with `index.html` directly in your repository's publishing folder. For a repository published from its root, put the files in the root, without an extra enclosing folder.

## Update the existing website

Replace your old `index.html` with this new `index.html`, then commit the change. Keep your existing GitHub Pages publishing settings. Wait for that commit's Pages deployment to finish before opening the updated website. If the old layout is still visible, reload the page with **Ctrl + F5**.

**తెలుగు:** ZIPను extract చేసి, అందులోని ఫైళ్ళను మీ GitHub repositoryలో upload చేయండి. పాత `index.html` స్థానంలో కొత్త `index.html` పెట్టి commit చేయండి. Deployment పూర్తయిన తర్వాత website తెరవండి. పాత రూపం కనిపిస్తే **Ctrl + F5** నొక్కండి.

## GitHub Pages for a new repository

1. Upload the extracted files to your chosen branch.
2. Open **Settings → Pages**.
3. Under **Build and deployment → Source**, select **Deploy from a branch**.
4. Choose the publishing branch and **/(root)**, then select **Save**.
5. Open the website address displayed by GitHub when deployment finishes.

Official instructions: [Configure a GitHub Pages publishing source](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

## Practice

- All 2,700 questions are displayed together by default, grouped under their subjects and existing question ranges.
- Choose **CDP**, **Telugu**, **English**, **Maths**, **PS** or **BS** to immediately display every question in that subject. Maths, for example, displays all 240 questions at once.
- The original 30-question ranges remain available in **Question group**. These are the existing bank's question groups, rather than newly assigned syllabus chapters.
- Every question has **A, B, C and D** alternatives. All four appear side by side when the available width allows; narrower screens use two columns for longer alternatives and four for short alternatives. Original question images retain their printed numbering, with A–D mapped to options 1–4.
- Scroll and answer any question in any order. Each choice immediately shows **Correct** or **Incorrect**, highlights the correct option and displays that question's study hint.
- The first answer for each question is recorded. Other questions remain available immediately.
- Scores and answered counts apply to the selection currently displayed.
- Switching subjects, question groups or practice size retains normal practice answers and opened hints. When browser storage is available, normal progress is saved on this device and restored when you reopen the same website. English remains the default language.
- **Jump to a section** scrolls directly to a subject or question group, without requiring you to answer intervening questions.
- **Show hint** is available before answering. After answering, the hint appears under the answer key.
- English is the default. **English**, **తెలుగు** and **Both** controls are available on the home page and in the scrolling practice toolbar. Select **Both** for the bilingual arrangement shown in the example.
- Language changes retain answers, scores and opened hints. Single-language source content and text inside original images remain in their source form.
- Tap an original diagram to enlarge it.
- Completed results appear while all selected question cards remain visible.
- **Restart this selection** and **Clear answers** reset only the selected questions, leaving progress in other subjects or question groups intact.
- No npm installation, server, API key or build step is required. The question bank, hints and original images remain embedded in `index.html`.

## Options for every topic

Choose a subject or question group to display its progress dashboard. Each subject and original range heading also has a **Topic options** button that opens that selection's dashboard.

- **Continue practice** — scroll to the first question you have not answered. All selected questions remain displayed together.
- **Go to a question** — open a question-number grid. Normal practice uses green for correct answers, pink for wrong answers and a plain style for unanswered questions.
- **Review my mistakes** — show only the selected topic's incorrectly answered questions, with their correct answers and hints. **Back to all questions** restores the full scrolling list.
- **Practice test** — randomly select 10, 20, 30 or all available questions from the current topic. Each question appears once. Answer in any order and change selections before submitting. Hints, correctness and score remain hidden until **Submit test**. Unanswered questions are listed separately in the result. Normal practice progress is unaffected by tests.
- **Clear answers** — clear only the selected topic or question range. If it has recorded answers, a confirmation dialog appears before they are cleared.

**తెలుగు:** ప్రతి విభాగం లేదా ప్రశ్నల సమూహానికి పురోగతి, Continue practice, ప్రశ్న సంఖ్యల గ్రిడ్, తప్పుల సమీక్ష, అభ్యాస పరీక్ష, సమాధానాల తొలగింపు ఎంపికలు ఉన్నాయి. సాధారణ అభ్యాసంలో జవాబు ఎంచుకోగానే ఫలితం కనిపిస్తుంది. పరీక్షలో సమర్పించిన తర్వాత జవాబులు, సూచనలు, స్కోరు కనిపిస్తాయి.

## Question counts

| Subject | Questions |
| --- | ---: |
| CDP | 630 |
| Telugu | 630 |
| English | 720 |
| Maths | 240 |
| PS | 240 |
| BS | 240 |
| **Total** | **2,700** |

## Validation

The existing question-bank and hint payloads are retained byte for byte. JavaScript syntax and DOM integration checks cover all 2,700 questions, all 90 original range groups, all six subjects, immediate feedback, filters and languages, A–D labels, topic actions, question-number navigation, mistake review, selected-topic clearing, random tests, results hidden until submission, partial submission, test restarts, saved progress after reload and original image enlargement. A visual browser check was unavailable in the build environment.
