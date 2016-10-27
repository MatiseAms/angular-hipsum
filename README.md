# Hipster Ipsum Angular Directive

## Install it

Install directive using [bower](http://bower.io):
```bash
bower install angular-hipsum
```

Load script in html after angular.js file
```html
<script src="/vendor/angular-hipsum.js"></script>
```

## Use it
```html
<p hipsum paragraphs="2"></p>
<h1 hipsum length="14"></h1>
<h2 hipsum length="20"></h2>
```

## Available attributes
- `paragraphs`: number of paragraphs
```html
<p hipsum paragraphs="2"></p>
```
- `length`: length of string
```html
<p hipsum paragraphs="2"></p>
```

## TODO (wishlist)
- add `words` attribute to choose # of words
- add `kitchensink` element

# Credits
Special thanks to [Ian van ness](http://ianvanness.com/) for providing the source of Hipster Ipsum on http://hipsterjesus.com/
