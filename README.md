# Social Media Graphic Design website

A static, responsive four-page website for **Social Media Graphic Design: Posts, Carousels & Flyers**. No build step, package installation, database or API key is needed.

## Publish on GitHub Pages

1. Extract this ZIP on your computer.
2. Create a new **public** GitHub repository, for example `social-media-graphic-design-website`.
3. Upload the **contents** of the extracted folder to the repository root. `index.html` must be at the root, alongside `support.html`, `privacy-policy.html`, `terms-of-service.html` and the `assets` folder. Upload the extracted files, not the ZIP itself. Commit the files to `main`.
4. Open **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**.
5. Choose **main** and **/ (root)**, then click **Save**. If your default branch has a different name, use that branch.
6. Wait for GitHub Pages deployment to finish. The Pages settings screen will show the live website URL. Open it and check all four navigation links.
7. Send ChatGPT that **live GitHub Pages URL**, and optionally the repository URL. The plugin package can then be updated with the four verified public URLs.

For project repositories, the URL normally follows `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`. Use the exact URL GitHub shows. All local links and asset paths are relative, so the site works under a repository subpath.

GitHub's reference: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Pages and plugin metadata

| Page | File | Plugin listing field |
| --- | --- | --- |
| Website | `index.html` | `websiteURL` and package `homepage` |
| Support | `support.html` | `supportURL` |
| Privacy Policy | `privacy-policy.html` | `privacyPolicyURL` |
| Terms of Service | `terms-of-service.html` | `termsOfServiceURL` |

The links have not been inserted into the plugin package yet because the site is not published. Do not present an unverified or example URL as a live policy URL.

## Content and contact

- Operator: Shoaib Akhtar.
- Product: Social Media Graphic Design: Posts, Carousels & Flyers.
- Support contact currently uses the creator's LinkedIn profile: https://www.linkedin.com/in/mrcreatech/ . A LinkedIn account may be needed to message the creator. If you prefer a dedicated support email, replace the contact links and update the matching privacy/support text before publication.
- Policies dated 3 October 2026 describe the current skills-only package, no creator backend, this static website, support messages, third-party host processing and the optional affiliate recommendation guard.
- This site has no account, payment, analytics, external font, upload form or browser-storage code. GitHub Pages' security logging is explained in the Privacy Policy.
- Review the policies against your actual operations before publication, and update them if hosting, contact channels or data processing changes.
- The website ZIP does not include or publicly expose the plugin's template database or internal scripts.

## Local preview

Open `index.html` directly in your browser. All four pages work without a server. Alternatively, from this folder run `python3 -m http.server 8000` and open `http://localhost:8000`.

## Editing

Edit page text in the four HTML files. Shared styling is in `assets/styles.css`. The existing logo and favicon are in `assets/`. The optional `.nojekyll` file disables Jekyll processing; the plain HTML site also works if GitHub's upload interface omits that empty file.
