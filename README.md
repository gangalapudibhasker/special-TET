# AP Special TET — Scroll Practice

**గంగలపూడి భాస్కర్ రెడ్డి · Gangalapudi Bhasker Reddy**

## Files to upload

- `index.html` — the complete practice application.
- `.nojekyll` — static GitHub Pages marker.
- `README.md` — these instructions.

Extract the ZIP first. Upload its contents directly to your repository root, so that `index.html` is in the root rather than inside another folder.

## Updating your existing website

Replace the old `index.html` with this new `index.html` and commit the change. Your current GitHub Pages publishing settings can continue to use the same branch and folder.

**తెలుగు:** ZIPను extract చేయండి. అందులోని ఫైళ్ళను మీ GitHub repository మొదటి స్థాయి (root)లో upload చేయండి. పాత `index.html` ఫైల్ స్థానంలో కొత్త `index.html` ఫైల్‌ను పెట్టి commit చేయండి.

## Enabling GitHub Pages for a new repository

1. Upload the files and commit them to `main` (or your chosen publishing branch).
2. Open **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Choose your publishing branch and **/(root)**, then click **Save**.
5. Open the website address shown by GitHub after publication.

Official instructions: [Configure a GitHub Pages publishing source](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

## Practice

- All 2,700 questions appear in one continuous scrolling list by default.
- Select a subject, question group or practice size, then choose **Start practice**.
- Every question in your selected set is displayed together. Answer in any order.
- Choosing an option immediately shows whether it is correct, highlights the correct option, shows that question’s study hint, and updates the score.
- Each question records its first answer. Other questions remain available immediately.
- Use **Show hint** before answering whenever you need help.
- English is the default. The home-page controls offer **English**, **Telugu** and **Both**.
- Language changes retain your selected answers, score and opened hints.
- Tap a question diagram to enlarge it.
- After you complete the selected set, the results appear with the questions still visible.
- The app uses an embedded question bank and images. No npm installation, server, API key or build step is required.

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

The question-bank and hint payloads are retained byte for byte. JavaScript syntax and programmatic DOM interaction checks cover the scrolling list, answers in any order, immediate question-specific feedback, score locking, filters, language changes, diagrams, results and restarting. A visual browser check was unavailable in the build environment.
