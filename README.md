# Archibald - Hugo theme
Archibald is a slightly modified and cleaned-up version of [Athul's Archie
theme](https://github.com/athul/archie), which is a minimal and clean theme for
Hugo with a markdown-ish UI.

## Demo

Currently there's no demo, sorry :(

## Features
- Google Analytics Script
- Callouts
- Tags
- Auto Dark Mode(based on system theme)
- tl:dr; frontamatter

## Differences compared to Archie
- [lucide](https://github.com/lucide-icons/lucide) instead of
  [feather](https://feathericons.com/) for access to more icons
- different default colors
- cleaned-up css
- several bug fixes

## Installation
In your Hugo website directory, create a new folder named theme and clone this
repository
```bash
$ mkdir themes
$ cd themes
$ git clone git@github.com:BiCapitalization/archibald.git
```
Then, in `config.toml`, set `theme = "archibald"`. For more information read
the official [setup guide](https://gohugo.io/overview/installing/) of Hugo.

## Post format
Use the following as a reference for front matter options:
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
and licensed under the MIT License.
