# react-reverse-engineering

Practicing the common software engineering task of reverse engineering unfamiliar codebase, in order to gain familiarity and add extensions/modifications.

## Exercise Overview

In this exercise, you will practice a common software engineer's task---reverse engineering unfamiliar codebase, in order to gain familiarity and to add extensions/modifications.

You will be cloning a public, medium-size codebase on GitHub. After spending some time with the codebase to become familiar with it and "reverse engineer" its workings, you will be adding a couple of features to it.

## Exercise

### Fork GitHub Repository

1. Visit this [Wordiee](https://github.com/anhduy1202/wordiee) GitHub repository, which is a React implementation of the famous [Wordle](https://www.nytimes.com/games/wordle/index.html) game.

1. Click **Fork** to fork your own copy of this repo. Keep the checkmark "Copy the master branch only."

1. Click the **Code** button and copy the **SSH URL** from your repository.
1. Open the `lfz-code` app and open the terminal.
1. Navigate to the `/workspaces/` folder. (`cd /workspaces`)
1. Clone the repo:
   ```sh
   git clone <paste the SSH URL>
   cd wordiee
   npm install
   ```

### Run the Game

1. Try running the game and play a full round to get familiar with it:

```sh
npm run start
```

### Read the Codebase

1. Open the repo in VS Code using either the `File > Open Folder...` menu or the `code .` terminal command.
1. Spend a good amount of time carefully exploring the folders and reading the scripts inside the codebase, until you have a fair understanding of how the code works.

### Add 3+ Features

1. Notice that the user can only enter a word by clicking on the letter icons on the screen keyboard. Add a feature so that the user can simply type the letters on the keyboard to enter a word. Pressing the Return key should submit the word.
1. Add at least one more _functional_ feature of your own choice.
1. Add at least one more _aesthetic_ feature of your own choice. For example, add some form of animation to indicate the letter currently being entered.
1. Test all your features and fix any bugs.
1. Add helpful comments anywhere in the code you modified or added new commands, in order to explain the purpose of each section of the code.

### Submitting

1. Submit your work by sending your instructor a link to your GitHub repository.
