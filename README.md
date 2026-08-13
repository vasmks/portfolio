# Portfolio

A static portfolio containing two selected AI project case studies:

- TOONTRA webtoon localization
- Wafer manufacturing inspection

## Structure

```text
index.html                  Portfolio introduction
projects/                   Project case studies
assets/css/                 Page-specific stylesheets
assets/images/toontra/      TOONTRA images
assets/images/wafer/        Wafer inspection images
assets/video/wafer/         Wafer inspection video
```

The site does not require a build step or JavaScript.

## Local preview

From this directory, run:

```powershell
py -m http.server 8000
```

Then open `http://localhost:8000/`.

## GitHub Pages

1. Push the contents of this directory to the publishing branch of a GitHub repository.
2. In the repository settings, open **Pages**.
3. Choose **Deploy from a branch**, select the publishing branch, and use the repository root.

All links are relative, so the site also works when published as a project site under `username.github.io/repository-name/`.

## Privacy

The HTML pages contain `noindex`, `nofollow`, and `noarchive` directives. These ask compliant search engines not to list or cache the pages, but they are not access control. Anyone with the public URL can still view and share the site.

Do not add private source code, internal datasets, customer information, credentials, or identity-revealing documents to this directory.
