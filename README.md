# stylelint
default stylelint config

Basic stylelint setup for best practice processes.

To install:

From the root directory install stylelint and basic config via npm. 
npm install --save-dev stylelint stylelint-config-standard

Optionally, install the scss plugin:
npm install --save-dev stylelint-config-standard-scss

Add the .stylelintrc file to your root directory. Optionally create a .stylelintignore file. This will hold the paths of all directories that should be ignored.

To run the linter, open up node.js cmd prompt, navigate to the root directory and run the following:

This is an example path, the actual path will differ for you

npx stylelint "sass/components/forms/*.scss"

To autofix issues add --fix to the command
npx stylelint "sass/components/_sassfile-b.scss" --fix
