
# TypeScript Node Skeleton

This is a basic Node.js skeleton using ES6+ and TypeScript. Ideal for starting projects that require a clean, modern setup.

## Features
- TypeScript configuration (strict mode, ESNext, NodeNext modules)
- Ready-to-use build and dev scripts
- Nodemon for development

## Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v18+ recommended)
- [npm](https://www.npmjs.com/) (comes with Node.js)

### Installation
```bash
git clone https://github.com/efrenrgzmx/node-typescript-clean-skeleton.git
cd node-typescript-clean-skeleton
npm install
```

### Scripts
- `npm run build` – Compiles TypeScript to `dist/`
- `npm start` – Runs the compiled app (`dist/app.js`)
- `npm run dev` – Compiles and runs with Nodemon for hot-reload
- `npm run watch` – TypeScript in watch mode

### Usage
To start the project in development mode:
```bash
npm run dev
```
To build and run:
```bash
npm run build
npm start
```

## Project Structure
```
src/        # Source TypeScript files
	app.ts    # Entry point
dist/       # Compiled JavaScript output
```

## Configuration
- TypeScript config: `tsconfig.json`
- Main entry: `src/app.ts`

## Bugs or Improvements
Feel free to report any bugs or improvements. Pull requests are always welcome.
