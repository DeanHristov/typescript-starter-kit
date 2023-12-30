# Typescript-starter-kit

A minimalistic starter-kid based on [TypeScript](https://www.typescriptlang.org/) language

## Requirements

- [Node](https://nodejs.org/en/) `^16.15.0`
- [NPM](https://www.npmjs.com/) `^8.5.5`

## Installation

After confirming that your environment meets the
above [requirements](#requirements), it is time to clone the project
locally by doing the following:

```bash
$ git clone git@github.com:DeanHristov/typescript-starter-kit.git <project-name>
$ cd <project-name>
```

When you're done with the steps above, run the following command:

```bash
$ npm install # or yarn install
```

## Project Structure

The project structure presented in this boilerplate is **flatten**, where
functionality is grouped primarily by feature rather than the file type.

```

├── build                           # Auto-generated directory. Contains **production-ready** code.
│   └── *.js
│   └── [dir-name]                  # Sub directory
│       └── *.js
├── src                             # Application source code is stored here.
│   ├── [dir-name]                  # Sub directory that contains files (in Typescript) format.
│       └── [filename].ts
│   ├── [filename].ts
│   ├── index.ts                    # The entry point of the app.
├── .env                            # App-related ENV variables are stored here. MUST be created manually!
├── .env.example                    # A template which contains important variables for the app.
├── .eslintignore                   # Config file for ESLint
├── .eslintrc                       # Config file for ESLint
├── .gitignore                      # Config file for GIT
├── .prettierrc                     # Config file for Prettier
├── jest.config.js                  # Config file for Jestjs
├── nodemon.json                    # Config file for nodemon
├── package.json                    # The heart of the app. It holds important metadata about a project like scripts dependencies
├── package-lock.json               # Place where we controls the dependencies
├── README.md                       # A documentation file
├── tsconfig.json                   # Config file for typescript
```

## Main tasks

All tasks automation are based on [NPM scripts](https://docs.npmjs.com/misc/scripts).

| Tasks                     | Description                                           |
| ------------------------- | ----------------------------------------------------- |
| `npm run start:dev`       | Running the app in **dev** mode                       |
| `npm run build`           | Building the code in **production-ready** mode        |
| `npm run start`           | Running the app in **prod** mode                      |
| `npm run test`            | Running the unit tests ( using jest)                  |
| `npm run test:watch`      | Running the unit with `--watchAll` mode ( using jest) |
| `npm run prettier-format` | Code formatting                                       |

## Running the Project

Running the app in **development** mode.

```bash
$ npm run start:dev
```

## Running the Project in production mode.

Firstly, build the app with the following command:

```bash
$ npm run build
```

Running the app in **development** mode.

```bash
$ npm start
```

## Used technologies

- NodeJS- https://nodejs.org/en/
- Git - https://git-scm.com/
- TypeScript - https://www.typescriptlang.org/

## NPM Packages

- [typescript](https://www.npmjs.com/package/typescript)
- [prettier](https://www.npmjs.com/package/prettier)
- [ts-jest](https://www.npmjs.com/package/ts-jest)
- [jest](https://www.npmjs.com/package/jest)
- [ts-node](https://www.npmjs.com/package/ts-node)
- [nodemon](https://www.npmjs.com/package/nodemon)
- [rimraf](https://www.npmjs.com/package/rimraf)
- [eslint](https://www.npmjs.com/package/eslint)
- [eslint-config-prettier](https://www.npmjs.com/package/eslint-config-prettier)
- [eslint-plugin-jest](https://www.npmjs.com/package/eslint-plugin-jest)
- [eslint-plugin-prettier](https://www.npmjs.com/package/eslint-plugin-prettier)

## Made by

Author: [D. Hristov](https://dhristov.eu/) | Version: v1.0.0
