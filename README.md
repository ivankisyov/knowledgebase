# Knowledge base
My collection of useful information, related to different web dev topics

# These are the books you're looking for
- [youtube video](https://youtu.be/H6OQ2RESp4s?t=1910)

Too Lazy, Did Not Watch ^^:
1. Inside the Machine (Jon Stokes)  
2. Code: The Hidden Language of Computer Hardware and Software 
3. Concrete Mathematics (Ronald L. Graham, Donald E. Knuth и Oren Patashnik) 
4. Structure and Interpretation of Computer Programs 
5. How to Design Programs 
6. The C Programming Language (BRIAN W KERNIGHAN, DENNIS M. RITCHIE) 
7. The Elements of Style (William Strunk Jr. и E.B. White) 
8. The Elements of Programming Style (Kernighan и Plauger) 
9. Code Complete (Steve McConnell) 
10. Clean Code (Robert C. Martin) 
11. Refactoring: Improving the Design of Existing Code (M. Fowler) 
12. The Algorithm Design Manual 
13. Introduction to Algorithms 
14. Compiler Principles, Techniques and Tools 
15. Modern Operating System (Tanenbaum) 
16. Practical Common Lisp 
17. Land of LISP 
18. The Little Schemer 
19. LISP (LISP In Small Pieces) 
20. The Well Grounded Rubyist 
21. Practical Object-Orientetd Design in Ruby 
22. Effective C++ (Scott Meyers) 
23. Effective JAVA (Joshua Bloch) 
24. JAVA Concurrency in Practice 
25. Growing Object-Oriented Software Guided by Tests 
26. Predicting the Unpredictable 
27. Extreme Programming Explained 
28. Thinking, Fast and Slow 
29. Godel, Escher, Bach

# Notes on Robert Martin's Clean Code book:
- bad code tries to do too much
- clean code has a single purpose, it is focused
- **Extract Method refactoring** - one method that says more clearly what it does, and some submethods saying how it is done
- The next time you write a line of code, remember you are an author, writing for readers who will judge your effort.
- **The Boy Scouts rule** - Leave the campground cleaner than you found it
- clarity is king, professionals write code that others can understand
- About functions - Making the code read like a top-down set of TO paragraphs is an effective technique for
keeping the abstraction level consistent:
> "To include the setups and teardowns, we include setups, then we include the test page content, and then we include the teardowns.
>
> To include the setups, we include the suite setup if this is a suite, then we include the regular setup.
>
> To include the suite setup..."

- The smaller and more focused a function is, the easier it is to choose a descriptive name.
- A long descriptive name is better than a short enigmatic name. A long descriptive name is better than a long descriptive comment
- the ideal number of function's arguments is 0 :) You should avoid having more than two arguments

> "Master programmers think of systems as stories to be told
>
> never forget that your real goal is to tell the story of the system, and that the functions
>
> you write need to fit cleanly together into a clear and precise language to help you with
>
> that telling"
- Don’t comment bad code - rewrite it
- Short functions don’t need much description. A well-chosen name for a small function that does one thing is usually better than a comment header
- Objects expose behavior and hide data
- Data structures expose data and have no significant behavior
- The quintessential form of a data structure is a class with public variables and no functions.
This is sometimes called a data transfer object, or DTO
- what makes code readable: clarity, simplicity and density of expression(code in succinct and expressive forms, code not loaded with details that interfere with its expressiveness)
- **about unit tests**:
> ...having an automated suite of unit tests that cover the production code is the key to
>
> keeping your design and architecture as clean as possible. Tests enable all the -ilities,
>
> because **tests enable change**.
- **about classes**:
> ...We want our systems to be composed of many small classes, not a few large ones. 
>
> Each small class encapsulates a single responsibility, has a single reason to change, 
>
> and collaborates with a few others to achieve the desired system behaviors.
- We should also be able to write a brief description of the class in about 25 words,
without using the words “if,” “and,” “or,” or “but.”

# Notes on The Passionate Programmer by Chad Fowler
- Stay focused on winning, and the fear of losing will be forever a memory
- You’re about to make a big investment. It may not be a lot of money, but it’s **your time — your life**
- software person should understand a business domain not only well enough to develop software for it
but also to become one of its authorities
- You might be “just a programmer,” but being able to speak to your business clients in the language
of their business domain is a critical skill
- think about business domains you invest your time in
- The people around you affect your own performance. Choose your crowd wisely
- Always be the worst guy in every band you’re in
- Thinking about not losing is not the way to win
- If you want to really learn something, try teaching it to someone else
- whenever I want to really learn about something, write about it

# Knowledge Stalking

The following list contains people I found while researching various web dev topics:
- [Carlos Caballero](https://www.carloscaballero.io/)
- [Anastasia](https://twitter.com/coffeestasia)

# Algorithms and Data Structures
- [with JS examples](https://github.com/trekhleb/javascript-algorithms)

# Node.js
- [best practices](https://github.com/goldbergyoni/nodebestpractices)

# Style Guides
- [Google Style Guides](https://google.github.io/styleguide/)

# Code Reviews
- [Google Engineering Practices Documentation](https://google.github.io/eng-practices/)
- [What google taught me about code reviews](https://www.freecodecamp.org/news/what-google-taught-me-about-code-reviews/)
- [How to Make Your Code Reviewer Fall in Love with You](https://mtlynch.io/code-review-love/)

# Testing

### Times and Dates
- [How to correctly mock Moment.js/dates in Jest](https://medium.com/free-code-camp/how-to-correctly-mock-moment-js-dates-in-jest-25fa2528ca11)

### Angular Testing

#### Articles
- [all-you-need-to-know-about-mocking-in-angular-tests](https://christianlydemann.com/all-you-need-to-know-about-mocking-in-angular-tests/)

#### Testing libs
- [ng-mocks](https://github.com/ike18t/ng-mocks)
- [spectator](https://github.com/ngneat/spectator)

#### Marble testing

- [RxJS unit testing in Angular application](https://www.udemy.com/course/rxjs-unit-testing-in-angular-application-the-whole-picture/)
- [Testing asynchronous RxJs operators](https://medium.com/angular-in-depth/testing-asynchronous-rxjs-operators-5495784f249e)
- [Marble testing with RxJS testing utils](https://medium.com/@kevinkreuzer/marble-testing-with-rxjs-testing-utils-3ae36ac3346a)
- [todo#1](https://github.com/ReactiveX/rxjs/tree/master/spec/operators)
- [todo#2 check getting started](https://github.com/cartant/rxjs-marbles)

# Regular Expressions
- [Learn Regular Expressions](https://www.freecodecamp.org/news/learn-regular-expressions-with-this-free-course-37511963d278/)

# TypeScript
- [Generics and Augmentation will Make You a TypeScript Wizard](https://medium.com/iqoqo-engineering/two-advanced-techniques-to-make-you-a-typescript-wizard-df42e00b1cf8)

# JWT
- [JWT: The Complete Guide to JSON Web Tokens](https://blog.angular-university.io/angular-jwt/)

# Angular 

### Blogs
- [Victor Savkin](https://blog.nrwl.io/@vsavkin)
- [Kevin Kreuzer](https://kreuzercode.com/)
- [Tomas Trajan](https://medium.com/@tomastrajan)
- [Wesley Grimes](https://wesleygrimes.com/)
- [Minko Gechev](https://blog.mgechev.com/)
- [Nils Mehlhorn](https://nils-mehlhorn.de/)
- [Deborah Kurata](https://blogs.msmvps.com/deborahk/)

### VideoCast
- [Angular Air](https://angularair.com/)

### Articles

- [Everything you need to know about ng-template, ng-content, ng-container, and *ngTemplateOutlet in Angular](https://www.freecodecamp.org/news/everything-you-need-to-know-about-ng-template-ng-content-ng-container-and-ngtemplateoutlet-4b7b51223691/)
- [Angular ng-template, ng-container and ngTemplateOutlet - The Complete Guide To Angular Templates](https://blog.angular-university.io/angular-ng-template-ng-container-ngtemplateoutlet/)

### Videos
- [My YouTube Angular Playlist](https://www.youtube.com/playlist?list=PLgxIWyhARVtnq3pQHJ8SuIhblZ4EAG6D-)
- [CRUD Tutorial](https://www.youtube.com/watch?v=JYPyy-hvjYc&list=PL6n9fhu94yhXwcl3a6rIfAI7QmGYIkfK5&index=2&t=0s)

## Architecture

- [How to architect epic Angular app in less than 10 minutes](https://medium.com/@tomastrajan/how-to-build-epic-angular-app-with-clean-architecture-91640ed1656)
- [Handle single import of core module](https://github.com/tomastrajan/angular-ngrx-material-starter/blob/master/projects/angular-ngrx-material-starter/src/app/core/core.module.ts)
- [Tips on app architecture](https://medium.com/@tomastrajan/how-to-build-epic-angular-app-with-clean-architecture-91640ed1656)
- [More tips on app architecture](https://medium.com/@tomastrajan/6-best-practices-pro-tips-for-angular-cli-better-developer-experience-7b328bc9db81)

### Repos

#### App Folder Structure

- [Example #1](https://github.com/gothinkster/angular-realworld-example-app)
- [Example #2](https://github.com/tomastrajan/angular-ngrx-material-starter)
- [Example #3](https://github.com/ngx-rocket/starter-kit)

### [NX](https://nx.dev/angular)

#### Tutorials

- [Nx Explainer: Dev Tools for Monorepos, In-Depth with Victor Savkin](https://www.youtube.com/watch?v=h5FIGDn5YM0&t=23s&ab_channel=Nrwl-NarwhalTechnologiesInc.)
- [Nx Workspaces Course (Free version) - By Nrwl](https://www.youtube.com/watch?v=2mYLe9Kp9VM&list=PLakNactNC1dH38AfqmwabvOszDmKriGco&ab_channel=Nrwl-NarwhalTechnologiesInc.)
- [NX Docs: Resources](https://nx.dev/latest/angular/getting-started/resources)

## RxJS

> **Reactive programming: What Data Will Change, and What Data Do the Components Need?**  
_**Learn to think in streams**_. A stream is a collection of events that will change over time. Think about what can change in your application and call these streams of data. Let’s call them source streams...[check out the rest of the article](https://blog.strongbrew.io/thinking-reactively-in-angular-and-rxjs/)

## Decorators

- [autounsubscribe](https://netbasal.com/automagically-unsubscribe-in-angular-4487e9853a88)
- [until-destroy](https://github.com/ngneat/until-destroy)

## Caching with RxJS
- [Caching with RxJS](https://blog.thoughtram.io/angular/2018/03/05/advanced-caching-with-rxjs.html)

### Articles

- [Avoiding switchMap-related Bugs](https://ncjamieson.com/avoiding-switchmap-related-bugs/)
- [The SIP principle](https://blog.strongbrew.io/the-sip-principle/)
- [dev.to](https://dev.to/rxjs)

## Forms

### Beginner Level
- [Intro to Forms](https://www.youtube.com/watch?v=xYv9lsrV0s4&t=935s&ab_channel=AngularConnect)
### Advanced
- [implementing-reusable-and-reactive-forms-in-angular](https://indepth.dev/posts/1415/implementing-reusable-and-reactive-forms-in-angular-2)
- [deeply-nested-angular-reactive-form](https://indepth.dev/posts/1227/i-changed-my-implementation-of-an-extremely-deeply-nested-angular-reactive-form-and-you-wont-believe-what-happened)
- [The Best Way to build reactive sub-forms with Angular](https://medium.com/@tomastrajan/angular-reactive-sub-forms-type-safe-without-duplication-dbd24225e1e8)
- [Reducing the forms boilerplate — make your Angular forms reusable](https://medium.com/angular-in-depth/reducing-the-forms-boilerplate-make-your-angular-forms-reusable-ee06d7c07f47)
    - [Angular Forms – Kara Erickson](https://www.youtube.com/watch?v=CD_t3m2WMM8&ab_channel=AngularConnect)
- [The Control Value Accessor | Jennifer Wadella](https://www.youtube.com/watch?v=kVbLSN0AW-Y&t=3s&ab_channel=ng-conf)
    - [repo](https://github.com/tehfedaykin/galaxy-rating-app)
    
## Authentication

### Articles

- [The Complete Guide to Angular User Authentication with Auth0](https://auth0.com/blog/complete-guide-to-angular-user-authentication/)
    
## NgRx

### Why using store solution:

>...At this point, we have a good view on what the problem was in the Facebook application: the Facebook home screen + chat needed to display multiple View Models of the Same Model data at the same time on the same screen....[check out the rest of the article](https://blog.angular-university.io/angular-ngrx-store-and-effects-crash-course/)


### Articles

- [Managing State in Angular Applications using NgRx](https://blog.nrwl.io/using-ngrx-4-to-manage-state-in-angular-applications-64e7a1f84b7b)
- [Best Practices for Enterprise Angular Applications](https://itnext.io/ngrx-best-practices-for-enterprise-angular-applications-6f00bcdf36d7)
- [Start using ngrx/effects for this](https://indepth.dev/start-using-ngrx-effects-for-this/)
- [How to upgrade your Angular and NgRx Apps to v8](https://ultimatecourses.com/blog/how-to-upgrade-your-angular-and-ngrx-apps-to-v8)

### Videos

- [Easy Angular Unit Testing in NgRx - JavaScript Marathon](https://www.youtube.com/watch?v=NOT-nJLDnyg&t=1456s&ab_channel=ThisDotMedia)
    - [My Notes](https://gist.github.com/ivankisyov/2a4719747e294e9fcd7b3f2a8bd1de3f)

- [John Crowson - Using MockStore in NgRx 8](https://www.youtube.com/watch?v=Jh3uEy6dcVo&list=PLgxIWyhARVtlXIzbCYhYK5xsPPO6A6tL8&index=10&t=0s)
    - [presentation pdf](https://johncrowson.com/assets/angular-up.pdf)
    - My Notes: 
      - `store.scannedActions$` usage for checking out the dispatching within a component
      - when using mock selectors there is no need to pass initial state to mock store
      - resetSelectors API
      - effect using data from the store and not dispatching action: time: 21:44

### Repos

- [ngrx repo](https://github.com/ngrx/platform/tree/master/projects/example-app)
- [angular-university: ngrx-course](https://github.com/angular-university/ngrx-course)
- [samjulien: demonstrating NgRx concepts](https://github.com/samjulien/nostalgia-mart)

### NgRx Entity

- [Angular NgRx Entity - Complete Practical Guide](https://blog.angular-university.io/ngrx-entity/)

## i18n

- [Building Angular apps with internationalization (i18n) in mind | Naomi Meyer](https://www.youtube.com/watch?v=cUDUqqOtBvM&ab_channel=AngularConnect)
- [ngx-translate](http://www.ngx-translate.com/)

### Learning platforms

- [nrwl/connect](https://connect.nrwl.io/)

### Best Practices

- [Angular Checklist](https://angular-checklist.io/default/checklist/architecture)
- [Refactoring Angular Apps – How To Keep Angular Apps Clean](https://christianlydemann.com/refactoring-angular-apps-how-to-keep-angular-apps-clean/)

### VS Code extensions

- [Angular Essentials (Version 9)](https://marketplace.visualstudio.com/items?itemName=johnpapa.angular-essentials&wt.mc_id=vscode_angular_snippets-github-jopapa)

### Angular and Prettier
- [Setting up Prettier in an Angular CLI Project](https://medium.com/@victormejia/setting-up-prettier-in-an-angular-cli-project-2f50c3b9a537)

# Authentication and Authorization

## Articles

- [Architecture Scenarios](https://auth0.com/docs/architecture-scenarios)
- [Token Storage](https://auth0.com/docs/tokens/token-storage)
- [MFA](https://auth0.com/blog/multifactor-authentication-mfa/)

# Github pages

## Deploy angular app
- [useful link](https://dzone.com/articles/deploy-angular-app-on-github-pages)




