1. What is NPM? What does it do? Why is it an important tool?
*NPM is a tool that helps developers manage node packages. It is important because it allows you to integrate libraries or frameworks that other developers have made.*
2. What problems does NPM solve?
*Using NPM allows developers to have a more streamlined process to installed packages/libraries than having to search the web, download, and copy the files into their projects.*
3. Describe the 3 main parts of NPM.
*A command line tool, a registry, and a website.*
4. What is the package.json file?
*It is a JSON file that houses metadata about your project, scripts which create shortcut commands for your terminal, and a list of dependencies that are included in the project.*
5. What is the scripts section of the package.json file? How do you use it? What are the default commands, and how do you use your own?
*Scripts are terminal commands that perform a set of actions. You give the key of the JSON object the name of the shortcut for the command, and the value of the JSON object the command that the shortcut should run. The default commands are test and start, and you can use your own by defining them via a JSON object like mentioned earlier and calling "npm run (your key name here)".*
6. What are dependencies? What does this section define? What are dev dependencies? Why is it important to define dev dependencies vs dependencies?
*Dependencies is a list of packages and their versions that the project uses. Dev dependencies are dependencies that are only needed for local development and testing, whereas dependencies are packages that are required for your application's production. It is important to define these because you wouldn't want to define a dependency that is not optimized and therefore ready for anybody to use in the dependencies list or one that is required for production in the dev dependencies list.*
7. How do you install dependencies? Where do dependencies get installed?
*You can install dependencies by calling "npm install (dependency name)" in the terminal. Dependencies are stored in the node_modules folder.*
8. When running scripts with NPM, where does NPM look (path) for the dependencies of those scripts?
*NPM runs scripts from the root of the package folder.*
9. Name 3 NPM commands, and why they are important.
*- Update: This command is important because it will keep your packages updated to the latest version*
*- Dedupe: This command is important because it can simply the structure of the local package tree by moving dependencies further up the tree so that they can be more effectively shared by multiple dependent packages are therefore reduce the need for duplicate packages to be used in different parts of the dependency tree.*
*- Access: This command is important because it limits the access users could have on private packages by setting access controls on them.*