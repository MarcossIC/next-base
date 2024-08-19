# ⚡Next professional boilerplate </br> [![GitHub Actions Workflow Status][status-workflow-badge]][status-workflow-badge-link] ![GitHub commit activity (branch)][commit-activity-badge] ![GitHub Created At][created-at-badge] [![MarcossIC][made-by-badge]][made-by-badge-link]

Welcome to nextjs professional boilerplate, an open source template for nextjs. It is prepared with functionalities that will help you make quality code, and will facilitate the maintainability of the code. You can find versions with different functionalities among the branches. I hope you like it

## ✨ Features

You can find these things in the template:

<ul>

<li>
<a style="text-decoration: none;"  href="https://nextjs.org/" target="_blank" rel="noopener noreferrer"> <img src="https://cdn.simpleicons.org/nextdotjs/01000f" alt="Nextjs" width=17 height=17> <b>Next.js</b>
  </a> - Pre-configured, with default src and app router + Bundler analyzer
</li>

<li style="padding-top: 4px;">
<a style="text-decoration: none;" href="https://tailwindcss.com/" target="_blank" rel="noopener noreferrer"> <img src="https://cdn.simpleicons.org/tailwindcss/06B6D4" alt="Tailwind css" width=17 height=17> <b>TailwindCSS</b>
  </a> - By default, CSS Framework for rapid UI development
</li>

<li style="padding-top: 4px;">
<a style="text-decoration: none;" href="https://cva.style/docs" target="_blank" rel="noopener noreferrer"> 
<img src="./.github/assets/cva.svg" alt="CVA" width=17 height=17> <b>CVA</b>
  </a> - To easily manage component variants
</li>

<li style="padding-top: 4px;">
  <a style="text-decoration: none;" href="https://eslint.org/" target="_blank" rel="noopener noreferrer"> <img src="https://cdn.simpleicons.org/eslint/4B32C3" alt="Eslint"  width=17 height=17> <b>Eslint</b>
  </a> - For cleaner code, find errors faster
</li>

<li style="padding-top: 4px;">
<a style="text-decoration: none;" href="https://prettier.io/" target="_blank" rel="noopener noreferrer"> <img src="https://cdn.simpleicons.org/prettier/F7B93E" alt="Prettier"  width=17 height=17> <b>Prettier</b>
  </a> - To keep the code formatted
</li>

<li style="padding-top: 4px;">
<a style="text-decoration: none;" href="https://www.typescriptlang.org/" target="_blank" rel="noopener noreferrer"> <img src="https://cdn.simpleicons.org/typescript/3178C6" alt="Typescript" width=17 height=17> <b>Typescript</b>
  </a> - By default, configured with strict types and with ts-reset for types safety
</li>

<li style="padding-top: 4px;">
<a style="text-decoration: none;" href="https://jestjs.io/" target="_blank" rel="noopener noreferrer"> <img src="https://cdn.simpleicons.org/jest/C21325" alt="Jest" width=17 height=17>  <b>Jest</b>
  </a> and <a style="text-decoration: none;" href="https://testing-library.com/react" target="_blank" rel="noopener noreferrer"> <img src="https://cdn.simpleicons.org/testinglibrary/E33332" alt="Testing Library"  width=17 height=17> <b>Testing Library</b>
  </a> - For unit tests and integration tests
</li>

<li style="padding-top: 4px;">
<a style="text-decoration: none;" href="https://storybook.js.org/docs" target="_blank" rel="noopener noreferrer"> <img src="https://cdn.simpleicons.org/storybook/FF4785" alt="Storybook" width=17 height=17>  <b>Storybook</b>
  </a> - To create tests and use cases for your components 
</li>

<li style="padding-top: 4px;">
<a style="text-decoration: none;" href="https://github.com/typicode/husky#readme" target="_blank" rel="noopener noreferrer"> <img src="https://cdn.simpleicons.org/precommit/FAB040" alt="Pre commit" width=17 height=17> <b>Husky</b>
  </a> - Configured to raise, git hooks for the pre commit, pre push and commit message
</li>

<li style="padding-top: 4px;">
<a style="text-decoration: none;" href="https://commitlint.js.org/" target="_blank" rel="noopener noreferrer"> <img src="https://cdn.simpleicons.org/commitlint/000000" alt="Commitlint" width=17 height=17> <b>Commitlint</b>
  </a> with <a style="text-decoration: none;" href="https://www.conventionalcommits.org/en/v1.0.0/" target="_blank" rel="noopener noreferrer"> <img src="https://cdn.simpleicons.org/conventionalcommits/FE5196" alt="Pre commit" width=17 height=17> <b>Conventional commit</b></a> - To maintain a clean and solid commit history
</li>

<li style="padding-top: 4px;">
<a style="text-decoration: none;" href="https://github.com/features/actions" target="_blank" rel="noopener noreferrer"> <img src="https://cdn.simpleicons.org/githubactions/2088FF" alt="Github Action" width=17 height=17> <b>Github Actions</b>
  </a> - Pre-configured actions for smooth workflows
</li>

