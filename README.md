# NAVTS Preview Hub

A separate preview environment for the NAVTS website. Production remains in `helpnavts/navts-site`.

## Preview publishing
This is a static multi-page website. GitHub Actions is configured to publish the `main` branch to GitHub Pages when Pages is enabled with **GitHub Actions** as the build source.

Expected preview URL: https://helpnavts.github.io/navts-preview-hub/

The site uses a repository subpath for assets and internal links. It includes `noindex,nofollow` and a disallow-all robots policy so the preview is not intended for search indexing.

## Workflow
1. Develop and test changes here.
2. Review the public preview.
3. After approval, port the approved changes to `navts-site`.
4. Do not deploy previews to the production custom domain.
