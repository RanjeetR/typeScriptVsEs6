# Typescript Vs  Es6 
# Why TypeScript Or ES6
- Classes
- Interfaces
- Annotations
- Decorators
- Arrow functions
- access modifiers
# Es6 features
- Arrows 
- Classes
- Enhanced object literals 
-  Template strings 
- Destructuring 
-  Let + const - iterators                              
- for..of - generators 
-  Unicode 
-   Modules - module loaders 
-    Map + set + weakmap + weakset - proxies - symbols 
-    Subclassable built-ins - promises 
-   Math + number + string + array + object APIs 
-    Binary and octal literals - reflect api - tail calls
* Node.js is built against modern versions of the V8 engine. Node has implemented much of ES2015, according to its docs.
* Many modern browsers and Node are supporting ES6.
# Build system for Es6 
> There are many old browsers that are not supporting ES6. We can transpile Es6 using tools like Babel.  Babel makes it easy to compile ES6 to ES5 


# TypeScript
> Any valid javascript i.e Es5 or ES6 is valid in Typescript, TypeScript Indicates that we now have types, but these types are optional.
We can write any valid javascript in TypesScript that means It is not mandatory to know typescript as a language. 

```sh
            ES5 + ES6 = TypeScript
```
# TypeScript features
> TypeScript supports all features form ES5 and ES6 on top of that TypeScript Provide its own feature too. TypeScript provides a structured language on top of JavaScript.
> TypeScript is not writing less code but the value of TypeScript is in writing safer code, it helps us to write code more efficiently as we take advantage of tooling for identifying issues and automatically filling in parameters, properties, functions, and more (often known as auto complete and intellisense).

- Types 
- Interfaces
- Futures of ES6
# Frameworks comfortable with ES6 or TypeScript
- Node js natively built with ES6.
- Angular 2 is written in TypeScript
  > Angular 2 is built with TypeScript, currently it has wide development support online and google is also trying to push this combination into developers.
Angular2 official documentation and examples are using typescript.
- React.js & ES6 :- React uses Es6, it takes functional programming to the next level.Es6 is much more cleaner and give more fun than ES5. 
-  Vue.js Supports both ES6 and TypeScript ( Vuejs Version 2.5.0).
  
# TypeScript for JavaScript

```sh
 1)  [] + []; // JavaScript will give you "" (also dont give runtime error), TypeScript will error.
 2) {} + []; // Javascript =>  : 0, TS => Error
 3) [] + {}; // JS => : "[object Object]", TS => Error
 4) {} + {}; // JS => : NaN, TS => Error
 5) "hello" - 1; // JS => : NaN, TS => Error
```


# Conclusion
 >   The chossing between TypeScript and Es6 is difficult one because both provides almost same feature. TypeScripts takes an edge  here by providing ES6 feature + Ts feature.
> This decision should be based on which framework we are going to work on,
As TypeScript is obvious choice for Angular 2 and ES6 is for React
> Build system is required in both cases.
Learning curve is almost same, if you learn ES6 then writing typescript is small step.


```sh
          Prepared  by Ranjeet R Hange
```




