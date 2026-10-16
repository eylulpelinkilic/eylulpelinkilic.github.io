# Eylül Pelin Kılıç — academic website

A lightweight, responsive academic homepage, prepared from the supplied CV. Plain HTML and CSS: no package installation, framework, or build step. The layout is inspired by https://atfortes.github.io/; the implementation and illustrations are original.

## GitHub Pages

Your username is `eylulpelinkilic`. Create the public repository **eylulpelinkilic.github.io** if it does not already exist. If GitHub reports that the name is taken, open the existing repository and review its contents before uploading.

1. Go to https://github.com/new and enter `eylulpelinkilic.github.io` as the repository name. Choose Public, enable Add README, and create it.
2. Unzip `pelin-github-pages.zip`. Open its inner folder. In the repository, choose **Add file → Upload files**. Upload the contents of the folder, including `index.html`, `styles.css`, and the entire `assets` folder. `index.html` must be at the repository root, not inside another folder. Commit to `main`.
3. Open **Settings → Pages**. Set Source to **Deploy from a branch**, select **main** and **/(root)**, and save.
4. GitHub will publish the site at https://eylulpelinkilic.github.io/. This can take up to 10 minutes. Check the repository's Actions tab if deployment fails.

The ZIP also includes `.nojekyll` to disable Jekyll processing. Hidden files may not appear in Finder, but this site works without it because it uses ordinary filenames and plain HTML/CSS.

Official instructions: https://docs.github.com/en/pages/quickstart
Publishing source: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Editing

- **Text, links, dates and projects:** edit `index.html` in the GitHub Pages package (or `dist/index.html` in this development checkout).
- **Photo:** place a portrait at `assets/profile.jpg`, change the profile image's `src` to `assets/profile.jpg`, and change its `alt` to `Eylül Pelin Kılıç`. The current image is an initials monogram.
- **CV:** replace `assets/CV_Eylul_Pelin_Kilic.pdf` with your updated CV, keeping the filename. The included PDF is the original uploaded document, including its contact details.
- **Colors and spacing:** edit `styles.css`. The site follows the visitor's light/dark system preference.
- **Publication entries:** the current CV lists ongoing research, so the website has a Research Experience section. Add a Publications section when you have titles, authors, venues and links ready.
- **Research illustrations:** the SVGs are conceptual illustrations, not experiment outputs.

You can open `index.html` directly in a browser to review the complete website. All assets are local, so it works offline. The HTML remains readable without scripts; the site does not use JavaScript, external fonts, tracking, cookies, or a contact-form service.

## Content provenance

CV: `CV_Eylul_Pelin_Kilic(1).pdf`, supplied 16 October 2026. Degree dates in the future are labeled expected. The course-project F1 values are reported from that CV and have not been independently re-evaluated. The downloadable CV is unchanged. Review and update the date in the footer when revising the content.

## Development checkout

`dist/` contains the deployable site. `.openai/hosting.json` belongs to the private working preview and is excluded from the GitHub Pages ZIP. The ZIP contains only the public site and these instructions.
