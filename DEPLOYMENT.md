# Static demo deployment

The page is buildless HTML/CSS with relative asset paths and works under a GitHub Pages repository subpath. It has no package dependencies or application backend.

After owner approval, create a separate public repository with fresh Git history, copy only the approved whitelist, and configure GitHub Pages to deploy from the main branch / root. The `.nojekyll` file disables Jekyll processing. Do not copy the private repository `.git` directory, use a fork, or change its visibility.

No repository or live demo URL is claimed here. Add the actual URLs only after GitHub confirms creation and Pages reports a successful deployment, followed by checking the served page and media. [Official publishing-source documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).
