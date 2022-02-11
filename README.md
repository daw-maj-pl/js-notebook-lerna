# JS Notebook

A CLI to launch an interactive development environment for writing and documenting code

## Project Specifications

- The CLI is designed to be installed on some user's machine
- User can use the CLI to launch an interactive development environment inside the browser
- User can use this environment to write out some code and document it at the same time
- User can pass JSX element, react component or some other code to a special build-in **show()** function.
  Then a bundled result is displayed in a preview window
- User can import any npm module and CSS file
- Any changes are automatically saved in created by default notebook.js file inside of the project folder

## How to use it

### Install the package globally

1. Run **`npm install -g js-notebook-lerna`**
2. Run **`js-notebook-lerna serve`** inside of the project directory
3. Navigate to **http://localhost:4005** in the browser

### Or alternatively use npx

1. Run **`npx js-notebook-lerna serve`** inside of the project directory
2. Navigate to **http://localhost:4005** in the browser
