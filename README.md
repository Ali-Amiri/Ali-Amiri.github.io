# Academic Profile Website — ready to customize

This is an original academic website starter inspired by the **structure** of a professional researcher's personal website. It is not copied from someone else's website. It contains eight pages, one shared stylesheet, and content placeholders.

## Step 1: Customize content

1. Extract the ZIP file on your computer.
2. Open every `.html` file in a text editor (Notepad, VS Code, etc.).
3. Replace **Your Name**, **Your University**, `you@university.edu`, research description, and every sample publication/news entry.
4. Open `contact.html` and replace generic LinkedIn, ORCID and GitHub URLs.
5. To add a real photo: save your headshot as `assets/photo.jpg`. In each HTML file, replace the avatar block `<div class="avatar" aria-label="Profile-photo placeholder">YN</div>` with `<div class="avatar"><img src="assets/photo.jpg" alt="Portrait of Your Name"></div>`.
6. Update the copyright year as appropriate. For your actual PDF CV, you may add the document under `assets/` and link to it on the homepage.
7. Preview locally by double-clicking `index.html`.

## Step 2: Create your free website on GitHub

1. Create or sign in at https://github.com.
2. Note your username, for example `researcher123`.
3. New repository > Repository name: `researcher123.github.io` (replace with your **exact** GitHub username). Choose **Public**, then Create repository.
4. In the new repository, choose **Add file > Upload files**. Upload the files extracted from this ZIP, including the `assets` folder, keeping the same hierarchy. **Do not upload the ZIP as a ZIP**.
5. Commit the files to the default branch.
6. Go to **Settings > Pages > Build and deployment**.
7. Set Source to **Deploy from a branch**, Branch to the default branch (usually **main**), folder **/(root)**, then **Save**.
8. Visit `https://researcher123.github.io/` (replace with your username). Deployment may take up to 10 minutes.

## Step 3: Link your site on LinkedIn

LinkedIn > Me > View Profile > Contact info > Edit > Add website > paste the GitHub Pages URL > Save.

## Files

- `index.html` — homepage and news highlights
- `publications.html` — publications and DOI/PDF links
- `research.html` — research projects
- `teaching.html` — courses
- `data.html` — data and research resources
- `awards.html` — awards
- `talks.html` — speaking and presentations
- `contact.html` — professional contact links
- `assets/site.css` — all design settings

## Troubleshooting

- 404 error? Confirm repository name matches your username, Pages source is set to the branch root, and `index.html` is in the root.
- Missing styling? Confirm `assets/site.css` exists with that exact path.
- A page is not found? Confirm the file name exactly matches the navigation link.
- Site does not update? Wait a few minutes, check repository Actions and Pages settings, then hard refresh the browser.

**Important:** All sample claims are placeholders. Replace them with verified information before publishing.
