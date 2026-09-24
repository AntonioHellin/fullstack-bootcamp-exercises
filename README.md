# fullstack-bootcamp-exercises

A structured course repository containing practical exercises, modules, and starter projects for full-stack modern web development.

## Project Overview

`fullstack-bootcamp-exercises` organizes course work across progressive modules covering frontend and backend technologies. Currently features `part1`, introducing React 19 component structures, props passing, and local development configurations.

## Features

- **Progressive Course Architecture**: Independent modular directories (`part1`, etc.).
- **Modern React**: React 19 frontend foundation configured with standard testing utilities.
- **Testing Setup**: Jest DOM and React Testing Library pre-configured.

## Prerequisites

- [Node.js](https://nodejs.org/) (version 18.x or later)
- [npm](https://www.npmjs.com/) (version 9.x or later)

## Installation/Build

1. Clone the repository and navigate to the root directory:
   ```bash
   git clone https://github.com/AntonioHellin/fullstack-bootcamp-exercises.git
   cd fullstack-bootcamp-exercises
   ```

2. Navigate to the module of interest (for example, `part1`):
   ```bash
   cd part1
   npm install
   ```

3. (Optional) Configure environment variables:
   ```bash
   cp .env.example .env
   ```

4. Build for production:
   ```bash
   npm run build
   ```

## Usage

Start the development server for a module:
```bash
cd part1
npm start
```
The application will open at `http://localhost:3000`.

To run test suites:
```bash
npm test
```

## License

This project is licensed under the MIT License.
