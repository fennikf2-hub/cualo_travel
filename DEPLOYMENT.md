# GitHub Pages

This static site deploys automatically from the `main` branch with the
`Deploy to GitHub Pages` workflow. The repository root is published as-is;
`index.html` forwards visitors to the main page in `cualo.html`.

For the first deployment, open **Settings > Pages** in the repository and set
**Build and deployment > Source** to **GitHub Actions**. After that, each push
to `main` publishes the site. The published URL is shown in the workflow run's
deployment environment.
