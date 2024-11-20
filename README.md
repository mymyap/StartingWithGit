# StartingWithGit
This repo simply holds my notes on getting started with Git

## Markdown:
https://docs.github.com/de/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax


## tutorials:
https://skills.github.com/


### git
commit: "save" to local clone of repo
push: "save" to the hosted (original) repo (aka remote repo)
pull: check for, download and merge updated data from remote repo to local repo
pull request: merge a branch into another

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

### command line git

to commit file:
```
git commit -a -m "Adding hello from the codespace!"
```
-a: all files
-m: message in quotation marks

to push the commit:
```
git push
```


Your code has been pushed to your repository!





