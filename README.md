# Task2-Blog-Website-Bharat-Intern
Install Node.js:

Before you can use npm, you need to have Node.js installed on your system. You can download it from the official website: Node.js.
Open a Terminal or Command Prompt:

Once Node.js is installed, open a terminal or command prompt on your computer.
Navigate to Your Project Directory:

Use the cd command to navigate to your project directory. For example:
bash
cd path/to/your/project
Initialize a Package (if not already done):

If your project doesn't have a package.json file, you can create one using the following command:
bash
npm init
Follow the prompts to provide information about your project. You can press Enter to accept the default values for most of the prompts.
Install a Node Module:

To install a module, use the npm install command followed by the module name. For example:
bash
npm install module_name
Replace "module_name" with the name of the module you want to install.
Save the Module as a Dependency:

If you want to save the module as a dependency in your package.json file, use the --save or -S flag:

bash
npm install module_name --save
If you are installing a module for development purposes (e.g., testing or building), you can use the --save-dev or -D flag:

bash
npm install module_name --save-dev
Install Modules from package.json:

If you have a package.json file with a list of dependencies, you can install all of them at once by running:
bash
npm install
