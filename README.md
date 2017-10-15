<p align="center">
  <img src="logo.png" alt="Awesome PostCSS">
</p>

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Build Status](https://api.travis-ci.org/jjaderg/awesome-postcss.svg?branch=master)](https://travis-ci.org/jjaderg/awesome-postcss)

> An selected list of PostCSS resources and other things related.

**PostCSS** is not a preprocessor; it doesn’t transform CSS. As a matter of fact, it doesn’t do much by itself at all. What it does is provide a CSS parser and a framework for creating plugins that can analyse, lint, handle assets, optimise, create fallbacks, and otherwise transform parsed CSS. PostCSS parses CSS into an _abstract syntax tree [AST](https://en.wikipedia.org/wiki/Abstract_syntax_tree)_, passes it through a series of plugins, and then concatenates back into a string.

Your contributions are always welcome. But, please take a quick gander at the contribution [guidelines](https://github.com/jjaderg/awesome-postcss/blob/master/CONTRIBUTING.md) first.

## Contents

- [Official Resources](#official-resources)
- [Community](#community)
- [Podcast](#podcast)
- [Articles](#articles)
- [Task Runner](#task-runner)
- [Guides](#guides)
- [Plugins](#plugins)
- [Presentations](#presentations)

## Official Resources

- [GitHub Repository **★ 16,246**](https://github.com/postcss/postcss) - Official postcss repository.
- [API Reference](http://api.postcss.org/index.html) - Detailed postcss API.

## Community

- [Twitter](https://twitter.com/PostCSS) - Official twitter of postcss.
- [Gitter](https://gitter.im/postcss/postcss) - Open source instant messaging for postcss users and developers.
- [Stack Overflow](https://stackoverflow.com/questions/tagged/postcss) - Where questions about postcss are answered.
- [Vkontakte](https://m.vk.com/postcss) - A Russian-based online social networking service.

## Podcast

- [	206 JavaScript Jabber | PostCSS with Ben Briggs](https://devchat.tv/js-jabber/206-jsj-postcss-with-ben-briggs) - *English*
- [Issue 24 radiojs | The most stylish minifier](https://radiojs.ru/2015/06/radiojs-24/) - *Russian*
- [Issue №9 Web standards-ru](https://soundcloud.com/web-standards/episode-9) - *Russian*
- [Podfanatic | Sam Richard — Sass, Front-end Development](https://podfanatic.com/podcast/non-breaking-space-show/episode/sam-richard-sass-and-postcss) - *English*
- [Viewsources Podcast | post processing css](https://viewsourc.es/2015/06/15/episode-8-post-processing-css/) - *English*

## Articles

- [A look into writing future CSS with PostCSS and cssnext](https://bigbitecreative.com/a-look-into-writing-future-css-with-postcss-cssnext/)
- [Breaking up with Sass - PostCSS](https://benfrain.com/breaking-up-with-sass-postcss/)
- [Extending Sass with PostCSS](https://ashleynolan.co.uk/blog/extend-sass-with-postcss)
- [How to Build Your Own CSS Preprocessor With PostCSS](https://www.sitepoint.com/build-css-preprocessor-postcss/)
- [It's Time for Everyone to Learn About PostCSS](http://davidtheclark.com/its-time-for-everyone-to-learn-about-postcss/)
- [I'm Excited About PostCSS](http://davidtheclark.com/excited-about-postcss/)
- [Improving the Quality of Your CSS with PostCSS](https://www.sitepoint.com/improving-the-quality-of-your-css-with-postcss/)
- [Meet PostCSS - Future of CSS after preprocessors](http://www.meetpostcss.com/)
- [Musings from Someone Discovering PostCSS](https://taupecat.com/blog/2016/04/28/musings-from-someone-discovering-postcss/)
- [Nem Sass, nem LESS, nem Stylus: PostCSS!](https://blog.taller.net.br/nem-sass-nem-less-nem-stylus-postcss/) - *Brazilian Portuguese*
- [PostCSS – Sass Killer or Preprocessing Pretender?](https://ashleynolan.co.uk/blog/postcss-a-review)
- [So you want to make a PostCSS plugin](https://css-tricks.com/want-make-postcss-plugin/)
- [That postcss. Its so hot right now](https://cantina.co/that-postcss-its-so-hot-right-now/)
- [Introduction to Postcss](https://www.smashingmagazine.com/2015/12/introduction-to-postcss/)
- [7 Postcss Pluguins to Ease You Into Postcss](https://www.sitepoint.com/7-postcss-plugins-to-ease-you-into-postcss/)
- [Some thinks you may think about postcss](http://julian.io/some-things-you-may-think-about-postcss-and-you-might-be-wrong/)

## Task Runner

### Grunt

- [grunt-australian-stylesheets](https://github.com/stevemao/grunt-australian-stylesheets) - Compile Australian css with [PostCSS australian stylesheets](https://github.com/dp-lewis/postcss-australian-stylesheets).

### Gulp

- [gulp-autoprefixer](https://github.com/sindresorhus/gulp-autoprefixer) - Prefix css with Autoprefixer.
- [gulp-postcss](https://github.com/postcss/gulp-postcss) -  Pipe css through Postcss processors with a single parse.
- [gulp-australian-stylesheets](https://github.com/stevemao/gulp-australian-stylesheets) - Compile Australian css with [PostCSS australian stylesheets](https://github.com/dp-lewis/postcss-australian-stylesheets).
- [gulp-rucksack](https://github.com/seaneking/gulp-rucksack) - Gulp plugin for Rucksack - a little bag of css superpowers.
- [gulp-pxtorem](https://github.com/cuth/gulp-pxtorem) - A gulp plugin for [postcss-pxtorem](https://github.com/cuth/postcss-pxtorem).
- [gulp-html-postcss](https://github.com/StartPolymer/gulp-html-postcss) - Process inline css in HTML using postcss gulp plugin.



## Guides

*Guides for developers start their studies PostCSS.*

##### PostCSS Deep Dive:

- [Create your own plugin](https://webdesign.tutsplus.com/tutorials/postcss-deep-dive-create-your-own-plugin--cms-24605)
- [Miscellaneous goodies](https://webdesign.tutsplus.com/tutorials/postcss-deep-dive-miscellaneous-goodies--cms-24603)
- [Preprocessing with “PreCSS”](https://webdesign.tutsplus.com/tutorials/postcss-deep-dive-preprocessing-with-precss--cms-24583)
- [Roll your own preprocessor](https://webdesign.tutsplus.com/tutorials/postcss-deep-dive-roll-your-own-preprocessor--cms-24584)
- [Shortcuts and shorthand](https://webdesign.tutsplus.com/tutorials/postcss-deep-dive-shortcuts-and-shorthand--cms-24602)
- [What you need to know](https://webdesign.tutsplus.com/tutorials/postcss-deep-dive-what-you-need-to-know--cms-24535)

##### PostCSS Quickstart Guide:

- [Exploring plugins](https://webdesign.tutsplus.com/tutorials/postcss-quickstart-guide-exploring-plugins--cms-24566)
- [Gulp setup](https://webdesign.tutsplus.com/tutorials/postcss-quickstart-guide-gulp-setup--cms-24543)
- [Grunt setup](https://webdesign.tutsplus.com/tutorials/postcss-quickstart-guide-grunt-setup--cms-24545)
- [Instant setup options](https://webdesign.tutsplus.com/tutorials/postcss-quickstart-guide-instant-setup-options--cms-24536)

##### Using PostCSS:

- [for minification and optimization](https://webdesign.tutsplus.com/tutorials/using-postcss-for-minification-and-optimization--cms-24568)
- [for cross browser compatibility](https://webdesign.tutsplus.com/tutorials/using-postcss-for-cross-browser-compatibility--cms-24567)
- [Together with sass, stylus, or LESS](https://webdesign.tutsplus.com/tutorials/using-postcss-together-with-sass-stylus-or-less--cms-24591)
- [with BEM and SUIT methodologies](https://webdesign.tutsplus.com/tutorials/using-postcss-with-bem-and-suit-methodologies--cms-24592)


### Plugins

- [postcss parts](https://www.postcss.parts) - A searchable catalog of PostCSS plugins
- [atom-language-postcss](https://github.com/azat-io/atom-language-postcss) - Atom language support for PostCSS
- [poststylus](https://github.com/seaneking/poststylus) - PostCSS adapter for Stylus
- [postcss-instagram](https://github.com/azat-io/postcss-instagram) - This is a PostCSS plugin for adding Instagram filters to your photos.
- [postcss-normalize](https://github.com/jonathantneal/postcss-normalize) - Simple normalize.css wrapper for PostCSS
- [postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) - Magically generate all the @font-face rules by [@jonathantneal](https://github.com/jonathantneal)
- [postcss-loader](https://github.com/postcss/postcss-loader) - PostCSS loader for webpack
- [css-declaration-sorter](https://github.com/Siilwyn/css-declaration-sorter) - A Node.js module and PostCSS plugin to sort the CSS declarations inside each selector based on their property names by [@Siilwyn](https://github.com/Siilwyn)
- [postcss-pxtorem](https://github.com/cuth/postcss-pxtorem) - Convert pixel units to rem (root em) units using PostCSS
- [postcss-selector-parser](https://github.com/postcss/postcss-selector-parser) - Selector parser with built in methods for working with selector strings
- [postcss-html](https://github.com/gucong3000/postcss-html) - PostCSS Syntax for parsing HTML / Markdown / Vue component

## Presentations

##### Videos

- [PostCSS - First Look](https://www.lynda.com/CSS-tutorials/PostCSS-First-Look/442850-2.html)
- [PostCSS the Future after Sass and Less](https://www.youtube.com/watch?v=73dl5dk9z4Q) by [@ai](https://github.com/ai)
- [Fix global CSS with PostCSS](https://www.dotconferences.com/2015/12/andrey-sitnik-fix-global-css-with-postcss) by [@ai](https://github.com/ai)
- [PostCSS, cssnext and the future of CSS](https://vimeo.com/159185299) by [@MoOx](https://github.com/MoOx)
- [Kick your CSS up a notch with PostCSS](https://www.youtube.com/watch?v=-_gIKdHYP3E) by [@mxstbr](https://github.com/mxstbr)

## Who to Follow

- Andrey Sitnik [@andreysitnik](https://twitter.com/andreysitnik)
- Evil Martians [@evilmartians](https://twitter.com/evilmartians)

## Thanks to...

- In particular [Afonso Pacifer](https://github.com/afonsopacifer) for helping me with CC License. :+1:
- My friends [Marcus Silva](https://github.com/mvfsillva) and [Willian Justen](https://github.com/willianjusten) by motivating me. :v:
- [Daniel Schmidt](https://github.com/danielmschmidt/) for your important contribution to this list.

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/) © [Jader Gomes](https://github.com/jjaderg)
