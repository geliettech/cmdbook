# Package Manager Command Comparison

Part of [CLI Command Book](../README.md). A quick side-by-side for switching between [npm](./npm.md), [pnpm](./pnpm.md), and [Yarn](./yarn.md).

| Action | npm | pnpm | Yarn |
|---|---|---|---|
| Install all deps | `npm install` | `pnpm install` | `yarn` |
| Add a package | `npm install <pkg>` | `pnpm add <pkg>` | `yarn add <pkg>` |
| Add dev dependency | `npm install <pkg> -D` | `pnpm add <pkg> -D` | `yarn add <pkg> --dev` |
| Remove a package | `npm uninstall <pkg>` | `pnpm remove <pkg>` | `yarn remove <pkg>` |
| Install globally | `npm install -g <pkg>` | `pnpm add -g <pkg>` | `yarn global add <pkg>` |
| Run a script | `npm run <script>` | `pnpm run <script>` | `yarn run <script>` |
| Update deps | `npm update` | `pnpm update` | `yarn upgrade` |
