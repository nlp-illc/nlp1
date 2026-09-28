# Add a new edition

Let's suppose the new edition runs in some `YEAR`.

Create a folder `./YEAR` and add `./YEAR/index.md` with the preamble
```
---
layout: home
permalink: /YEAR/
---
```
Then update the root's `./index.html` to redirect to the new edition.

To keep things simple, use `./YEAR/index.md` for everything you need. To ease navigation, you can have a neat navigation bar within the site's banner, simply add something like the following to the preamble:
```
menu:
- Syllabus
- Team
```
where `Syllabus` and `Team` are Markdown section headers within `./YEAR/index.md`.
Of course, if you need to have additional pages, you can have them, but follow the instructions in the subsection below.

Last, update `./past.md` with a link to the older edition. If YEAR is 2027, then perhaps you add something of the kind:
```markdown
Previous editions: [2026]({{ '/2026/' | relative_url }})
```


## Other pages within the new edition

For other md files in the new edition's folder, such as `./YEAR/syllabus.md`, use the preamble
```
---
layout: default
title: Syllabus
permalink: /YEAR/syllabus/
tagline: YEAR
---
```
The `tagline` will remind anyone navigating the site that they are in the right edition (without them having to check their browser's address bar). 

Note that when linking to this, for example from `./YEAR/index.md`, paths are relative eg `[detailed program](./syllabus)`.

# Credit

This site uses the Cayman theme

[![Gem Version](https://badge.fury.io/rb/jekyll-theme-cayman.svg)](https://badge.fury.io/rb/jekyll-theme-cayman)

*Cayman is a Jekyll theme for GitHub Pages. You can [preview the theme to see what it looks like](http://pages-themes.github.io/cayman), or even [use it today](#usage).*


