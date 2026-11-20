# Bo Wang | 王泊

Personal academic homepage hosted at [3bai233.github.io](https://3bai233.github.io/).

## Site structure

- `index.html` — English homepage
- `zh/index.html` — Chinese homepage
- `assets/css/bo-home.css` — responsive shared design
- `assets/images/` — paper illustrations and the site icon (profile photograph can be added separately)
- `files/Bo_Wang_Academic_CV_EN.pdf` and `files/Bo_Wang_Academic_CV_CN.pdf` — public academic CVs

The homepage uses static HTML and CSS so it works directly on GitHub Pages. The `.nojekyll` marker allows the branch-based deployment to serve the static site without compiling the legacy Jekyll/Sass template. The original template sources are retained in the repository for reference.

Edit the two HTML pages to update the profile, research, publications, or achievements. Keep public CV files synchronized with the information shown on the website. Avoid uploading private contact details or anonymous submissions.

## Deployment

Copy the contents of this package (including the hidden `.nojekyll` file) into the existing `3bai233/3bai233.github.io` repository root. Commit to the existing `master` branch. GitHub Pages should serve from the `master` branch's root directory; the static site does not require a Ruby or Node build.

## Figure credits

- HEIR dataset overview: [HEIR project](https://heir-project.github.io/) (original project figure).
- BAMI method overview: [Neur-IO/BAMI](https://github.com/Neur-IO/BAMI) (original project figure).

The repository was initialized from [Academic Pages](https://github.com/academicpages/academicpages.github.io). See LICENSE.
