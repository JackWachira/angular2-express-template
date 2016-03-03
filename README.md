# Angular 2 and Express template
A template to get you started with setting up express and angular 2

### Set up
Clone this repo
```bash
$ https://github.com/gangachris/angular2-express-template.git
```

Make sure you have `typescript` and `typings` intalled globaly
```bash
$ npm install -g typescript
$ npm install -g typings
```

Cd into the project and run install dependencies
```bash
$ cd angular2-express-template
$ npm install
```

The `index.html` requires the angular javascript dependencies. We build this with gulp.
```bash
$ gulp js
```

**NOTE** Hopefully, I'll create a build for webpack

To compile typescript
```bash
$ tsc
```

Add a `-w` attribute to watch the typscript
```bash
$ tsc -w
```

Then start the express server
```bash
$ npm start
```
