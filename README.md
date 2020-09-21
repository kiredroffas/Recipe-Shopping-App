# RecipeShoppingApp
* This recipe/shopping list web application utilizes Angular.js, TypeScript/JavaScript, Bootstrap, HTML, and CSS.
* Using Firebase user authentication, users must create an account and login to access the recipe list. The recipe list remains locked until a user logs in. Error messages are displayed on incorrect login information. A CSS loading spinner is used while the async login calls are being made.
* Once users are logged in, recipes can be added to the recipe list, edited, or deleted. Each addition to the recipe list requires a name, image url, and description before it can be saved to the list. Optionally, ingredients/amounts of ingredients can also be saved with the recipe.
* A Firebase server accessed with REST API calls allows for loading of previously saved recipes through selecting 'Fetch Data' in the Manage tab in the header. Once new recipes have been added, users can save all of the recipes to the server with the 'Save Data' option in the Manage tab in the header. Be careful not to overwrite the recipes on the server by saving a empty recipe list (i.e. use the 'Fetch Data' option first upon logging in, then use 'Save Data' after you have finished adding/editing recipes).
* Each recipe in the recipe list also has the option to be added to the shopping list, which will add the ingredients from the selected recipe to the shopping list part of the app, accessed by clicking the 'Shopping List' tab in the header.
* The shopping list tab provides a list of all of the selected ingredients you have added from selected recipes in the recipe list, including type and quantity. New ingredients can also be added here, requiring a name and quantity for each ingredient. Current ingredients in the list can also be updated and deleted.

* Angular concepts used within this application: components, styles, bootstrap, selectors, string interpolation, property/event binding, directives, local template references, services/dependency injection, routing, observables, template driven/reactive forms, pipes, http requests (REST), authentication, optimization - feature modules, lazy loading, ahead-of-time compilation, deployment.

## To access the application in its deployed state
* Firebase web hosting: https://recipe-shopping-app-c70a7.web.app

## Screenshots
![Alt text](/screenshots/sc1.png?raw=true "Login")
![Alt text](/screenshots/sc11.png?raw=true "Login info")
![Alt text](/screenshots/sc2.png?raw=true "Login incorrect")
![Alt text](/screenshots/sc3.png?raw=true "Recipes")
![Alt text](/screenshots/sc4.png?raw=true "Recipes fetched")
![Alt text](/screenshots/sc5.png?raw=true "Recipe selected")
![Alt text](/screenshots/sc6.png?raw=true "Recipe manage tab")
![Alt text](/screenshots/sc7.png?raw=true "New recipe add")
![Alt text](/screenshots/sc8.png?raw=true "New recipe in recipe list")
![Alt text](/screenshots/sc9.png?raw=true "Shopping list with added ingredients")
![Alt text](/screenshots/sc2.png?raw=true "Shopping list ingredient update")

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.1.8.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
