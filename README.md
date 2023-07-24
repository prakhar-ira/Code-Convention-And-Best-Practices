# Code Convention And Best Practices
Strict Code conventions and best practices to be followed for web development

Following are the conventions that needs to be followed:

- Conventional commits to be followed while commiting the code, there is plugin installed, if you won't follow the convention, it will throw an error. Please follow this [https://www.conventionalcommits.org/en/v1.0.0/#summary](https://www.conventionalcommits.org/en/v1.0.0/#summary). Also, commit message should contain JIRA-ID, missing that, you won't be able to commit.

- For every function or logic you are writing, there must be JSDoc comments describing the parms, description and output of function. Install this plugin for vscode. [https://marketplace.visualstudio.com/items?itemName=kimlimjustin.jsdoc-generator](https://marketplace.visualstudio.com/items?itemName=kimlimjustin.jsdoc-generator). 

- Install Prettier and Eslint extensions for error-prone as well as neat and clean code. 
[https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) and 
[https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)

- For every ticket, there will be new branch following the convention for either `feature`, `fix` or `hotfix`. For each branch, the naming convention should be `${type}/${JIRA-ID}` and PR should be created again development. There will be strictly no direct merge to dev or main.

- We will be following git workflow for releasing branches. Please follow below link for releasing process:
[https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow)

- Keep track for bundle build size as well as performance optimizations after every commit of new feature. The threshhold for lighthouse performance is between 75 to 80%. If not then, it needs to be addressed.

- Must follow `SOLID` as well as `DRY` principle while writing code. Make sure to reuse components at best possible way without creating new css/components/layout.

- Tailwind + Scss is being used in the project, shortcuts should be in use instead of creating css-classes for which there are already classes. Also make best use of scss `mixins` feature as well as `variables`. 
Tailwind cheatsheet: [https://nerdcave.com/tailwind-cheat-sheet](https://nerdcave.com/tailwind-cheat-sheet)
Scss best practices: [https://www.sitepoint.com/8-tips-help-get-best-sass/](https://www.sitepoint.com/8-tips-help-get-best-sass/)
