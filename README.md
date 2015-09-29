# Retina Sprite SASS Mixin

Sass (SCSS) + Compass Mixin to use sprites with retina and base 64 support.

##Usage

This mixin uses [Compass](http://compass-style.org/) to render and implement PNG sprites.

Simply add the icon you want to add in the sprite to `[your-image-path]/ico` and the same icon with double the size (retina) to `[your-image-path]/ico-retina`

Add the icon to your element (preferrably pseudo-elements) using `@include ico(name-of-the-icon)`. 

## Base64 embedding

If by any reason you'll need the sprite to be added as base64 (if you have cross-domain issues, for instance) you can call it in a slightly different way: `@include ico(name-of-the-icon, $base64: true)`.  

