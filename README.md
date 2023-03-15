# AngularTourOfHeroes

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 15.2.1.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.



## Services 
1. are a great way to share information among classes that don't know each other.
2. Create a MessageService next and inject it in these two places. 
3. Inject in HeroService, which uses the service to send a message. 
4. Inject in MessagesComponent, which displays that message, and also displays the ID when the user clicks a hero.
5. You refactored data access to the HeroService class.
6. You registered the HeroService as the provider of its service at the root level so that it can be injected anywhere in the application.
7. You used Angular Dependency Injection to inject it into a component.
8. You gave the HeroService get data method an asynchronous signature.
9. You discovered Observable and the RxJS Observable library.
10. You used RxJS of() to return Observable<Hero[]>, an observable of mock heroes.
11. The component's ngOnInit lifecycle hook calls the HeroService method, not the constructor.
12. You created a MessageService for loosely coupled communication between classes.
13. The HeroService injected into a component is created with another injected service, MessageService.

## Dashboard view process
1. Add a Dashboard view
2. Add the ability to navigate between the Heroes and Dashboard views
3. When users click a hero name in either view, navigate to a detail view of the selected hero
4. When users click a deep link in an email, open the detail view for a particular hero
5. You added the Angular router to navigate among different components
6. You turned the AppComponent into a navigation shell with <a> links and a <router-outlet>
7. You configured the router in an AppRoutingModule
8. You defined routes, a redirect route, and a parameterized route
9. You used the routerLink directive in anchor elements
10. You refactored a tightly coupled main/detail view into a routed detail view
11. You used router link parameters to navigate to the detail view of a user-selected hero
12. You shared the HeroService with other components

## Get data from server
1. You added the necessary dependencies to use HTTP in the application
2. You refactored HeroService to load heroes from a web API
3. You extended HeroService to support post(), put(), and delete() methods
4. You updated the components to allow adding, editing, and deleting of heroes
5. You configured an in-memory web API
6. You learned how to use observables
