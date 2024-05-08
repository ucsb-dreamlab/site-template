# Github Pages Site Template

This repository can be used as a starting point for making simple web sites with
GitHub pages. It provides a bare-bones configuration using the default CSS styles
and page layout of the [minimal theme](https://github.com/pages-themes/minimal).

Click the "Use this template" button at the top of the page to
create a new repository with the project files. 

## Using your new site

For single page sites, add your page content to [`index.md`](index.md). GitHub
Pages uses [markdown](https://commonmark.org/help/) to convert the contents of
the file to HTML.

## Customizing your site

You can customize your site by modifying the existing theme ('minimal') or 
switching to a new theme. To modify the existing theme:

- add custom [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference) to the `assets/css/styles.scss`
- Modify the page page layout,`_layouts/default.html`

To change the theme, update the `_config.yml`: replace the existing `theme` or `remote_theme` setting
with new settings found in the new themes documentation. 

## Reference

- GitHub Pages uses the Jekyll to build the site: [https://jekyllrb.com](https://jekyllrb.com)
- Jekyll 'layouts' are written using the Liquid template language: [https://shopify.github.io/liquid/](https://shopify.github.io/liquid/) 
- Markdown reference: [https://commonmark.org/help/](https://shopify.github.io/liquid/) 

