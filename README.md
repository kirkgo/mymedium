# MyMedium #

Live theme preview available at [kirk-patrick.com](http://kirk-patrick.com).

This is a theme for [Octopress](http://Octopress.org). Inspired by MediumFox and leveraging the latest [Bootstrap](http://getbootstrap.com/), and is a very clean, focused, and unique theme.

## Installation ##

````
$ cd yourOctopress
$ git submodule add https://github.com/kirkgo/mymedium .themes/mymedium
$ git submodule update --init
$ rake install['mymedium'] # for zsh, use: rake install\['mymedium'\] 
$ rake generate
````

### Grab the latest updates ###

````
$ cd yourOctopress
$ git submodule update
$ rake generate
# regenerate, make changes, etc...
````

## Alternate Installation Without Git Submodule ##
````
$ cd yourOctopress
$ git clone https://github.com/kirkgo/mymedium .themes/mymedium
$ rake install['mymedium'] # for zsh, use: rake install\['mymedium'\]
$ rake generate
````

## Customization ##
You can change the main intro hero, the following landing row, and footer in the following locations;  
hero: `source/_includes/custom/hero.html`  
landing row: `source/_includes/custom/home_landing_row.html`  
footer: `source/_includes/custom/footer.html`  

You can change the background image used behind the hero by replacing the image in `source/images/background.jpg`

### Excerpts ###

I highly recommend using excerpts of your posts, this will allow your short excerpt to be used on your index page instead of including the entire post (unless that's what you want).  

To create an excerpt for your posts add `<!--more-->` in the actual markup for your posts. Anything before this tag will be used as the excerpt for said post.

## Pull-Requests! ##

This is a draft and can definitely will be improved on. Pull requests are very much welcomed and desired. Don't be afraid. Just do it! :)

## Demo ##

This is the theme currently powering the site at [kirk-patrick.com](http://kirk-patrick.com)

## Notice ## 

This theme is based on the [MediumFox](https://github.com/sevenadrian/MediumFox) theme created by [Adrian Artiles](http://adrianartiles.com)