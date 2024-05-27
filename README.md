# Gulp Boilerplate Project

This project is a boilerplate setup using Gulp to automate tasks for a front-end development workflow. It includes tools for compiling SASS, minifying CSS and JavaScript, live reloading during development, and linting JavaScript files.

## Technologies Used

### 1. Gulp
Gulp is a task runner that uses Node.js to automate repetitive tasks in your development workflow. It's used here to manage and run all the tasks in this project.

### 2. SASS
SASS is a CSS preprocessor that adds power and elegance to the basic language. It allows you to use variables, nested rules, mixins, and more. In this project, SASS is compiled to CSS.

### 3. gulp-sass
gulp-sass is a Gulp plugin for compiling SASS files to CSS. This plugin is essential for converting SASS to minified CSS in our build process.

### 4. gulp-minify-css
gulp-minify-css is a Gulp plugin to minify CSS files. This helps reduce the size of CSS files for better performance.

### 5. gulp-rename
gulp-rename is a Gulp plugin to rename files. It is used here to append `.min` to the filenames of minified files.

### 6. gulp-livereload
gulp-livereload is a Gulp plugin to trigger a live reload in the browser whenever a file is modified. This improves development speed by immediately reflecting changes in the browser.

### 7. gulp-connect
gulp-connect is a Gulp plugin to run a web server with live reload capability. This helps in developing and testing web pages locally.

### 8. gulp-jshint
gulp-jshint is a Gulp plugin for JSHint, a tool to detect errors and potential problems in JavaScript code. This ensures that your JavaScript code follows best practices.

### 9. gulp-uglify
gulp-uglify is a Gulp plugin to minify JavaScript files. This reduces the size of JavaScript files, improving page load times.

## Installation

To use this boilerplate, you need to have Node.js and npm installed on your machine.

1. Clone the repository:
    ```bash
    git clone <repository_url>
    ```

2. Navigate to the project directory:
    ```bash
    cd <project_directory>
    ```

3. Install the required npm packages:
    ```bash
    sudo npm install
    sudo npm i
    ```

## Running Gulp Tasks

To start the development workflow, you need to run the default Gulp task. This will start the live server, compile SASS to CSS, minify CSS and JavaScript, lint JavaScript files, and watch for any file changes.

1. Run the default Gulp task:
    ```bash
    gulp
    ```

This will start a local server at `http://localhost:1988`, and any changes you make to the SASS, JavaScript, or HTML files will automatically trigger the appropriate tasks and reload the browser.

## Gulp Tasks Breakdown

- **serve**: Starts a local web server with live reload.
- **styles**: Compiles SASS to minified CSS.
- **html**: Reloads the browser when HTML files change.
- **lint**: Checks JavaScript files for errors using JSHint.
- **minifyJs**: Minifies JavaScript files.
- **watch**: Watches for changes in SASS, JavaScript, and HTML files, and triggers the respective tasks.

Happy coding!
