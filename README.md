# docposter Format

**This repo contains an experimental quarto extension. It is not being maintained or supported at this time.**

docposter is an experimental format to prepare posters in Markdown and HTML/CSS via quarto instead of manual layout using slide presentation software. This repo is an evolution of [drposter](https://github.com/bbucior/drposter), rebuilding and simplifying that RMarkdown format as a quarto extension. Depending on your use case, other alternatives such as [posterdown](https://github.com/brentthorne/posterdown) or [quarto dashboards](https://quarto.org/docs/dashboards/) may be more suitable.

## Installing docposter

```bash
quarto use template bbucior/docposter
```

This command will install the extension and create an example qmd file and _quarto.yml project that you can use as a starting place for your poster.

## Using docposter

Render the poster by running `quarto render` within your project directory.

See the project template.qmd file for additional information about the layout syntax, customizing the appearence via custom.css, and other project options. For now, these project settings are intended to be reverse-compatible with drposter, though may be subject to change in a future version.

## Example

Here is the source code for a minimal sample document: [template.qmd](template.qmd).
