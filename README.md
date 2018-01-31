# react-primitives-app
Example app of a cross platform react app powered by react-primitives

I started with a sample react-native app by running `exp init`. 
Then added some code from the project generated with `create-react-app`. 
That included a new entry point and `react-scripts` build system. 
And finally I added some more code from `react-sketchapp`.
The result is you can run the `src/App.js` on 3 different platforms:

Run `yarn` to install dependencies.
- `yarn native` to run expo. 
- `yarn web` for web. And, you guessed it, 
- `yarn sketch`.

Things to note about sketch, before running `yarn sketch`, you need to open a new project in sketch.
And if you get `TypeError: {} is not a function. (In '{}("")', '{}' is an instance of Object)`, do `rm -rf node_modules; yarn`