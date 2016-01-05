Typeahead.js and Bootstrap 4
============================

For Bootstrap 3 try [typeaheadjs.css](https://github.com/bassjobsen/typeahead.js-bootstrap-css/)

typeahead.js
------------
The [typeahead.js](https://github.com/twitter/typeahead.js) library consists of 2 components: the suggestion engine, Bloodhound, and the UI view, Typeahead. The suggestion engine is responsible for computing suggestions for a given query. The UI view is responsible for rendering suggestions and handling DOM interactions. Both components can be used separately, but when used together, they can provided a rich typeahead experience.

Bootstrap 4
-----------
Bootstrap is a sleek, intuitive, and powerful front-end framework for faster and easier web development, created by [Mark Otto](http://twitter.com/mdo) and [Jacob Thornton](http://twitter.com/fat), and maintained by the [core team](https://github.com/twbs?tab=members) with the massive support and involvement of the community.

To get started, check out <http://getbootstrap.com>!

History
-------
With Twitter Bootstrap 3 the typeahead plugin had been dropped. [@mdo](http://twitter.com/mdo) says: "in favor of folks using [Twitter's typeahead](https://github.com/twitter/typeahead.js). Twitter's typeahead has more features than the old bootstrap-typeahead.js and less bugs." Twitter's typeahead don't work direct with Bootstrap 4. The DOM structure of the dropdown menu used by `typeahead.js` differs from the DOM structure of the Bootstrap dropdown menu. You'll need to load some additional CSS in order to get the `typeahead.js` dropdown menu to fit the default Bootstrap theme. You can download the basic CSS here, or use the SCSS file to integrate it into your project. CSS and SCSS are build with the latest SCSS code of Bootstrap 4 (alpha). Code does not introduce new mixins and only extends Bootstrap's SCSS.

Note also the [orginal typeahead plugin](https://github.com/bassjobsen/Bootstrap-3-Typeahead) still works with Bootstrap 4. 

Download
========

 - Download the latest [typeaheadjs.css](https://github.com/bassjobsen/typeahead.js-bootstrap4-css/blob/master/typeaheadjs.css) or [typeaheadjs.scss](https://github.com/bassjobsen/typeahead.js-bootstrap4-css/blob/master/typeaheadjs.scss).

How to use
==========

CSS
---
Include the CSS file after Bootstrap's CSS in your HTML:

	<link href="bootstrap.min.css" rel="stylesheet">
	<link href="typeaheadjs.css" rel="stylesheet">

Sass
----
 1. Copy typeaheadjs.scss into your Bootstrap's SCSS folder
 2. Import this file at the end of bootstrap.scss: `@import "typeaheadjs.scss";`
 3. Recompile Bootstrap 
 
Example
-------
![ScreenShot](https://raw.github.com/bassjobsen/typeahead.js-bootstrap4-css/master/screenshot.png)
