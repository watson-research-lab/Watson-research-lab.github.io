---
# Title, summary, and page position.
linktitle: Bambu Lab X1-Carbon 3D Printer
summary: Learn about and how to use Bambu Lab 3D Printer
weight: 1
icon: book
icon_pack: fas

# Page metadata.
title: Bambu Lab X1-Carbon 3D Printer
date: '2018-09-09T00:00:00Z'
type: book # Do not modify.
---

## Features

The [Voltera Nova](https://www.voltera.io/nova) is a 3D printer capable of producing flexible hybrid electronics and PCBs.

This feature can be used for publishing content such as:

- **Online courses**
- **Project or software documentation**
- **Tutorials**
- **Notes**

The `courses` folder may be renamed. For example, we can rename it to `docs` for software/project documentation or `tutorials` for creating an online course.

## The Equipment

**To remove these pages, delete the `courses` folder and see below to delete the associated menu link.**

## How to Use It

After renaming or deleting the `courses` folder, you may wish to update any `[[main]]` menu links to it by editing your menu configuration at `config/_default/menus.toml`.

For example, if you delete this folder, you can remove the following from your menu configuration:

```toml
[[main]]
  name = "Courses"
  url = "courses/"
  weight = 50
```

Or, if you are creating a software documentation site, you can rename the `courses` folder to `docs` and update the associated _Courses_ menu configuration to:

```toml
[[main]]
  name = "Docs"
  url = "docs/"
  weight = 50
```

## Overall User Manual
If you use the _docs_ layout, note that the name of the menu in the front matter should be in the form `[menu.X]` where `X` is the folder name. Hence, if you rename the `courses/example/` folder, you should also rename the menu definitions in the front matter of files within `courses/example/` from `[menu.example]` to `[menu.<NewFolderName>]`.
