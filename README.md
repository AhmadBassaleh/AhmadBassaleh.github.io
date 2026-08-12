# Ahmad Bassaleh Academic Website

This folder is ready to publish with GitHub Pages.

## Publish it

1. Sign in to GitHub.
2. Create a new **public** repository named exactly:

   `AhmadBassaleh.github.io`

3. Upload these files to the root of the repository:
   - `index.html`
   - `styles.css`

4. Commit the files.
5. Open the repository's **Settings**.
6. In the sidebar, open **Pages**.
7. Under **Build and deployment**, choose:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/(root)**
8. Save.

The site will use the address:

`https://AhmadBassaleh.github.io`

## Easy edits

### Add a professional photo
Replace this line in `index.html`:

```html
<div class="avatar" aria-hidden="true">AB</div>
```

with:

```html
<img class="avatar-photo" src="profile.jpg" alt="Ahmad Bassaleh" />
```

Then add `profile.jpg` to the repository.

### Add Google Scholar, ORCID, LinkedIn, and CV
Add links inside the `hero-links` or `contact` sections.

For a CV, upload a file named `cv.pdf`, then use:

```html
<a class="button" href="cv.pdf" target="_blank">CV</a>
```

### Add another publication
Duplicate the `<article class="publication">...</article>` block in the Publications section and edit the title, journal/conference, year, description, and links.

## Files

- `index.html` — website content
- `styles.css` — design and responsive layout

No build tools or frameworks are required.
