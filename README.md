# Angular Panel

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 14.0.3, Bootstrap and FontAwesome Icons.
Also, it is an architecture proposal with a simple login flow with Amgular AuthGuard, lazy loading, and routing.

### The Simple Architecture 
```
- app
-- guards
-- modules
  |-- admin
    |--- components
-- services
-- components
  |-- login
  |-- forgot-password
  |-- not-found
```

<img width="223" alt="Screenshot 2022-06-30 at 14 51 01" src="https://user-images.githubusercontent.com/11242953/176694464-db04c3e6-7980-4b6e-88fb-c497bff91cff.png">

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.
If you are in vs code all you need is to run you debugger with F5

## Code scaffolding

For scafofolding you should run:
* Modules - `ng g m modules/[name of module]` if we want module with route add `--rounting`
* Services - `ng g s services/[name of service]`
* Guard - `ng g g guards/[name of guard]`
* Components - `ng g c components/[name of component]`

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
