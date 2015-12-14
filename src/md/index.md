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

## <span class="icon-keyboard"></span> KATA: Native function `myIndexOf()`

Implement the JavaScript native function `myIndexOf()`  

The `myIndexOf()` method returns the index within the calling String object of the first occurrence of the specified value, starting the search at _fromIndex_ , returns -1 if the value is not found. The indexOf method is case sensitive.

| Parameter | Description |
|-----------|-------------|
| `searchValue` | A string representing the value to search for. |
| `fromIndex` | The location within the calling string to start the search from. It can be any integer between 0 and the length of the string. The default value is 0. |


!SLIDE tdd kata

## <span class="icon-keyboard"></span> KATA: Native function `myIndexOf()`

- [Instructions](https://github.com/juanmaguitar/katas-javascript/blob/master/indexOf/README.md)
- [Spec](https://github.com/juanmaguitar/katas-javascript/blob/master/indexOf/spec/indexOfSpec.js)
- [Src](https://github.com/juanmaguitar/katas-javascript/blob/master/indexOf/src/indexOf.js)
- [Test](http://juanmaguitar.github.io/katas-javascript/indexOf/SpecRunner.html)


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

!SLIDE tdd kata

## <span class="icon-keyboard"></span> KATA: Poker

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

## <span class="icon-keyboard"></span> Closures practice

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

## <span class="icon-keyboard"></span> Functional programming exercises

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

## <span class="icon-keyboard"></span> KOAN Javascript-Jasmine

Do the following [KOAN](https://github.com/mrdavidlaing/javascript-koans) to practice javascript concepts

!SLIDE concepts

## <span class="icon-keyboard"></span> KOAN Javascript-Jasmine

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

## <span class="icon-keyboard"></span> jQuery Exercises

Do the following exercises and then let's share and comment the solutions

- [Hide/Show a Form](http://jsfiddle.net/juanma/kuLjg92s/)

!SLIDE jquery

## <span class="icon-keyboard"></span> KOAN jQuery

Do the following [KOAN](https://github.com/juanmaguitar/jquery-koans) to assure the undersanding of jquery concepts

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

!SLIDE workflow contents

## Contents

- [Bower](http://bower.io/)
  - [`bower.json`](https://github.com/bower/spec/blob/master/json.md)
  - [bower configuration](https://github.com/bower/spec/blob/master/config.md)

<!-- ######################## RESOURCES TDD ######################## --> 

!SLIDE workflow no-bullet-list resources

## Resources for this Unit

- [Introducing Grunt | Boucup](http://bocoup.com/weblog/introducing-grunt/)
- [Get Up And Running With Grunt | Smashing Magazine](http://www.smashingmagazine.com/2013/10/29/get-up-running-grunt/)
- [Meet Grunt: The Build Tool for JavaScript | tutsplus](http://code.tutsplus.com/tutorials/meet-grunt-the-build-tool-for-javascript--net-24856)
- [JS Task Runners Comparison: Grunt vs Cake vs Gulp vs Broccoli](http://blog.cozycloud.cc/technic/2014/06/18/task-runners-comparison/)


!SLIDE no-bullet-list resources

## Final Resources

- <span class="icon-link"> [Awesome Javascript](https://github.com/sorrycc/awesome-javascript)


