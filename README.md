# Statamic Alfred Extensions
Alfred Extensions to make using [Statamic](http://statamic.com) even *easier*. You will need Alfred and the Powerpack to use these.

## How to Install
Double-click the extension of your choice to install.

--------------------------------------

## New Dated Statamic Entry
*Creates a date based entry in the active or top-most Finder window and opens it in IA Writer.*

If you don't want to open the entry in IA Writer, you can edit the last line to use the editor of your choice.

Type keyword `entry` and enter the title of your entry. The markdown file will be created using today's date and a slugged version of the title.
```
entry New Blog Post
```
Will create: `yyyy-mm-dd-new-blog-post.md` with the YAML front-matter pre-loaded.

```
---
title: New Blog Post
---
```