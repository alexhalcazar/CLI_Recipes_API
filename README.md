# CLI_Recipes_API

Created with Node.js and JavaScript.
This application uses Yargs to build a custom Command Line Application.
Interacts with multiple Application Programming Interfaces.
Allows a user to search for a meal category which returns a recipe.

## Installation 

1. Clone the Repository:

```bash
git clone https://github.com/alexhalcazar/CLI_Recipes_API
cd CLI_Recipes_API
```

## Dependencies 

2. Install Dependencies:

The project relies on the following npm packages:

- [prompts](https://www.npmjs.com/package/prompts) (v2.4.2) - A lightweight, beautiful, and user-friendly interactive prompts library.
- [superagent](https://www.npmjs.com/package/superagent) (v8.0.9) - HTTP request library for Node.js that works with both callbacks and promises.
- [yargs](https://www.npmjs.com/package/yargs) (v17.7.1) - A powerful command-line parser for Node.js that helps you build interactive command-line tools.

Run the following command to install the required dependencies:

```bash
npm install
```

This will install the necessary packages isted in the **'dependencies'** section of your **'package.json'** file.

## Usage

3. Run the CLI:

Once the dependencies are installed, you can run the CLI using:

```bash
node cli.js
```

This assumes that **'cli.js'** is your main entry point. Adjust the command accordingly if your entry point is different.

4. Available Commands:

**Search for Recipes:**
```bash
npm start search <query>
```
Replace '<query>' with your desired meal category.

5. Responding to Prompts

When prompted for a meal category, use the up and down arrow keys to cycle through the available meals.

With your desired meal category selected press 'Return'.

## Reporting Issues

If you encounter any issues or have suggesttions for improvement, please [create an issue](https://github.com/alexhalcazar/CLI_Recipes_API/issues)

## Authors

Alex Alcazar