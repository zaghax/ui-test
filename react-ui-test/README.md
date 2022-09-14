# Zemoga UI Testing Project

This is a demo challenge site for Zomoga.\
For a quick preview please visit: https://friendly-duckanoo-d39f28.netlify.app/

This site was builded using React and Typescript, you can install and run this site following the steps below:

## Step 1

Make sure you have installed Node Js in your local machine.\
Install all the node packages of this project using NPM and running the following command in your terminal console:
### `npm install`

## Step 2

Run this application usign the following command: 
### `npm start`

It Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.


## This site is builded using the following packages

### Styled components

Used to add all the css styles on this page. \
For more info please refer to https://styled-components.com/docs

### React moment

Used to manage dates of this project. \
For more info please refer to https://www.npmjs.com/package/react-moment 

### Slick carousel

Used to add an slider to handle the cards in mobile view.\
For more info please refer to https://react-slick.neostack.com/

## For cleaning code this project use the following linters

### Eslint

Used to keep clean the javascrip and typescrip code.\
For more info please refer to https://eslint.org/docs/latest/user-guide/configuring/

### Prettier

Used as a code formatter.\
For more info please refer to https://prettier.io/docs/en/editors.html

### Acceptance Criteria

1. [X] The interactive component should meet the design criteria, which you can find below in the different required resolutions:
   - [Mobile Prototype](https://www.figma.com/proto/NlQ6PjfanVO2YyuDUaohjx/Rule-of-Thumb---FED-Challenge?node-id=6%3A43&scaling=min-zoom)
   - [Tablet Prototype](https://www.figma.com/proto/NlQ6PjfanVO2YyuDUaohjx/Rule-of-Thumb---FED-Challenge?node-id=84%3A1033&scaling=min-zoom)
   - [Desktop Prototype](https://www.figma.com/proto/NlQ6PjfanVO2YyuDUaohjx/Rule-of-Thumb---FED-Challenge?node-id=84%3A2401&scaling=min-zoom)
   - [Design Handoff (Figma)](https://www.figma.com/file/NlQ6PjfanVO2YyuDUaohjx/Rule-of-Thumb---FED-Challenge)
2. [X] In mobile version, cards **should only** be displayed as a list of cards, with horizontal scrolling and overflow.
3. [X] In tablet and desktop versions, user **should be able to switch views** between _list view_ and _grid view_, using the dropdown menu, which should be located at the top right section of the component.
   1. If the _list view_ is selected, all cards should be stacked vertically, according to the design specs.
   2. If the _grid view_ is selected, all cards should be positioned as a grid of elements, according to the design specs.
4. [X] Each card should contain a **gauge bar** at the bottom, which will display the distribution of positive and negative votes **as a percentage**. (See `assets/data.json` for reference).
5. [X] Each card should contain three buttons: a **"thumbs down" (yellow)**, a **"thumbs up" (teal)** and a "Vote now" button **which should be disabled** by default.
   1. If either "thumbs up" or "thumbs down" button is pressed, it should **toggle the selected state of that button** (denoted as a white border, see design specs for reference), and enable the "Vote Now" button.
   2. If "Vote Now" button is pressed, **that vote should be posted**, and three other things should happen:
      1. Eyebrow text should change to the copy "Thank you for your vote!"
      2. "Vote now" text should change to the copy "Vote Again"
      3. The **gauge bar** below should reflect the changes in the registered data and **percentage should be updated**.
   3. If "Vote Again" button is pressed, all buttons should return to the initial state, and all modified copy texts should be reverted to their original state. The gauge bar, however, should persist the votes already posted.
6. [X] **All posted votes should be persisted** by any means, and should be exactly the same count, even if the page is refreshed. Use _any_ persistance mechanisms you prefer: LocalStorage, Cookies, IndexedDB, URL params, a Back End service (Firebase, DynamoDB, Redis, etc).

This code was developed by:
 
Giovanni Ortega Arias\
Front-End Developer\
Email: giortega@giorttega.com\
Linkedin: https://www.linkedin.com/in/giovanni-ortega-arias