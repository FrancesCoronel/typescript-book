## Draft Outline

> Take the ideas from your proposal and organize them into chapters. Then, for each chapter, include a few sentences explaining what subjects you’ll cover in that chapter. Give us a sense of how many pages you plan for your book to be.

## Pages

I estimate the book will have 250 to 300 pages.

- Syllabus Overview
- Totally Tooling Types
  - Covers variables
- Flunking Functions, decorators, generics
  - Covers functions
- Messy Modules
- Creating a Class (Literally)
- Declarations
- Linting & Testing
- Frameworks & Dependencies
- Modularity
- Final Project
  - todomvc
- Graduation

The extensive adoption of JavaScript for application development, and the ability to use HTML and JavaScript to create Windows Store apps, has made JavaScript a vital part of the Windows development ecosystem. Microsoft has done extensive work to make JavaScript easier to use. Microsoft's TypeScript extends many familiar features of .NET programming to JavaScript. With TypeScript Succinctly by Steve Fenton, you will learn how TypeScript provides optional static typing and classes to JavaScript development, how to create and load modules, and how to work with existing JavaScript libraries through ambient declarations. TypeScript is even significantly integrated with Visual Studio to provide the autocompletion and type checking you are most comfortable with.

JavaScript is everywhere, both as a pure language and in popular libraries like Angular, jQuery and Knockout, but users of modern object-oriented languages like Java and C# often find JavaScript frustrating to use and hard to extend to large-scale applications. TypeScript is an innovative open source language from Microsoft that combines powerful language features and enhanced tooling support with the key attractions of JavaScript as a flexible, dynamic language that can run in any browser and on any operating system. Pro TypeScript tells you everything you need to know about this exciting new language and how to use it in your applications.

Starting with an introduction to the language and its features, the book takes you through some of the major features of TypeScript in depth, from working with the type system through object-orientation to understanding the runtime and the TypeScript compiler. The book then covers some of the factors you need to consider when running a TypeScript application in the browser, including interacting with the DOM, making asynchronous requests, and working with useful browser APIs, followed by a demonstration of server-side TypeScript using the popular Node.js framework.

Because TypeScript compiles to plain JavaScript, exception handling, memory management and garbage collection can differ depending on where you run your program, so these topics get a chapter to themselves. You’ll also find out how to include popular JavaScript frameworks in your applications, so you can combine the benefits of TypeScript with some of the best JavaScript code that’s already out there waiting to be used. The final chapter gives an overview of automated testing for TypeScript applications.

Pro TypeScript offers a balanced and practical guide to a language that will transform your experience of JavaScript development.

What you’ll learn The key TypeScript language features How to work with the TypeScript type system How to transfer your object-orientation skills to TypeScript Useful JavaScript patterns and features that work well with TypeScript How to consume existing JavaScript libraries in your TypeScript program How to run TypeScript in a web browser or on a server Who this book is for
Pro Typescript is for the professional application developer writing applications to run on JavaScript engines in browsers or on web servers. To get the most out of this book, you should be familiar with object-oriented programming in a modern language such as C# or Java. The techniques shown will build on your existing object-oriented programming skills and show you how to transfer them to your TypeScript applications.

avaScript is old and its dynamic nature can make it very difficult to build large applications in a maintainable way. But, add the immense power of compile-type static typing and all of the sudden you've got an enterprise-ready language that saves you from many common JavaScript issues and actually makes web development an enjoyable experience. TypeScript is a superset of JavaScript - completely compatible in every way, yet it brings the language to a whole new level.

JavaScript is the defacto language of the world. TypeScript is JavaScript, only better.

Join experienced coder, Jess Chadwick, as he explores the world of TypeScript. Starting with the basics and fundamental ECMAScript 2015 features that TypeScript expands upon, Jess shows you all the ways that TypeScript allows you to bring your JavaScript development to the next level

One of the reasons many developers flock to JavaScript is because of the freedom that comes with writing code in a classless dynamic language, so why now the appeal to re-introduce coding "restrictions" into their day-to-day life with super-sets like TypeScript? Weren't we fine before without classes, lambdas, type-safety, interfaces, generics, enums, etc.? The short answer is of course, ES6 (the recently finalized 6th version of JavaScript) is bringing many new features and we'll all be adjusting to it eventually, and TypeScript blends well with many new ES6 features, yet offers many of its own ideas (which C# developers will instantly recognize) and the reader can evaluate for themselves the merit of each feature.

TypeScript offers many features that (unlike with C#) that compile away once your code is converted to native JavaScript (ie, you can't use reflection after the fact to infer types), so its main benefit is realized in introducing a compilation step to your current JavaScript coding process. This means you can enforce strong typing, use interfaces, generics, enums, explicitly declare public/private class members, which can potentially eliminate many problems that come with scaled-out enterprise level JavaScript applications. For those craving many of the object-oriented features they miss from C#, Java or similar languages, TypeScript ports over a familiar syntactic sugar to carve out JavaScript in a familiar way.

There were several times reading through this book where I started thinking that while TypeScript might not always be a better way to write JavaScript, it still feels like a better way to write C#. After I stopped working in C# for six months or so in favor of JavaScript, I suddenly had need to put together a simple C# application to assist the back-end developers at my company, and found myself trying to do things that were easy to do in JavaScript but extremely difficult to do in C#. Often you can't know for sure if you're going in the right direction without trying out a few things, and therefore the speed of JavaScript development is one of the best assets to rapid development, in my opinion. In C# this meant trying to try out an idea before sculpting out all the classes you need, and often I dipped into using the "dynamic" type, only to find it doesn't often play nicely with everything else in the whole C# ecosystem or behave the way you expect. After I had the basic ideas hammered out though, I was then able to go back through the application and clean it up by separating functionality into the appropriate classes and introduce the different types needed to stabilize the application. And it's that workflow that I'd point to as idea (again, in my opinion): prototype rapidly, and then stabilize the application with the clean refactoring necessary and "future proof" it with type safety.

This book covered a lot of material, including a full 60-page final chapter on building an SPA from scratch with TypeScript, but my only critique of it is it heavily favored Backbone throughout the book. Any quick peak at the popular front-end frameworks by search engine popularity (on google trends) will show Backbone tanking compared to the others out there (especially to Angular and React, and has recently even been overtaken by Ember), and with the Angular team's announcement of their adoption of TypeScript seems like it would have been the ideal candidate, but that's only my opinion and I'm sure many readers out there have reasons why they prefer other JS frameworks.

A tool like TypeScript (whether leveraged on the front-end JS or back-end in something like Node) allows that kind of workflow to be realized and helps preserve some of the great ideas present in languages like C# or Java. Time will tell how well TypeScript will catch on and how accepted it will become, especially as more developers beginning using ES6. My expectation is it will be most useful in larger applications. (less)