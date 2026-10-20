# Publishing This Repo on GitHub

## Option A: GitHub website (no command line)

1. Sign in at github.com and click **New repository**.
2. Name it `cyberbridge-oklahoma`, set it to **Public**, and do **not** add a README (this repo already has one). Click **Create repository**.
3. On the empty repo page, click **uploading an existing file**.
4. Unzip `cyberbridge-oklahoma.zip` on your computer, open the folder, select everything inside it and drag it onto the page. (The `.github` folder is hidden on some computers; if it doesn't upload, you can skip it.)
5. Write a commit message like "Initial curriculum" and click **Commit changes**.

## Option B: Command line

```bash
cd cyberbridge-oklahoma
git init
git add .
git commit -m "Initial curriculum, workshops and Phishing Spotter"
git branch -M main
git remote add origin https://github.com/<your-username>/cyberbridge-oklahoma.git
git push -u origin main
```

## Turn on GitHub Pages (makes Phishing Spotter playable online)

1. In the repo, go to **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`. Save.
3. After a minute or two the site is live at `https://<your-username>.github.io/cyberbridge-oklahoma/`.
4. The game is at `.../activities/phishing-spotter/`. Put that link (or a QR code of it) on your workshop slides.

## Finish personalizing

Everything is already filled in. After Pages is on, paste the Pages link into the repo's "About" box.

## Make it look active and professional

- Add **topics** on the repo home page (gear icon next to "About"): `cybersecurity`, `education`, `ai-literacy`, `oklahoma`, `gilman-scholarship`, `open-educational-resources`.
- Add the Pages link to the "About" box.
- After each session, add a row to `impact/workshop-tracker.csv`.
- Use **Issues** for feedback from teachers (templates are in `.github/ISSUE_TEMPLATE/`).
