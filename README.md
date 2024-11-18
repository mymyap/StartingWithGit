# StartingWithGit
This repo simply holds my notes on getting started with Git

## Markdown:
https://docs.github.com/de/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax


## tutorials:
https://skills.github.com/



### Pages (website)
enable in settings-> pages -> Build and Deployment

pages uses Jekyll

in root:
_config.yml   ->  configure pages (=website)
index.md -> if exists, will contain website
readme.md -> if index.md does not exist, will be used as website. 



_config.yml: content e.g. 


```
theme: minima
title: test site
author: my
description: blub

```
minima is a Blog-style theme 

posts will be in:
_posts\YYYY-MM-DD-title-words-connected-with-hyphen.md
--> the index.md will list these posts as links

each post needs to contain this as a header (=frontmatter)

```
---
title: "this is a title"
date: 2024-11-13
---
```

