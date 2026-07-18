# Yarn Commands

Part of [CLI Command Book](../README.md).

## What is Yarn?

Yarn is a package manager for JavaScript, originally created as a faster, more secure alternative to npm. It manages project dependencies via `package.json` and supports features like workspaces for monorepos and deterministic installs via lockfiles.

| Command | Description |
|---|---|
| `yarn init` | Create a new `package.json` |
| `yarn` / `yarn install` | Install all dependencies |
| `yarn add <pkg>` | Add a package to dependencies |
| `yarn add <pkg> --dev` | Add a dev dependency |
| `yarn global add <pkg>` | Install a package globally |
| `yarn remove <pkg>` | Remove a package |
| `yarn upgrade` | Update dependencies |
| `yarn run <script>` | Run a script |
| `yarn list` | List installed packages |
| `yarn outdated` | Check for outdated packages |
| `yarn audit` | Check for vulnerabilities |
| `yarn cache clean` | Clear the yarn cache |

See also: [Package Manager Comparison](./comparison.md)
