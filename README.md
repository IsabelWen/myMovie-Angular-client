# MyMovieAngularClient

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 17.1.1.

## Description
The client-side for an app called myMovie based on its existing server-side code (REST API and database).

## Dependencies
* Angular: Web application framework for building single-page client applications.
* Angular Material: UI component library for Angular, implementing Google's Material Design.
* TypeDoc: Generates HTML API documentation from TypeScript code.

## Views
### Welcome View
* Allows users to either log in with a username and password or signup

### Main View
* Returns all movie from the API to the user
* Ability to see director details, genre details and synopsis of each movie
* in Navbar:
    * Ability to log out
    * Ability to navigate to Profile View

### Profile View
* Displays user registration details
* Allows users to update their info (username, email, date of birth)
* Allows existing users to deregister
* Displays favorite movies
    * Allows users to remove a movie from their list of favorites

## Set up this App
* Clone this repository.
* Navigate to the myMovie-Angular-client folder and run `npm install`
* Install Angular by running `npm install -g @angular/cli`
* Install Angular Material as a project dependency using your Angular CLI `ng add @angular/material`
    * Choose "Custom" to select a custom theme
    * Yes to set up Angular typography styles
    * Yes to set up browser animations for Angular Material
* Install TypeDoc as a project dependency by running `npm install typedoc --save-dev`
* Run `ng serve`, then navigate to  `http://localhost:4200/`