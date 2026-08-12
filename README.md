# Juan David Acevedo — Single-File Portfolio

This version intentionally contains the four portfolio screenshots **inside `index.html` itself** as Base64 data URIs.

That means:
- No `assets` folder is required.
- No image paths need to resolve.
- Uploading only `index.html` to the root of a GitHub Pages repository is sufficient.
- The same file can also be opened locally in a browser.

## GitHub Pages

Upload `index.html` to the root of the repository:

```text
repository/
└── index.html
```

Then enable:

Settings → Pages → Deploy from branch → `main` → `/ (root)`

This is the most robust version if the previous deployment was showing broken-image icons.
