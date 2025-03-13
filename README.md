# Litmus Library

Preview address (temporary)

https://ambitious-beach-01703d200.6.azurestaticapps.net/

## How to add documents

Add a new folder into `/content/post`, folder name does not control the name of the article. 

Then in this folder, create the `index.md` file, this is your article. In this file, add a front matter(see below), and then you can start the content of the article. 

If you have images and other files that go inside this article, put them inside the same folder, and you can refer them just like referring to a normal image file in the same directory, like `![Image Title](file-name.png)`.

## Front matter

You need front matter before the body of the markdown file to make them identifiable by Hugo. Below is an very basic example.

```
---
title: Article title, required. 
description: Short description, optional, leave blank if not needed
date: Something like 2025-03-13, I highly recommend setting one. 
---
```
The `---` at the beginning and end is required as it signifies this is front matter. 