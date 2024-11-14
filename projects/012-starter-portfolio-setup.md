# Project: Starter Portfolio Setup with Package Manager

## Project Description:
In this project, you will create the basic setup for a personal portfolio website using a package manager (npm or Yarn). The goal is to introduce you to the process of managing project dependencies and automating common tasks using package manager scripts.

### Key Features:
- Set up a simple portfolio structure with HTML, CSS, and JavaScript.
- Use a package manager to install essential development tools and dependencies.
- Configure custom scripts in the `package.json` file to automate tasks like starting the local server or building the project.

### Learning Objectives:
- Learn how to initialize a project and manage dependencies using npm or Yarn.
- Understand the differences between development and production dependencies.
- Learn how to automate tasks using npm or Yarn scripts.

## Project Requirements:
1. **Initial Setup**:
   - Create a new project directory.
   - Initialize a new npm or Yarn project by running `npm init` or `yarn init` in the terminal.

2. **Folder Structure**:
   - Create the following folder structure:
     - `/src` (for source files)
     - `/dist` (for distribution files, after build)
     - `/assets` (for images, fonts, and other assets)
   
3. **Install Development Dependencies**:
   - Install a development server tool (e.g., `lite-server` or `parcel`) to serve your website locally.
   - Install a CSS preprocessor (e.g., `sass`) for styling the project.
   - Install any other tools you need for your development process (e.g., `eslint` for linting).

4. **Create Portfolio Structure**:
   - **HTML**: Create a basic structure with sections like "About Me", "Projects", and "Contact".
   - **CSS**: Style the page to make it visually appealing, using modern CSS techniques (e.g., Flexbox or CSS Grid).
   - **JavaScript**: Add interactivity to the website (e.g., a simple form or modal).

5. **Scripts**:
   - In the `package.json`, add custom scripts to automate the following tasks:
     - `start`: Starts the local development server.
     - `build`: Prepares the project for production by optimizing and moving the files to the `/dist` folder.
     - `lint`: Runs a linter to check the JavaScript code for potential issues.

6. **Documentation**:
   - Include comments and notes in the `package.json` file explaining the different dependencies and scripts.

## Resources:
- **npm Documentation**: [npm Docs](https://docs.npmjs.com/)
- **Yarn Documentation**: [Yarn Docs](https://classic.yarnpkg.com/en/docs/)
- **Using npm Scripts**: [npm Scripts Guide](https://docs.npmjs.com/misc/scripts)
- **Setting up a Local Development Server**: [Lite-Server Documentation](https://www.npmjs.com/package/lite-server)
- **CSS Preprocessing with SASS**: [SASS Documentation](https://sass-lang.com/guide)
- **Automating Tasks with npm**: [Automating with npm](https://www.smashingmagazine.com/2020/05/advanced-usage-npm-scripts/)
