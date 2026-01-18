# Dev Container Configuration

This directory contains the configuration for GitHub Codespaces and VS Code Dev Containers.

## What's Included

The devcontainer is configured with the following tools and runtimes to support all sample languages in this repository:

### Languages & Runtimes
- **Python 3.11**: For Python samples and notebooks
- **Node.js 20**: For TypeScript/JavaScript samples
- **.NET 9.0**: For C# samples
- **Java 17 with Maven**: For Java samples

### Tools
- **Git**: Version control
- **GitHub CLI**: GitHub integration
- **pre-commit**: Automated code quality checks

### VS Code Extensions
- Python development (Python, Pylance, Jupyter)
- TypeScript/JavaScript development (ESLint, Prettier)
- C# development (C# DevKit)
- Java development (Java Extension Pack, Maven)
- Azure tools (Azure Functions, Azure Account)
- GitHub Copilot (AI pair programming)

## Post-Create Setup

When the devcontainer is created, it automatically:
1. Installs Python dependencies from `dev-requirements.txt`
2. Sets up pre-commit hooks for code quality checks

## Port Forwarding

The following ports are automatically forwarded:
- 3000, 5000, 8000, 8080 - Common development server ports

## Usage

### GitHub Codespaces
Click the "Open in GitHub Codespaces" badge in the main README or:
1. Go to the repository on GitHub
2. Click **Code** → **Codespaces** → **Create codespace on main**

### VS Code Dev Containers
1. Install the [Dev Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
2. Open the repository in VS Code
3. Click the green button in the bottom-left corner
4. Select "Reopen in Container"

## Customization

You can customize the devcontainer configuration by editing `devcontainer.json`. See the [Dev Containers documentation](https://containers.dev/) for more information.
