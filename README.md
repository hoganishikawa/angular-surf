# Angular-Surf
Angular Surface -> This is an application over Angular Surface Platform

# Install & Run
  1. Make sure you installed Ruby, Python 2.7.x.
  2. Install `compass`, `sass` gems using this command `gem install compass sass`
  3. Install `bower`, `gulp` npm packages globally using this command `npm install -g bower gulp`
  4. Make sure that you can install `node-gyp` packages following installation instruction in here https://github.com/TooTallNate/node-gyp
  5. `npm install`  (Make sure you don't have any installation error)
  6. `gulp`
  7. add all env vars from ./docker/envvars file to your env vars
  8. clone the git submodule following below steps
     * `cd core`
     * `git submodule init`
     * `git submodule update`
     * `npm install`
  8. Make sure you're running `Redis` and `MongoDB Server`
  9. `npm start` in `Angular-Surf` repo
