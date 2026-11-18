# Alex Morgan — Digital Marketing Portfolio (Classroom Demo)

This is a **static HTML / CSS / JavaScript website**, not a React app. It does **not** need `package.json`, `npm install`, or a build command to deploy.

The content is entirely fictional, and the marketing metrics are simulated. The images are AI-generated.

## Files

```
index.html              # The website
assets/site.css         # Local, precompiled Tailwind CSS (no CDN dependency)
assets/portrait.jpg
assets/marketing-workspace.jpg
assets/analytics-dashboard.jpg
assets/fashion-campaign.jpg
.nojekyll               # GitHub Pages configuration
README.md
```

**IMPORTANT:** Upload the contents of this extracted ZIP to the **top level** of your GitHub repository. There should be an `index.html` directly visible on the GitHub repository homepage, NOT inside a second folder named `alex-morgan-portfolio`.

## Deploy with Vercel Drop (no GitHub required)

1. Visit https://vercel.com/drop and sign in.
2. Drag in this ZIP or the extracted contents. The website root contains `index.html`.
3. Choose `index.html` as the root page if asked.
4. Deploy.

## Deploy from GitHub to Vercel

1. Create a new GitHub repository.
2. Upload all the files in the ZIP to the repository root (open the ZIP first; do not upload the ZIP file as a single file).
3. In Vercel, choose **Add New → Project → Import your repository**.
4. Framework preset: **Other**. Root directory: **./** (repository root). Build command: **None / empty**. Output directory: **None / empty**. Install command: **None / empty**.
5. Deploy.

## Deploy with GitHub Pages

1. Create a public GitHub repository and upload all files to its root.
2. Open **Settings → Pages**.
3. Choose **Deploy from a branch**, set **main** and **/ (root)**, then save.
4. Your site will appear at `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/` once GitHub has published it.

## Edit

- Update the written content and fictional projects in `index.html`.
- Replace images under `assets/` keeping their file names, or update the paths in `index.html`.
- The HTML uses Tailwind utility classes compiled into `assets/site.css`; if you significantly change classes, regenerate the stylesheet rather than relying on the CDN.
- Never portray the example metrics, work experience, or certifications as real achievements.

If you see a 404, verify that `index.html` appears at the root of the deployed repository and that the deployment's root directory is set to the same folder.
