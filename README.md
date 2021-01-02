# Archibald - Hugo theme
Archibald is a minimal and clean theme for hugo with a markdown-ish UI.

Forked from [Athul's Archie theme](https://github.com/athul/archie)

## Demo

[Check the Demo](https://athul.github.io/archie/) hosted on GitHub Pages :smile: . You can find the source code to that in the `site` branch of this repository

![](/images/theme.png)
![](/images/archie-dark.png)
## Feature
- Google Analytics Script
- Callouts
- Tags
- Auto Dark Mode(based on system theme)
- tl:dr; frontamatter

## Installation
In your Hugo website directory, create a new folder named theme and clone the repo
```bash
$ mkdir themes
$ cd themes
$ git clone git@github.com:BiCapitalization/archie.git
```
Edit the `config.toml` file with `theme = "archibald"`
For more information read the official [setup guide](https://gohugo.io/overview/installing/) of Hugo.

## Writing Posts
Create a new `.md` file in the *content/posts* folder
```yml
---
title: Title of the post
description:
date:
tldr: (optional)
draft: true/false (optional)
tags: [tag names] (optional)
---
```

## Credits
Forked from [Athul's Archie theme](https://github.com/athul/archie), which is
itself forked from from the [Ezhil Theme](https://github.com/vividvilla/ezhil),
and licensed under MIT License.

