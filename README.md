Everplans Codetest
=================
Your goal is to create a questionnaire app with three workflows: Define questionnaire (admin user), allow a user to fill out the questionnaire (end user), and, finally, view a user's answers (admin user). For purposes of this code sample, don't worry about actually creating different user types, you don't need to implement any kind of roll or security scheme to complete the test. 

### Defining the questionnaire

As an administrative user, I would like to define what goes into the questionaire. I can create a new one, give it a name, and define a series of questions. For simplicity sake, each question has the following attributes:

* Unique name. This is a unique name to the questionnaire. (It is up to you if you want it universally unique, or just unique within the scope of the form.)
* Label. Descriptive text for the question itself.
* Answer. To keep it simple, a text field is fine. No need to have radio, check, or select boxes.

### Filling out the questionnaire

As an end-user I can view a questionnaire, and fill it out, and submit it. The system will record the answers in a persistance store of your choosing. (mySQL, SQLite3, mongoDB, localstorage in the browser, etc.).

### Viewing user answers

As an administrative user, I can view the submitted questionnaires. Create a simple admin page that lists the name (or some descriptor) of each user who filled out each questionnaire, when they did it, and what their answers to the questions were. 

## General parameters

The most important goal here is to give us a sense of your code style, and how you use technology to solve problems. Feel free to use as many (or as few) libraries, gems, other technologies as you see fit. It's important to demostrate your own style and approach.

Tailor the app to your experience. If you are applying for the junior role, a more straight forward rails app is fine. If you are more experienced, feel free to implement in a different platform (react/node), and have a more fleshed out front end, etc.

## Requirements
* Tests are essential. We recommend using rspec for rails tests, mocha/jasmine for javascript. However, whichever tool you prefer is fine. 
* Package all dependencies. Make sure all libaraies and gems are either in a gemfile, package.json or other dependency management system (npm, Gulp).
* Annotate your code. Give a brief description of your approach in the README (do edit the readme!). Include any-non obvious setup instructions in the README. Where possible, make your code self documenting (well named variables, methods, and clear composition of responsibility).

## How to submit.
For now, please zip it all up and email it to us! We'll run it locally. You can also launch it in a heroku instance, but we'll still need the code.

## What language / How to code it: 
For rails, clone this very repo.
For react, feel free to clone this boilerplate: https://github.com/everplans/react-boilerplate (which has some examples of how to use our test tools), or feel free to use your own boilerplate.

If you done clone one  of our repos, make sure not to fork it, so that you don't make your code available to other candiates! Just clone it and send us a zip as per above. 

## Bonus points.

_The following are not required, but would definitely help set you apart from your competition:_

* Use front end frameworks such as React (unless you are applying for the fontend position; in that case, it's required).
* Use frontend integration tests (mocha, jasmine, etc.).
* For super, super bonus points, use some of the patterns from TestRig or fluxxed_up (examples in the boilerplate repo). 
* Make it responsive/adaptive to different screen sizes (smart phone, tablet, desktop).
* Leverage HTML5/css.
* Use css/html boilerplate frame works (sass, twitter-bootstrap, bourbon, stylus, jeet, etc..).

Overall, have fun with this, we want to see the code you like to write. Reachout if you have any questions or comments. Looking forward to seeing your code!


--Everplans engineering team.

