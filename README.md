# Public legal site source

These files are the public Terms of Service and Privacy Policy for the Kami Discord bot. Review the text whenever the bot's features or data handling change. The pages use only local HTML and CSS, so they can be copied into the root of a separate public GitHub Pages repository without a build step.

The bot's source repository is private. GitHub Free cannot publish GitHub Pages from a private repository. To publish without exposing bot code:

1. Create a **public** repository named `dsv1-legal` under `nen-exploit`.
2. Copy `index.html`, `terms.html`, `privacy.html`, `site.css`, `.nojekyll`, and the `.github/ISSUE_TEMPLATE/` folder from this folder to the root of that repository, then commit and push them. Leave GitHub Issues enabled so data requests work.
3. In the public repository, open **Settings → Pages → Build and deployment** and choose **Deploy from a branch**, branch `main`, folder `/ (root)`. Enable HTTPS if GitHub offers that switch.
4. After Pages reports the site live, open all three pages to verify them. The expected links are:
   - `https://nen-exploit.github.io/dsv1-legal/`
   - `https://nen-exploit.github.io/dsv1-legal/terms.html`
   - `https://nen-exploit.github.io/dsv1-legal/privacy.html`
5. Put the last two links into the Discord Developer Portal's Terms of Service URL and Privacy Policy URL fields.

Do not upload the bot repository, runtime `data/` files, `config.json`, or encryption keys to the public repository. These links are examples until the public repository is created and Pages is enabled.
