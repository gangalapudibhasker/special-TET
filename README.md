# AP Special TET — Topic-wise Scroll Practice

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
- Questions appear in compact numbered cards like the supplied example. Short options appear in four columns; longer options adapt to the available screen width.
- Scroll and answer any question in any order. Each choice immediately shows **Correct** or **Incorrect**, highlights the correct option and displays that question's study hint.
- The first answer for each question is recorded. Other questions remain available immediately.
- Scores and answered counts apply to the selection currently displayed.
- Switching subjects, question groups or practice size retains answers and opened hints during the current page session. Reloading the page starts a fresh session.
- **Jump to a section** scrolls directly to a subject or question group, without requiring you to answer intervening questions.
- **Show hint** is available before answering. After answering, the hint appears under the answer key.
- English is the default. **English**, **తెలుగు** and **Both** controls are available on the home page and in the scrolling practice toolbar. Select **Both** for the bilingual arrangement shown in the example.
- Language changes retain answers, scores and opened hints. Single-language source content and text inside original images remain in their source form.
- Tap an original diagram to enlarge it.
- Completed results appear while all selected question cards remain visible.
- **Restart this selection** clears answers only for the displayed selection. Answers outside that selection remain available during the page session.
- No npm installation, server, API key or build step is required. The question bank, hints and images are embedded in `index.html`.

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

The existing question-bank and hint payloads are retained byte for byte. JavaScript syntax and DOM integration checks cover all 2,700 questions, all 90 original range groups, all six subject filters, answers in any order, immediate feedback, progress retained across filters, selection-specific scoring, language toggles, hints, original diagrams, results and restarting. A visual browser check was unavailable in the build environment.
