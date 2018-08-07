Portfolio based on code from Traversy Media's 7-part "Responsive Portfolio Website Project" Youtub Tutorail.
https://www.youtube.com/watch?v=gYzHS-n2gqU&list=PLillGF-RfqbYoGoCjKoMOkVznV6aSXKzU

Code for Traversy Media's portfolio located at github account - https://github.com/bradtraversy/modern_portfolio
  1.  This responsive code uses html5, Sass, CSS and a little bit of JavaScript.
  2.  It uses grid to stack the elements as the screen shrinks
  3.  It uses media query to handle screen sizes.  
  4.  The end result is a great looking website.
  
My portfolio takes the base code of Traversy Media and adapts to Angular 6 framework.

I maintained the basic design and behavior his site.  The menu buttons on the upper right transitions to an "X".  The Menu items slide in from the right in staggered sequence.  The pages come in split from the top and bottom.

What changed is that the individual html pages were put into the Angular component pages. 

Grids did not work.  Media queries did not work.  Or I did not have the expertise to make it work.

Instead, I converted the grid format on the About's and Project's page to Angular's FlexLayout using Angular Materials' Mat-card to provide the responsiveness to the website.  It came out very nicely.

Some of the Scss were also not working. I resolved by using the component scss page were needed and judiciously coding css in-line on the html pages.

I also modified the Scss to get a "same-look" across all the pages.

Instead a contact page with email address and contact information for me, I coded an email contact form on my about page.  

This portfolio is a work in progress, as I continue to improve its functionality.


# Portfolioang

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.0.8.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
