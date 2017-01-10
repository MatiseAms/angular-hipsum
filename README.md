# Hipster Ipsum Angular Directive

## Install it

Install directive using [bower](http://bower.io):
```bash
bower install angular-hipsum
```

Or [npm](https://www.npmjs.com/):
```bash
npm install angular-hipsum
```

Load script in html after `angular.js` file
```html
<script src="/vendor/angular-hipsum.js"></script>
```

Then, inject `ngHipsum` in your application module:
```javascript
angular.module('myApp', ['ngHipsum']);
```

## Use it
```html
<p hipsum paragraphs="2"></p>
<h1 hipsum words="6"></h1>
<h2 hipsum length="20"></h2>
```

## Available attributes
- `paragraphs`: number of paragraphs (up to 99 paragraphs)
```html
<p hipsum paragraphs="2"></p>
```
- `words`: number of words (as long as there are words available 💩)
```html
<p hipsum words="2"></p>
```
- `length`: length of string
```html
<p hipsum paragraphs="2"></p>
```

## TODO (wishlist)
- ~~Add `words` attribute to choose # of words~~
- Add `kitchensink` element

# Credits
Special thanks to [Ian van Ness](http://ianvanness.com/) for providing the source of Hipster Ipsum on http://hipsterjesus.com/
