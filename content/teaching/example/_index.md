---
date: "2018-09-09T00:00:00Z"
draft: False
lastmod: "2018-09-09T00:00:00Z"
linktitle: Teaching Experience
menu:
  example:
    name: Overview
    weight: 1
summary: POL 510/610 Statistics for Politics and Public Administration (Teaching in Fall 2020); POL 522/622 Introduction to Graduate Public Administration (Teaching in Fall 2020); PAD 6109 Institutions and Society (Spring 2020); PAD 5935 Governing Sustainable Communities (Fall 2019); PAD 3003 Public Administration in American Society (Fall 2017 & Spring 2018)
title: Overview
toc: false
type: docs
weight: 1
---

## Flexibility

This feature can be used for publishing content such as:

* **Online courses**
* **Project or software documentation**
* **Tutorials**

The `courses` folder may be renamed. For example, we can rename it to `docs` for software/project documentation or `tutorials` for creating an online course.

## Delete tutorials

**To remove these pages, delete the `courses` folder and see below to delete the associated menu link.**

## Update site menu

After renaming or deleting the `courses` folder, you may wish to update any `[[main]]` menu links to it by editing your menu configuration at `config/_default/menus.toml`.

For example, if you delete this folder, you can remove the following from your menu configuration:

```toml
[[main]]
  name = "Courses"
  url = "courses/"
  weight = 50
```

Or, if you are creating a software documentation site, you can rename the `courses` folder to `docs` and update the associated *Courses* menu configuration to:

```toml
[[main]]
  name = "Docs"
  url = "docs/"
  weight = 50
```

## Update the docs menu

If you use the *docs* layout, note that the name of the menu in the front matter should be in the form `[menu.X]` where `X` is the folder name. Hence, if you rename the `courses/example/` folder, you should also rename the menu definitions in the front matter of files within `courses/example/` from `[menu.example]` to `[menu.<NewFolderName>]`.
