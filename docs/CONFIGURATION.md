# Project Configuration

## Development Environment Setup

This guide will help you set up your development environment to work efficiently with this project.

### Prerequisites

1. **Node.js and npm**
   - Install Node.js (version 18.x or later) from [nodejs.org](https://nodejs.org)
   - npm comes bundled with Node.js
   - Verify installation:
     ```bash
     node --version
     npm --version
     ```

2. **Git**
   - Install Git from [git-scm.com](https://git-scm.com)
   - Verify installation:
     ```bash
     git --version
     ```

3. **Code Editor**
   - We recommend using Visual Studio Code
   - Install from [code.visualstudio.com](https://code.visualstudio.com)
   - Recommended VS Code extensions:
     - ESLint
     - Prettier
     - ES7+ React/Redux/React-Native snippets
     - Auto Import
     - Path Intellisense

### Project Setup

1. **Clone the Repository**
   ```bash
   git clone [repository-url]
   cd open-react-vite
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Environment Variables**
   - Copy `.env.example` to `.env`
   - Update the environment variables as needed
   - Never commit `.env` file to version control

### Development Workflow

1. **Starting the Development Server**
   ```bash
   npm run dev
   ```
   - The application will be available at `http://localhost:5173`

2. **Building for Production**
   ```bash
   npm run build
   ```
   - Creates optimized production build in the `dist` directory

3. **Running Tests**
   ```bash
   npm test
   ```

### Code Quality Tools

1. **Linting**
   - ESLint is configured for code quality
   - Run linter:
     ```bash
     npm run lint
     ```

2. **Formatting**
   - Prettier is configured for code formatting
   - Format code:
     ```bash
     npm run format
     ```

### Git Workflow

1. **Branch Naming Convention**
   - Feature branches: `feature/description`
   - Bug fixes: `fix/description`
   - Hotfixes: `hotfix/description`

2. **Commit Messages**
   - Use conventional commits format
   - Example: `feat: add new feature`, `fix: resolve bug`

### Troubleshooting

1. **Common Issues**
   - If you encounter dependency issues:
     ```bash
     rm -rf node_modules
     npm install
     ```
   - If the development server fails to start:
     ```bash
     npm run dev -- --force
     ```

2. **Getting Help**
   - Check the project's issue tracker
   - Review the documentation
   - Contact the maintainers

### Additional Resources

- [Vite Documentation](https://vitejs.dev/guide/)
- [React Documentation](https://reactjs.org/docs/getting-started.html)
- [TypeScript Documentation](https://www.typescriptlang.org/docs/)