<li style="padding-top: 4px;">
<a style="text-decoration: none;" href="https://zod.dev/" target="_blank" rel="noopener noreferrer"> <img src="https://cdn.simpleicons.org/zod/3E67B1" alt="Zod" width=17 height=17> <b>Zod</b>
  </a> - For type validation
</li>

<li style="padding-top: 4px;">
<a style="text-decoration: none;" href="https://zustand.docs.pmnd.rs/getting-started/introduction" target="_blank" rel="noopener noreferrer"> <img src="./.github/assets/zustand.png" alt="Zustand" width=17 height=17> <b>Zustand</b>
  </a> - To handle global states simply and cleanly
</li>
</ul>

## 🎯 Getting Started

To start using this template, follow the following steps:

1. Fork & clone repository:

```bash
git clone https://github.com/<your_username>/<repo_name>.git
```

2. Install the dependencies:
   In this case you can use the package manager you want. I personally recommend `pnpm`

```bash
pnpm install
```

3. Run the development server:

```bash
pnpm dev
```

4. Open `http://localhost:3000` with your browser to see the result.

5. The project uses husky and patch-package to automate git hooks and validate dependencies. This is executed, with the "postinstall" every time you do install:

```bash
npx patch-package && node setup-husky.js
```

If you do not want to run husky on every installation, remove this `&& node setup-husky.js` from the `postinstall` in the `package.json`

## 📐 Scripts Overview

The template has the following scripts available in the `package.json`:

- `dev`: Starts the development server
- `build`: Builds the app for production
- `analyze`: Analyzes the bundle sizes for Client, Server and Edge environments
- `start`: Starts the production server
- `lint`: Lints the code using ESLint
- `lint:fix`: Automatically fixes linting errors
- `commitlint:last`: Check if the last commit follows the commitlint rules
- `format`: Checks the code for proper formatting
- `format:fix`: Automatically fixes formatting issues
- `prepare`: Run husky setup script
- `test`: Runs unit and integration tests
- `test:watch`: Runs unit and integration tests in watch mode
- `storybook`: Start storybook dev server
- `prebuild:storybook`: Pre-build jest test for storybook
- `build:storybook`: Build storybook server for deployment
- `postinstall`: Applies patches to external dependencies and run prepare script

## :spades: Package manager

The template does not force you to use a specific package manager so you can choose the one you want. This is why no lock file was uploaded.

However, if you are sure of the package manager you are going to use for the project. You can upload the lock file. And change the `npx` commands to the one you are using.

### :heavy_exclamation_mark: Considerations

In case you choose to use `yarn` as a package manager you should add some things:

- Add this dependency:

```bash
yarn add postinstall-postinstall --save-dev
```

- Update post install:
  You need to find the postinstall script and add the `-y` flag to it

```json
"postinstall": "npx patch-package -y && node setup-husky.js"
```

If you have already decided on the package manager you use, you can consider adding this line to the end of your `package.json`:

```json
"packageManager": "<manager>@<version>"
```

Example:

```json
//With pnpm
"packageManager": "pnpm@9.7.0"
//With yarn
"packageManager": "yarn@1.22.22"
//With npm
"packageManager": "npm@10.8.2"
```

## :shipit: Testing

To handle the unit and integration tests, jest and testing library are being used. Playwright is used for the e2e tests

### Runing test

- **Unit and integration tests**: Run Jest tests using `pnpm test`

### Acceptance Tests

You can write your acceptance tests using storybook's [play][storybook-play-link] function. This will allow you greater versatility, you will be able to test your tests along with the interactions that storybook gives

## 🎨 Styling

For styles, added Tailwind CSS, a CSS framework for quick styling. In case you need to use your own CSS, it is recommended to use [CSS Modules][css-module-link].

### CVA

The template comes by default with [cva][cva-docs-link], [clsx][clsx-docs-link] and [tw-merge][tw-merge-docs-link]. These utilities serve to facilitate the creation of variants for your components, this will help you maintain a design system easily. Then CVA will simplify the process of creating variants for your design systems, without compromising CSS control.

<!-- Badges -->

[commit-activity-badge]: https://img.shields.io/github/commit-activity/m/MarcossIC/next-template/main?logo=github
[created-at-badge]: https://img.shields.io/github/created-at/MarcossIC/next-template?logo=github
[made-by-badge]: https://img.shields.io/badge/made_by-MarcossIC-blue?color=4017d1&link=https://marcosic.netlify.app&logo=readdotcv
[status-workflow-badge]: https://img.shields.io/github/actions/workflow/status/MarcossIC/next-template/next_analysis.yml?label=Status

<!-- Links -->

[status-workflow-badge-link]: https://github.com/MarcossIC/next-template/actions/workflows/next_analysis.yml
[made-by-badge-link]: https://marcosic.netlify.app
[storybook-play-link]: https://storybook.js.org/docs/writing-stories/play-function#writing-stories-with-the-play-function
[css-module-link]: https://nextjs.org/docs/pages/building-your-application/styling/css-modules
[cva-docs-link]: https://cva.style/docs
[clsx-docs-link]: https://github.com/lukeed/clsx#readme
[tw-merge-docs-link]: https://github.com/dcastil/tailwind-merge
