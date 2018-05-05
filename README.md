# Awesome PostCSS

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Build Status](https://api.travis-ci.org/jdrgomes/awesome-postcss.svg?branch=master)](https://travis-ci.org/jdrgomes/awesome-postcss)

> An selected list of PostCSS resources and other things related.

**PostCSS** is not a preprocessor; it doesn’t transform CSS. As a matter of fact, it doesn’t do much by itself at all. What it does is provide a CSS parser and a framework for creating plugins that can analyse, lint, handle assets, optimise, create fallbacks, and otherwise transform parsed CSS. PostCSS parses CSS into an _abstract syntax tree [AST](https://en.wikipedia.org/wiki/Abstract_syntax_tree)_, passes it through a series of plugins, and then concatenates back into a string.

Your contributions are always welcome. But, please take a quick gander at the contribution [guidelines](https://github.com/jdrgomes/awesome-postcss/blob/master/CONTRIBUTING.md) first.

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
- [Podfanatic | Sam Richard — Sass, Front-end Development](https://podfanatic.com/podcast/non-breaking-space-show/episode/sam-richard-sass-and-postcss) - *English*

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

###### Grunt

- [grunt-australian-stylesheets](https://github.com/stevemao/grunt-australian-stylesheets) - Compile Australian css with [postcss-australian-stylesheets
](https://github.com/dp-lewis/postcss-australian-stylesheets).

###### Gulp

- [gulp-autoprefixer](https://github.com/sindresorhus/gulp-autoprefixer) - Prefix css with Autoprefixer.
- [gulp-postcss](https://github.com/postcss/gulp-postcss) -  Pipe css through postcss processors with a single parse.
- [gulp-australian-stylesheets](https://github.com/stevemao/gulp-australian-stylesheets) - Compile Australian css with [postcss-australian-stylesheets
](https://github.com/dp-lewis/postcss-australian-stylesheets).
- [gulp-rucksack](https://github.com/seaneking/gulp-rucksack) - Plugin for rucksack - a little bag of css superpowers.
- [gulp-pxtorem](https://github.com/cuth/gulp-pxtorem) - Plugin for [postcss-pxtorem](https://github.com/cuth/postcss-pxtorem).
- [gulp-html-postcss](https://github.com/StartPolymer/gulp-html-postcss) - Process inline css in HTML using postcss gulp plugin.

## Guides

###### PostCSS Deep Dive

- `PostCSS Deep Dive:` [Create your own plugin](https://webdesign.tutsplus.com/tutorials/postcss-deep-dive-create-your-own-plugin--cms-24605).
- `PostCSS Deep Dive:` [Miscellaneous goodies](https://webdesign.tutsplus.com/tutorials/postcss-deep-dive-miscellaneous-goodies--cms-24603).
- `PostCSS Deep Dive:` [Preprocessing with “PreCSS”](https://webdesign.tutsplus.com/tutorials/postcss-deep-dive-preprocessing-with-precss--cms-24583).
- `PostCSS Deep Dive:` [Roll your own preprocessor](https://webdesign.tutsplus.com/tutorials/postcss-deep-dive-roll-your-own-preprocessor--cms-24584).
- `PostCSS Deep Dive:` [Shortcuts and shorthand](https://webdesign.tutsplus.com/tutorials/postcss-deep-dive-shortcuts-and-shorthand--cms-24602).
- `PostCSS Deep Dive:` [What you need to know](https://webdesign.tutsplus.com/tutorials/postcss-deep-dive-what-you-need-to-know--cms-24535).

###### PostCSS Quickstart Guide

- `PostCSS Quickstart Guide:` [Exploring plugins](https://webdesign.tutsplus.com/tutorials/postcss-quickstart-guide-exploring-plugins--cms-24566).
- `PostCSS Quickstart Guide:` [Gulp setup](https://webdesign.tutsplus.com/tutorials/postcss-quickstart-guide-gulp-setup--cms-24543).
- `PostCSS Quickstart Guide:` [Grunt setup](https://webdesign.tutsplus.com/tutorials/postcss-quickstart-guide-grunt-setup--cms-24545).
- `PostCSS Quickstart Guide:` [Instant setup options](https://webdesign.tutsplus.com/tutorials/postcss-quickstart-guide-instant-setup-options--cms-24536).

###### Using PostCSS

- `Using PostCSS:` [for minification and optimization](https://webdesign.tutsplus.com/tutorials/using-postcss-for-minification-and-optimization--cms-24568).
- `Using PostCSS:` [for cross browser compatibility](https://webdesign.tutsplus.com/tutorials/using-postcss-for-cross-browser-compatibility--cms-24567).
- `Using PostCSS:` [Together with sass, stylus, or less](https://webdesign.tutsplus.com/tutorials/using-postcss-together-with-sass-stylus-or-less--cms-24591).
- `Using PostCSS:` [with BEM and SUIT methodologies](https://webdesign.tutsplus.com/tutorials/using-postcss-with-bem-and-suit-methodologies--cms-24592).

## Plugins

- [postcss parts](https://www.postcss.parts) - A searchable catalog of postcss plugins by [@mxstbr](https://github.com/mxstbr).
- [atom-language-postcss](https://github.com/azat-io/atom-language-postcss) - Atom language support for postcss by [@azat-io](https://github.com/azat-io).
- [poststylus](https://github.com/seaneking/poststylus) - Postcss adapter for stylus by [@seaneking](https://github.com/seaneking).
- [postcss-instagram](https://github.com/azat-io/postcss-instagram) - This is a postcss plugin for adding instagram filters to your photos by [@azat-io](https://github.com/azat-io).
- [postcss-normalize](https://github.com/jonathantneal/postcss-normalize) - Simple normalize.css wrapper for postcss by [@jonathantneal](https://github.com/jonathantneal).
- [postcss-font-magician](https://github.com/jonathantneal/postcss-font-magician) - Magically generate all the @font-face rules by [@jonathantneal](https://github.com/jonathantneal).
- [postcss-loader](https://github.com/postcss/postcss-loader) - Postcss loader for webpack by [PostCSS Team](https://github.com/postcss).
- [css-declaration-sorter](https://github.com/Siilwyn/css-declaration-sorter) - Sort css declarations fast and automatically in a certain order by [@siilwyn](https://github.com/Siilwyn).
- [postcss-pxtorem](https://github.com/cuth/postcss-pxtorem) - Convert pixel units to rem (root em) units using postcss by [@cuth](https://github.com/cuth).
- [postcss-selector-parser](https://github.com/postcss/postcss-selector-parser) - Selector parser with built in methods for working with selector strings by [PostCSS Team](https://github.com/postcss).
- [postcss-html](https://github.com/gucong3000/postcss-html) - Postcss Syntax for parsing HTML / Markdown / Vue component by [@gucong3000](https://github.com/gucong3000).

## Presentations

###### Videos

- [PostCSS - First Look](https://www.lynda.com/CSS-tutorials/PostCSS-First-Look/442850-2.html) - A quick first look at postcss, an engine for processing css with javascript by [@planetoftheweb](https://github.com/planetoftheweb).
- [PostCSS the Future after Sass and Less](https://www.youtube.com/watch?v=73dl5dk9z4Q) - Andrey will talk about ideas behind the postcss by [@ai](https://github.com/ai).
- [Fix global CSS with PostCSS](https://www.dotconferences.com/2015/12/andrey-sitnik-fix-global-css-with-postcss) - Andrey explains how to use the power of postcss to make isolated components without a global reset and avoid conflicts between them by [@ai](https://github.com/ai).
- [PostCSS, cssnext and the future of CSS](https://vimeo.com/159185299) - Maxime explains how the postcss and its ecosystem will help you to avoid to write some legacy code, to lint you code or to write and enjoy today tomorrow’s CSS syntax, today, using cssnext by [@MoOx](https://github.com/MoOx).
- [Kick your CSS up a notch with PostCSS](https://www.youtube.com/watch?v=-_gIKdHYP3E) - Learn how to bring your CSS to the next level with PostCSS. Explore the endless possibilities and master writing a CSS transformation plugin by [@mxstbr](https://github.com/mxstbr).

## Who to Follow

- Andrey Sitnik [@andreysitnik](https://twitter.com/andreysitnik)
- Evil Martians [@evilmartians](https://twitter.com/evilmartians)
- Ray Villalobos [@planetoftheweb](https://twitter.com/planetoftheweb)
- Max Stoiber [@mxstbr](https://twitter.com/mxstbr)
- Maxime Thirouin [@MoOx](https://twitter.com/MoOx)
- Azat S. [@azat_io](https://twitter.com/azat_io)
- Sean King [@seaneking](https://twitter.com/seaneking)

### Thanks to...

[Afonso Pacifer](https://github.com/afonsopacifer), [Marcus Silva](https://github.com/mvfsillva), [Willian Justen](https://github.com/willianjusten) and [Daniel Schmidt](https://github.com/danielmschmidt/) by motivation, help and contribution.

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Jader Gomes](https://github.com/jdrgomes) has waived all copyright and related or neighboring rights to this work.
