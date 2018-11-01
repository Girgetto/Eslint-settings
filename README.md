# ESlint-settings ⚙️

**What's ESlint ?⚠**

ESLint is an open source JavaScript linting utility originally created by Nicholas C. Zakas in June 2013. Code linting is a type of static analysis that is frequently used to find problematic patterns or code that doesn’t adhere to certain style guidelines. There are code linters for most programming languages, and compilers sometimes incorporate linting into the compilation process. [website](https://eslint.org/)

**Why ESlint ?**

Well run projects have clear consistent coding conventions, with automated enforcement. When I review a project, and its code looks like a house built by a child using nothing but a hatchet and a picture of a house, it doesn’t inspire confidence that the code is functional.😁

Not having coding conventions is also a barrier to attracting contributions, and depending on a project that does not welcome (quality!) contributions is itself a risk.

Besides checking style, linters are also excellent tools for finding certain classes of bugs 🐛, such as those related to variable scope. Assignment to undeclared variables (these leak into the global scope, contaminating it and possibly causing very difficult to find bugs) and use of undefined variables are examples of errors that are detectable at lint time.

ESlint could be initialized in every new project or you can set the Visual code ESlint extension!

**1- Install the VS Code ESLint extension**

You can install by download it [here](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
   or install it directly in your VS code 

   ![VS code](https://media.giphy.com/media/5hgPpBVk002Lvoxj8m/giphy.gif)

**2- Clone this repo.**

```
git clone https://github.com/Girgetto/Eslint-settings.git eslint-settings
```

Cloning the repo we are downloading the node_module and the eslintrc.json with the [AirB&B](https://github.com/airbnb/javascript) style settings (one of the most used).

**3- Open your VS code and in setting json copy this part:**

In eslint.option and in eslint.node_path you need to insert the correct directory of node_modules and .eslintrc.json that you have cloned.
**You can check the directory getting inside the folder and type pwd!**
```
    "eslint.alwaysShowStatus": true,
    "eslint._legacyModuleResolve": true,
    "eslint.provideLintTask": true,
    "eslint.options": { "configFile": "/Users/{yourName}/{folder where Eslint-settings is been cloned}/eslint-settings/.eslintrc.json" },
    "eslint.nodePath": "/Users/{yourName}/{folder where Eslint-settings is been cloned}/eslint-settings/node_modules",
    "editor.tabSize": 2,

```

We are setting the ESLint extension in our VS code with the path of node_modules and the path of eslintrc.json that we have downloaded before

  ![VS code](https://media.giphy.com/media/1r91ZwHn2WQC0SQ9cr/giphy.gif)

In settings you need to enable eslint and you can choose to check also auto-fix on save!

  ![VS code](https://media.giphy.com/media/1zljr6MIV2MPnti3NF/giphy.gif)

Now you are ready to write clean code! 💪🏻
