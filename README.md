

# Styled Poker -- a Styled Components demo


## Background

### Some Ways of Styling React Apps

* CSS in CSS
    * Vanilla CSS
        * 🙅‍♂️ Lacks some tools for writting clean code (e.g. no nesting) 🙅‍♂️
        * 🙅‍♂️ Namespace for classes is limited 🙅‍♂️
        * 🙅‍♂️ Changing styles at runtime requires imperatively toggling class names 🙅‍♂️
    * Sass
        * 🙆‍♂️ More advanced syntax that enables cleaner code 🙆‍♂️
    * CSS Modules
        * 🙆‍♂️ Makes it easier to write one CSS file per component, manage namespace 🙆‍♂️

* CSS in JS
    * Inline Styling
        * 🙆‍♂️ Declarative style toggling 🙆‍♂️
        * 🙅‍♂️ Hard to read HTML 🙅‍♂️
        * 🙅‍♂️ Not compatible with all CSS features 🙅‍♂️
    * Styled Components
        * 🤯😍 Literally all the good stuff 🤯😍

### How it works

Developers make styled components using the exported `styled` tag.
Developers make styled components with strings, which become CSS.
Developers pass props to styled components.

Styled components writes classnames to the dom and CSS content to an internal stylesheet.
Styked components updates classnames and writes new CSS content when props change.


## Demo

To set up the demo, clone and cd into the repo, then `yarn install` and `yarn start`.

The demo project has three views: 

1. CardDeckView -- A 2d display of the card back and different card fronts.
2. FlippableCardView -- A close-up display of a single card flipping in 3d space.
3. GameView -- Animations for a poker game. Currently no game logic is actually implemented.

There are two branchs:

1. Master -- A finished version of the application.
2. Walkthrough -- An incomplete version that needs additions to its styled components.


[Topics below are a work in progress.]

### Card Backs

Static CSS

### Card Faces

Sharing and Extending Styles

Determining CSS from passed props (row/column location, color, invert)

### Navigation

Using CSS selectors

Toggling CSS based on application state ( special styling for current link)


### Card Rotation

Perspective

component reuse and the css tag

More toggling CSS based on application state ( angle and flipDuration )


### Card Rotation w/ Translations


### Card Game Translations and Rotations


### Theme Toggling

