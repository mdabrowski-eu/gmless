# GMless Games Website

This repository contains source files for a Hugo site about GMless games. Articles are generated from text files located in the `sources` directory.

## Posts

The articles under `website/content/posts` were manually created from the text
files in the `sources` directory. No additional scripts are required to update
them.

## Building the Site

The site uses the **PaperMod** theme. Add the theme as a submodule:

```bash
git submodule add https://github.com/adityatelange/hugo-PaperMod website/themes/PaperMod
```

Then build with Hugo:

```bash
hugo -s website
```

Deploy the `public/` folder to GitHub Pages.
