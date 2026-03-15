# Crafting Project

A React web application built with Vite, React 19, and Tailwind CSS.

## Prerequisites

- Node.js (version 18 or higher)
- npm or yarn package manager

## Installation

1. Clone the repository
2. Navigate to the project directory
3. Install dependencies:

```bash
npm install
```

## Available Commands

### Development
```bash
npm run dev
```
Starts the development server with hot reload. The application will be available at `http://localhost:5173` (or another port if 5173 is occupied).

### Build
```bash
npm run build
```
Creates an optimized production build in the `dist` folder.

### Preview
```bash
npm run preview
```
Previews the production build locally. Useful for testing the built application before deployment.

### Lint
```bash
npm run lint
```
Runs ESLint to check for code quality issues and potential errors.

## Project Structure

```
crafting/
├── public/          # Static assets
├── src/             # Source code
├── index.html       # HTML template
├── package.json     # Project dependencies and scripts
├── vite.config.js   # Vite configuration
└── README.md        # This file
```

## Technologies Used

- **React 19** - UI library
- **Vite** - Build tool and development server
- **Tailwind CSS** - CSS framework
- **ESLint** - Code linting

## Getting Started

1. Install dependencies: `npm install`
2. Start development server: `npm run dev`
3. Open your browser and navigate to the provided URL
4. Start building your application!

## Production Deployment

1. Build the application: `npm run build`
2. Deploy the contents of the `dist` folder to your hosting service
