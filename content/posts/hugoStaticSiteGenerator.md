---
title: "Hugo"
date: 2022-01-04T13:49:38+05:30
draft: true
tags: ["Hugo"]
categories: ["Tech"]
ShowToc: true
---

## Hugo 
---

### Download the hugo binary from 
https://github.com/gohugoio/hugo/releases

copy to the env path

---

### Install a revealjs hugo theme to the themes folder

```
 git clone https://github.com/dzello/reveal-hugo.git .\themes\reveal-hugo\
```

##### can sometimes cause issues : copy the zip file and extract contents to the themes folder

---

### add the themes to the config.toml file

```
theme = "reveal-hugo"

[outputFormats.Reveal]
baseName = "index"
mediaType = "text/html"
isHTML = true
```
---

### add a file _index.md under contents folder 
```
+++
title = "How to say hello"
outputs = ["Reveal"]
+++
```
---

## server the site using 'hugo server'
```
hugo server
```

---

###### Create a git repository and push the contents

```
git init
git add .
git commit -m "first commit"
git remote add origin [your repo name]
git push origin master

```

---

###### Step 1 :Create a netlify site and push the contents from git

![Step 1](../../img/hugo/1.png center)

---

###### Step 2 : Create a netlify site and push the contents from git

![Step 2](../../img/hugo/2.png)

---

###### Step 3 : Create a netlify site and push the contents from git

![Step 3](../../img/hugo/3.png)

---

###### Create a netlify site and push the contents from git

![Step 4](../../img/hugo/4.png)

---

###### Create a netlify site and push the contents from git

![Step 5](../../img/hugo/5.png)

---
###### Create a netlify site and push the contents from git

![Step 6](../../img/hugo/6.png)

---

###### Create a netlify site and push the contents from git

![Step 7](../../img/hugo/7.png)

---
###### Create a netlify site and push the contents from git

![Step 8](../../img/hugo/8.png)

---
###### Create a netlify site and push the contents from git

![Step 9](../../img/hugo/9.png)