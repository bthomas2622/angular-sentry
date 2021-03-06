# Angular Sentry Sample App

This is a simple angular app that can generate errors and send to Sentry. 

## First configure your Sentry dsn key

In order for your Sentry project to capture errors thrown by this sample app you will need to put in the Data Source Name (DSN) for your project in the Sentry.Init config. This is located in the file `app.module.ts` in */angular-sentry/src/app/app.module.ts*

***NOTE***: If you do not have a DSN you will need to obtain one by "Create a project - Angular" in the Sentry UI. And get the associated DSN. 

```
Sentry.init({
  dsn: "your-dsn-key" ,
});
```

## Run the Application

1. Install the necessary npm packages with `npm i`
2. Navigate to the app folder *angular-sentry*
3. Run the command: `ng serve --open` (or `npm run start` defined in *package.json*). This will open your browser to *localhost:4200" where application is being served. NOTE: ensure you have Angular CLI installed with `npm install -g @angular/cli`

---
---

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.2.2.

### Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

### Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.