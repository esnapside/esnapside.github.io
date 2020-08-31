# Esnapside Website

Hosts the company website for Esnapside using Jekyll and Github pages  
Website available [here](https://esnapside.com)  
It uses [liquid](https://shopify.github.io/liquid/) for HTML templating and pre-processing

# Local development

1. Clone locally
2. Install `jekyll` and `github-pages` gems
```bash
gem install jekyll github-pages
```
3. Run `jekyll serve`
4. Visit http://localhost:4000


# Theme
Agency theme based on [Agency bootstrap theme ](https://startbootstrap.com/template-overviews/agency/)
View this jekyll theme in action [here](https://y7kim.github.io/agency-jekyll-theme)

# How to use

The header section is defined in `/_includes/header`  

## Portfolio
Projects are in `/_posts` and images in `/img/portfolio`  
Each file is an entry which looks like:
```md
---
title: Round Icons
subtitle: Graphic Design
layout: default
modal-id: 6
date: 2014-07-15
img: roundicons.png
thumbnail: roundicons-thumbnail.png
alt: image-alt
project-date: April 2014
client: Start Bootstrap
category: Web Development
description: Lorem ipsum dolor sit amet, usu cu alterum nominavi lobortis. At duo novum diceret. Tantas apeirian vix et, usu sanctus postulant inciderint ut, populo diceret necessitatibus in vim. Cu eum dicam feugiat noluisse.

---
```

## Services
Described in the `/_includes/services`  
3 services per row, the second class of the second `i` tag defines the icon

## About
Images are in `/img/about/` and file in `/_includes/about`


## Team
Team members and info are in '_config.yml'
Images are in `/img/team/`
For the supported social media icons check [Font Awesome](https://fontawesome.com/)