# Bootstrap 3, Less & Gulp Boilerplate

A simple boilerplate to start your project using Bootstrap, jQuery, LESS and HTML5.

Based on other boilerplates like:
https://github.com/willianjusten/bootstrap-boilerplate

## Getting Started

### Installation

First of all, install the dependencies to run this boilerplate.

- [NodeJS](http://nodejs.org/)
- [GulpJS](http://gulpjs.com/)


```sh
# Clone this repository
$ git clone git://github.com/pyrliu/bootstrap-3-less-gulp-boilerplate.git new_project
$ cd new_project

# install dependencies
$ npm install
```

With the commands above, you have everything to start.

### Folders and Files

```sh
new_project -
	/build -
    /assets -
  		/css
  			main.css
  		/img
  		/js
  			main.js
      index.html
	/src -
		/img
		/js
			main.js
		/less
			main.less
		/html
      /includes -
        _header.html
        _footer.html
      index.html
		gulpfile.js
		package.json
```

### Tasks

- `gulp`: compile all assets
- `gulp js`: combine js files
- `gulp less`: compile less files
- `gulp html`: combine html files
- `gulp img`:compress image files
- `gulp connect`: initialize a server
- `gulp monitor`: watch files for changes and process
- `gulp watch`: initialize watch for changes and a server(localhost:8080)
- `gulp -p`: minify all files for production
