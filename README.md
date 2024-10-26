# React Vite Template

A minimal template for building React applications using Vite. This template is designed to help you quickly set up a new React project with a modern development environment.

## Features

- Fast development with Vite
- React setup with JSX support
- Modern JavaScript support
- Pre-configured ESLint and Prettier for code quality and formatting
- Pre-configured Git hooks with Husky to run lint-staged on staged files, ensuring code style consistency and quality before each commit

## Prerequisites

- [Node.js](https://nodejs.org/) (v20 or later)
- [Git](https://git-scm.com/)
- [Visual Studio Code](https://code.visualstudio.com/)

## Setup VS Code

- Install extensions
  - ESLint (by Microsoft)
  - Prettier – Code formatter (by Prettier)
- Open VS Code settings -> `Workspace`
  - Check `Editor: Format On Save`
  - `Editor: Default Formatter`: `Prettier - Code formatter`

## Getting Started

Follow these steps to get your React Vite Template up and running:

- Login your Github account.
- Click the **Fork** button in the top right corner of this repository to create a copy under your own GitHub account.
- Open your terminal and run the following commands to clone your forked repository. Change `<your-username>` and `<project-name>` accordingly.

  ```bash
  git clone https://github.com/<your-username>/react-vite-template.git <project-name>
  cd <project-name>
  ```

- Change the project name in the `package.json` file. Look for the `name` field and update it to your desired project name.

- Install the dependencies.

  ```bash
  npm install
  ```

## Scripts

- `dev`: Runs the development server using Vite. This script launches the app on a local server, allowing you to view your application in real-time and see changes as you develop.

  ```bash
  npm run dev
  ```

- `build`: Builds the application for production using Vite, generating optimized files in the dist folder. These files are ready for deployment to a web server.

  ```bash
  npm run build
  ```

- `lint`: Runs ESLint to analyze the code in the src folder, identifying syntax and style issues to ensure code quality and consistency across the project.

  ```bash
  npm run lint
  ```

- `preview`: Starts a local server to preview the production build. Useful for testing the final output before deploying to a live environment.

  ```bash
  npm run preview
  ```

- `prepare`: Initializes Husky, which sets up Git hooks for the project. Running this once after cloning the project will activate Husky to use pre-configured hooks, like linting staged files before each commit.

  ```bash
  npm run prepare
  ```

## Learn More

To learn more about React and Vite, consider exploring these resources:

- [React Documentation](https://react.dev/learn)
- [Vite Documentation](https://vite.dev/guide/)
