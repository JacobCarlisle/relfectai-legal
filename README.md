# ReflectAI GitHub Pages Site

This folder contains a ready-to-publish static site for your GitHub Pages legal and support URLs.

## Files

- `index.html`
- `privacy.html`
- `support.html`
- `styles.css`

## What To Replace Before Publishing

Search for bracketed placeholders like:

- `[support email]`
- `[support URL]`
- `[your legal name or company]`
- `[minimum age for your market, for example 13 or 16]`
- `[privacy policy URL]`

## Publish To GitHub Pages

1. Open your GitHub Pages repository.
2. Upload these four site files to the publishing root of that repo.
3. Commit the changes.
4. Wait for GitHub Pages to publish.

If your Pages URL is:

- `https://yourusername.github.io/reflectai-legal/`

Then your final URLs will be:

- `https://yourusername.github.io/reflectai-legal/privacy.html`
- `https://yourusername.github.io/reflectai-legal/support.html`

## Next Step In The App

After publishing, put those final URLs into:

- `ReflectAI/ReflectAI/ReflectAI/ReflectAI-Config.plist`

Keys to update:

- `PRIVACY_POLICY_URL`
- `SUPPORT_URL`
