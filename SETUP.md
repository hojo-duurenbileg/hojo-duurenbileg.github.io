# Publishing this site on GitHub Pages

1. Create a GitHub account with a professional username, for example `hojo-duurenbileg`.
2. Create a new public repository named exactly `<your-username>.github.io`.
3. On the repository page, click **Add file > Upload files** and drag in everything from this folder:
   `index.html`, the `assets` folder and the `files` folder. Click **Commit changes**.
4. Go to **Settings > Pages**. Under "Build and deployment", set Source to **Deploy from a branch**,
   Branch to **main** and folder to **/ (root)**, then **Save**.
5. After a minute or two the site is live at `https://<your-username>.github.io`.

## Before you publish
- **Paper:** confirm with Dr. Lichti's group that you can share `files/least-squares-matching-report.pdf`.
  If not, delete the file and change the "Read the paper" button to say "Paper available on request".
- **Year:** the page says 2017 (the research period). The PDF file itself was created in January 2019.
  Change the year in the hero text and the citation if the report is dated 2019.
- **Resume:** add your resume as `files/resume.pdf`, or delete the "Résumé (PDF)" link in the About section.
- **Capstone:** when the code is on GitHub, replace "Code coming soon" with a link to the repository.

## Adding a project
In `index.html`, find the commented block under the Code section, copy it, remove the comment
markers and fill in the name, description, languages and links. Use README_TEMPLATE.md for each
project repository.

## Optional
- Custom domain: buy one (for example `hojoduurenbileg.com`) and add it under **Settings > Pages > Custom domain**.
