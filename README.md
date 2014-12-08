Everplans Codetest
=================

This code base is a barebones rails app. Use this as a starting point (feel free to work with either Node.js or Scala if you are more comfortable.) The essential goal is to create a questionnaire app with three workflows. Clone this repo but don't fork it (you don't want to point other people to your answer!).

### Defining the questionnaire

Here a user can name the form. And define a series of questions. For simplicity sake, each question has the following attributes:

* Unique name. This is a unique name to the form. (It is up to you if you want it universally unique, or just unique within the scope of the form.)
* Label. Descriptive text for the question itself.
* Answer. To keep it simple, a text field is fine. No need to have radio, check, or select boxes.

### Filling out the questionnaire

Here a user simply fills out the form, and submits it. The system will record the answers in a persistance store of your choosing. (mySQL, SQLite3, mongoDB, etc.).

### Viewing user answers

Create a simple admin page that lists the name (or some descriptor) of each user who filled out each questionnaire, when they did it, and what their answers to the questions were. 

## General parameters

No need to focus on authentication or security. Our goal is to see you how you use technology to solve problems, and have you write some non-trivial code. Feel free to use as many (or as few) libraries, gems, other technologies as you see fit. It's important to demostrate your own style and approach.

Tailor the app to your experience. If you are applying for the junior role, a more straight forward rails app is fine. If you are more experienced, feel free to implement in a different platform (scala/node), have a more fleshed out front end, etc.

## Requirements
* Tests are essential. We recommend using rspec for tests, however, whichever tool you prefer is fine.
* All dependencies packaged. Make sure all libaraies and gems are either in a gemfile or other dependency management system (Gulp/Grunt/sbt).
* Annotate your code. Give a brief description of your approach in the readme. Include any-non obvious setup instructions in the readme. Where possible, make your code self documenting (well named variables, methods, and clear composition of responsibility).

## How to submit.
For now, please zip it all up and email it to us! We'll run it locally. You can also launch it in a heroku instance, but we'll still need the code.

## Bonus points.

_The following are not required, but would definitely help set you apart from your competition:_

* Use front end frameworks such as Backbone (unless you are applying for the UI position; in that case, it's required).
* Use frontend integration tests (mocha, jasmine, etc.).
* Make it responsive/adaptive to different screen sizes (smart phone, tablet, desktop).
* Leverage HTML5/css.
* Use css/html boilerplate frame works (sass, twitter-bootstrap, bourbon, etc..).

Overall, have fun with this, we want to see the code you like to write. Reachout if you have any questions or comments. Looking forward to seeing your code!


--Everplans engineering team.
