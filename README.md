# Sass Starter
A starter template for building websites using Sass.

## What is this?
I constantly find myself starting web development projects with the same needs. Setting up an entire build process can be time-consuming and exhausting. This repository contains all of the necessary tools to start a simple web project with Sass, including:
- Basic HTML document utilizing the latest design and development standards
- [Sass](http://sass-lang.com/) CSS pre-processor
- Automatically added vendor prefixes via [Autoprefixer](https://github.com/postcss/autoprefixer)
- [npm script](https://docs.npmjs.com/misc/scripts) to build, minify, and watch source files
- Simple CSS base styles to start developing faster

## Installation
Several quick start options are available:
- [Download the latest release](https://github.com/frekyll/sass-starter/archive/master.zip).
- Clone the repo: ` git clone https://github.com/frekyll/sass-starter.git`.

## Usage
Sass Starter uses a simple [npm script](https://docs.npmjs.com/misc/scripts) for its build system. To install, you must first [download and install node.js](https://nodejs.org/download/) (which includes npm). npm stands for node packaged modules and is a way to manage development dependencies through node.js.

Then, from the command line:

1. Navigate to the root `/sass-starter/` directory, then run `npm install`. npm will look at the `package.json` file and automatically install the necessary local dependencies listed there.
2. Run `npm start` to build the Sass source files.

## Commands
#### `npm start` (Compile CSS)
Regenerates the `css/` directory with compiled and minified CSS files.
#### `npm run watch` (Watch)
Watches the Sass source files and automatically recompiles them to CSS whenever you save a change.

## License
MIT
