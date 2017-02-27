JavaScript 资源汇总
========
    
## 精彩文章

**A re-introduction to JavaScript***  
https://developer.mozilla.org/en-US/docs/Web/JavaScript/A_re-introduction_to_JavaScript  
Why a re-introduction? Because JavaScript is notorious for being the world's most misunderstood programming language. While often derided as a toy, beneath its deceptive simplicity lie some powerful language features, one that is now used by an incredible number of high-profile applications, showing that deeper knowledge of this technology is an important skill for any web or mobile developer.

**Maze Generation: Algorithm Recap**  
http://weblog.jamisbuck.org/2011/2/7/maze-generation-algorithm-recap  
When React 0.13 came out, everybody freaked out.
The introductory post made it clear that mixins are on their way out.


**The [real] problem with JavaScript**  
https://medium.com/unhandled-exception/the-real-problem-with-javascript-6b78cad97b6e  
https://medium.com/@wob/the-sad-state-of-web-development-1603a861d29f  
讨论 JS 、Web 开发、前端生态，起因是第2篇文章，观点挺偏激的，引发了激烈地讨论，不过的确指出了 Web 生态圈面临的一些问题。第1篇文章比较中肯，作者也在试图建立一个知识库来解决技术选型问题，这是他采集信息的一个调研： [Should I Use](https://alterx.typeform.com/to/ASrKf9)。这两个文章还引申出两个有意思的东西：[Magpie Developer](http://blog.codinghorror.com/the-magpie-developer/)、[The programming language cycle](http://quoderat.megginson.com/2006/03/06/programming-languages-of-distinction/)

**The Single Biggest Mistake Programmers Make Every Day**  
https://medium.com/javascript-scene/the-single-biggest-mistake-programmers-make-every-day-62366b432308  
I believe the single biggest mistake that every programmer makes from time to time is overcomplicating things. Simplify your code. Start with the least complicated implementation and work your way toward more complex solutions only when the problem demands it.
Remember:  
- Keep It Stupid Simple (KISS)
- Make it work, make it right, make it fast.
- Understand the problem. (Know what “make it work” means.)
- Begin at the beginning.
- Start with tests.
- Do One Thing (DOT).
- Start small and iterate.
- Pure function > Function > Factory > Class  
Simple beats clever every day of the week.

**How do Promises Work?**  
http://robotlolita.me/2015/11/15/how-do-promises-work.html  
In this blog post we’ll look at what promises are, how they work, and why you should or shouldn’t use them.  

**Concurrently JavaScript**  
http://blog.getify.com/concurrently-javascript-1/  
What is concurrency? How is it different from parallelism? JavaScript is single-threaded on the event loop, so how does its asynchrony fit into the mix?

**Top JavaScript Frameworks, Libraries and Tools and When to Use Them**  
http://www.sitepoint.com/top-javascript-frameworks-libraries-tools-use/  
This article is part of a web development series from Microsoft. It seems like almost every other week there is a new JavaScript library taking the web community by storm! The web community is increasingly vibrant, diverse and is moving rapidly on multiple fronts. It would be an impossible feat to survey every major JavaScript framework and library. Instead,I will share some of the most famous and influential ones for front-end development. 

## JS 语言进化

- [JSX](http://jsx.github.io/) JSX is a statically-typed, object-oriented programming language designed to run on modern web browsers.
- [TypeScript](http://www.typescriptlang.org/) 编译比较慢，并未深度改造  
- [CoffeeScript](http://coffeescript.org) 增强了JavaScript的简洁性与可读性，但对 js 改造太大，并不适合在大团队使用  
- [ELM](http://elm-lang.org/) the best of functional programming in your browser  


## 应用框架  

一些专注于 Web 应用如何开发的框架  

- [cycle.js](http://cycle.js.org/) A functional and reactive JavaScript framework for cleaner code
- [vuejs](http://vuejs.org/) Vue.js is a library for building interactive web interfaces.  
It provides data-driven components with a simple and flexible API.
- [wayjs](https://github.com/gwendall/way.js) Simple, lightweight, persistent two-way databinding  
- <http://t3js.org/>  


## jquery edit in place plugin

- [X-editable](http://vitalets.github.io/x-editable/)
- [Jeditable](http://www.appelsiini.net/projects/jeditable)

## generate form from json

- **[jsonform](https://github.com/joshfire/jsonform)**  文档非常好，对标准化的支持也不错
- [Easy Forms for jQuery: Alpaca](http://www.alpacajs.org/) 重量级的类库，功能很强，但可集成度比 jsonform 低

## 数据表格

- [Handsontable](http://handsontable.com/): Handsontable is a minimalistic Excel-like data grid editor for HTML, JavaScript & jQuery

## Jquery插件

- [jCarousel Lite](http://www.gmarwaha.com/jquery/jcarousellite/) : jCarousel Lite is a jQuery plugin that carries you on a carousel ride filled with images and HTML content. Put simply, you can navigate images and/or HTML in a carousel-style widget. It is super light weight, at about 2 KB in size, yet very flexible and customizable to fit most of our needs. 

## JS parser 

- [acorn.js](http://marijnhaverbeke.nl/acorn/)  
- [esprima](http://esprima.org/)  

## UI Framework

mobile webapp : 

- **[Ionic](http://ionicframework.com/)** : Create amazing apps
The beautiful, open source front-end framework for developing hybrid mobile apps with HTML5.  
- [Onsen UI](http://onsenui.io/) : The Answer to PhoneGap UI Development. A Custom Elements-Based HTML5 UI Framework.  
- [Webix](http://webix.com/) : Build rich UI in a few lines of code.  
- [Sencha Touch](http://www.sencha.com/products/touch/)  
- [Kendo UI](http://www.telerik.com/kendo-ui) : Everything you need to build sites and apps
with pure JavaScript and HTML5.  
- https://github.com/makeusabrew/bootbox  Bootbox.js is a small JavaScript library which allows you to create programmatic dialog boxes using Bootstrap modals
- https://github.com/hubspot/vex  Vex is a modern dialog library which is highly configurable, easily stylable, and gets out of the way.  

pc : 

- [Bootstrap](http://getbootstrap.com/)
- [Semantic UI](http://semantic-ui.com/)

## Game

- [Egret Engine](http://www.egret-labs.org/) : Egret Engine（白鹭引擎）是一款使用TypeScript语言构建的开源免费的移动游戏引擎。白鹭引擎的核心定位是开放，高效，优雅。通过它，你可以快速地创建HTML5类型的移动游戏，也可以将游戏项目编译输出成为目标移动平台的原生游戏应用。
- [Turbulenz Engine](https://github.com/turbulenz/turbulenz_engine) : Turbulenz is an HTML5 game engine and server-side APIs available in JavaScript and TypeScript for building and distributing 2D and 3D games that run on platforms that support HTML5 features such as modern browsers without the need for plugins.


## lib 

- [](http://vanilla-js.com/)  Vanilla JS is a fast, lightweight, cross-platform framework
for building incredible, powerful JavaScript applications.
- [way.js](https://github.com/gwendall/way.js) : Simple, lightweight, persistent, framework-agnostic two-way databinding Javascript library (with no to little JS code to write).  
- [vuejs](http://vuejs.org/)  
- [Parsing URLs in JavaScript](http://www.abeautifulsite.net/parsing-urls-in-javascript/)  
- [URI.js](https://github.com/medialize/URI.js)  
- [MetricsGraphics.js](http://metricsgraphicsjs.org/)  
- https://github.com/ottomao/bugfreejs  佛祖保佑，永无bug  
- http://peeinears.github.io/MagicEye.js/  
- [opentype.js](https://github.com/nodebox/opentype.js)  opentype.js is a JavaScript parser and writer for TrueType and OpenType fonts.  字体变成路径
- https://github.com/aui/font-spider/  
- [Fetch is the new XHR](https://github.com/github/fetch)  

### 数据可视化

**Sigma.js: a JavaScript library for graph drawing**  
http://sigmajs.org/  
Sigma is a JavaScript library dedicated to graph drawing. It makes easy to publish networks on Web pages, and allows developers to integrate network exploration in rich Web applications.

**Plotly.js - JavaScript library for scientific interactive charts**  
https://plot.ly/javascript/open-source-announcement/  
https://github.com/plotly/plotly.js/  
Today, Plotly is announcing that we have open-sourced plotly.js, the core technology and JavaScript graphing library behind Plotly’s products (MIT license). It's all out there and free. Any developer can now integrate Plotly’s library into their own applications unencumbered. Plotly.js supports 20 chart types, including 3D plots, geographic maps, and statistical charts like density plots, histograms, box plots, and contour plots.  

### angular  

http://jeff-collins.github.io/ment.io/  Mentions and Macros for Angular  

## embeddable Javascript engine

http://www.duktape.org/  
http://cylonjs.com/  

## 企业级应用组件

**WebODF**  
http://webodf.org/  
WebODF is a JavaScript library that makes it easy to add Open Document Format (ODF) support to your website and to your mobile or desktop application. It uses HTML and CSS to display ODF documents.

**dhtmlx**  
http://dhtmlx.com/  
A cross-browser JavaScript library for building rich Web and Mobile apps  

**Webix**
http://webix.com/  
Webix provides a great number of JavaScript UI widgets with a pefect look and feel great on various devices. All of them can be effortlessly customized in accordance with your preferences thanks to the rich and clear API.

## Editor

**bootstrap-wysihtml5**  
http://jhollingworth.github.io/bootstrap-wysihtml5/  
Simple, beautiful wysiwyg editors  bootstrap-wysihtml5 is a javascript plugin that makes it easy to create simple, beautiful wysiwyg editors with the help of wysihtml5 and Twitter Bootstrap
相近的： http://mindmup.github.io/bootstrap-wysiwyg/  

**TinyMCE**  
http://www.tinymce.com/  
TinyMCE is a platform independent web based Javascript HTML WYSIWYG editor control released as Open Source under LGPL. TinyMCE has the ability to convert HTML TEXTAREA fields or other HTML elements to editor instances.  

## UI Framework

http://demos.telerik.com/kendo-ui/  

## 异步编程

**Zone.js**  
https://github.com/angular/zone.js  
Implements Zones for JavaScript, inspired by Dart. A Zone is an execution context that persists across async tasks. You can think of it as thread-local storage for JavaScript VMs.  
这个库会在 angular 2.0 中使用。  

## tools


## 数据模拟

**json-server**  
https://github.com/typicode/json-server  
Get a full fake REST API with zero coding in less than 30 seconds (seriously)   

### 编译构建

codekit  

**babel**  
http://babeljs.io/  
Babel is a JavaScript compiler. Use next generation JavaScript, today.

**JSPM**  
jspm is a package manager for the SystemJS universal module loader, built on top of the dynamic ES6 module loader

### 混淆

- [JavaScript Obfuscator - JS Packer](http://packer.50x.eu/)  
- [gulp-obfuscate](https://github.com/mikegroseclose/gulp-obfuscate)  
- [“短”化你的代码](http://ucren.com/blog/archives/549)  

### browser-based

基于浏览器内核的一些工具，可用在测试、竞品等环节

- [Slimerjs](http://slimerjs.org/)  
- [Phantomjs](http://phantomjs.org/)  
- [page-monitor](https://github.com/fouber/page-monitor)  
- [casperjs](http://casperjs.org/)  

## Services

- [harp](https://www.harp.io/)
- [Adobe® PhoneGap™ Build](https://build.phonegap.com/)

## 其它

- [node-webkit](https://github.com/rogerwang/node-webkit)  
- [p5js](http://p5js.org/)  
- [Grunt and RequireJS are out, it’s all about Gulp and Browserify now](http://www.100percentjs.com/just-like-grunt-gulp-browserify-now/)  
- [No more JS frameworks](http://bitworking.org/news/2014/05/zero_framework_manifesto)  
- [详解this](http://wayou.github.io/2015/01/18/all-this/) [原文](http://wayou.github.io/2015/01/18/all-this/)  
- [HAXE](http://haxe.org/)  Haxe is an open source toolkit based on a modern, high level, strictly typed programming language, a cross-compiler, a complete cross-platform standard library and ways to access each platform's native capabilities. 
- [国外优秀JavaScript资源推荐](http://www.ido321.com/302.html)  
- [7GUIs](https://github.com/eugenkiss/7guis) 7GUIs is a GUI programming usability benchmark  
- highlight.js  
- [Web缓存基础：术语、HTTP报头和缓存策略](https://linux.cn/article-5456-1.html)  