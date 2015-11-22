# Training Advanced JS

by [JuanMa Garrido](#trainer)

<!-- ######################## COVER ######################## --> 

!SLIDE #MainCover no-bullet-list
 
## Advanced JS Training  

- TDD/BDD with Jasmine
- Object Oriented Javascript
- jQuery
- Frontend Arquitecture
- ES6

<!-- ######################## TEACHER ######################## --> 

!SLIDE #trainer no-bullet-list

## Teacher: JuanMa Garrido
 
<ul>
<li><a class="icon-envelope" href="mailto:JuanMa.Garrido@gmail.com" target="_blank">JuanMa.Garrido@gmail.com</a></li>
<li><a class="icon-twitter" href="https://twitter.com/juanmaguitar" target="_blank">@juanmaguitar</a></li>
<li><a class="icon-linkedin" href="http://www.linkedin.com/in/juanmagarrido" target="_blank">http://www.linkedin.com/in/juanmagarrido</a></li>
<li><a class="icon-github" href="https://github.com/juanmaguitar" target="_blank">https://github.com/juanmaguitar</a></li>
</ul>

<ul>
<li><a class="icon-pixelovers" href="http://pixelovers.com" target="_blank">https://pixelovers.com</a></li>
<li><a class="icon-twitter" href="https://twitter.com/pixelovers" target="_blank">@pixelovers</a></li>
<li><a class="icon-book" href="http://apuntesjs.com" target="_blank">Apuntes de Javascript</a></li>

</ul>

<!-- ######################## CONTENTS ######################## --> 

!SLIDE contents general

## Contents

1. <span class="icon-calendar"> TDD/BDD with Jasmine
1. <span class="icon-calendar"> JS Avanzado: objetos, falsy values, scope y closures, dom y bom
1. <span class="icon-calendar"> JS Avanzado: this, prototype y herencia
1. <span class="icon-calendar"> JS Avanzado: patrones de diseño
1. <span class="icon-calendar"> jQuery
1. <span class="icon-calendar"> jQuery
1. <span class="icon-calendar"> Arquitectura Frontend: NPM, Grunt, JSLint, format, compilation
1. <span class="icon-calendar"> ES2015 (ES6)
1. <span class="icon-calendar"> ES2015 (ES6)
1. <span class="icon-calendar"> Final Practice

<!-- ######################## COVER ######################## --> 

!SLIDE coverSession tdd

<section class="logos">
  <div class="box">
    ![Javascript Logo](img/JavaScript-logo.png)
    ![Jasmine Logo](img/jasmine_vertical.png)
  <div>
</section>
 
## Advanced JS Training  
### TDD/BDD with **Jasmine**  


<!-- ######################## CONTENTS ######################## --> 

!SLIDE #contents tdd

## Contents

1. [Unit Testings](https://github.com/juanmaguitar/apuntes-javascript-avanzado/tree/master/markdown/unit_testings#1--unit-testings-pruebas-unitarias)
1. [TDD y BDD](https://github.com/juanmaguitar/apuntes-javascript-avanzado/tree/master/markdown/unit_testings#2--tdd-y-bdd)
1. [Testing Frameworks](https://github.com/juanmaguitar/apuntes-javascript-avanzado/tree/master/markdown/unit_testings#3--testing-frameworks) 
1. [Testing Runners](https://github.com/juanmaguitar/apuntes-javascript-avanzado/tree/master/markdown/unit_testings#4--testing-runners) 

<!-- ######################## RESOURCES TDD ######################## --> 

!SLIDE tdd kata

## <span class="icon-keyboard"></span> KATA: Native function `myIndexOf()`

Implement the JavaScript native function `myIndexOf()`  

The `myIndexOf()` method returns the index within the calling String object of the first occurrence of the specified value, starting the search at _fromIndex_ , returns -1 if the value is not found. The indexOf method is case sensitive.

| Parameter | Description |
|-----------|-------------|
| `searchValue` | A string representing the value to search for. |
| `fromIndex` | The location within the calling string to start the search from. It can be any integer between 0 and the length of the string. The default value is 0. |


!SLIDE tdd kata

## <span class="icon-keyboard"></span> KATA: Poker

Create a useful model of a standard 52-card deck of cards:  

- 4 suits - spades, hearts, diamonds, clubs
- 13 ranks - Ace, two to ten, Jack, Queen, King

I should be able to draw a poker hand (5 card draw, not Texas hold 'em) and identify useful properties of the hand :

- Is there a pair of card? (e.g. two Aces)
- Is there three of a kind?
- Four of a kind?
- Are there two pairs?
- Is there a straight? (e.g. 4, 5, 6, 7, 8 of any suit)
- Is there a flush? (e.g. 2, 4, 6, 8, King - all of Hearts)
- What is the highest/lowest card?

<!-- ######################## RESOURCES TDD ######################## --> 

!SLIDE tdd no-bullet-list resources

## Resources for this Unit

- <span class="icon-book"> [Test Driven JavaScript Development](http://www.amazon.es/Driven-JavaScript-Development-Developers-Library/dp/0321683919)
- <span class="icon-link"> [Jasmine](https://jasmine.github.io/)
- <span class="icon-link"> [Karma](http://karma-runner.github.io/0.13/index.html)
- <span class="icon-link"> [Phantom JS](http://phantomjs.org/)
- <span class="icon-github"> [Karma Coverage](https://github.com/karma-runner/karma-coverage)
- <span class="icon-github"> [JS Unit Testing Guide](https://github.com/mawrkus/js-unit-testing-guide)
 
<!-- ######################## RESOURCES TDD ######################## --> 

!SLIDE tdd no-bullet-list resources

## Resources for this Unit

- <span class="icon-link"> [Headless testing with Jasmine, PhantomJS and Grunt](http://simonsmith.io/headless-testing-with-phantomjs-and-grunt/)
- <span class="icon-link"> [Let’s Code: Test-Driven JavaScript](http://www.letscodejavascript.com/)
- <span class="icon-link"> [Testing Your JavaScript with Jasmine](http://code.tutsplus.com/tutorials/testing-your-javascript-with-jasmine--net-21229)
- <span class="icon-link"> [Automated testing on the MEAN stack](http://www.techinsight.io/review/devops-and-automation/automating-unit-and-integration-testing-with-the-mean-stack/)


<!-- ######################## KATAS ######################## --> 

!SLIDE tdd no-bullet-list resources

## Katas

- <span class="icon-github"> [JS Kata Kit](https://github.com/mawrkus/js-kata-kit)
- <span class="icon-link"> [Code Kata | pernix](http://katas.softwarecraftsmanship.org/)
- <span class="icon-link"> [Code Kata | Dave Thomas](http://codekata.com/)
- <span class="icon-link"> [Project Euler](https://projecteuler.net/archives)
- <span class="icon-link"> [codekatas.org](http://www.codekatas.org/)
- <span class="icon-link"> [Javascript Katas](http://www.javascriptkata.com/)
- <span class="icon-link"> [Cyber Dojo](http://cyber-dojo.org/)
- <span class="icon-link"> [CodeWars](http://www.codewars.com/)

<!-- ######################## COVER Advanced JS ######################## --> 

!SLIDE coverSession concepts

<section class="logos">
  <div class="box">
    ![Javascript Logo](img/JavaScript-logo.png)
  <div>
</section>
 
## Advanced JS Training  
### Advanced **Javascript** concepts  


<!-- ######################## COVER Advanced JS ######################## --> 

!SLIDE coverSession jquery

<section class="logos">
  <div class="box">
    ![jQuery Logo](img/jquery-logo.gif)
  <div>
</section>
 
## Advanced JS Training  
### Using **jQuery**  


<!-- ######################## WHAT IS GRUNT ######################## --> 

!SLIDE what

> Grunt is a @@Task Runner@@ 

!SLIDE what

> Grunt is a @@Build Tool@@ 

!SLIDE what

> Grunt is a @@Command Line@@ 

!SLIDE what3

> Grunt is a (@@Javascript@@) @@Task Runner@@. Some of these tasks @@Build@@ stuff (transcompiling, deploy...)

!SLIDE what2

[Originally described](http://bocoup.com/weblog/introducing-grunt/) as:

> Grunt is a @@task-based@@ @@command line@@ @@build tool@@ for @@JavaScript@@ projects.

!SLIDE what2

and for Ruby developers...

> Grunt is like a javascript version of Ruby's [Rake](https://github.com/ruby/rake)

<!-- ######################## CLEAR IDEAS ######################## --> 

!SLIDE clear-ideas small no-bullet-list

## Clear Ideas about Grunt

- ?<span class="icon-building"></span>Grunt and Grunt-plugins are installed and managed via [npm](https://npmjs.org/), the [Node.js](http://nodejs.org/) package manager.
- ?<span class="icon-terminal"></span>To use _Grunt from comand line_ we have to install (globally) the [Grunt's CLI](http://gruntjs.com/using-the-cli) → `npm install -g grunt-cli`
- ?<span class="icon-terminal"></span>In _new projects_ we install Grunt and Grunt-plugins as node modules → `npm install --save-dev grunt grunt-contrib-jshint`
- ?<span class="icon-terminal"></span>In _existing Grunt projects_ we install Grunt and Grunt-plugins with → `npm install`

!SLIDE clear-ideas no-bullet-list

## Clear Ideas about Grunt

<!-- 
- ?<span class="icon-cogs"></span>The _grunt command line_ (globally) runs the grunt 'package' at `node_modules` (locally)
-->

- Main Files:
	- ?<span class="icon-file"></span>`@@@package.json@@@`: The Grunt runner and Grunt plugins used in the _Gruntfile.js_ are set as project dependencies in this file
	- ?<span class="icon-file"></span>`@@@Gruntfile.js@@@`: The tasks are defined/configured and grunt plugins are loaded in this file 
	
!SLIDE clear-ideas no-bullet-list smallcode

## Clear Ideas about Grunt

- <span class="icon-code"></span> [sample](http://browsenpm.org/package.json) [`package.json`](https://docs.npmjs.com/files/package.json):

```
{
  "name": "my-project-name",
  "version": "0.1.0",
  "@@devDependencies@@": {
    "grunt": "~0.4.5",
    "grunt-contrib-jshint": "~0.10.0",
    "grunt-contrib-nodeunit": "~0.4.1",
    "grunt-contrib-uglify": "~0.5.0"
  }
}
```

!SLIDE clear-ideas no-bullet-list smallcode smaller

## Clear Ideas about Grunt

- <span class="icon-code"></span> [sample](http://gruntjs.com/sample-gruntfile) `Gruntfile.js`:

```
module.exports = function(grunt) {
  grunt.@@initConfig@@({
    jshint: {
      files: ['Gruntfile.js', 'src/**/*.js', 'test/**/*.js'],
      options: {
        globals: {
          jQuery: true
        }
      }
    },
    watch: {
      files: ['<%= jshint.files %>'],
      tasks: ['jshint']
    }
  });
  grunt.@@loadNpmTasks@@('grunt-contrib-jshint');
  grunt.loadNpmTasks('grunt-contrib-watch');
  grunt.@@registerTask@@('default', ['jshint']);
};
```

!SLIDE clear-ideas no-bullet-list

## Clear Ideas about Grunt

- ?<span class="icon-briefcase"></span>**Productivity** →  with Grunt we can @@automate@@ everything in the _development environment_: minify, checking, testing, concatenate, uglify, transcompile, deploy...
- ?<span class="icon-globe"></span>**Community** →  more than [4000 grunt plugins](http://gruntjs.com/plugins) available  at NPM
- ?<span class="icon-code"></span>**Transcompilation** →  Ease the source-to-source compilation (Haml, Jade, Sass, LESS, Stylus, CoffeeScript, Dart, TypeScript, and more.) 

!SLIDE clear-ideas no-bullet-list not-alone

## Clear Ideas about Grunt

- Grunt is not alone in the task-manager/build-tools world:
	- ?<span class="devicons devicons-javascript_badge"></span> [grunt](http://gruntjs.com/), [cake](http://coffeescript.org/documentation/docs/cake.html), [broccoli](https://github.com/broccolijs/broccoli), [gulp](http://gulpjs.com/) and [more](https://gist.github.com/callumacrae/9231589)
	- ?<span class="devicons devicons-ruby"></span> [rake](https://github.com/ruby/rake), [capistrano](http://capistranorb.com/)
    - ?<span class="devicons devicons-python"></span> [paver](http://paver.github.io/paver/), [pynt](https://github.com/rags/pynt)
    - ?<span class="devicons devicons-java"></span> [ant](http://ant.apache.org/)
    - ?<span class="devicons devicons-php"></span> [phing](https://www.phing.info/) 

!SLIDE clear-ideas no-bullet-list

## Clear Ideas about Grunt

- ?<span class="icon-calendar"></span>[Released in @@March 2012@@](http://bocoup.com/weblog/introducing-grunt/) by [Ben Allman ](http://twitter.com/cowboy)

<!-- ######################## USING GRUNT ######################## --> 

!SLIDE smallcode no-bullet-list

## <span class="icon-keyboard"></span> Using Grunt in an existing project

- @@Steps@@:

	1. Change to the project's root directory.
	1. Install project dependencies with `npm install`
	1. Run Grunt with `grunt`

!SLIDE smallcode

## <span class="icon-keyboard"></span> Using Grunt in an existing project

```
$ git --version
$ node -v
$ npm -v
$ npm install -g grunt-cli
$ git clone https://github.com/juanmaguitar/grunt-workshop.git
$ cd grunt-workshop
$ npm install
$ grunt --version
$ grunt -h
$ grunt tasks
$ grunt compass
$ grunt shower
$ grunt serve

```

!SLIDE first-tasks smallcode showterm

## <span class="icon-keyboard"></span> Using Grunt in an existing project

[[+]](http://showterm.io/5dbd18bd9b0a2c10caf7c)

<iframe src="http://showterm.io/5dbd18bd9b0a2c10caf7c" width="700" height="380"></iframe>

<!-- ######################## FIRST TASKS ######################## --> 

!SLIDE smallcode no-bullet-list

## <span class="icon-keyboard"></span> Creating my first Grunt project

- @@Steps@@:

    1. Create a _project_ folder (and _src_ subfolder)
    1. Create a `package.json` interactively with `npm init`
    1. Create a simple `Gruntfile.js` (simple task, no plugin loading)
    1. Launch the task w/ Grunt

!SLIDE first-tasks smallcode

## <span class="icon-keyboard"></span> Creating my first Grunt project

	.
	├── Gruntfile.js
	├── package.json

```
$ mkdir project
$ cd project/
$ mkdir src
$ npm init
$ npm install @@--save-dev@@ grunt
$ vi Gruntfile.js
	module.exports = function(grunt) {
		@@@grunt.registerTask@@@('foo', function() {
		       grunt.log.writeln('foo is running...');
		});
	};
$ grunt foo
```

!SLIDE first-tasks smallcode showterm

## <span class="icon-keyboard"></span> Creating my first Grunt project 

[[+]](http://showterm.io/a177bf1bdcc8033709a69)

<iframe src="http://showterm.io/a177bf1bdcc8033709a69" width="700" height="380"></iframe>

!SLIDE smallcode no-bullet-list

## <span class="icon-keyboard"></span> Loading Grunt plugins

- @@Steps@@:

    1. Create a _project_ folder and _src_ subfolder
    1. Create a `package.json` interactively with `npm init`
    1. Create a `Gruntfile.js` (as defined [here](#gruntfile1))
    1. Launch the default task w/ Grunt

!SLIDE first-tasks smallcode

## <span class="icon-keyboard"></span> Loading Grunt plugins

	.
	├── Gruntfile.js
	├── package.json
	└── src
	    └── foo.js

```
$ mkdir project2
$ cd project2/
$ mkdir src
$ npm init
$ npm install --save-dev @@grunt grunt-contrib-jshint@@
```

!SLIDE #gruntfile1 first-tasks smallcode

## <span class="icon-keyboard"></span> Loading Grunt plugins

```
$ vi Gruntfile.js
	module.exports = function(grunt) {
	  @@@grunt.loadNpmTasks('grunt-contrib-jshint');@@@
	  grunt.initConfig({
	    @@@jshint@@@: {
	      options: {
	        curly: true,
	        eqeqeq: true
	      },
	      target1: ['Gruntfile.js', 'src/**/*.js']
	    }
	  });
	  @@@grunt.registerTask('default', ['jshint']);@@@
	};
$ grunt
```

!SLIDE first-tasks smallcode showterm

## <span class="icon-keyboard"></span> Loading Grunt plugins

[[+]](http://showterm.io/7a31032086f0cc49f3cec)

<iframe src="http://showterm.io/7a31032086f0cc49f3cec" width="700" height="380"></iframe>

<!-- ######################## CLEAR IDEAS GRUNTFILE.JS ######################## --> 

!SLIDE clear-ideas-gruntfile no-bullet-list smallcode

## Clear Ideas about Gruntfile.js

- <span class="icon-code"></span> [`grunt.initConfig({...})`](http://gruntjs.com/api/grunt.config#grunt.config.init) → [Configuration object](http://gruntjs.com/sample-gruntfile)
```
grunt.initConfig({
    pkg: grunt.file.readJSON('package.json')
    @@uglify@@: {
        @@options@@: {
            // the banner is inserted at the top of the output
            banner: '/*! <%= pkg.name %> <%= grunt.template.today("dd-mm-yyyy") %> */\n'
        },
        @@dist@@: {
            @@files@@: {
                'dist/<%= pkg.name %>.min.js': ['<%= concat.dist.dest %>']
            }
        }
    }
});
```

!SLIDE clear-ideas-gruntfile no-bullet-list smallcode

## Clear Ideas about Gruntfile.js

- <span class="icon-code"></span> Tasks are _configured_ via `initConfig` using @@task-named properties@@ as key of a configuration object that has:
	- @@[_targets_](http://gruntjs.com/configuring-tasks#task-configuration-and-targets)@@ →  groups of files/options (`dist`) →  `grunt uglify:dist`
	- @@[`options`](http://gruntjs.com/configuring-tasks#options)@@ →  custom setting overriding general settings (also _target_ devel)
	- @@[`files`](http://gruntjs.com/configuring-tasks#files)@@ →  src & dest files



!SLIDE clear-ideas-gruntfile no-bullet-list smallcode

## Clear Ideas about Gruntfile.js

- <span class="icon-code"></span>[`grunt.loadNpmTasks(...);`](http://gruntjs.com/api/grunt.task#grunt.task.loadnpmtasks) → Load the Grunt plugins.
	- `grunt.@@loadNpmTasks@@("grunt-contrib-uglify");`
<br/><br/>
- <span class="icon-code"></span>[`grunt.registerTask(...);`](http://gruntjs.com/api/grunt.task#grunt.task.registertask) → Aliases for already loaded/created tasks
    - `grunt.@@registerTask@@('default', ['jshint', 'qunit', 'concat', 'uglify']);`

<!-- ######################## FINAL PROJECT ######################## --> 

!SLIDE smallcode no-bullet-list

## <span class="icon-laptop"></span> Fully functional Grunt project

    ├── Gruntfile.js
    ├── dist
    ├── index.html
    ├── package.json
    ├── src
    │   ├── js
    │   │   ├── bar.js
    │   │   └── foo.js
    │   ├── scss
    │   │   └── styles.scss
    │   └── vendor
    │       └── jquery--1.3.js
    └── test
-├── barSpec.js
  -└── fooSpec.js
[Day 1] 
[Day 2] -!SLIDE smallcode no-bullet[Day 3] [Day 4] -list

-[Day 5] ## <span class="icon-laptop"></span> Fully functional Grunt pr[Day 6][Day 7]  [Day 8] [Day 9] [Day 10] oject

-- _Given the previous structure, create a Grunt project that provides the -llowing tasks:_
-
-span class="icon-terminal"></span> [`grunt concat`](https://github.com/gruntjs/grunt-contrib-concat) → concatenate all _.js_ files  at _src_ folder (using `;` as separator) in a npm-project-named _.js_ file placed at _dist_ folder
- <span class="icon-terminal"></span> [`grunt uglify`](https://github.com/gruntjs/grunt-contrib-uglify) → _uglify_  file generated by _concat_ task into a new _.min.js_ file placed at _dist_ folder
- <span class="icon-terminal"></span> [`grunt jshint`](https://github.com/gruntjs/grunt-contrib-jshint) → validate the js code (Gruntfile.js, _src/js_, _test_)

!SLIDE smallcode no-bullet-list

## <span class="icon-laptop"></span> Fully functional Grunt project

- <span class="icon-terminal"></span> [`grunt compass`](https://github.com/gruntjs/grunt-contrib-compass) → compile _src/styles.scss_ file into a _dist/styles.css_
- <span class="icon-terminal"></span> `grunt` or `grunt default`→ launches all previous tasks (jshint, concat, uglify, compass)

- <span class="icon-terminal"></span> [`grunt watch`](https://github.com/gruntjs/grunt-contrib-watch) → watch any change done at _Gruntfile.js_ or _src_ folder and launches _default_ task w/ new changes

!SLIDE smallcode no-bullet-list

## <span class="icon-laptop"></span> Fully functional Grunt project (extras)

- <span class="icon-terminal"></span> [`grunt jasmine`](https://github.com/gruntjs/grunt-contrib-jasmine) → launch all jasmine tests at _test_ folder (add it to _default_ task)
- <span class="icon-terminal"></span> [`grunt serve`](https://github.com/gruntjs/grunt-contrib-connect) → launch a local server at _localhost:8081_ (after launching _default_ task)

<!-- ######################## MORE INFO ######################## --> 

!SLIDE

##More info

- [Grunt | Official Site](http://gruntjs.com/)
- [Introducing Grunt | Boucup](http://bocoup.com/weblog/introducing-grunt/)
- [Get Up And Running With Grunt | Smashing Magazine](http://www.smashingmagazine.com/2013/10/29/get-up-running-grunt/)
- [Meet Grunt: The Build Tool for JavaScript | tutsplus](http://code.tutsplus.com/tutorials/meet-grunt-the-build-tool-for-javascript--net-24856)
- [JS Task Runners Comparison: Grunt vs Cake vs Gulp vs Broccoli](http://blog.cozycloud.cc/technic/2014/06/18/task-runners-comparison/)

