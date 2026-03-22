# Site Editing Guide

The homepage is now organized so the most common edits live in a few obvious files:

- Home biography text: `_pages/about.md`
- Homepage summary, quick links, and news: `_data/home.yml`
- Homepage structure: `_layouts/home.html`
- Shared publication card UI: `_includes/publication-card.html`
- Custom styling for the homepage and publication page: `_sass/_custom.scss`

If you want a publication to appear in the homepage's "Selected Publications" section, add this to the publication front matter:

```yml
selected: true
```

That can be added to any file in `_publications/`.
