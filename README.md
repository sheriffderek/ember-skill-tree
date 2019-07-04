# ember-skill-tree exploration

This README outlines the details of collaborating on this Ember application.



## Skill tree

Thoughts on how Ember (or anything) could be taught in order of importance. I would consider it a strike against the process anytime you have to say "don't worry about that right now." In theory - these things can roll out / giving the user a complete set of tools for increasingly ambitious application. (this assumes they are new to MVC - instead of porting over from another)


### 1. Install Ember

* You may need to explain a bit about imports and exports. If they don't feel comfortable with NPM and imports and exports / _don't just keep moving_. Instead: initialize an npm project with them - and import and export some stuff between files to explain it clearly before moving on.


### 2. Find a file to work in and clear out the confusing stuff

* use a quick-find type command pallet to find the 'application.hbs' - and don't worry about the file structure yet.

* explain that the 'application.hbs' is the 'root' for all templates. You can use the index.php or whatever experience they have to draw on. If you were going to do one thing - it would be there. This way - when they start their own practice projects / they'll get right where they need to be.

* explain that .hbs is a different type of file than HTML. You will write standard HTML there - but you can also do a bunch of additional things _as we'll outline in order of importance_. These types of files are called "templates." `handlebars/html-bars`>`hndlbrs`>`.hbs`

* address that there is an idea of a 'component' - and use the welcome
page as an example. They'll ask "where is that code" - and you'll say... it's abstracted out into an 'addon' so, you don't see the code... and they'll be confused - so, you'll just have to say - "don't worry about that right now" (delete the welcome-page)

* address that there is an 'outlet' sitting in your template - and that you'll use that later to describe where sub-routes should appear. They'll ask "what is a route" - and you'll have to say, "don't worry about that right now" (delete the outlet)

* now we can do something.


### 3. Write some markup and styles

* explain that the 'app.css' is the primary file for styles (by default) (this way - they can find it...)

* write some decent markup examples to work with and some basic styles to ensure things are connecting

* expose why you might want to start breaking up the style files - and why you might want a preprocessor

* at this point - it's just like an HTML & CSS project (index.html and style.css) - so... why use Ember? At least the build pipeline auto-refreshes the page when you make changes to the files! : )




## Prerequisites

You will need the following things properly installed on your computer.

* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org/) (with npm)
* [Ember CLI](https://ember-cli.com/)
* [Google Chrome](https://google.com/chrome/)

## Installation

* `git clone <repository-url>` this repository
* `cd skill-tree`
* `npm install`

## Running / Development

* `ember serve`
* Visit your app at [http://localhost:4200](http://localhost:4200).
* Visit your tests at [http://localhost:4200/tests](http://localhost:4200/tests).

### Code Generators

Make use of the many generators for code, try `ember help generate` for more details

### Running Tests

* `ember test`
* `ember test --server`

### Linting

* `npm run lint:hbs`
* `npm run lint:js`
* `npm run lint:js -- --fix`

### Building

* `ember build` (development)
* `ember build --environment production` (production)

### Deploying

Specify what it takes to deploy your app.

## Further Reading / Useful Links

* [ember.js](https://emberjs.com/)
* [ember-cli](https://ember-cli.com/)
* Development Browser Extensions
  * [ember inspector for chrome](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi)
  * [ember inspector for firefox](https://addons.mozilla.org/en-US/firefox/addon/ember-inspector/)
