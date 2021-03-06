# MyMedium #

This is a theme for [Octopress](http://Octopress.org). 

It's a very clean and focused theme based on MediumFox that uses the latest version of [Bootstrap](http://getbootstrap.com/).

## Installation ##

````
$ cd your-octopress-directory
$ git submodule add https://github.com/kirkgo/mymedium .themes/mymedium
$ git submodule update --init
$ rake install['mymedium'] # for zsh, use: rake install\['mymedium'\] 
$ rake generate
````

### Grab the latest updates ###

````
$ cd your-octopress-directory
$ git submodule update
$ rake generate
# regenerate, make changes, etc...
````

## Alternate Installation Without Git Submodule ##
````
$ cd your-octopress-directory
$ git clone https://github.com/kirkgo/mymedium .themes/mymedium
$ rake install['mymedium'] # for zsh, use: rake install\['mymedium'\]
$ rake generate
````

## Customization ##
You can change the main intro hero, the following landing row, and footer in the following locations:  

* hero: `source/_includes/custom/hero.html`  
* landing row: `source/_includes/custom/home_landing_row.html`  
* footer: `source/_includes/custom/footer.html`  

You can change the background image used behind the hero by replacing the image in `source/images/background.jpg`

### Excerpts ###

I highly recommend using excerpts of your posts, this will allow your short excerpt to be used on your index page instead of including the entire post (unless that's what you want).  

To create an excerpt for your posts add `<!--more-->` in the actual markup for your posts. Anything before this tag will be used as the excerpt for said post.

## Pull-Requests! ##

This is a draft and can definitely will be improved on. Pull requests are very much welcomed and desired. Don't be afraid. Just do it! :)

## Copyright & License ##

Copyright (C) 2016 Kirk Patrick - Released under the MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
