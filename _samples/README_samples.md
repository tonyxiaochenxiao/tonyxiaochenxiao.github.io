# Template samples (not published)

These are the original academicpages template files, kept only for reference.
Jekyll does not publish this folder: it starts with "_" and is also listed under `exclude` in `_config.yml`.

Each file is renamed `sample_<original name>`. Its original location is the folder path
with the leading "_" restored, e.g.

- `_samples/pages/sample_markdown.md`   -> `_pages/markdown.md`  (Markdown/feature guide)
- `_samples/posts/sample_*.md`          -> `_posts/*.md`         (example blog posts)
- `_samples/portfolio/sample_*`         -> `_portfolio/*`
- `_samples/teaching/sample_*`          -> `_teaching/*`
- `_samples/files/sample_*`             -> `files/*`             (dummy papers, slides, bibtex)
- `_samples/images/sample_*`            -> `images/*`
- `_samples/github_workflows/sample_scrape_talks.yml` -> `.github/workflows/scrape_talks.yml`
- `_samples/talkmap*`, `_samples/markdown_generator/` -> repository root

To reuse a sample, copy it back to its original location and remove the `sample_` prefix.
