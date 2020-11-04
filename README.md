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

- Simple Typescript class behaves like Component.

- We can create more than on Component.

- Angular Applications are Component based Applications.

- Because of Components code Reusability is High in Angular.

- We can provide communication between one Component to another Component.

- Angular follows the MVC Architecture.

- Component Acting as Interface between View and Service.

- Typescript classes behaves like Component.

### Modules

- we can establish the communication between server to database by using modules.

  > Ex.=> Mysql, mssql, mongodb,, firebase

10. What is a decorator in Angular ?

    - We can use predefined classes by using "@".

    - Using predefined classes by using @ symbol called as "decorator".

    - Decorators are used to defined the Meta Data.

11. What are Decorators Vs Annotations or MetaData ?
    -> Decorators are actually the functions, which extends the class object behavior at design time, by annoting them.

    -> But the decorators are imported as a annotation from '@angular/core' and attached with the class using the sign @.

    # Example:

        @Pipe

        class TestPipe { }

        -> Here @Pipe is an annotation that tells the Angular, that the class with which the annotation is attached to will get the Pipe behavior.
