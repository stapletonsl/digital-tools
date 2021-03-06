---
title: Discovery
nav: true
---

# Phase 2: Discovery

{% include figure.html img="ch-discovery.png" alt="A boy and his tiger run to the snow" caption="Oh boy! Here we go!" width="75%" %}

## Qualitiative data capture

### Survey tools 💬 

**Recommended**
 - [Online Research Survey Tool](https://prodsurvey.rcs.griffith.edu.au/doco2/) - Griffith Supported, free
 - [RedCap](https://www151.griffith.edu.au/redcap/) - Griffith Supported, free
 
**Other options**
 - [Google Forms](https://docs.google.com/forms/)
 - [Microsoft Forms](http://forms.office.com)
 - [Survey Monkey](https://www.surveymonkey.com)
 - [Qualtrics](https://www.qualtrics.com) - Griffith no longer holds a license

---

## Reference Management

### 🏷 Bibliographic tools

***Recommended***

 - [EndNote](https://www.griffith.edu.au/library/study/referencing) - Griffith supported, free
 - [Zotero](https://www.zotero.org)
 - [Mendeley](https://www.mendeley.com)

***Other options***
 - [Papers](https://www.papersapp.com)
 - [F1000](https://f1000workspace.com/?lg)
 - [BibTex](https://www.bibtex.org)

---

# Introduction

One amazingly useful GitHub feature is [GitHub Pages](https://guides.github.com/features/pages/){:target='_blank'}.
It provides free static web hosting from any repository.
Gh-pages is intended to host relatively simple sites for your GitHub portfolio, project, or documentation.
Because it is free and a valuable transferable skill, this is a great option for teaching and learning.

Many organizations are using GitHub to collaboratively create and publish public workshop websites. 
For example: 

- [Programming Historian](http://programminghistorian.org/)
- [Software Carpentry](https://software-carpentry.org/), [Data Carpentry](http://www.datacarpentry.org/), [Library Carpentry](https://librarycarpentry.org/)
- this site!

{% capture text %}Note:
There are *soft* limits and guidelines for gh-pages usage: sites should be < 1GB, use < 100GB bandwidth per month, and make < 10 builds per hour.
If your site exceeds these quotas, GitHub will send you a notice asking you to modify the repository.
All content must follow the [community guidelines](https://help.github.com/articles/github-community-guidelines/), e.g. no violence, obscene sex, or illegal stuff.{% endcapture %}
{% include alert.md text=text color=secondary %}

# workshop-template-b

`workshop-template-b` is a Jekyll project to create a simple workshop website, with a [Bootstrap](https://getbootstrap.com/){:target='_blank'} theme, designed for hosting on [gh-pages](https://pages.github.com/){:target='_blank'}.

It works best for about 5 pages of instructions, plus index, all written in Markdown. 
The navigation to the main pages is exposed at top and bottom of each page for easy stepping through the lessons.

## Why?

Rather than making slides for a workshop, why not make a website? 
It's easier to write, access, share, and reuse. 
GitHub and gh-pages makes this super easy.

It is a better [Open Educational Resource](https://en.wikipedia.org/wiki/Open_educational_resources){:target='_blank'} since anyone can easily fork and adapt!
