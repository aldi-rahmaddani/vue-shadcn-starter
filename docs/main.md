# Frontend Starter Template

Starter template for frontend projects with full customization.

## Table of Contents

- [Tech stack](#🚀-tech-stack)
- [Installation](#⚙️-installation)
- [Available Scripts](#📜-available-scripts)
- [Project Structure](#🏗️-project-structure)
- [Conventional Commits](#✍️-conventional-commits)
- [License](#⚖️-license)

## 🚀 Tech Stack

### Package Manager

![pnpm](https://img.shields.io/badge/-Pnpm-F69220?logo=pnpm&logoColor=fff&style=for-the-badge)

### Library

![Vite](https://img.shields.io/badge/-Vite-646CFF?logo=vite&logoColor=fff&style=for-the-badge)
![Vue](https://img.shields.io/badge/-Vue-4FC08D?logo=react&logoColor=fff&style=for-the-badge)
![Typescript](https://img.shields.io/badge/-Typescript-3178C6?logo=typescript&logoColor=fff&style=for-the-badge)
![Shadcn UI](https://img.shields.io/badge/-Shadcn_UI-000000?logo=shadcn/ui&logoColor=fff&style=for-the-badge)
![Tailwind CSS](https://img.shields.io/badge/-Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=fff&style=for-the-badge)

### Linter and Formatter

![ESLint](https://img.shields.io/badge/-Eslint-4B32C3?logo=ESLint&logoColor=fff&style=for-the-badge)
![Prettier](https://img.shields.io/badge/-Prettier-F7B93E?logo=prettier&logoColor=000&style=for-the-badge)
![Editor Config](https://img.shields.io/badge/-Editor_Config-FEFEFE?logo=editorconfig&logoColor=000&style=for-the-badge)

### Precommit Hooks

- Husky
- Lint Staged

## ⚙️ Installation

To get started with the project, clone the repository and install the dependencies:

```bash
git clone https://github.com/aldi-rahmaddani/react-shadcn-starter.git

cd react-shadcn-starter

pnpm install
```

## 📜 Available Scripts

### Running a project

```bash
pnpm dev
```

Go to browser and open url http://localhost:5173, it is the default port of vite if available.

### Bundling projects for production

```bash
pnpm build
```

The build results are available in the /dist folder by default.

### Preview project build results

```bash
pnpm preview
```

Go to browser and open url http://localhost:4173, it is the default port of vite if available.

### Running a linter to check code writing style

```bash
pnpm lint
```

### Setup precommit hooks

```bash
pnpm prepare
```

## 🏗️ Project Structure

```bash
.husky
.vscode/
└── settings.json
docs/
└── main.md
public
src/
├── assets/
│ ├── css
│ └── img
├── components/
│ └── ui
├── lib/
│ └── utils.ts
├── router/
│ └── index.ts
├── views/
│ ├── AboutView.vue
│ └── HomeView.vue
├── App.vue
└── main.ts
.editorconfig
.gitattributes
.gitignore
.prettierignore
.prettierrc
components.json
eslint.config.js
index.html
LICENSE
package.json
pnpm-lock.yaml
postcss.config.js
README.md
tailwind.config.js
tsconfig.app.json
env.d.ts
tsconfig.json
tsconfig.node.json
vite.config.ts
```

## ✍️ Conventional Commits

Commit message writing standards

### Commit Format

```bash
<type>(<scope>): <description>
```

### Example

```bash
feat(auth): add login functionality

fix(ui): resolve button alignment issue
```

### List of Commit Types

| Type     | Description                                             |
| :------- | :------------------------------------------------------ |
| feat     | Added new features                                      |
| fix      | Fix bugs                                                |
| style    | Non-code changes (formatting, whitespace, etc.)         |
| chore    | Minor changes (dependency updates, build process, etc.) |
| test     | Add or update tests                                     |
| refactor | Code changes without changing functionality             |
| refactor | Code changes without changing functionality             |
| ci       | Changes to CI/CD configuration                          |
| docs     | Documentation updates                                   |

## ⚖️ License

Licensed under the [MIT license](https://github.com/aldi-rahmaddani/vue-shadcn-starter/blob/main/LICENSE.md).
