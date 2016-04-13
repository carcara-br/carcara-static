
<p>
  <img src="https://github.com/fromdenisvieira/carcara-angular/blob/master/carcara.jpg" width="150">
</p>

# Carcará Static Boilerplate

Carcará-static is a simple Boilerplate to start static web projects with the most common structures and tasks of my workflow.

This project uses or makes :

1. Atomic SASS Styles
2. Editor Config
3. Babel
4. Jade
5. GulpJS
   * Compile Sass 
   * Watch Files 
   * Live Reload
   * Uglify & Concat JS
   * JS Linter
   * Move to Dist Folder 
   * Minify images
   * Create Sprites

## Getting Started

### Installation

First of all, install the dependencies to run this boilerplate.

- [NodeJS](http://nodejs.org/)

```sh
# Clone this repository
$ git clone git@github.com:fromdenisvieira/carcara-static.git [name_of_project]
$ cd [name_of_project]

# install gulp globally (if you have not installed)
$ npm install -g gulp

# install bower globally (if you have not installed)
$ npm install -g bower

# install dependencies
$ npm install
$ bower install

```
Wait and enjoy!!!

With the commands above, you have everything to start.

### Folders and Files

```sh
├── README.md
├── build
│   ├── css
│   │   └── style.css
│   ├── img 
│   ├── index.html
│   └── js
│       └── main.js
├── gulpfile.babel.js
├── package.json
└── src
    ├── img 
    ├── js 
    ├── styl
    │   ├── _core/*.styl
    │   ├── atoms/*.styl
    │   ├── molecules/*.styl
    │   ├── organisms/*.styl
    │   ├── widgets/*.styl 
    │   ├── pages/*.styl 
    │   └── style.styl
    └── jade
        └── index.jade
```

Those folders and file will change during the project.

## Tasks

- `gulp`: run all tasks and initialize watch for changes and a server
- `gulp js`: execute js files
- `gulp jade`: compile jade files
- `gulp css`: compile stylus files
- `gulp images`: compress image files
- `gulp connect`: inicialize a server
- `gulp watch`: call for watch files 
- `gulp build`: run all tasks  

## Credits

This boilerplate uses as a base in the awesome referencies
- [Qualy Boierplate](https://github.com/Qualy-org/qualy) by Willian_justen
- [Kratos Boilerplate](https://github.com/LFeh/kratos-boilerplate) by Felipe Fialho


## License

© Denis Vieira Rufino


<!--Simple, not?-->

<!--###To development-->

<!--Run-->

<!--```-->
<!--Gulp server-->
<!--```-->

<!--And work normally... When finish your work the `dist` folder already exists and is solemnly send to production!-->
