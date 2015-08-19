# Ghost-CSSZenGarden

This is a straight port of [CSSZenGarden](http://www.csszengarden.com)'s index.html to Ghost.

## Status

Mostly done?  
Partials and context pages exist.  
Code injection works.  

### Code injection

We rely on Ghost's code injection feature to inject the stylesheet meta-ref.
I.e. you need to set this line (e.g.) in Ghost's header code injection.
`	<link rel="stylesheet" media="screen" href="//csszengarden.com/214/214.css?v=8may2013">`

This allows us to simply point to another CSS to chnage the whole look and feel of the blog.

Note that depending on the stylesheet, minor adjustment might need to be tweaked, or that there are glitches.


## Goal

Use one the many great stylesheets from [CSSZenGarden](http://www.csszengarden.com)
with your Ghost blog.

## Getting this theme

1. `git clone` this repo.
2. `git fetch origin` to get all the remote branches.
3. `git checkout` the branch (number) for the stylesheet you want to use.
4. Set the styleheet via code injection.

## Kudos

Thanks to [CSSZenGarden](http://www.csszengarden.com) for the great inspiration it provides since its inception.

## Good working stylesheets

214 looks neat. (I used that one when setting up the templates).
