<div align="center">

# Inikit 🚀

[![npm version](https://badge.fury.io/js/inikit.svg)](https://www.npmjs.com/package/inikit)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub issues](https://img.shields.io/github/issues/ajaykumarn3000/Inikit)](https://github.com/ajaykumarn3000/Inikit/issues)
[![GitHub stars](https://img.shields.io/github/stars/ajaykumarn3000/Inikit)](https://github.com/ajaykumarn3000/Inikit/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/ajaykumarn3000/Inikit)](https://github.com/ajaykumarn3000/Inikit/network)
[![GitHub contributors](https://img.shields.io/github/contributors/ajaykumarn3000/Inikit)](https://github.com/ajaykumarn3000/Inikit/graphs/contributors)

</div>

> The best way to get started with Next.js and React projects.

Inikit is a powerful, open-source CLI tool that scaffolds modern web
applications with industry-standard development tools and configurations. Built
for developers, by developers, to streamline the project setup process and
enforce best practices from day one.

<!-- ## 🌟 Why Inikit?

In the fast-paced world of web development, setting up a new project with all
the necessary tools and configurations can be time-consuming and error-prone.
Inikit solves this by providing:

- **Zero Configuration**: Get started immediately with sensible, battle-tested
  defaults
- **Best Practices**: Industry-standard tools and configurations out of the box
- **Developer Experience**: Consistent setup across teams and projects
- **Modern Stack**: Latest versions of popular tools and frameworks
- **Flexibility**: Choose only the tools you need for your project

## ✨ Features

- 🎯 **Framework Support**: Next.js and React (with Vite)
- 📝 **TypeScript Ready**: Full TypeScript support out of the box
- 🎨 **Styling**: Tailwind CSS integration
- ✅ **Code Quality**: ESLint, Prettier, and Commitlint pre-configured
- 🔧 **Git Hooks**: Husky for automated code quality checks
- 🚀 **Zero Configuration**: Get started immediately with sensible defaults
- 📦 **Modern Tooling**: Latest versions of all dependencies -->

## 🚀 Quick Start

### Using npx (Recommended)

The fastest way to scaffold a new project:

```bash
npx inikit@latest
```

### Global Installation

For repeated use, install globally:

```bash
npm install -g inikit
inikit
```

### System Requirements

- **Node.js**: 18.0 or higher
- **npm**: 7.0 or higher (or **yarn**/**pnpm** equivalent)
- **Git**: For version control (recommended)

## 🛠️ What You Get

### Frameworks

- **Next.js** - Full-stack React framework with App Router
- **React** - Modern React with Vite for fast development

### Development Tools

- **TypeScript** - Type-safe JavaScript development
- **Tailwind CSS** - Utility-first CSS framework
- **Prettier** - Opinionated code formatter
- **ESLint** - JavaScript/TypeScript linter
- **Commitlint + Husky** - Enforce conventional commit messages

## 📋 Usage

When you run Inikit, you'll be prompted to:

1. **Project Name**: Enter your project name (lowercase, no spaces)
2. **Framework**: Choose between Next.js or React
3. **TypeScript**: Enable/disable TypeScript support
4. **Dev Tools**: Select from Tailwind CSS, Prettier, and Husky+Commitlint

```bash
$ npx inikit@latest

Welcome to Inikit v1.2.4

✔ Enter the project name › my-awesome-app
✔ Select a framework › Next.js
✔ Do you want to use TypeScript? › Yes
✔ Select dev tools › Tailwind CSS, Prettier, Husky

✅ Project initialized successfully!
```

## 🏗️ Local Development

Want to contribute to Inikit or test changes locally? Here's how to get started:

### Prerequisites

- Node.js 18.0 or higher
- npm 7.0 or higher
- Git

### Clone and Setup

```bash
# Clone the repository
git clone https://github.com/ajaykumarn3000/Inikit.git
cd Inikit

# Install dependencies
npm install

# Run in development mode
npm run dev

# Build the project
npm run build

# Test the CLI locally (creates a global symlink)
npm link
inikit

# Unlink when done testing
npm unlink -g inikit
```

### Available Scripts

| Script                 | Description                                 |
| ---------------------- | ------------------------------------------- |
| `npm run dev`          | Run the CLI in development mode with `tsx`  |
| `npm run build`        | Build the project for production            |
| `npm run lint`         | Run ESLint to check for code issues         |
| `npm run lint:fix`     | Auto-fix ESLint issues where possible       |
| `npm run format`       | Format code with Prettier                   |
| `npm run format:check` | Check if code is properly formatted         |
| `npm run clean`        | Remove the `dist` directory                 |
| `npm run deploy`       | Build and publish to npm (maintainers only) |

### Project Structure

```text
Inikit/
├── index.ts              # Main CLI entry point
├── utils.ts              # Core utility functions
├── package.json          # Project configuration
├── templates/            # Template files for different tools
│   ├── commitlint/       # Commitlint configuration
│   ├── husky/            # Git hooks
│   ├── prettier/         # Prettier configuration
│   └── tailwind/         # Tailwind CSS files
├── dist/                 # Compiled output (created after build)
└── README.md             # This file
```

## 📄 Project Policies & Community Files

For details on contributing, security, and community standards, see:

- [LICENSE](./LICENSE)
- [Code of Conduct](./CODE_OF_CONDUCT.md)
- [Contributing Guidelines](./CONTRIBUTING.md)
- [Security Policy](./SECURITY.md)

## 🐛 Issues and Support

We're here to help! If you encounter any issues or have questions:

### 🚨 Bug Reports

- **GitHub Issues**:
  [Report bugs here](https://github.com/ajaykumarn3000/Inikit/issues)
- Please use our bug report template for faster resolution

### 💡 Feature Requests

- **GitHub Discussions**:
  [Suggest new features](https://github.com/ajaykumarn3000/Inikit/discussions)
- Help us understand your use case and requirements

### ❓ Questions and Support

- **GitHub Discussions**:
  [Ask questions here](https://github.com/ajaykumarn3000/Inikit/discussions)
- **Documentation**: Check our README for common use cases
- **Examples**: Look at the templates directory for configuration examples

### 🔍 Before Reporting

1. **Search existing issues** to avoid duplicates
2. **Check the latest version** - your issue might already be fixed
3. **Review the documentation** - the answer might already be there
4. **Test with a minimal example** - helps us reproduce the issue

## 🌟 Community

Join our growing community of developers:

- ⭐ **Star the project** on GitHub to show your support
- 🐛 **Report issues** to help us improve
- 💬 **Join discussions** to share ideas and ask questions
- 🤝 **Contribute code** to make Inikit even better
- 📢 **Share with others** who might find Inikit useful

## 🔒 Security

If you discover a security vulnerability, please report it privately by emailing
[ajaykumarn3000@gmail.com](mailto:ajaykumarn3000@gmail.com). Please do not
report security vulnerabilities through public GitHub issues.

## 📊 Project Stats

- **Language**: TypeScript
- **Package Manager**: npm
- **License**: MIT
- **Maintained**: ✅ Actively maintained
- **Node.js**: 18.0+ required

## 🗺️ Roadmap

We're continuously working to improve Inikit. Here's what's on our radar:

- [ ] **Framework Support**: Vue.js, Svelte, Angular
- [ ] **Additional Tools**: Vitest, Jest, Cypress
- [ ] **Package Managers**: Yarn, pnpm support
- [ ] **Templates**: More starter templates
- [ ] **CI/CD**: GitHub Actions, GitLab CI templates
- [ ] **Database**: Prisma, Drizzle integration options
- [ ] **UI Libraries**: More component library options

Want to contribute to any of these? We'd love your help!

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file
for details.

## 👥 Author

**Ajaykumar Nadar** - [Github](https://github.com/ajaykumarn3000) |
[Portfolio](https://ajaykumarn3000.in)

## 🙏 Acknowledgments

Inikit stands on the shoulders of giants. We're grateful to:

- **Open Source Community**: For the amazing tools and libraries we integrate
- **Framework Teams**: Next.js, React, Vite, and TypeScript teams for their
  excellent work
- **Tool Maintainers**: ESLint, Prettier, Husky, and Commitlint contributors
- **Contributors**: Everyone who has contributed code, reported issues, or
  shared feedback
- **Users**: The developer community that uses and trusts Inikit
- **Inspiration**: Projects like create-next-app, create-react-app, and
  create-vite

Special thanks to all the developers who believe in making development tools
better and more accessible.

---

<div align="center">

**Made with ❤️ by [Ajaykumar Nadar](https://ajaykumarn3000.github.io)**

_Building tools that developers love to use_

[⭐ Star on GitHub](https://github.com/ajaykumarn3000/Inikit) •
[🐛 Report Bug](https://github.com/ajaykumarn3000/Inikit/issues) •
[💡 Request Feature](https://github.com/ajaykumarn3000/Inikit/discussions) •
[🤝 Contribute](https://github.com/ajaykumarn3000/Inikit/blob/main/CONTRIBUTING.md)

</div>
