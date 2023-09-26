# magicwords

## Overview

This boilerplate is set up for a Full-Stack JavaScript project using Node.js, Express.js, Next.js, and Tailwind CSS. It is configured to enable quick development of a web application where you need server-side rendering and a focus on CSS customization. This boilerplate is ideal for projects requiring web scraping and data analysis.
## Features

- [x] Server-side rendering with Next.js
- [x] Express.js for backend logic
- [x] Tailwind CSS for styling
- Pre-configured folder structure

## Getting Started

1. Clone this repository

```bash
git clone https://github.com/mooselamb/magicwords.git
```

2. Navigate into the project directory:

```bash
cd magicwords
```

3. Install dependencies:

```bash
npm install
```

4. Folder structure:

```
- backend/
    - controllers/
    - routes/ 
    - src/
        - models/
        - routes/
            - api.ts
            - index.ts
        - add.ts
        - app.ts
    - package.json
    - package-lock.json
    - tsconfig.json  

- frontend/
    - public/
        - index.html
    - src/
        - components/
        - App.tsx
        - index.tsx
    - styles/
        - output.css
        - styles.css
    - output.css
    - package.json
    - package-lock.json
    - tsconfig.json
    - tailwind.config.js

- README.md
```

## Usage

To start the development server:

```bash
npm run dev
```

To build the project:

```bash
npm run build
```

## Database

This boilerplate is set up to integrate with a PostgreSQL database. (Connection instructions to be added.)

## Contributions

Contributions are welcome! Please open an issue if you have any questions or suggestions. Feel free to fork this repository and submit pull requests.

## License

```
[MIT](https://choosealicense.com/licenses/mit/)
```

## Project Configuration

- '.editorconfig' - Editor configuration to maintain consistent coding styles.
- '.eslintrc.json' - ESLint configuration for linting JavaScript code.
- '.prettierrc' - Prettier configuration for code formatting.
- 'LICENSE' - MIT license.
