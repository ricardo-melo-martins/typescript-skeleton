<div align="right">
  
#### ⚡ **RMM** ⚡
  
</div>

<div align="right">

  <sup>
thank you for visiting! 
🙌🤗⭐
  </sup>
  
</div>

# Typescript Skeleton

This is a basic framework, a minimalist template using Typescript. It assists me in the quick start to create tests, POC or projects. 

> Simple can be harder than complex: You have to work hard to get your thinking clean to make it simple. But it's worth it in the end because once you get there, you can move mountains. ~Steve Jobs 


## Features

- [Typescript 5.3+](https://www.typescriptlang.org/) is a strongly typed programming language that builds on JavaScript, giving you better tooling at any scale.
- [ESLint](https://eslint.org/) statically analyzes your code to quickly find problems. It is built into most text editors and you can run ESLint as part of your continuous integration pipeline.
- [Prettier](https://prettier.io/) is an opinionated code formatter.
- [Nodemon](https://nodemon.io/) is a utility, that will monitor for any changes in your source and automatically restart your server. Perfect for development.
- [ts-node](https://typestrong.org/ts-node/) is a TypeScript execution engine and REPL for Node.js.
- [@types/node](https://www.npmjs.com/package/@types/node) - This package contains type definitions for node (<https://nodejs.org/>).
- [EditorConfig](https://editorconfig.org/) helps maintain consistent coding styles for multiple developers working on the same project across various editors and IDEs.
- [TypeDoc](https://typedoc.org) Automatic document generation
- [npm-check-updates](https://github.com/raineorshine/npm-check-updates) upgrades your package.json dependencies to the latest versions, ignoring specified versions.

## How to use 

### Make a repository

- [Click here to generate](https://github.com/ricardo-melo-martins/typescript-skeleton/generate) with this template [<sup>❓</sup>](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template) 
- Edit the package.json with your desired stuff


### Or clone template to your system

```bash

git clone git@github.com:ricardo-melo-martins/typescript-skeleton.git

# access the folder
cd typescript-skeleton 

# make it yours
rm -rf .git

```



## How to Install

Install dependencies

```bash
# Node.js >=20 is required
npm i
# or 
yarn
```

Run the project for local development.

```bash
npm dev
# or 
yarn dev
```

Build the project for a production environment.

```bash
npm run build
```

Check the latest versions of all project dependencies:

```sh
npm run check

Checking ...\typescript-skeleton\package.json
[====================] 13/13 100%

All dependencies match the latest package versions :)

```

## Package.json

Available commands for:

### Build
- `build` -  Build one or more projects and their dependencies
- `build:watch` - Watch input files 
- `build:release` - Build specified settings on `tsconfig.release.json`
- `prebuild` - Checks possibility

### Execution

- `start` - Run static compiled on path `dist`
- `start:dev` - Run nodemon on path `src`
- `start:prod` - Run production env on path `dist`

### Code style

- `format` - Prettier format code style
- `lint` - ESLint code format verify
- `lint:fix` - ESLint verify and fix

### Clean

- `clean` - Remove cache, coverage and dist folder

### Docs

- `doc:gen` - Automatic document generate
- `doc:clean` - Delete doc folder

### Packages

- `check` - Check the latest versions of all project dependencies

## System requirements

- [Node](https://nodejs.org/en/download) 20+
- [Typescript Cli](https://www.typescriptlang.org/download)
- [Vscode](https://code.visualstudio.com/) *`(Optional)`* This template has productivity-focused settings, snippets and extensions.


## VSCode

Formatting/Linting

Install [dbaeumer.vscode-eslint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) extension in your VS Code to use eslint for formatting and linting. A configuration file (.eslintrc.js) is already provided in the project.


## License

Typescript Skeleton is [MIT licensed](LICENSE).

## Author


Created with fun by [Ricardo Melo Martins](https://github.com/ricardo-melo-martins).


<div align="right">
  <sub>
    I thank :heart: the teams of 
  </sub>
</div>

<div align="right">
<a href="https://nodejs.org/" target="blank" alt="NodeJs">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nodejs/nodejs-original.svg" width="30" alt="NodeJS" />
</a>
<a href="https://www.typescriptlang.org/" target="blank">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/typescript/typescript-original.svg" width="30" alt="Typescript" />
</a>
<a href="https://eslint.org/" target="blank">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/eslint/eslint-original.svg" width="30" alt="ESLint"/>
</a>
<a href="https://nodemon.io/" target="blank">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nodemon/nodemon-original.svg" width="30" alt="Nodemon"/>
</a>
<a href="https://prettier.io/" target="blank" >
  <img src="https://prettier.io/icon.png" width="30" alt="Prettier" />
</a>
<a href="https://www.npmjs.com/" target="blank" >
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/npm/npm-original-wordmark.svg" width="30" alt="Npmjs"/>
</a>
<a href="https://code.visualstudio.com/" target="blank" >
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vscode/vscode-original.svg" width="30" alt="Vscode"/>
</a>
</div>
