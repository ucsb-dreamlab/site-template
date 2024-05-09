# Github Pages Site Template

This repository can be used as a starting point for making simple web sites with
GitHub pages. It provides a bare-bones configuration using the default CSS styles
and page layout of the ['minimal'](https://github.com/pages-themes/minimal) Jekyll 
theme.

Click the "Use this template" button at the top of the page to
create a new repository with the project files. 

## Enabling GitHub Pages for your repo

In your repository __Settings__, navigate to the [__Pages__](settings/pages) tab, and
set the following options:

- __Source__ should be set to "Deploy from a branch"
- __Branch__ should be set to "main" and the folder should be "/ (root)"

It may take a few minutes for the GitHub Pages Action to build and deploy your site.

## Using your new site

Without any modifications, the site's front page ([`index.md`](index.md))
displays a lists 'posts' and their descriptions. The [example post](_posts/2024-05-08-testpost.md)  
describes the process for creating new posts.

If you prefer a single-page site, without any posts, you can replace the existing
content of `index.md` with your new page content. GitHub Pages uses 
[markdown](https://commonmark.org/help/) to convert the contents of the file to HTML. 

You can upload images and other files to the [`assets`](assets)
folder and include them in your page using markdown like this:

```md
Image:
![this is an image](/assets/my-image.jpg)

File link:
[CSV file](/assets/my-file.csv)
```

## Customizing your site

You can customize your site by modifying the existing theme ('minimal') or 
switching to a new theme. To modify the existing theme:

- add custom [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference) to [`assets/css/styles.scss`](assets/css/styles.scss)
- Modify the page layout file, [`_layouts/default.html`](_layouts/default.html)

To change the theme, update [`_config.yml`](_config.yml): replace the existing `theme` or `remote_theme` setting
with new settings found in the new themes documentation. 

## Reference

- GitHub Pages uses Jekyll to build the site: [https://jekyllrb.com](https://jekyllrb.com)
- Jekyll 'layouts' are written using the Liquid template language: [https://shopify.github.io/liquid/](https://shopify.github.io/liquid/) 
- Jekyll converts content to HTML using Markdown: [https://commonmark.org/help/](https://shopify.github.io/liquid/) 

