# Knowledge base
My collection of useful information, related to different web dev topics

# These are the books you're looking for
- [youtube video](https://youtu.be/H6OQ2RESp4s?t=1910)

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

# Code Reviews
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

- [Testing asynchronous RxJs operators](https://medium.com/angular-in-depth/testing-asynchronous-rxjs-operators-5495784f249e)
- [Marble testing with RxJS testing utils](https://medium.com/@kevinkreuzer/marble-testing-with-rxjs-testing-utils-3ae36ac3346a)

# TypeScript
- [Generics and Augmentation will Make You a TypeScript Wizard](https://medium.com/iqoqo-engineering/two-advanced-techniques-to-make-you-a-typescript-wizard-df42e00b1cf8)

# Angular 

### Blogs
- [Victor Savkin](https://blog.nrwl.io/@vsavkin)
- [Kevin Kreuzer](https://kreuzercode.com/)
- [Tomas Trajan](https://medium.com/@tomastrajan)
- [Wesley Grimes](https://wesleygrimes.com/)
- [Minko Gechev](https://blog.mgechev.com/)

### Angular People

- [Victor Savkin](https://vsavkin.com/)
- [Mike Brocchi](https://twitter.com/brocco)
- [Justin Schwartzenberger](https://twitter.com/schwarty)
- [Deborah Kurata](https://twitter.com/DeborahKurata)
- [Thomas Burleson](https://twitter.com/thomasburleson)
- [Sam Julien](https://twitter.com/samjulien)
- [Mike Ryan](https://twitter.com/MikeRyanDev)

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

### Articles

- [Avoiding switchMap-related Bugs](https://ncjamieson.com/avoiding-switchmap-related-bugs/)
- [The SIP principle](https://blog.strongbrew.io/the-sip-principle/)
- [dev.to](https://dev.to/rxjs)

## Forms

### Beginner Level
- [Intro to Forms](https://www.youtube.com/watch?v=xYv9lsrV0s4&t=935s&ab_channel=AngularConnect)
### Intermediate Level
- [The Best Way to build reactive sub-forms with Angular](https://medium.com/@tomastrajan/angular-reactive-sub-forms-type-safe-without-duplication-dbd24225e1e8)
### Advanced
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




