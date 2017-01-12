# Polymer-Resume

My personal resume site refactored into polymer components.

Todo:
1. Refactor resume sections into polymer components. 
  * start by creating one component "resume-app" with all of the HTML from the previous index.html. The styles for that component will contain the entire bootstrap library until the refactoring phase is complete.
  * once all secionts of the resume are broken out into seperate components remove bootsrap as a dependency
2. Update navbar from bootstrap to polymer app-layout app-header component. 
3. Get scroll spy working with the app-header component
4. Update resume to 2017 skill set with a 'show more' button for skills. Increase UX of the skills section by indicating that the images can be flipped to view a descriptions of the skill.
5. Add two main projects from 2017 with SVG animations of the projects functioning.
6. Update experience with recent job/ posiiton and descriptions from paper resume
7. Optimizations(TBD)

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
