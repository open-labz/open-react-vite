# Installation Guide

This guide will help you set up the Open React Vite project on your local development machine.

## Prerequisites

Before you begin, ensure you have the following installed on your system:

- [Node.js](https://nodejs.org/) (version 18 or higher)
- [npm](https://www.npmjs.com/) (comes with Node.js)
- [Git](https://git-scm.com/) (for version control)

## Installation Steps

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd open-react-vite
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```
   This will start the development server, typically at `http://localhost:5173`

## Available Scripts

- `npm run dev` - Starts the development server
- `npm run build` - Builds the project for production
- `npm run lint` - Runs ESLint to check code quality
- `npm run preview` - Previews the production build locally

## Project Structure

- `/src` - Contains the source code
- `/public` - Static assets
- `/docs` - Documentation files
- `vite.config.ts` - Vite configuration
- `tsconfig.json` - TypeScript configuration

## Troubleshooting

If you encounter any issues during installation:

1. Make sure you have the correct Node.js version installed
2. Try deleting the `node_modules` folder and `package-lock.json`, then run `npm install` again
3. Check the console for any error messages

## Additional Resources

- [Vite Documentation](https://vitejs.dev/guide/)
- [React Documentation](https://react.dev/)
- [TypeScript Documentation](https://www.typescriptlang.org/docs/)

