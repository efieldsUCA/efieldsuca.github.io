# Portfolio

A small multi-page personal portfolio. Each nav tab is its own page.

## Files
```
index.html       Home
about.html       About
cv.html          CV
projects.html    Projects
css/style.css    Shared styles for every page
images/          Put your photos + project images here
```

## Edit
- Swap the placeholder text and links (search for `yourusername` and update GitHub URLs).
- Add images to `images/` and update the `src=""` paths.
- To add a project: copy one `.project-card` block in `projects.html`.
- The nav is repeated on each page — the current page's link has `class="active"`.

## Publish (GitHub Pages)
1. Create a repo and push these files to it.
2. Repo → **Settings → Pages**.
3. Under **Build and deployment**, set Source = *Deploy from a branch*, branch = `main`, folder = `/ (root)`.
4. Save. Your site goes live at `https://yourusername.github.io/repo-name/` in a minute or two.

Fonts load from Google Fonts, so no build step is needed.
