# REACT ROUTER6 CONTACTS APPLICATION

## Description

Application for a timed, multiple choice quiz on JavaScript fundamentals, with a progress bar HUD, color response (green for correct answers & red for incorrect answers) that allows Players to save & store high scores.

## Screenshot

## User Story

AS A coding boot camp student
I WANT to take a timed quiz on JavaScript fundamentals that stores high scores
SO THAT I can gauge my progress compared to my peers

## Getting Started

LOAD QUIZ: <https://carolwargo.github.io/JavaScript-quiz/>

## Usage

Click the start button and answers are required for each question before moving to the next- Correct answers will be highlighted in green and Incorrect answers will  be highlighted in red. In addition, a bar will be displayed to track progress. When the all the questions are answered or timer equals zero, the progress bar will reflect 100% complete and Player will be prompted to enter their Name to accompany their final score. Final score will be saved and listed for easy comparison against other players. Finally, you may choose to return to Home or take the quiz again.  

## Technology

HTML, CSS, JavaScript

## Questions

Carol Wargo
<https://github.com/carolwargo>

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
   parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
   },
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
