# Alex Morgan: Digital Marketing Portfolio (fictional demo)

A fictional classroom demonstration. Alex Morgan is not a real person, all campaign results are simulated, and the images are AI-generated.

## What is in this folder
- `index.html`: the whole website (HTML, CSS and JavaScript in one file)
- `assets/`: the four images used by the site
- `.nojekyll`: tells GitHub Pages to serve the files as they are

The site loads Tailwind CSS and the Poppins font from the internet, so it needs a connection to display correctly.

## Edit the content
Open `index.html` in any text editor (VS Code, Notepad) and search for:
- `const P=[` : the four projects (titles, results, case study text, chart numbers)
- `$('#tl').innerHTML` : experience, education and skills
- `$('#ex').innerHTML` : the six expertise cards
- `$('#tools')` and `$('#certs')` : tools and certifications
- `<h1` and the line starting `Hi, I` : hero heading and introduction
- `LinkedIn:` : replace the placeholder links with your own
To swap an image, replace the file in `assets/` and keep the same file name.
Open `index.html` by double-clicking it to preview changes.

## Publish on GitHub Pages
1. Sign in at github.com and click **New repository**. Name it (for example `portfolio`), keep it Public, and click **Create repository**.
2. Unzip this folder. On the new repository page click **uploading an existing file**.
3. Drag in everything inside the folder: `index.html`, the `assets` folder and `.nojekyll`. If `.nojekyll` is hidden, skip it, the site still works. Click **Commit changes**.
4. Go to **Settings > Pages**. Under **Build and deployment**, set Source to **Deploy from a branch**, choose branch **main** and folder **/ (root)**, then click **Save**.
5. Wait 1 to 2 minutes. Your site will be at `https://YOUR-USERNAME.github.io/portfolio/`.

## Publish on Vercel (optional)
1. Sign in at vercel.com with your GitHub account.
2. Click **Add New > Project** and import your repository.
3. Leave all settings as they are (no build command needed) and click **Deploy**.

## Before sharing publicly
Keep the fictional demonstration labels. If you turn this into your real portfolio, replace the name, photo, projects and results with your own verified work.
