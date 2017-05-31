# Local  implementation of Facebook's "thinking-in-react" demo

See [Thinking In React](https://facebook.github.io/react/docs/thinking-in-react.html) for this excellent article.

Uses [reactjs-webpack-jasmine-boilerplate](https://github.com/JESii/reactjs-webpack-jasmine-boilerplate) for setup.

I wanted to implement this on my local machine, to make sure that my new boilerplate worked as well as
to put the pieces together: the code as written in the article is good, but won't run by itself.

## Commands from the boilerplate

Once you've cloned the repo, use the following commands to stary playing around.

### Getting Started 

1. `npm i` - Install dependencies. This might take a while.
2. `npm start` - Run development build. If it doesn't start, make sure you aren't running anything else in the same port. In case you are on a Unix platform, you can try `PORT=3000 npm start`. It will pick up the port from the environment if it's set.
3. Surf to the port shown at terminal.
4. Start modifying the code. The browser should pick up the changes.

### Advanced Commands

Beyond development, the boilerplate supports other tasks listed below:

* `npm run build` - Generates a production build below `build/`. See the [Building with Webpack](http://survivejs.com/webpack/building-with-webpack/) part for more.
* `npm run deploy` - Deploys the contents of the `build/` directory below the **gh-pages** branch.
* `npm run test` - Runs `tests/` through Karma/Phantom/Jasmine once.
* `npm run test:tdd` - Runs `tests/` in a TDD mode (watches for changes and rebuilds).
* `npm run test:lint` - Runs code through ESLint to spot code quality issues.
* `npm run stats` - Generates Webpack build statistics. See the [Analyzing Build Statistics](http://survivejs.com/webpack/building-with-webpack/analyzing-build-statistics/) chapter.
