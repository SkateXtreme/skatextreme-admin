# SkateXtreme Admin Pages

This repository hosts static legal and account-related pages for SkateXtreme that are published via **GitHub Pages**.

## Published Pages

- `index.html` – Landing page linking to all documents
- `privacy.html` – Privacy Policy
- `account-deletion.html` – Account deletion procedure
- `support.html` – Support & contact information (App Store support URL)

## Enable GitHub Pages

1. Go to the repository on GitHub: Settings → Pages.
2. In **Build and deployment**, choose:
   - Source: `Deploy from a branch`
   - Branch: `main` / folder: `/ (root)`
3. Click **Save**. GitHub will build and publish the site.
4. After a few minutes your pages will be available at:
   - `https://<your-username>.github.io/<repository-name>/` (index)
   - `https://<your-username>.github.io/<repository-name>/privacy.html`
   - `https://<your-username>.github.io/<repository-name>/account-deletion.html`

## Updating Content

Edit the corresponding HTML file, commit, and push to `main`. GitHub Pages redeploys automatically (usually within 1–2 minutes).

## Optional: Custom Domain

1. Add your domain (e.g. `legal.skatextreme.com`) under Settings → Pages → Custom domain.
2. Create a `CNAME` DNS record pointing the custom domain to `<your-username>.github.io`.
3. Wait for DNS to propagate and enforce HTTPS when available.

## Cache & Refresh Notes

Static HTML changes may be cached briefly by browsers or CDNs. Use a hard refresh (Shift+Reload) if you do not see updates immediately.

## Support & Contact

Use the following for your App Store “Support URL” (after Pages is enabled):

`https://<your-username>.github.io/<repository-name>/support.html`

Direct email support: `info@skatextreme` (replace with full domain when ready, e.g. `info@skatextreme.com`). Encourage users to include:
- Account username or registered email
- App version & device details
- Clear description / steps to reproduce (if a bug)

If users have a designated coach, they can reach out to them directly for training guidance.

## License

Internal documentation pages. Do not reuse externally without authorization.
