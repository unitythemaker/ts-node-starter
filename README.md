# TypeScript Starter Template

Welcome to the TypeScript Starter Template! This repository provides a solid foundation for starting your TypeScript projects with a powerful and modern development environment. It comes pre-configured with ESLint, Prettier, and Husky, allowing you to enforce coding standards and maintain consistent code formatting throughout your project.

## Features

- TypeScript: A strict syntactical superset of JavaScript that adds optional static typing to the language.
- ESLint: A powerful and extensible linting tool for JavaScript and TypeScript that enforces code quality and best practices.
- Prettier: An opinionated code formatter that enforces a consistent code style across your project.
- Husky: A Git hooks manager that enables you to run tasks automatically during Git events, such as committing or pushing.

## Getting Started

To start using this template, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/unitythemaker/ts-node-starter.git
   ```
2. Navigate to the project folder:
   ```
   cd ts-node-starter
   ```
3. Install dependencies:
   ```
   npm install
   ```
4. Start the development server:
   ```
   npm run dev
   ```

## Available Scripts

In the project directory, you can run the following scripts:

- `npm run dev`: Starts the development server.
- `npm run build`: Compiles the TypeScript code into JavaScript.
- `npm start`: Runs the compiled JavaScript.
- `npm run lint`: Runs the ESLint linter to check for code quality issues.
- `npm run format`: Formats the code with Prettier.
- `npm run test`: Runs the test suite (Note: You will need to add a test runner and test files to your project).

## Switching to Yarn or pnpm

If you prefer to use Yarn or pnpm as your package manager, you can easily switch from npm by following the steps below.

### Switching to Yarn

1. Run the following command to generate a `yarn.lock` file and import the dependencies from `package-lock.json`:

   ```
   yarn import
   ```

2. Once this is done, you can safely remove the `package-lock.json` file and start using Yarn commands in place of npm commands. For example, instead of `npm install`, you would run `yarn install`.

### Switching to pnpm

1. (Optional) Make sure you have a `pnpm-workspace.yaml` file if you're working with workspaces.

2. Run the following command to generate a `pnpm-lock.yaml` file and import the dependencies from `package-lock.json`:

   ```
   pnpm import
   ```

3. Once this is done, you can safely remove the `package-lock.json` file (or other lockfiles) and start using pnpm commands in place of npm commands. For example, instead of `npm install`, you would run `pnpm install`.

## Configurations

This template comes with the following configurations:

- `tsconfig.json`: TypeScript configuration file.
- `.eslintrc`: ESLint configuration file, containing rules and extensions for TypeScript.
- `.prettierrc`: Prettier configuration file, specifying code formatting options.
- `.husky`: Husky configuration folder, containing pre-commit and pre-push hooks.

Feel free to modify these files according to your project requirements.

## Contributing

Contributions are always welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is released under the [MIT License](LICENSE).
