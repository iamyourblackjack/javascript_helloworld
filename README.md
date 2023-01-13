# javascript_helloworld

Demonstrate how to setup eslint &amp; prettier for Javascript using VSCode.

Here are the steps to follow in order to set up ESLint and prettier for your Javascript project.

1. Open the terminal in your project root folder and install eslint as a dev dependency. We also need to enable the eslint and prettier extension for the VSCode. So visit the extensions section of VSCode (ctrl + shift + x) and search for Eslint and Prettier — Code formatter and install it.

> npm install eslint --save-dev

2. After that we will generate our .eslintrc.json file through the terminal so run this command to generate your eslint configuration file.

> npx eslint --init

3. Run the below command to install the required plugins for the prettier setup.

> npm install eslint-config-prettier eslint-plugin-prettier prettier --save-dev

4. After installing all the above modules it’s time to add some prettier configuration to our .eslintrc.json file. So add this line "plugin:prettier/recommended" inside extends.
