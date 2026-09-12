# PAS Giannina investor website and Content Studio

## Publish on GitHub Pages

1. Extract this ZIP.
2. Upload its contents to the repository root, preserving the `admin` folder. Keep the public page named `index.html`.
3. In repository Settings → Pages, choose Deploy from a branch → main → /(root), then Save.
4. Open the Pages URL when GitHub finishes publishing. Add `/admin/` to that site address to open Content Studio.

The current target is `antoniemykallewis-source/PASGIANNA`. Content Studio is preconfigured with that repository name and branch. Connect it using the instructions in `EDITING.md`.

## Files

- `index.html`: complete investor website with all 11 photographs, embedded typefaces, 3D rendering and interactive content.
- `content.json`: the shared website text. Content Studio publishes updates to this file.
- `admin/index.html`: Content Studio, including section search, text fields, preview, local drafts, backups and authenticated GitHub publishing.
- `.nojekyll`: use static GitHub Pages hosting.
- `EDITING.md`: instructions for connecting and editing.
- `QA.md`: what was checked and testing limits.
- `THIRD-PARTY-NOTICES.md`: photo and software credits.

No build command, separate image folder, CDN or paid database is required. `index.html` also opens directly as a self-contained local file using its embedded copy. Hosted pages load the latest published `content.json`.

## Editing

Open Content Studio, search for the words you want to change and edit them. Preview changes before selecting Review & publish. A fine-grained GitHub token restricted to this repository with Contents: read and write is required to publish. The token is kept only in the editor tab's memory and sent only to GitHub. Drafts remain local until explicitly published.

## Included experience

Six main investor chapters; nine regional photos; two authentic stadium photos; interactive 3D with software rendering fallback; financial scenarios; promotion tabs; ownership and valuation details; financial tables; risk details; biographies; and the full investor reader. Incomplete academic-institution wording has been removed from Fotis Stefanis's biography and the reader.

The inquiry button copies inquiry text. It does not send email or submit a form. Existing source financial figures, projections and material conditions remain unchanged.

## Distribution

The source brief is confidential. A private repository and a private website are separate settings. GitHub Pages websites are ordinarily public even when their source repository is private; a noindex tag does not restrict access. Personal-account Pages hosting from private repositories requires GitHub Pro.

GitHub reference: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
