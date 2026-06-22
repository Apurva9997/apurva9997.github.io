# Pages structure

This repository is a GitHub Pages user site, so every committed HTML file is served under `https://apurva9997.github.io/`.

Current structure:

```text
/
  index.html              # Current deployed root page
  pages/
    index.html            # Directory of available pages
    agentic-loop/
      index.html          # The Agentic Loop interactive explainer
    example/
      index.html          # Starter page to duplicate
```

To add another page:

1. Copy `pages/example/` to a new folder, for example `pages/my-new-page/`.
2. Edit `pages/my-new-page/index.html`.
3. Add a card for it in `pages/index.html`.
4. Push to GitHub.

The new page will be available at:

```text
https://apurva9997.github.io/pages/my-new-page/
```

If you want a shorter URL, create the folder at the repository root instead:

```text
/
  my-new-page/
    index.html
```

That will publish at:

```text
https://apurva9997.github.io/my-new-page/
```
