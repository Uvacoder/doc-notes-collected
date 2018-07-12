# Angular
My personal and public notes while practising on Angular.

## Good to know
Install [Node.js](https://nodejs.org/en/download/) if it is not already. 

Editors:
- [Visual Studio Code](https://code.visualstudio.com/)
- [Webstorm](https://www.jetbrains.com/webstorm/)
- [Sublime Text](https://www.sublimetext.com/)
- [Atom](https://atom.io/)

## Basic setup
<img src="https://cli.angular.io/images/cli-logo.svg">

Navigate to ```http://localhost:4200/``` in default. The app will automatically reload for any changes in the source files.

## Useful Commands
- Use ```ng serve --open``` or ```ng serve -o``` to open the browser on ```http://localhost:4200/```.
- Use ```ng serve --port 1903``` to serve on custom port.
- Use ```ng test``` to run all unit tests.
- Use ```ng build``` to build and bundle the application for deployment.
    > `development`: default mode, do not minify or uglify code,
    
    > `production`: minify and uglify code.
    - To build for production: ```ng build --target=production```
- Use ```ng new my-dream-app --style=scss``` for scss instead of css(default).
- Use ```ng generate class my-new-module``` or ```ng g cl my-new-module``` to add a module.
- Use ```ng generate class my-new-class``` or ```ng g cl my-new-class``` to add a class.
- Use ```ng generate component my-new-component``` or ```ng g cl my-new-component``` to add a component.
- Use ```ng generate service my-new-service``` or ```ng g cl my-new-service``` to add a service.
- Use ```ng generate directive  my-new-directive``` or ```ng g cl my-new-directive``` to add a directive.
- Use ```ng generate enum my-new-enum``` or ```ng g cl my-new-enum``` to add a enum.
- Angular CLI will automatically adjust the letter case of the file name, so the following commands have the same effect:
    > All three commands are equivalent
    - ```ng generate class my-new-class```
    - ```ng generate class myNewClass```
    - ```ng generate class MyNewClass```
    
## Useful Links
- Videos
    - English
        - [Angular 6 Tutorial](https://www.youtube.com/watch?v=0eWrpsCLMJQ&list=PLC3y8-rFHvwhBRAgFinJR8KHIrCdTkZcZ)
        - [Angular 6 Tutorials](https://www.youtube.com/watch?v=UoVytwPk3iA&list=PLYxzS__5yYQlqCmHqDyW3yo5V79C7eaTe)
        - [Angular In 60 Minutes](https://www.youtube.com/watch?v=KhzGSHNhnbI)
        - [Learn Angular 6 in 60 Minutes - Free Beginners Crash Course](https://www.youtube.com/watch?v=z4JUm0Bq9AM&t=732s)
    - Turkish
        - [Angular 6 Dersleri](https://www.youtube.com/watch?v=y5V6LOUwSWM&list=PLBKqEm_6KxTFlSkIJbDJ_eML11o0yI1VM)
        - [Angular 5 Dersleri](https://www.youtube.com/watch?v=TRd0ihuNdvs&list=PLqG356ExoxZWvyGkeytVjxpO-4BhjXvJ5&index=1)
        - [Angular 4 Eğitimi](https://www.youtube.com/watch?v=PbgKzD_0naM)
        - [TypeScript ile Angular 2 Uygulamaları Geliştirmek - Bora Kaşmer](https://www.youtube.com/watch?v=-G7Dq028thg)
- Articles
- Books
    - English
        - [ng-book](https://www.ng-book.com/2/)