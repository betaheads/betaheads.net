# Betaheads.net

This is website of "Betaheads" minecraft server. Built with [11ty](https://www.11ty.dev/).

## Requirements

- node.js version 16 or later.
- npm, compatible with node.js v16.

## Local development

To run local development mode you need to choose root project folder then run this command:

`npm run start`

## Build project

You can build project running this command in root folder:

`npm run build`

all result files goes to `./_site` folder.

## Adding posts to blog

Posts stored as .md files in `./content/blog` folder.

To add new post better to create new folder like `./content/blog/my-new-post` and put all the images and text files in this folder.

After creating .md file you need to put this text in head of file.
Using this text you can configure page/post information.

```
---
title: Server rules
description: Server rules. In game rules and Discord rules.
date: 2024-03-18
tags:
  - Info
  - another tag
---
```
### Images

Images can be with relative path, in this case you need to use this constructions in your .md file:

`{% image "./your_image.JPG", "alt text!" %}`

## Contribution

Feel free to add posts and helps us make this site better!
