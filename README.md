# websquids-react-vite-starter

## Overview

**websquids-react-vite-starter** is a starter project designed for building modern web applications. It includes essential tooling and configuration to streamline development with React, TypeScript, Vite, TailwindCSS, and a collection of utilities to ensure code quality and performance.

## Features

- **Vite**: Lightning-fast build tool and dev server.
- **React**: Latest React framework for building UI components.
- **TypeScript**: Strongly typed development for scalable and maintainable code.
- **TailwindCSS**: Utility-first CSS framework for fast UI styling.
- **Zustand**: Simplified state management.
- **ESLint**: Linter for maintaining consistent and error-free code.
- **Prettier**: Code formatter for consistent style.
- **Radix UI**: Accessible UI primitives.
- **Lucide Icons**: Beautiful, customizable React icons.

---

## Requirements

- **Node.js**: ^16.0.0
- **pnpm**

---

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd websquids-react-vite-starter
   ```

2. Install dependencies:
   ```bash
   pnpm i
   ```

---

## Usage

### Development

Start the development server:

```bash
pnpm dev
```

### Build

Build the project for production:

```bash
pnpm build
```

### Preview

Preview the production build locally:

```bash
pnpm preview
```

### Lint

Run ESLint to check for code quality issues:

```bash
pnpm lint
```

### Format Code

Format code using Prettier:

```bash
pnpm format
```

### Fix Linting Issues

Automatically fix lint issues:

```bash
pnpm lint:fix
```

---

## Project Structure

```plaintext
.
├── src/          # Source code
├── public/       # Static assets
├── package.json  # Project configuration
├── vite.config.js # Vite configuration
└── README.md     # Project documentation
```

---

## Key Dependencies

### Runtime

- `react` & `react-dom`: ^19.0.0
- `zustand`: State management
- `tailwindcss`: Utility-first CSS
- `lucide-react`: Icon library

### Development

- `vite`: Build tool
- `typescript`: Type-checking
- `eslint` & `prettier`: Code quality and formatting tools
- `@vitejs/plugin-react`: Vite plugin for React

---

## Customization

To configure TailwindCSS, modify the `tailwind.config.js` file in the root directory.

---

## Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

---

## License

This project is licensed under the **MIT License**. See the [LICENSE](./LICENSE) file for details.

---

## Author

Developed by [websquids LLC](https://websquids.com).

For any questions or support, contact [info@websquids.com](mailto:info@websquids.com).
