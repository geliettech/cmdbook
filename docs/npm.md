# npm Commands

Part of [CLI Command Book](../README.md).

## What is npm?

npm (Node Package Manager) is the default package manager for Node.js. It's used to install, manage, and publish JavaScript packages, and comes bundled automatically when you install Node.js.

| Command | Description |
|---|---|
| `npm init` | Create a new `package.json` (interactive) |
| `npm init -y` | Create `package.json` with defaults |
| `npm install` | Install all dependencies from `package.json` |
| `npm install <pkg>` | Install and add a package to dependencies |
| `npm install <pkg> --save-dev` | Install as a dev dependency |
| `npm install -g <pkg>` | Install a package globally |
| `npm uninstall <pkg>` | Remove a package |
| `npm update` | Update packages to latest allowed versions |
| `npm run <script>` | Run a script defined in `package.json` |
| `npm ls` | List installed packages |
| `npm outdated` | Check for outdated packages |
| `npm audit` | Check for known vulnerabilities |
| `npm audit fix` | Automatically fix vulnerabilities where possible |
| `npm cache clean --force` | Clear the npm cache |
| `npm ci` | Clean install from `package-lock.json` (faster, for CI) |

See also: [Package Manager Comparison](./comparison.md)
