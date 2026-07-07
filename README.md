# Mahesh Dhole — Personal Academic Website

A free, fast academic website hosted on GitHub Pages. No frameworks, no build step —
plain HTML and CSS you can edit in any text editor.

## Files

| File | Purpose |
|------|---------|
| `index.html` | Home / About page |
| `research.html` | Job market paper, working papers, work in progress, conferences |
| `teaching.html` | Instructor and TA record, teaching interests |
| `cv.html` | CV summary page with PDF download button |
| `style.css` | All styling (colors, fonts, layout) |
| `CV_Mahesh_Dhole.pdf` | Downloadable CV |

## How to publish on GitHub Pages (free, ~10 minutes)

1. **Create a GitHub account** at https://github.com (if you don't have one).
   Your username: `Mahesh8892`.

2. **Create a new repository** named exactly `mahesh8892.github.io`. Make it **Public**. Do not add a README.

3. **Upload the files.** On the new repository page, click
   "uploading an existing file", then drag in ALL the files from this
   `website` folder (`index.html`, `research.html`, `teaching.html`, `cv.html`,
   `style.css`, and the `files` folder with the CV PDF). Click **Commit changes**.

4. **Wait 1–2 minutes.** Your site is live at:
   `https://mahesh8892.github.io`

That's it — GitHub Pages is enabled automatically for repositories named
`mahesh8892.github.io`.

## Updating the site later

- Edit any file directly on GitHub (click the file → pencil icon → commit),
  or re-upload a replacement. Changes go live in about a minute.
- **New CV:** replace `CV_Mahesh_Dhole.pdf` with the new PDF (same filename,
  and nothing else needs to change).
- **Post your JMP draft:** upload the PDF as `Dhole_JMP.pdf`, then in
  `research.html` remove the comment markers around the "Draft (PDF)" button and
  delete the "Draft available upon request" line.
- **Add your photo:** put a `photo.jpg` in the root folder, then in `index.html`
  replace the placeholder `<div class="photo-placeholder">…</div>` with
  `<img src="photo.jpg" alt="Mahesh Dhole">` (the comment above it shows exactly this).

## Custom colors

Open `style.css` — the colors are defined at the top under `:root`.
`--accent` (currently SIU-style maroon `#7a0019`) controls headings, links, and buttons.

## After it's live

- Update the website link on your CV, cover letters, and Google Site
  (or set the Google Site to redirect).
- Test on your phone — the layout is responsive.
