# ANGULAR INTERVIEW QUESTIONS AND ANSWERS

1.  Whats the use of Angular ?

    - Angular is the Binding framework.
    - Angular is used to develop the both "web applications" and "mobile applications".
    - Angular follows the MVC Design Pattern.
      M - Model
      V - View
      C - Component

    - TypeScript variables behaves like Model.

    - we can use HTML, HTML5, Python, Angular Material, ReactJS as View in MVC.

    - TypeScript classes behaves like Component.

2.  What is AngularJS(1.x) vs Angular(2,3,4,5,6,7,8,9,10) ?

        AngularJS                         Angular 10
        Language: JavaScript              Language: Typescript
        Architecture: Controller          Architecture: Component
        Mobile compliant:No               Mobile complaint: Yes
        Lazy loading: No                  Lazy loading: Yes
        CLI: No                           CLI: Yes

3.  What are directives in Angular ?

    - Directives are used to manipulate the DOM Elements.
      > Ex. p div button table

4.  Explain the different types of Angular directives ?

    - we have two types of directives.

    1. predefined directives
    2. custom directives

    - the directives provided by angular framework called as predefined directives.

    - the directives developed by us based on application requirement called as custom directives.

5.  Explain the importance of NPM and Node_Modules folder ?

    > npm install -g typescript@latest

    - "npm" stands for node packaging manager.
    - "-g" stands for global installation.

    - node_modules containes libraries, these libraries helps to execute the angular / react applications.
    - It is a repository of all packages currently installed for your project.

6.  Explain the importance of Package.json file in Angular ?

    - this file used to download the 3rd party libraries.
    - all these libraries downloads to "node_modules" folder.

7.  What is typescript and why do we need it ?

    - TS superset of JS. It addes types to JS.

    - TS gives nice OOP environment which transpiles /convert to JavaScript.

    - we will build Angular10 applications by using "TypeScript".

    - TypeScript is the "Programming language".

    - TypeScript given by "microsoft".

    - "superset of javascript" also called as TypeScript.

    - TypeScript follows the OOPS.

8.  Explain importance of Angular CLI ?

    - we will install Angular10 by using following command.

    > npm install -g @angular/cli@latest

    - "cli" stands for command line interface
    - "cli" is the tool provided by google.
    - "cli" tool used to build and execute the angular applications

9.  Explain the importance of Component and Modules ?

### Component

- Component bind the View and Model

- Simple Typescript class behaves like Component.

- We can create more than on Component.

- Angular Applications are Component based Applications.

- Because of Components code Reusability is High in Angular.

- We can provide communication between one Component to another Component.

- Angular follows the MVC Architecture.

- Component Acting as Interface between View and Service.

- Typescript classes behaves like Component.

### Modules

- Module will groups components.

- we can establish the communication between server to database by using modules.

> Ex.=> Mysql, mssql, mongodb,, firebase

10. What is a decorator in Angular ?

    - We can use predefined classes by using "@". @Component(Angular Component), @NgModule(Angular Module)

    - Using predefined classes by using @ symbol called as "decorator".

    - Decorators are used to defined the Meta Data.

    - Decorator is also called Metadata or Annotations.

11. What are Decorators Vs Annotations or MetaData ?
    -> Decorators are actually the functions, which extends the class object behavior at design time, by annoting them.

    -> But the decorators are imported as a annotation from '@angular/core' and attached with the class using the sign @.

    # Example:

        @Pipe

        class TestPipe { }

        -> Here @Pipe is an annotation that tells the Angular, that the class with which the annotation is attached to will get the Pipe behavior.

12. What is a template ?

    Template is an HTML view of Angular in which we can write directives.

Inline template:<b>test</b>

templateURL: app.component.html

13. Explain the four types of Data bindings in Angular ?

Data Binding is how the view and component interact with each other.

        1.  Expression binding or Interpolation{{}} : data flows from controller to view. mix with HTML

        2.  property binding: [(ngModel)] when change happens in component reflect in view.

        3.  Event Binding: (click) goes from view to component.

        4.  2 -way binding: [()] data and event flow from component to view and vice versa.

14. Explain architecture of Angular ?

        1.Template(HTML View)
        2. Component: Binds view and model
        3. Modules: groups components logically
        4. Bindings : defines how the view and component communicate
        5. directives - Changes the HTML DOM Behavior. Ex. Interpolation, ngModel, Click
        6. Service: helps to share the common logic across the project.
        7. Dependency Injection: coomunication between component and service is called D.I

15. What is SPA in Angular ?

    SPA stands for Single Page Application.

    Loading one component to another component without refreshing whole page.

16. How to implement SPA in Angular ?

        Angular Routing

17. How to implement routing in Angular ?
    Routing is Navigating from 1 component to another component.
    <router-outlet>

    1. collection - which url will go to which component
    2. <router-outlet> - where exactly page is loaded
    3. router link: for HTML will load.
       router.navigate

18. Explain Lazy Loading in Angular?

        On demand loading.

        loading what is necessary and what we want.

19. How to implement Lazy Loading in Angular ?

    divide your project into separate modules.

    load children.

20. Define Services ?

    share common business logic across Angular projects.

21. What is Depedency Injection ?

    DI is communication between component and services.

22. How to implement Depedency Injection ?

    @NgModule(decorator ): providers attributes

23. Whats the benefit of Depedency Injection ?

    Advantage is decoupling. change in 1 place object instances across the project.

24. Differentiate between ng serve and ng build ?

    > ng serve --> build in memory

    > ng build -- build application in dist folder

25. Explain the --prod parameter in ng build ?

    code minification is done.

Angular Interview Questions and Answers - Part 2

26. Explain ViewChild and ViewChildren?

    - in angular, we can provide communication between components in 4 ways.

      1. @Input()
      2. @Output()
      3. @ViewChild()
      4. @ViewChildren()

      - @Input() used to pass the data from parent component to child component.

      - @Output() used to pass the data from child component to parent component.

      - @ViewChild() & @ViewChildren() are used to pass the data between sibilings.

27. Why do we need Template reference variables?

        Template variables help you use data from one part of a template in another part of the template. With template variables, you can perform tasks such as respond to user input or finely tune your application's forms.

        A template variable can refer to the following:

        -->a DOM element within a template
        -->a directive
        -->an element
        -->TemplateRef

28. What is ContentProjection?

29. Explain Content projection Slot?

30. What is ContentChild and ContentChildren?

31. ViewChild vs ViewChildren vs ContentChild vs ContentrChildren?

Angular interview questions - Part 3

Questions No:- 32 :- Explain the importance of Component life cycle ?

Questions No:- 33 :- Explain events and sequence of component life cycle ?

Questions No:- 34 :- Constructor vs ngOnInit() ?

Angular Interview Questions and Answers - Part 4

Questions No:- 35 :- How to make HTTP calls using Angular ?

Questions No:- 36 :- What is the need of Subscribe function ?

Questions No:- 37 :- How to handle errors when HTTP fails ?

Questions No:- 38 :- How to pass data between components ?

Questions No:- 39 :- Explain importance of input, output & event emitters ?

Questions No:- 40 :- How to pass during routing ?

Questions No:- 41 :- Is it a good practice to pass data using services ?

Angular Interview Questions and Answers - Part 5

Question No: 42:- What is the need of Angular Pipes?

Question No: 43:- Can you name some built-in Angular Pipes?

Question No: 44:- How to create Custom pipes in Angular?
