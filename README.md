# PhD Personal Homepage

This folder contains a traditional static academic homepage that can be deployed without a build step.

## Files

- `index.html` - homepage content and structure
- `styles.css` - traditional two-column academic styling
- `script.js` - mobile navigation and publication filters
- `assets/favicon.svg` - simple placeholder favicon

## Customize

Replace these placeholders before publishing:

- Google Scholar, GitHub, CV, and ORCID links
- paper links, project links, and BibTeX links
- any outdated submission status or dates
- add your CV PDF under `assets/` and change the `CV` link to point to it

## Deploy With GitHub Pages

1. Create a GitHub repository named `YOUR_USERNAME.github.io`.
2. Copy all files from this folder into the repository root.
3. Commit and push the files.
4. Open `Settings -> Pages` in the repository.
5. Select the main branch and root folder.
6. Your site will be available at `https://YOUR_USERNAME.github.io/`.

## Deploy With Netlify

1. Open Netlify and choose "Add new site".
2. Drag this folder into the deploy area, or connect the GitHub repository.
3. Netlify will publish the static files directly.

## Deploy With Vercel

1. Import the GitHub repository in Vercel.
2. Use the default static project settings.
3. Deploy. Vercel will serve `index.html` from the repository root.
