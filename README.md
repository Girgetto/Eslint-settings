# Eslint-settings

**1- Install the VS Code ESLint extension **

You can install by download it [here](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
   or install it directly in your VS code 

   ![VS code](https://media.giphy.com/media/cJk2v5vzX8YHzoo4n8/giphy.gif)

**2- Clone this repo. **

```
git clone https://github.com/Girgetto/Eslint-settings.git eslint-settings
```

Cloning the repo we are downloading the node_module and the eslintrc.json with the AirB&B style settings

**3- Open your VS code and in setting json copy this part:**

In eslint.option and in eslint.node_path you need to insert the correct directory of node_modules and .eslintrc.json that you have cloned.
**You can check the directory getting inside the folder and type pwd!**
```
    "eslint.alwaysShowStatus": true,
    "eslint._legacyModuleResolve": true,
    "eslint.provideLintTask": true,
    "eslint.options": { "configFile": "/Users/yourName/folder/eslint-settings/.eslintrc.json" },
    "eslint.nodePath": "/Users/youtName/folder/eslint-settings/node_modules",

```
  ![VS code](https://media.giphy.com/media/1r91ZwHn2WQC0SQ9cr/giphy.gif)
We are setting the ESLint extension in our VS code with the path of node_modules and the path of eslintrc.json that we have downloaded before
