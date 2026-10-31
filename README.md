# SmartTriage: Techfest IIT Bombay Round 1 submission

Static website (HTML + CSS only). No build step, no server, no API keys.

## Folder structure

```
.
├── index.html                         the submission page
├── .nojekyll                          tells GitHub Pages to serve files as they are
├── README.md                          this file
└── assets/
    ├── style.css                      all styling (light and dark themes)
    ├── favicon.svg                    browser-tab icon
    └── SmartTriage_Techfest_Round1_Redesigned.pdf   PDF linked from the page
```

External resource: IBM Plex Sans and IBM Plex Mono load from Google Fonts. If they cannot load, the page falls back to system fonts.

## Deploy on GitHub Pages

1. Create a new **public** repository on GitHub (for example `smarttriage-techfest`).
2. Unzip this folder. Upload **everything inside it** (including the `assets` folder and the `.nojekyll` file) to the repository root: *Add file > Upload files*, drag the contents in, then *Commit changes*.
3. Open the repository's **Settings > Pages**.
4. Under *Build and deployment*, set *Source* to **Deploy from a branch**, choose branch **main** and folder **/ (root)**, then **Save**.
5. Wait one to two minutes. Your link will be `https://<your-username>.github.io/<repository-name>/`.
6. Open the link in a private window and check the figure, tables and the PDF button.

Tip: if the `.nojekyll` file does not show in your file manager, it is a hidden file. The site still works without it.
