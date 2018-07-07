![SAEDigital](https://s3.sa-east-1.amazonaws.com/avasae/avasae/logos/logo-sae.png)

# Challenge Front-End

This challenge purpose is to build a theater management application that will use data of an REST API.

# Assessment Instructions (Author: Ivam Galvão Filho):
To test the application you must follow these steps:

### 1-Download the Git application at:
https://github.com/ivamgf/SAE-Desafia-Front-end

### 2-After extracting the folder you can use any IDE to open the project but, the preference for design in Angular 6 is the use of IDE Visual Studio Code.

### 3-In the terminal one must enter the following commands for installation and update of packages and frameworks:
> npm install

> npm install -g bower

> bower install

> npm install -g @ angular / cli

### 4-To compile the project the following command should be typed in the terminal:
> ng serves --open

### Note:
The following version of the application has the following errors checked in Unit, Integration and Cross Browser tests:
a) Rendering problem in some browsers due to the single-page application paradigm used in the AngularJS project. Angular 6 has its own method that has been modified in this project which causes the error.
b) Problem of undefined property in the template. Possible solution is to perform an iteration with for in the component.ts in typescript before doing * ngFor in the template.
c) Post, put, delete, reserve and cancel buttons do not complete the request due to port 4200 permission. Problem can be solved with CORS configuration in api Back-end or building a web server.
d) The build was performed but it was not possible to perform the production build due to the errors previously exposed.
e) The following main dependencies were used in the project:
Angular 6, Bower, Npm, NodeJS, Bootstrap, Jquery and Sass.
f) The following features were also used: Microsoft Visual Studio Code, Postman, Swagger, Django, Jasmine, Karma, Protractor and GitKraken.

## Instructions
The applicant is free to take the challenge with the technology as you wishes, but we have a preference for VueJS.


Imagine that you are building a public library to publish on your github, then other people have used your library, so it should contain all the necessary details in your README.MD. (Eg: How to install, How to upload, features...)

UI / UX of the application will be evaluated as if all functionalities have been implemented correctly.

The API with all its documentation is available at: http://desafia.sae.digital

1. Take the ** fork ** from this repository and create a branch with your name. (eg, marcelo-moraes).
2. After finishing the challenge, create a ** Pull Request ** with your name. (eg, marcelo-moraes).
3. Wait for some contributor to do the code review.

## Resources
Please, confirm below the features that should be implemented in the application:
  * Shows (http://desafia.sae.digital/api/shows/); 
  * Armchairs (http://desafia.sae.digital/api/armchairs/);
  * Bill (http://desafia.sae.digital/api/bills/);

  
# How will we evaluate?
  * We'll upload the application and access via localhost;
  * We'll register / edit / delete / update the show;
  * We'll reserve and cancel reservations for the seats;
  * We'll verify if the amount collected is accurate and correct.
  
# Observations
- Use good practice of GIT;
- All code must be written in English;
- Take a look at the endpoint filters, it may help you ;)
  
# Questions

If you have any questions, consult the [questions previously asked](https://github.com/saedigital/SAE-Desafia-Front-end/issues).

If you do not find your answer, feel free to [open a issue](https://github.com/saedigital/SAE-Desafia-Front-end/issues/new) =]
