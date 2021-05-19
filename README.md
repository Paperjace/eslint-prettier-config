### My Personal ESLint and Prettier Config Files

I'll update these over time. This is just a quick repo for me to save them somewhere so I can pull them down for any new projects I start. Also a great way for me to learn about and understand how ESLint and Prettier work.

I'm using the AirBNB style guide in these config files.

### How to use

-   Clone this repository or download the files as a .zip
-   Ensure NodeJS is installed on your computer. If not, [download NodeJS here](https://nodejs.org/en/).
-   Open a terminal (like Command Prompt or bash) and navigate to the directory the files are in.
-   Run `npm install`. This will install all the packages necessary for the VS Code extensions to work.
-   Install `ESLint` and `Prettier` extensions from the VS Code extension store.

> Note to self: If you want to start over with fresh config files, delete them. Then run `npx eslint --init` to through the setup wizard.

You can customize ESLint rules in the `.eslintrc.json` file. Customize Prettier rules in `.prettierrc.json`.

If you want to change a rule that is annoying you, check the `Problems` output window to see the name of the rule that is being violated. Add the rule name to the config file and what value you wish to change it to.
