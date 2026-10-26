# Repetition, Similarity, Relevance

Jordan Gunn's earlier research proposal connecting repetition, semantic reminding, and narrative memory.

[Read the manuscript](https://githubpsyche.github.io/narrative-memory-proposal/) · [Download the PDF](https://githubpsyche.github.io/narrative-memory-proposal/index.pdf)

This is a Quarto **manuscript** project, not a Quarto book or a standalone HTML document. The article website includes manuscript navigation and a PDF download.

## Version

The proposal is preserved from a source version dated 19 February 2024. The scientific wording is retained, with a separately labelled publication note added in October 2026. Presentation changes move the abstract into manuscript metadata, separate the title and subtitle, repair Markdown list spacing, and escape mathematical set braces. The original provisional claims and incomplete citations are not silently revised.

Original Markdown Git blob: `efd1123223707d08b4f9f768528f89800e796fd7`.

This repository contains only the publication project, not the earlier private working repository or its history.

## Build and publish

Requirements: Quarto 1.8.27 and a LaTeX installation with LuaLaTeX.

```sh
quarto render
touch docs/.nojekyll
```

The `docs/` directory is the checked-in, rendered manuscript website. GitHub Pages publishes it from the `main` branch. To update the site, render locally, review the HTML and PDF, then commit and push the source and `docs/` output together.
