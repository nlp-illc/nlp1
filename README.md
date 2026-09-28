# Add a new edition

Create a folder `/year` and add `/year/index.md` with the preamble
```
---
layout: home
permalink: /year/
---
```
Then update the root's `/index.html` to redirect to the new edition.

To keep things simple, use `year/index.md` for everything you need. To ease navigation, you can have a neat navigation bar within the site's banner, simply add something like the following to the preamble:
```
menu:
- Syllabus
- Team
```
where `Syllabus` and `Team` are Markdown section headers within `year/index.md`.
Of course, if you need to have additional pages, you can have them, but follow the instructions in the subsection below.

Last, update `past.md` with a link to the older edition. Something of the kind:
```markdown
Previous editions: [2026](/2026)
```


## Other pages within the new edition

For other md files in the new edition's folder, such as `/year/syllabus.md`, use the preamble
```
---
layout: default
title: Syllabus
permalink: /2026/syllabus/
---
```

Note that when linking to this, for example from `index/year.md`, paths are relative eg `[program](./syllabus)`.

# Credit

This site uses the Cayman theme

[![Gem Version](https://badge.fury.io/rb/jekyll-theme-cayman.svg)](https://badge.fury.io/rb/jekyll-theme-cayman)

*Cayman is a Jekyll theme for GitHub Pages. You can [preview the theme to see what it looks like](http://pages-themes.github.io/cayman), or even [use it today](#usage).*

![Thumbnail of Cayman](thumbnail.png)

