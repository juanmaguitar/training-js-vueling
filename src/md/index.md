# Training Advanced JS

by [JuanMa Garrido](#trainer)

<!-- ######################## COVER ######################## --> 

!SLIDE #MainCover no-bullet-list
 
## Advanced JS Training  

- TDD/BDD with Jasmine
- Javascript Advanced Concepts
- jQuery
- Frontend Architecture
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

1. <span class="icon-calendar"> TDD/BDD w/ Jasmine
1. <span class="icon-calendar"> Advanced JS concepts: Functions & Closures
1. <span class="icon-calendar"> Advanced JS concepts: Arrays & Functional Programming
1. <span class="icon-calendar"> Advanced JS concepts: Objects & Inheritance
1. <span class="icon-calendar"> jQuery
1. <span class="icon-calendar"> jQuery
1. <span class="icon-calendar"> Workflow Tools: NPM, Grunt, Bower & Yeoman
1. <span class="icon-calendar"> ES2015 (ES6)
1. <span class="icon-calendar"> ES2015 (ES6)
1. <span class="icon-calendar"> Frontend Arquitecture: Modular Arquitecture, Bundles & Asynchronous loading (w/ CommonJs & Webpack)

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

!SLIDE tdd

## Contents

- [Unit Testings](https://github.com/juanmaguitar/apuntes-javascript-avanzado/tree/master/markdown/unit_testings#1--unit-testings-pruebas-unitarias)
- [TDD y BDD](https://github.com/juanmaguitar/apuntes-javascript-avanzado/tree/master/markdown/unit_testings#2--tdd-y-bdd)
- [Testing Frameworks](https://github.com/juanmaguitar/apuntes-javascript-avanzado/tree/master/markdown/unit_testings#3--testing-frameworks) 
- [Testing Runners](https://github.com/juanmaguitar/apuntes-javascript-avanzado/tree/master/markdown/unit_testings#4--testing-runners) 

<!-- ######################## CONTENTS ######################## --> 

!SLIDE tdd

## Contents

- [Jasmine](http://addyosmani.github.com/backbone-fundamentals/#jasmine)
  - [Suites, Specs & Spies](http://addyosmani.github.com/backbone-fundamentals/#suites-specs-spies)
    - [Spies](http://jasmine.github.io/edge/introduction.html#section-Spies)
    - [Spy cheatsheet](http://tobyho.com/2011/12/15/jasmine-spy-cheatsheet/)
  - [beforeEach and afterEach()
](http://addyosmani.github.com/backbone-fundamentals/#beforeeach-and-aftereach)
  - [jQuery matchers and fixture loader](https://github.com/velesin/jasmine-jquery)
  - [Faking response AJAX](https://github.com/jasmine/jasmine-ajax)

<!-- ######################## RESOURCES TDD ######################## --> 

!SLIDE tdd kata

## <span class="icon-laptop"></span> KATA: Native function `myIndexOf()`

Implement the JavaScript native function `myIndexOf()`  

The `myIndexOf()` method returns the index within the calling String object of the first occurrence of the specified value, starting the search at _fromIndex_ , returns -1 if the value is not found. The indexOf method is case sensitive.

| Parameter | Description |
|-----------|-------------|
| `searchValue` | A string representing the value to search for. |
| `fromIndex` | The location within the calling string to start the search from. It can be any integer between 0 and the length of the string. The default value is 0. |


!SLIDE tdd kata

## <span class="icon-laptop"></span> KATA: Native function `myIndexOf()`

- [Instructions](https://github.com/juanmaguitar/katas-javascript/blob/master/indexOf/README.md)
- [Spec](https://github.com/juanmaguitar/katas-javascript/blob/master/indexOf/spec/indexOfSpec.js)
- [Src](https://github.com/juanmaguitar/katas-javascript/blob/master/indexOf/src/indexOf.js)
- [Test](http://juanmaguitar.github.io/katas-javascript/indexOf/SpecRunner.html)


!SLIDE tdd kata

## <span class="icon-laptop"></span> KATA: Poker

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

!SLIDE tdd kata

## <span class="icon-laptop"></span> KATA: Poker

- [Instructions](https://github.com/juanmaguitar/katas-javascript/blob/master/poker/README.md)
- [Spec](https://github.com/juanmaguitar/katas-javascript/blob/master/poker/spec/PokerHandSpec.js)
- [Src](https://github.com/juanmaguitar/katas-javascript/blob/master/poker/src/PokerHand.js)
- [Test](http://juanmaguitar.github.io/katas-javascript/poker/SpecRunner.html)


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

<!-- ######################## CONTENTS ######################## --> 

!SLIDE concepts

## Contents

- [Funciones](https://github.com/juanmaguitar/apuntes-javascript-intermedio/tree/master/markdown/funciones#funciones)
  - [Estructura y Parametros](https://github.com/juanmaguitar/apuntes-javascript-intermedio/tree/master/markdown/funciones#parametros)
  - [Funciones pre-definidas](https://github.com/juanmaguitar/apuntes-javascript-intermedio/tree/master/markdown/funciones#funciones-pre-definidas)
  - [Scope de las funciones](https://github.com/juanmaguitar/apuntes-javascript-intermedio/tree/master/markdown/funciones#Ámbito-scope-de-las-funciones)
  - [Funciones Callback](https://github.com/juanmaguitar/apuntes-javascript-intermedio/tree/master/markdown/funciones#funciones-callback)
  - [Closures](https://github.com/juanmaguitar/apuntes-javascript-intermedio/tree/master/markdown/funciones#closures)

- [Ejemplos de Closures](http://msdn.microsoft.com/en-us/magazine/ff696765.aspx)

!SLIDE clear-ideas no-bullet-list smallcode concepts

```
var x = 'Hello World';
function foo(){
    var x;
    alert( x );
    x = 'New Value';
    alert( x );
}
foo();
```

¿Qué devolveran los alert? ¿Por qué?

!SLIDE clear-ideas no-bullet-list smallcode concepts

```
function test() {
    foo();
    bar();
    var foo = function () {
        alert("this won't run!");
    }
    function bar() {
        alert("this will run!");
    }
}
test();

```

¿Qué devolverá la ejecución de test? ¿Por qué?

!SLIDE clear-ideas no-bullet-list smallcode concepts

```
var a = 1;
function f() {
    var a = 2;
    function n() {
        alert(a);
    }
    n();
}
f();

```

¿Qué nos mostrará este código en el alert()? ¿Por qué?

!SLIDE concepts

## <span class="icon-laptop"></span> Closures practice

Do the following exercises to practice closures [http://nathansjslessons.appspot.com/lesson?id=1000](http://nathansjslessons.appspot.com/lesson?id=1000)

<!-- ######################## CONTENTS ######################## --> 

!SLIDE concepts

## Contents

- [Arrays](https://github.com/juanmaguitar/apuntes-javascript-intermedio/tree/master/markdown/objetos#arrays)
- [Array as an Object](https://github.com/juanmaguitar/apuntes-javascript-intermedio/tree/master/markdown/objetos_globales#array)
  - [Array basic methods](https://github.com/juanmaguitar/apuntes-javascript-intermedio/tree/master/markdown/objetos_globales/arrays)
  - [Functional programming w/ array higher order functions](https://github.com/juanmaguitar/apuntes-javascript-intermedio/tree/master/markdown/objetos_globales/arrays#métodos-de-array-como-higher-order-functions)

!SLIDE clear-ideas no-bullet-list smallcode concepts

```
var mathy = function(x) {
    return function (y) {
        return function (z) {
            return (x / y) - z;
        }
    }
}
```

¿Cómo hariamos la operación `(4 / 3) - 2` con este código en una linea?

<!-- http://jtfmumm.com/blog/2013/08/31/nested-higher-order-functions-in-javascript/ -->

!SLIDE clear-ideas no-bullet-list smallcode concepts smaller

```
var superGreeter = function(greeting) {
    return function(place) {
        return function(nickname) {
            return function(name) {
                return greeting + ', ' + name + '! Welcome to ' + place + ', ' + nickname + '.';
            }
        }
    } 
};

superGreeter('Hey')('Berlin')('old pal')('Hans')
//'Hey, Hans! Welcome to Berlin, old pal.'

hiParisBuddyGreeter = superGreeter('Hi')('Paris')('buddy');
helloTokyoGreeter = superGreeter('Hello')('Tokyo');

hiParisBuddyGreeter('Franz')
//'Hi, Franz! Welcome to Paris, buddy.'
helloTokyoGreeter('friend')
//[Function]
helloTokyoGreeter('friend')('Yuki')
//'Hello, Yuki! Welcome to Tokyo, friend.'

```

<!-- http://jtfmumm.com/blog/2013/08/31/nested-higher-order-functions-in-javascript/ -->

!SLIDE concepts

## <span class="icon-github"></span> Functional programming workflow

Follow the steps on [this repository](https://github.com/juanmaguitar/functional-programming-sm-steps) to see the workflow of some functional programming code

!SLIDE concepts

## <span class="icon-laptop"></span> Functional programming exercises

Do the [exercises 1-27](http://reactivex.io/learnrx/) to practice functional programming

<!-- ######################## CONTENTS ######################## --> 

!SLIDE concepts

## Contents

- [Objetos](https://github.com/juanmaguitar/apuntes-javascript-intermedio/tree/master/markdown/objetos)
    - [Funciones constructoras](https://github.com/juanmaguitar/apuntes-javascript-intermedio/tree/master/markdown/objetos#funciones-constructoras)
    - [Trabajando con Objetos](https://github.com/juanmaguitar/apuntes-javascript-intermedio/tree/master/markdown/objetos#trabajando-con-objetos)

- [`prototype`](https://github.com/juanmaguitar/apuntes-javascript-avanzado/tree/master/markdown/prototype)

- [Herencia](https://github.com/juanmaguitar/apuntes-javascript-avanzado/tree/master/markdown/herencia)

- [El valor de `this`](https://github.com/juanmaguitar/apuntes-javascript-avanzado/tree/master/markdown/this)


!SLIDE clear-ideas no-bullet-list smallcode concepts

```
function F() {
    function C() {
        return this;
    }
    return C();
}
var o = new F();

```

¿El valor de this se referirá al objeto global o al objeto o?

!SLIDE clear-ideas no-bullet-list smallcode concepts

```
function C(){
    this.a = 1;
    return false;
}
console.log(typeof new C());

```

¿Cuál es el resultado de ejecutar este trozo de código?

!SLIDE clear-ideas no-bullet-list smallcode concepts

```
var add = function (x, y) {
    this.val = x + y;
},
obj = { val: 0 };
add.apply(obj, [2, 8]);
console.log(obj.val);

```

¿Qué devolverá el `console.log`? ¿A quien apunta `this` al llamar add ?

!SLIDE clear-ideas no-bullet-list smallcode concepts

```
var myObject = {
    func1:function() {
        console.log(this);
        varfunc2 = function() {
            console.log(this);
            varfunc3=function() {
                console.log(this);
            }();
        }();
    }
};
myObject.func1();
```

¿Qué devolverá la ejecución de `myObject.func1`? ¿Por qué?

!SLIDE clear-ideas no-bullet-list smallcode concepts

```
var myObject = {
    myProperty:'Icanseethelight',
    myMethod:function() {
        var that=this;
        var helperFunction =  function() {
            console.log(that.myProperty);
            console.log(this);
        }();
    }
}
myObject.myMethod();
```

¿Qué devolverá la ejecución de `myObject.myMethod`? ¿Por qué?

!SLIDE concepts

## <span class="icon-laptop"></span> KOAN Javascript-Jasmine

Do the following [KOAN](https://github.com/mrdavidlaing/javascript-koans) to practice javascript concepts

!SLIDE concepts

## <span class="icon-laptop"></span> KOAN Javascript-Jasmine

- [Koans solved](https://github.com/juanmaguitar/javascript-koans/tree/master/koans)
- [Tests passing](http://juanmaguitar.github.io/javascript-koans/KoansRunner.html)



<!-- ######################## COVER Advanced JS ######################## --> 

!SLIDE coverSession jquery

<section class="logos">
  <div class="box">
    ![jQuery Logo](img/jquery-logo.gif)
  <div>
</section>
 
## Advanced JS Training  
### Using **jQuery**  

!SLIDE jquery

## Contents

- [About jQuery](http://learn.jquery.com/about-jquery/)
  
- [Using jQuery Core](http://learn.jquery.com/using-jquery-core/)
    - [**Selecting Elements**](http://learn.jquery.com/using-jquery-core/selecting-elements/)
    - [Manipulating Elements](http://learn.jquery.com/using-jquery-core/manipulating-elements/)
    - [The jQuery Object](http://learn.jquery.com/using-jquery-core/jquery-object/)
    - [Traversing](http://learn.jquery.com/using-jquery-core/traversing/)
      - [Examples](http://jsfiddle.net/juanma/pp3h1hpo/)
    - [Utility Methods](http://learn.jquery.com/using-jquery-core/utility-methods/)
  

!SLIDE jquery

## Contents

- [Using jQuery Core](http://learn.jquery.com/using-jquery-core/)
  - [`$.each()`  and `.each()`](http://learn.jquery.com/using-jquery-core/iterating/)
- [Events](http://learn.jquery.com/events/)
  - [¿Cómo funcionan los eventos en el DOM?](https://github.com/juanmaguitar/apuntes-javascript-intermedio/tree/master/markdown/eventos#eventos)
  - [Capturando eventos](https://github.com/juanmaguitar/apuntes-javascript-intermedio/tree/master/markdown/eventos#capturando-eventos) 
  - [Deteniendo el flujo de los eventos](https://github.com/juanmaguitar/apuntes-javascript-intermedio/tree/master/markdown/eventos#deteniendo-el-flujo-de-los-eventos)
  - [Delegación de eventos](https://github.com/juanmaguitar/apuntes-javascript-intermedio/tree/master/markdown/eventos#delegación-de-eventos)
  - [Eventos con jQuery](https://github.com/juanmaguitar/apuntes-javascript-intermedio/tree/master/markdown/eventos#eventos-con-jquery) 
  
!SLIDE jquery

## <span class="icon-laptop"></span> jQuery Exercises

Do the following exercises and then let's share and comment the solutions

- [Hide/Show a Form](http://jsfiddle.net/juanma/kuLjg92s/)

!SLIDE jquery

## <span class="icon-laptop"></span> KOAN jQuery

Do the following [KOAN](https://github.com/juanmaguitar/jquery-koans) to assure the understanding of jquery concepts

<!-- ######################## RESOURCES TDD ######################## --> 

!SLIDE jquery no-bullet-list resources

## Resources for this Unit

- <span class="icon-link"> [jQuery Source Viewer](http://james.padolsey.com/jquery/#v=1.11.2&fn=jQuery.css)
- <span class="icon-link"> [jQuery Deconstructed](http://davestewart.io/resources/javascript/deconstructed/jquery/)
- <span class="icon-facetime-video"> [10 things I learned from the jQuery Source](http://www.paulirish.com/2010/10-things-i-learned-from-the-jquery-source/)
- <span class="icon-link"> [You might not need jQuery](http://youmightnotneedjquery.com/) 
- <span class="icon-link"> [jsPerf](https://jsperf.com/popular) 
- <span class="icon-link"> [canIUse](http://caniuse.com/) 

<!-- ######################## RESOURCES TDD ######################## --> 

!SLIDE coverSession workflow

<section class="logos">
  <div class="box">
    ![npm logo](img/npm.svg)
    ![grunt logo](img/grunt.png)
    ![bower logo](img/bower.png)
    ![yeoman logo](img/yeoman.png)
  <div>
</section>
 
## Advanced JS Training  
### **Workflow** Tools  

!SLIDE workflow starting

## <span class="icon-gears"></span> Before starting...

For this section you need to install at your machine the following:

1. [**Node.js**](https://nodejs.org) and [**NPM**](https://www.npmjs.com/) from [https://nodejs.org/en/download/](https://nodejs.org/en/download/) (the [installation of node.js](https://docs.npmjs.com/getting-started/installing-node) includes NPM)  
2. [**Git**](http://git-scm.com/) from [http://git-scm.com/downloads](http://git-scm.com/downloads) <a class="icon-windows ml-xl" href="http://git-for-windows.github.io/"></a> <a class="icon icon-warning-sign ml-m" href="https://github.com/bower/bower#windows-users"></a>   
3. To use _[Grunt](http://gruntjs.com/), [Bower](http://bower.io/) and [Yeoman](http://yeoman.io/) from comand line_ we have to install them globally → `npm install -g yo bower grunt-cli`

!SLIDE workflow contents

## Contents

- [NPM](https://www.npmjs.com/)
  - [What is NPM?](https://docs.npmjs.com/getting-started/what-is-npm)
  - [Node modules](http://book.mixu.net/node/ch8.html) <a class="icon-facetime-video" href="https://docs.npmjs.com/getting-started/creating-node-modules"></a>
  - [Utilising Node.js and npm for front-end development workflow](http://jsforallof.us/2015/02/12/utilising-node-and-npm-for-front-end-development-workflow/)

- [Grunt | Official Site](http://gruntjs.com/)
  - [Configuring tasks](http://gruntjs.com/configuring-tasks)
  - [Creating tasks](http://gruntjs.com/creating-tasks) 
  
<!-- ######################## USING GRUNT ######################## --> 

!SLIDE smallcode no-bullet-list workflow

## <span class="icon-keyboard"></span> Using Grunt in an existing project

- @@Steps@@:

  1. Change to the project's root directory.
  1. Install project dependencies with `npm install`
  1. Run Grunt with `grunt`

!SLIDE smallcode workflow

## <span class="icon-keyboard"></span> Using Grunt in an existing project

```
$ git --version
$ node -v
$ npm -v
$ npm install -g grunt-cli
$ git clone git@github.com:juanmaguitar/training-js-vueling.git
$ cd training-js-vueling
$ npm install
$ grunt --version
$ grunt -h
$ grunt tasks
$ grunt compass
$ grunt shower
$ grunt serve

```

!SLIDE first-tasks smallcode showterm workflow

## <span class="icon-keyboard"></span> Using Grunt in an existing project

[[+]](http://showterm.io/96af3794234bd10f75b67)

<iframe src="http://showterm.io/96af3794234bd10f75b67" width="700" height="380"></iframe>

<!-- ######################## FIRST TASKS ######################## --> 

!SLIDE smallcode no-bullet-list workflow

## <span class="icon-keyboard"></span> Creating my first Grunt project

- @@Steps@@:

    1. Create a _project_ folder (and _src_ subfolder)
    1. Create a `package.json` interactively with `npm init`
    1. Create a simple `Gruntfile.js` (simple task, no plugin loading)
    1. Launch the task w/ Grunt

!SLIDE first-tasks smallcode workflow

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

!SLIDE first-tasks smallcode showterm workflow

## <span class="icon-keyboard"></span> Creating my first Grunt project 

[[+]](http://showterm.io/a177bf1bdcc8033709a69)

<iframe src="http://showterm.io/a177bf1bdcc8033709a69" width="700" height="380"></iframe>

<!-- ######################## CLEAR IDEAS ######################## --> 

!SLIDE clear-ideas small no-bullet-list workflow

## Clear Ideas about Grunt

- <span class="icon-building"></span>Grunt and Grunt-plugins are installed and managed via [npm](https://npmjs.org/), the [Node.js](http://nodejs.org/) package manager.
- <span class="icon-terminal"></span>To use _Grunt from comand line_ we have to install (globally) the [Grunt's CLI](http://gruntjs.com/using-the-cli) → `npm install -g grunt-cli`
- <span class="icon-terminal"></span>In _new projects_ we install Grunt and Grunt-plugins as node modules → `npm install --save-dev grunt grunt-contrib-jshint`
- <span class="icon-terminal"></span>In _existing Grunt projects_ we install Grunt and Grunt-plugins with → `npm install`

!SLIDE clear-ideas no-bullet-list workflow

## Clear Ideas about Grunt

<!-- 
- <span class="icon-cogs"></span>The _grunt command line_ (globally) runs the grunt 'package' at `node_modules` (locally)
-->

- Main Files:
  - <span class="icon-file"></span>`@@@package.json@@@`: The Grunt runner and Grunt plugins used in the _Gruntfile.js_ are set as project dependencies in this file
  - <span class="icon-file"></span>`@@@Gruntfile.js@@@`: The tasks are defined/configured and grunt plugins are loaded in this file 
  
!SLIDE clear-ideas no-bullet-list smallcode workflow
 
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

!SLIDE clear-ideas no-bullet-list smallcode smaller workflow

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

!SLIDE smallcode no-bullet-list workflow

## <span class="icon-keyboard"></span> Loading Grunt plugins

- @@Steps@@:

    1. Create a _project_ folder and _src_ subfolder
    1. Create a `package.json` interactively with `npm init`
    1. Install the grunt plugins (`grunt` & `grunt-contrib-jshint`)
    1. Create a `Gruntfile.js` (as defined [here](#gruntfile1))
    1. Launch the default task w/ Grunt

!SLIDE first-tasks smallcode  workflow

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

!SLIDE #gruntfile1 first-tasks smallcode  workflow

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

!SLIDE first-tasks smallcode showterm  workflow

## <span class="icon-keyboard"></span> Loading Grunt plugins

[[+]](http://showterm.io/7a31032086f0cc49f3cec)

<iframe src="http://showterm.io/7a31032086f0cc49f3cec" width="700" height="380"></iframe>

<!-- ######################## CLEAR IDEAS GRUNTFILE.JS ######################## --> 

!SLIDE clear-ideas-gruntfile no-bullet-list smallcode  workflow

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

!SLIDE clear-ideas-gruntfile no-bullet-list smallcode  workflow

## Clear Ideas about Gruntfile.js

- <span class="icon-code"></span> Tasks are _configured_ via `initConfig` using @@task-named properties@@ as key of a configuration object that has:
  - @@[_targets_](http://gruntjs.com/configuring-tasks#task-configuration-and-targets)@@ →  groups of files/options (`dist`) →  `grunt uglify:dist`
  - @@[`options`](http://gruntjs.com/configuring-tasks#options)@@ →  custom setting overriding general settings (also _target_ devel)
  - @@[`files`](http://gruntjs.com/configuring-tasks#files)@@ →  src & dest files



!SLIDE clear-ideas-gruntfile no-bullet-list smallcode  workflow

## Clear Ideas about Gruntfile.js

- <span class="icon-code"></span>[`grunt.loadNpmTasks(...);`](http://gruntjs.com/api/grunt.task#grunt.task.loadnpmtasks) → Load the Grunt plugins.
  - `grunt.@@loadNpmTasks@@("grunt-contrib-uglify");`
<br/><br/>
- <span class="icon-code"></span>[`grunt.registerTask(...);`](http://gruntjs.com/api/grunt.task#grunt.task.registertask) → Aliases for already loaded/created tasks
    - `grunt.@@registerTask@@('default', ['jshint', 'qunit', 'concat', 'uglify']);`



!SLIDE workflow contents

## Contents

- [Bower](http://bower.io/)
  - [`bower.json`](https://github.com/bower/spec/blob/master/json.md)
  - [bower configuration](https://github.com/bower/spec/blob/master/config.md)

- [Yeoman](http://yeoman.io/)
  - [Generators](http://yeoman.io/generators/)

<!-- ######################## FINAL PROJECT ######################## --> 

!SLIDE smallcode no-bullet-list  workflow

## <span class="icon-laptop"></span> Fully functional Grunt project

    ├── Gruntfile.js
    ├── dist
    ├── index.html
    ├── package.json
    ├── src
    │   ├── js
    │   │   ├── bar.js
    │   │   └── foo.js
    │   ├── scss
    │   │   └── styles.scss
    │   └── vendor
    │       └── jquery-2.1.3.js
    └── test
      ├── barSpec.js
      └── fooSpec.js

!SLIDE smallcode no-bullet-list workflow exercise

## <span class="icon-laptop"></span> Fully functional Grunt project

- _Given the previous structure, create a Grunt project that provides the following tasks:_

- <span class="devicons devicons-grunt icon-"></span> [`grunt concat`](https://github.com/gruntjs/grunt-contrib-concat) → concatenate all _.js_ files  at _src_ folder (using `;` as separator) in a npm-project-named _.js_ file placed at _dist_ folder
- <span class="devicons devicons-grunt icon-"></span> [`grunt uglify`](https://github.com/gruntjs/grunt-contrib-uglify) → _uglify_  file generated by _concat_ task into a new _.min.js_ file placed at _dist_ folder
- <span class="devicons devicons-grunt icon-"></span> [`grunt jshint`](https://github.com/gruntjs/grunt-contrib-jshint) → validate the js code (Gruntfile.js, _src/js_, _test_)

!SLIDE smallcode no-bullet-list  workflow exercise

## <span class="icon-laptop"></span> Fully functional Grunt project

- <span class="devicons devicons-grunt icon-"></span> [`grunt compass`](https://github.com/gruntjs/grunt-contrib-compass) → compile _src/styles.scss_ file into a _dist/styles.css_
- <span class="devicons devicons-grunt icon-"></span> `grunt` or `grunt default`→ launches all previous tasks (jshint, concat, uglify, compass)
- <span class="devicons devicons-grunt icon-"></span> [`grunt watch`](https://github.com/gruntjs/grunt-contrib-watch) → watch any change done at _Gruntfile.js_ or _src_ folder and launches _default_ task w/ new changes

!SLIDE smallcode no-bullet-list  workflow exercise

## <span class="icon-laptop"></span> Fully functional Grunt project (extras)

- <span class="devicons devicons-grunt icon-"></span> [`grunt jasmine`](https://github.com/gruntjs/grunt-contrib-jasmine) → launch all jasmine tests at _test_ folder (add it to _default_ task)
- <span class="devicons devicons-grunt icon-"></span> [`grunt serve`](https://github.com/gruntjs/grunt-contrib-connect) → launch a local server at _localhost:8081_ (after launching _default_ task)

!SLIDE smallcode no-bullet-list  workflow exercise

## <span class="icon-laptop"></span> Fully functional Grunt project (extras)

_Also, prepare the project w/ the following:_

- <span class="devicons devicons-npm icon-"></span> `package.json` → add here all grunt dependencies (you can test if this works by removing the `node_modules` folder, launching `npm install` and test that all grunt tasks work properly )
- <span class="devicons devicons-bower icon-"></span> `bower.json` → remove the folder `vendor` and add jquery as a bower dependency. Modify the grunt tasks if necessary.
- <span class="devicons devicons-grunt icon-"></span> [`livereload`](http://seanamarasinghe.com/developer/grunt-watch-livereload-with-javascript-sass/) → prepare your _watch_ grunt tasks to reload the page in the browser automatically when detect changes


<!-- ######################## MORE INFO ######################## --> 


<!-- ######################## RESOURCES TDD ######################## --> 

!SLIDE workflow resources

## Resources for this Unit  
  
- [Introducing Grunt | Boucup](http://bocoup.com/weblog/introducing-grunt/)
- [Get Up And Running With Grunt | Smashing Magazine](http://www.smashingmagazine.com/2013/10/29/get-up-running-grunt/)
- [Meet Grunt: The Build Tool for JavaScript | tutsplus](http://code.tutsplus.com/tutorials/meet-grunt-the-build-tool-for-javascript--net-24856)
- [JS Task Runners Comparison: Grunt vs Cake vs Gulp vs Broccoli](http://blog.cozycloud.cc/technic/2014/06/18/task-runners-comparison/)

<!-- ######################## COVER ######################## --> 

!SLIDE coverSession es2015

<section class="logos">
  <div class="box">
    ![es2015 logo](img/es-2015.jpg)
  <div>
</section>
 
## Advanced JS Training  
### **ES2015** 
#### (former ES6)

!SLIDE es2015 history

- [TC39](http://ecma-international.org/memento/TC39.htm)
  - ECMA Technical Committee evolving JavaScript
  - Members: companies (all major browser vendors, ...)

- [ECMAScript](http://www.ecmascript.org/index.php)
  + The name of the language standardized by ECMA
  + ECMAScript 1 => 1997
  + ECMAScript 2 => 1998
  + ECMAScript 3 => 1999
  + ~~ECMAScript 4~~ => abandoned
  + ECMAScript 5 => 2009
  + ~~ECMAScript 6~~ => rebaptised ECMAScript 2015

- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript?redirectlocale=en-US&redirectslug=JavaScript)
  - Colloquially: the language
  - Formally: one implementation of ECMAScript


!SLIDE es2015

## ES2015 Overview

- Approved in @@June 2015@@, 1st update since 2009!
- A lot of @@new syntax features@@
- @@Backwards compatible@@ (mostly syntactic sugar that can be desugared to older versions of the language)
- Current support: [Kangax compatibility table](http://kangax.github.io/compat-table/es6/)
- We can use them @@right now@@ with a source to source compiler (transpiler) : see [Babel](https://babeljs.io/), [Traceur](https://github.com/google/traceur-compiler) and [TypeScript](http://www.typescriptlang.org/)

!SLIDE es2015

## [Arrow Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions)

- Shorter syntax using `=>`
- Always anonymous
- Lexically bind `this`
- Really useful for event handlers and callbacks
- Really neat when using functional programming

!SLIDE es2015

## Arrow Functions

- [ECMAScript 6 equivalents in ES5: Arrow Functions](https://github.com/addyosmani/es6-equivalents-in-es5#arrow-functions)  
- [ES6 In Depth: Arrow functions](https://hacks.mozilla.org/2015/06/es6-in-depth-arrow-functions/)  
- [Understanding ECMAScript 6 arrow functions](https://www.nczonline.net/blog/2013/09/10/understanding-ecmascript-6-arrow-functions/)

!SLIDE es2015 smallcode

## Arrow Functions

Four versions:

```javascript
    (arg1, arg2, ...) => expr
    (arg1, arg2, ...) => { stmt1; stmt2; ... }
    singleArg => expr
    singleArg => { stmt1; stmt2; ... }
```

!SLIDE es2015 smallcode

## Arrow Functions

BEFORE (ES5)

```javascript
var self = this;
this.element.addEventListener('click', function(event) {
  self.registerClick(event.target.id);
});
```

!SLIDE es2015 smallcode

## Arrow Functions

AFTER (ES2015)

```javascript
this.element.addEventListener('click', event => {
  this.registerClick(event.target.id);
});
```

!SLIDE es2015 smallcode

## Arrow Functions

BEFORE (ES5)

```javascript
[1,3,4,5,6,7].filter(function(n) { return n % 2 } )
  .map(function(n, i) { return n + i } ); 
// [1, 4, 7, 10]
```

!SLIDE es2015 smallcode

## Arrow Functions

AFTER (ES2015)

```javascript
[1,2,3,4,5,6,7].filter(n => n % 2).map((n, i) => n+i);
```

!SLIDE es2015

## <span class="icon-laptop"></span> ES6 Katas: Arrow Functions

Do the following katas to assure the understanding of arrow functions
- [basics](http://tddbin.com/#?kata=es6/language/arrow-functions/basics)
- [function binding](http://tddbin.com/#?kata=es6/language/arrow-functions/binding)

!SLIDE es2015

## [Block Scope](https://hacks.mozilla.org/2015/07/es6-in-depth-let-and-const/)

- Two new types of _"variables"_: [`let`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/let) and [`const`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/const)
- Both with block scope

!SLIDE es2015

## Block Scope

- [ECMAScript 6 equivalents in ES5: Block Scoping Functions](https://github.com/addyosmani/es6-equivalents-in-es5#block-scoping-functions)  
- [ECMAScript 6 and Block Scope](http://ariya.ofilabs.com/2013/05/es6-and-block-scope.html)


!SLIDE es2015 smallcode

## Block Scope

BEFORE (ES5)

```javascript
var arr = [1, 2, 3];
for (var i = 0; i < arr.length; i++) {
  // i from 0 to 2
}
i; // 3
{
  var TEMPERATURE = 32;
  TEMPERATURE = 16;
  TEMPERATURE // 16
}
TEMPERATURE; // 16
```

!SLIDE es2015 smallcode

## Block Scope

AFTER (ES2015)

```javascript
var arr = [1, 2, 3];
for (let i = 0; i < arr.length; i++) {
  // i from 0 to 2
}
i; // ReferenceError: i is not defined!
{
  const TEMPERATURE = 32;
  TEMPERATURE = 16;
  TEMPERATURE; // 32
}
TEMPERATURE; // ReferenceError: TEMPERATURE is not defined!
```

!SLIDE es2015

## <span class="icon-laptop"></span> ES6 Katas: Block Scope

Do the following katas to assure the understanding of Block Scope
- [`let` declaration](http://tddbin.com/#?kata=es6/language/block-scoping/let)
- [`const` declaration](http://tddbin.com/#?kata=es6/language/block-scoping/const)

!SLIDE es2015 smallcode

## [Template Strings](https://hacks.mozilla.org/2015/05/es6-in-depth-template-strings-2/)

- Enclosed by back-ticks @@` `` ` @@
- Multi-line support
- Can contain placeholders `${ expression }`

```javascript
`string text`

`string text line 1
 string text line 2`

`string text ${expression} string text`
```

!SLIDE es2015 smallcode

## Template Strings

BEFORE (ES5)

```javascript
var name = "juanma";
var getSuitableDrink = function(who) {
  return who === 'juanma' ? 'beer' : 'cocktail'
};

console.log( 'Hello, '+name+'!\nFancy a '+getSuitableDrink()+'?' );

// Hello, juanma!
// Fancy a beer?
```

!SLIDE es2015 smallcode

## Template Strings

AFTER (ES2015)

```javascript
var name = "juanma";
var getSuitableDrink = function(who) {
  return who === 'juanma' ? 'beer' : 'cocktail'
};

console.log( `Hello, ${ name }!
  Fancy a ${ getSuitableDrink() }?` );
```


!SLIDE es2015

## Template Strings

- [Template Strings](https://hacks.mozilla.org/2015/05/es6-in-depth-template-strings-2/)
- [ECMAScript 6 equivalents in ES5: Template Literals](https://github.com/addyosmani/es6-equivalents-in-es5#template-literals)  

!SLIDE es2015

## <span class="icon-laptop"></span> ES6 Katas: Template Strings

Do the following katas to assure the understanding of template strings
- [basics](http://tddbin.com/#?kata=es6/language/template-strings/basics)
- [multiline](http://tddbin.com/#?kata=es6/language/template-strings/multiline)
- [tagged template strings](http://tddbin.com/#?kata=es6/language/template-strings/tagged)
- [`raw` property](http://tddbin.com/#?kata=es6/language/template-strings/raw)

!SLIDE es2015 smallcode

## [Enhanced Object Literals](https://github.com/lukehoban/es6features#enhanced-object-literals)

- Shorthand property names
- Shorthand methods names
- Dynamic property names
- [_getter_](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/get) and [_setter_](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Functions/set)


!SLIDE es2015 smallcode

## Enhanced Object Literals

```javascript
var a = "foo",
    b = 42,
    c = {};

function myMethod() {
    console.log('ooOoh!');
}

// Shorthand property names
@@var o = { a, b, c };@@

// Shorthand method name and dynamic property name
var o2 = {
  myMethod,
  @@['myPropertyNum'+b]: 'bar'@@
}
```

!SLIDE es2015 smallcode

## Enhanced Object Literals

```javascript
var messages = {
  @@get latest ()@@ {
    if (this.log.length == 0) return undefined;
    return this.log[this.log.length - 1]
  },
  @@set current (str)@@ {
    this.log[this.log.length] = str;
  },
  log: []
}

messages.current = "hey!";
messages.latest // hey!
```

!SLIDE es2015

## <span class="icon-laptop"></span> ES6 Katas: Enhanced Object Literals

Do the following katas to assure the understanding of Enhanced Object Literals
- [basics](http://tddbin.com/#?kata=es6/language/object-literal/basics)
- [computed properties](http://tddbin.com/#?kata=es6/language/object-literal/computed-properties)
- [getter](http://tddbin.com/#?kata=es6/language/object-literal/getter)
- [setter](http://tddbin.com/#?kata=es6/language/object-literal/setter)

!SLIDE es2015 smallcode

## [Default parameters](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Default_parameters)

```javascript
function f(x, y=12) {
  // y is 12 if not passed (or passed as undefined)
  return x + y;
}

f(3) === 15;
f(3, undefined) === 15;
```

!SLIDE es2015

## <span class="icon-laptop"></span> ES6 Katas: Default parameters

Do the following katas to assure the understanding of Default parameters
- [basic](http://tddbin.com/#?kata=es6/language/default-parameters/basics)
 


!SLIDE es2015 smallcode

## [Destructuring Assignment](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment)

- Array destructuring
- Object destructuring

!SLIDE es2015 smallcode

## Destructuring Assignment

```javascript
var [first, second, third, , fifth = 5] = [1, 2];
first // 1
second // 2
third // undefined
fifth // 5

[second, first] = [first, second] // swap values
first // 2
second // 1
```

!SLIDE es2015 smallcode

## Destructuring Assignment

```javascript
var customer = {
  name: 'John',
  surname: 'Doe',
  dateOfBirth: {
    year: 1988
  }
};

var {name, surname, dateOfBirth: {year}, children} = customer;
name // 'John'
surname // 'Doe'
year // 1988
children // undefined
```


!SLIDE es2015

## <span class="icon-laptop"></span> ES6 Katas: Destructuring Assignment

Do the following katas to assure the understanding of Destructuring Assignment
- [array](http://tddbin.com/#?kata=es6/language/destructuring/array)
- [string](http://tddbin.com/#?kata=es6/language/destructuring/string)
- [object](http://tddbin.com/#?kata=es6/language/destructuring/object)
- [defaults](http://tddbin.com/#?kata=es6/language/destructuring/defaults)
- [parameters](http://tddbin.com/#?kata=es6/language/destructuring/parameters)
- [assign](http://tddbin.com/#?kata=es6/language/destructuring/rename)

!SLIDE es2015 resources smallcode

## [Rest operator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/rest_parameters)

- Bind trailing parameters to an array using `...`
- Replaces the need for @@arguments@@

```javascript
function multiply(multiplier, ...numbers) {
  return numbers.map(n => multiplier * n);
}

var arr = multiply(2, 1, 2, 3);
console.log(arr); // [2, 4, 6]
```

!SLIDE es2015

## <span class="icon-laptop"></span> ES6 Katas: Rest operator

Do the following katas to assure the understanding of Rest operator
- [as parameter](http://tddbin.com/#?kata=es6/language/rest/as-parameter)
- [with destructuring](http://tddbin.com/#?kata=es6/language/rest/with-destructuring)



!SLIDE es2015 resources smallcode

## [Spread operator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_operator)

- For **function calls**: allows an expression to be expanded in places where multiple arguments are expected
- For **array litterals**: allows an expression to be expanded in places where multiple elements are expected

```javascript
function f(x, y, z) {
  return x + y + z;
}

var arr = [1, 2, 3];
f(...arr) === 6; // true

[0, ...arr, 4, 5, 6, 7]; // [0, 1, 2, 3, 4, 5, 6, 7]
```

!SLIDE es2015

## <span class="icon-laptop"></span> ES6 Katas: Spread operator

Do the following katas to assure the understanding of Spread operator
- [with arays](http://tddbin.com/#?kata=es6/language/spread/with-arrays)
- [with strings](http://tddbin.com/#?kata=es6/language/spread/with-strings)


!SLIDE es2015 resources smallcode

## [`Set`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Set)

- New **data structure** for handling collections
- Store unique values of any type, whether primitive values or object references
- Efficient and clean

```javascript
var s = new Set();
s.add("hello").add("goodbye").add("hello");
s.size === 2;
s.has("hello") === true;
s.delete("hello");
s.has("hello") === false;
```

!SLIDE es2015

## <span class="icon-laptop"></span> ES6 Katas: Set

Do the following katas to assure the understanding of Set
- [basics](http://tddbin.com/#?kata=es6/language/set/basics)
- [`set.add()`](http://tddbin.com/#?kata=es6/language/set/add)
- [`set.delete()`](http://tddbin.com/#?kata=es6/language/set/delete)
- [the API](http://tddbin.com/#?kata=es6/language/set/api)
- [`set.clear()`](http://tddbin.com/#?kata=es6/language/set/clear)

!SLIDE es2015 resources smallcode

## [`Map`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map)

- New **data structure** for handling collections
- Simple key/value map
- Any value (both objects and primitive values) may be used as either a key or a value
- Efficient and clean

!SLIDE es2015 resources smallcode

## Map

```javascript
var m = new Map();
m.set("hello", 42);
m.get("hello") === 42;

var s = { n:4 };
m.set(s, 34);
m.get(s) === 34;
```

!SLIDE es2015 resources smallcode smaller

## Map

```javascript
var myMap = new Map();

var keyString = "a string",
    keyObj = {},
    keyFunc = function () {};

// setting the values
myMap.set(keyString, "value associated with 'a string'");
myMap.set(keyObj, "value associated with keyObj");
myMap.set(keyFunc, "value associated with keyFunc");

myMap.size; // 3

// getting the values
myMap.get(keyString);    // "value associated with 'a string'"
myMap.get(keyObj);       // "value associated with keyObj"
myMap.get(keyFunc);      // "value associated with keyFunc"

myMap.get("a string");   // "value associated with 'a string'"
                         // because keyString === 'a string'
myMap.get({});           // undefined, because keyObj !== {}
myMap.get(function() {}) // undefined, because keyFunc !== function () {}
```

!SLIDE es2015

## <span class="icon-laptop"></span> ES6 Katas: Map

Do the following katas to assure the understanding of Map
- [basics](http://tddbin.com/#?kata=es6/language/map/basics)
- [`map.get()`](http://tddbin.com/#?kata=es6/language/map/get)
- [`map.set()`](http://tddbin.com/#?kata=es6/language/map/set)
- [initalize](http://tddbin.com/#?kata=es6/language/map/initialize)
- [`map.has()](http://tddbin.com/#?kata=es6/language/map/has)

!SLIDE es2015

## [Clases](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)

- Basic support
- `class` and [`extends`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes/extends) keywords
- [`constructor`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes/constructor) definition
- [`static`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes/static) method definitions

!SLIDE es2015 resources smallcode smaller

## Classes

BEFORE

```javascript
var Shape = function( id, x, y ) {
  this.id = id;
  this.x = x;
  this.y = y;
};
Shape.prototype.toString = function( x, y ) {
  return "Shape(" + this.id + ")"
};

var Rectangle = function( id, x, y, width, height ) {
  Shape.call( this, id, x, y );
};
Rectangle.prototype = Object.create(Shape.prototype);
Rectangle.prototype.constructor = Rectangle;
Rectangle.prototype.toString = function() {
  return "Rectangle > " + Shape.prototype.toString.call( this );
};
```

!SLIDE es2015 resources smallcode smaller

## Classes

BEFORE

```javascript
class Shape {
  constructor (id, x, y) {
    this.id = id;
    this.x = x;
    this.y = y;
    // or Object.assign(this, {id, x, y});
  }
  toString () {
    return `Shape(${this.id})`
  }
}

class Rectangle extends Shape {
  constructor (id, x, y, width, height) {
    super(id, x, y)
  }
  toString () {
    return "Rectangle > " + super.toString()
  }
}
```



!SLIDE es2015

## Classes

- [Examples Classes](https://googlechrome.github.io/samples/classes-es6/index.html)
- [ES6 | Classes and Inheritance](https://medium.com/ecmascript-2015/es6-classes-and-inheritance-607804080906#.yly3wqbsq)  

!SLIDE es2015

## <span class="icon-laptop"></span> ES6 Katas: Classes

Do the following katas to assure the understanding of Classes
- [creation](http://tddbin.com/#?kata=es6/language/class/creation)
- [accessors](http://tddbin.com/#?kata=es6/language/class/accessors)
- [static](http://tddbin.com/#?kata=es6/language/class/static)
- [extends](http://tddbin.com/#?kata=es6/language/class/extends)
- [more extends](http://tddbin.com/#?kata=es6/language/class/more-extends)
- [super in method](http://tddbin.com/#?kata=es6/language/class/super-in-method)
- [super in constructor](http://tddbin.com/#?kata=es6/language/class/super-in-constructor)

!SLIDE es2015

## [Modules](https://hacks.mozilla.org/2015/08/es6-in-depth-modules/)

- Native modules, alternative to [CommonJS](http://www.commonjs.org/) and [AMD](http://requirejs.org/docs/whyamd.html)
- Modules can export multiple values (unlike the others)
- Statically analyzed to load dependencies
- Dependencies are loaded asynchronously, but can be optimized with a module bundler ([rollup](http://rollupjs.org/) or [webpack](https://webpack.github.io/))

!SLIDE es2015 resources smallcode

## Modules

```javascript
// -------- jquery.js --------
export default function jQuery() {
  /* code */
}

// -------- code.js --------
import $ from 'jquery';
$('body').addClass('yay');

```

!SLIDE es2015 resources smallcode smaller

## Modules

```javascript
// --------- http.js --------
export function get(url) {
  /* code */
}

export function post(url, body) {
  /* code */
}

// -------- code.js --------
import { get, post } from 'http';
import { TIMEOUT as HTTP_TIMEOUT } from 'http';
import * as http from 'http';

get('/my/url').then(function(result) {
  /* code */
});

HTTP_TIMEOUT; // 1000;
http.post('/my/url', 'body');
```


!SLIDE es2015

## Modules

- [Writing Modular JavaScript With AMD, CommonJS & ES Harmony](http://addyosmani.com/writing-modular-js/)

!SLIDE es2015

## <span class="icon-laptop"></span> ES6 Katas: Modules

Do the following katas to assure the understanding of Modules
- [`import` statement](http://tddbin.com/#?kata=es6/language/modules/import)


!SLIDE es2015

## [Modules](https://hacks.mozilla.org/2015/08/es6-in-depth-modules/)

- Native modules, alternative to [CommonJS](http://www.commonjs.org/) and [AMD](http://requirejs.org/docs/whyamd.html)
- Modules can export multiple values (unlike the others)
- Statically analyzed to load dependencies
- Dependencies are loaded asynchronously, but can be optimized with a module bundler ([rollup](http://rollupjs.org/) or [webpack](https://webpack.github.io/))


!SLIDE es2015

## [Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array)

Array object extended with:

- New static methods: [`from()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/from), [`of()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/of)
- New instance methods: [`copyWithin()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/copyWithin), [`entries()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/entries) , [`fill()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/fill), [`find()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/find), [`findIndex()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/findIndex), [`keys()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/keys), [`values()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/values) 


!SLIDE es2015 resources smallcode

## Array

```javascript
Array.from(arguments) // [].slice.call(arguments);
Array.from({0: 'hello', 1: world, length: 2}); // ['hello', 'world']
Array.of(1, 2, 3) // [1, 2, 3]

[1, 2, 3, 4, 5].copyWithin(0, 3, 4) // [4, 2, 3, 4, 5]
[1, 2, 3].fill(4) // [4, 4, 4]
[4, 5, 8, 12].find(isPrime) // 5
[4, 5, 8, 12].findIndex(isPrime) // 2
[4, 5, 8, 12].keys() // iterator from 0 to 3
[4, 5, 8, 12].values() // iterator from 4 to 12
```

!SLIDE es2015

## <span class="icon-laptop"></span> ES6 Katas: Array

Do the following katas to assure the understanding of Array
- [`Array.from()`](http://tddbin.com/#?kata=es6/language/array-api/from)
- [`Array.of()`](http://tddbin.com/#?kata=es6/language/array-api/of) 
- [`[].fill()`](http://tddbin.com/#?kata=es6/language/array-api/fill) 
- [`[].find()`](http://tddbin.com/#?kata=es6/language/array-api/find) 
- [`[].findIndex()`](http://tddbin.com/#?kata=es6/language/array-api/findIndex)
- [`[].entries()`](http://tddbin.com/#?kata=es6/language/array-api/entries) 
- [`[].keys()`](http://tddbin.com/#?kata=es6/language/array-api/keys) 
- [`[].values()`](http://tddbin.com/#?kata=es6/language/array-api/values) 

!SLIDE es2015

## [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String)

String object extended with:

- New static methods: [`raw()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/raw)
- New instance methods: [`startsWith()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/startsWith), [`endsWith()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/endsWith), [`includes()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/includes), [`repeat()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/repeat), ...


!SLIDE es2015 resources smallcode

## String

```javascript
String.raw`Line 1\nLine 2\nLine 3` // 'Line 1\\nLine 2\\nLine 3'
'Hello world'.startsWith('Hello') // true
'Hello world'.endsWith('world') // true
'Hello world'.includes('orl') // true
'Hello world'.repeat(2) // 'Hello worldHello world'
```


!SLIDE es2015 resources

## Resources for this Unit  
  
- [Using Grunt & the ES6 Module Transpiler](http://www.thomasboyt.com/2013/06/21/es6-module-transpiler)
- [`grunt-es6-module-transpiler`](https://github.com/joefiorini/grunt-es6-module-transpiler)
- [ECMAScript 6 equivalents in ES5](https://github.com/addyosmani/es6-equivalents-in-es5)
- [ES6 In Depth](https://hacks.mozilla.org/category/es6-in-depth/)
- [ariya.ofilabs.com | ES6](http://ariya.ofilabs.com/tag/es6) 
- [ECMAScript 2015](https://medium.com/ecmascript-2015)
- [ES6 Katas](http://es6katas.org/)
- [Scratch JS (chrome plugin)](https://chrome.google.com/webstore/detail/scratch-js/alploljligeomonipppgaahpkenfnfkn)




!SLIDE no-bullet-list resources

## Final Resources

- <span class="icon-link"> [Awesome Javascript](https://github.com/sorrycc/awesome-javascript)


