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
1. <span class="icon-calendar"> Advanced JS concepts: Objects & inheritance
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

<!-- ######################## COVER Advanced JS ######################## --> 

!SLIDE coverSession jquery

<section class="logos">
  <div class="box">
    ![jQuery Logo](img/jquery-logo.gif)
  <div>
</section>
 
## Advanced JS Training  
### Using **jQuery**  


