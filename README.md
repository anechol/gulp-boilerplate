# gulp-boilerplate
Personal boilerplate for Gulp-based projects.

Includes:
* HTML file
* Folders
  * CSS (Normalize.css)
  * Sass
  * JavaScript
  * Images
  * Fonts
* Git ignore

Commands:
* `npm install` for Dependencies
* `gulp` to run BrowserSync on port 3000
* `gulp build` for production site

```html
<!-- Use this example to concatenate and minify CSS files during 'gulp build' -->

<!-- build:css main.min.css -->
<link rel="stylesheet" href="/css/normalize.css" media="screen" charset="utf-8">
<link rel="stylesheet" href="/css/skeleton.plus.css">
<link rel="stylesheet" href="/css/main.css" media="screen" charset="utf-8">
<!-- endbuild -->
```

and

```html
<!-- Use this example to concatenate and minify JS files during 'gulp build' -->

<!-- build:js main.min.js -->
<script src="https://code.jquery.com/jquery-3.1.1.js" integrity="sha256-16cdPddA6VdVInumRGo6IbivbERE8p7CQR3HzTBuELA=" crossorigin="anonymous"></script>
<script src="/js/main.js" charset="utf-8"></script>
<!-- endbuild -->
```
