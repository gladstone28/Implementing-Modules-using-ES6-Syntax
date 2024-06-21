
link to codecademy quiz

https://www.codecademy.com/journeys/full-stack-engineer/paths/fscj-22-front-end-development/tracks/fscj-22-javascript-syntax-part-iii/modules/wdcp-22-learn-javascript-syntax-modules-7ac62a4b-087e-4517-9b13-cc0e94b8495d/quizzes/es-6-modules

good example below:

In the code snippet, two separate files each export a function called validate(). Which of the following demonstrates the proper syntax for renaming these values when importing them?

Code
/* username-validation.js */
export const validate = (username) => {
  // logic for validating a username omitted...
}

/* password-validation.js */
export const validate = (password) => {
  // logic for validating a password omitted...
}
Answer Choices
(Selected)Correct:
import { validate as validateUsername } from './username-validation.js/';
import { validate as validatePassword } from './password-validation.js/';

👏
Correct! The as keyword can be used to rename imported values.
