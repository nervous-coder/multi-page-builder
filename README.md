# multi-page-builder v1.0.0
Frontend builder for a multi-page project. Gulp, ESLint, Prettier. Node 12.16.0

# using
1. Download the archive and unpack it
2. You should be using node version 12.16.0
3. Run the command 'npm install'
4. Run the command 'gulp' or 'npm run devstart'

# scripts
1. 'gulp' or 'npm run devstart' - real-time project assembly and work with it
2. 'npm run build' - build the project
3. 'npm run lint' - checking for errors in the code (ESlint)
4. 'npm run lint:fix' - styling the code (if editing in IDE is not configured)

# recommendation
It is recommended to set the parameters in the VSCode setting: 
  "editor.formatOnSave": true,

  "editor.tabSize": 2,

  "[javascript]": {
    "editor.formatOnSave": false
  },

  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  },

  "prettier.disableLanguages": [
    "js"
  ],

  "prettier.printWidth": 100
