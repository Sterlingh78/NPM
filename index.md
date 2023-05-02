## NPM Documentation Assignment

# 1. What is NPM? What does it do? Why is it an important tool?
NPM stands for Node Package Manager which does exactly that. It manages Nodejs packages for a project along with their versions. Without it everyone would have to manually install packages with specific versions

# 2. What problems does NPM Solve?
NPM tracks exactly which packages are needed for a project. Before NPM devs had to manually document packages and install them one by one.

# 3. Describe the 3 main parts of NPM.
1. Main website, 2. CLI, 3. The registry

# 4. What is the package.json file?
the package.json is how your project knows which Node packages your project depends on along with their versions. Also includes defenitions for commands like run, build, etc.

# 5. What is the scripts section of the package.json file? How do you use it? What are the default commands, and how do you use your own?
The scripts section includes definitions for the project scripts. You run the scripts by entering them in the terminal and you can add your own within the same scripts section in the package.json. Pretty much every package.json includes a "dev" and a "build" command.

# 6. What are dependencies? What does this section define? What are dev dependencies? Why is it important to define dev dependencies vs dependencies?
Dependencies are the Node packages that your project depends to run on. This section defines which packages and versions that the project needs. Dev dependencies are only for project development purposes only while dependencies are for production. Its important to seperate them because dev dependencies arent needed for the final product and enlarge the total size of the project.

# 7. How do you install dependencies? Where do dependencies get installed?
You install dependencies by running a command like 'npm install packagename'. After running this script in the terminal, node will install your package and populate the dependencies section of the package.json

# 8. When running scripts with NPM, where does NPM look (path) for the dependencies of those scripts?
NPM looks for them in the node_modules folder. This is the main folder where the modules are installed at the root of the project

# 9. Name 3 NPM commands, and why they are important.
1. NPM Install. This command is used in every single project, its the initial command to install all dependencies in a project. 2. NPM Run. This is the next most used command, devs will use this every time they work on the project. It starts the application up and displays in the browser. 3. NPM Publish. I havent used this command before but it is used to publish a package you have written yourself to NPM. Others can then install it using NPM Install

