# Statamic Alfred Extensions
Alfred Extensions to make using [Statamic](http://statamic.com) even *easier*. You will need Alfred and the Powerpack to use these.

## How to Use
Double-click the extension of your choice to install.
-------------------------------------

### New Dated Statamic Entry
*Creates a date based entry in the folder of your choice and opens it in IA Writer.*

You will want to edit the extension to set the path to your statamic and content folder. If you don't want to open the entry in IA Writer, you can edit the last line to use the editor of your choice.

Type keyword `stat` and enter the title of your entry. The markdown file will be created using today's date and a slugged version of the title.
```
stat New Entry
```
Will create: `yyyy-mm-dd-new-entry.md` with the YAML front-matter pre-loaded.

```
---
title: New Entry
---
```