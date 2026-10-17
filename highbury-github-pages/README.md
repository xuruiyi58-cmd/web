# Emma on the Feed

An interactive Instagram-style adaptation of Jane Austen's *Emma*.

This repository contains a static website. It does not require npm, a build command, or a server.

## Publish with GitHub Pages

1. Create a new public GitHub repository.
2. Upload **everything inside this folder** to the repository root. The repository root must contain `index.html`, `styles.css`, `script.js`, and the `media` folder.
3. Name the default branch `main`.
4. Open the repository's **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch** as the source.
6. Select the `main` branch and the `/ (root)` folder, then click **Save**.
7. Wait a few minutes and return to **Settings → Pages** to find the public URL.

The URL normally has this format:

```text
https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/
```

## Important

- Do not upload only `index.html`; the `media` folder contains all profile and post images.
- Keep all files in their current relative locations.
- The `.nojekyll` file prevents GitHub Pages from changing the static asset structure.
- To update the website later, replace the changed files and commit them to `main`. GitHub Pages will publish the new version automatically.

## Main files

- `index.html`: entry page
- `styles.css`: visual design and responsive layout
- `script.js`: profiles, posts, dialogs, and interactive messages
- `media/`: avatars and post images
