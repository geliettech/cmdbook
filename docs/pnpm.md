# pnpm Commands

Part of [CLI Command Book](../README.md).

## What is pnpm?

pnpm is a fast, disk-space-efficient package manager for JavaScript. Unlike npm and Yarn, it uses a single shared content-addressable store for packages, saving them once on disk and linking them into projects instead of duplicating files.

| Command | Description |
|---|---|
| `pnpm init` | Create a new `package.json` |
| `pnpm install` | Install all dependencies |
| `pnpm add <pkg>` | Add a package to dependencies |
| `pnpm add -D <pkg>` | Add a dev dependency |
| `pnpm add -g <pkg>` | Install a package globally |
| `pnpm remove <pkg>` | Remove a package |
| `pnpm update` | Update dependencies |
| `pnpm run <script>` | Run a script |
| `pnpm list` | List installed packages |
| `pnpm outdated` | Check for outdated packages |
| `pnpm audit` | Check for vulnerabilities |
| `pnpm store prune` | Clean unused packages from the store |
| `pnpm -r <command>` | Run a command across all packages in a monorepo |

See also: [Package Manager Comparison](./comparison.md)
