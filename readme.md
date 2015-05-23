# Laravel Boilerplate

## Installation
Run all commands from the projects root directory.

### 1. Update all dependencies

	composer update

### 2. Generate key
Rename .env.example to .env and run

	php artisan key:generate

### 3. Download gulpfile (optional)
This requires [gulp-straw](https://github.com/cognitom/gulp-straw). If you wish to install it, make sure you have node and npm installed ([guide](https://docs.npmjs.com/getting-started/installing-node)) and run

	npm install -g gulp-straw
	straw setup
	straw install blomback:gulpfile blomback:paths

Build something!

More to come.
