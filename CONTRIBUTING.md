# Contributing to Cmdbook

Thanks for considering a contribution! Cmdbook stays useful because people add the commands they actually use. Here's how to help.

## Ways to Contribute

- **Add a missing command** - something you use regularly that isn't listed yet
- **Improve a description** - make an existing entry clearer or more accurate
- **Fix an error** - wrong flag, outdated syntax, typo, etc.
- **Suggest structure** - better categories or organization (open an issue first for bigger changes)

## Before You Start

For small fixes (typos, a command or two), just open a pull request directly against the command `git` `npm` `pnpm` `yarn` branch.

For anything bigger - new sections, restructuring, or adding a new tool entirely - please open an issue first so we can align before you put in the work.

## Making a Change

1. **Fork** the repo and clone your fork locally
2. **Create a branch** for your change:
   ```bash
   git checkout -b add-git-worktree-command
   ```
3. **Add your entry** to the relevant file in `docs/` (`git.md`, `npm.md`, `pnpm.md`, or `yarn.md`), matching the existing format:
   ```markdown
   | `command here` | Short, clear description |
   ```
4. **Commit** with a descriptive message:
   ```bash
   git commit -m "Add git worktree command"
   ```
5. **Push** and open a pull request:
   ```bash
   git push origin add-git-worktree-command
   ```

## Style Guidelines

- One command per row, one line per description — no multi-line entries
- Descriptions should be short and focused on the most common use case, not every possible flag
- Use backticks around all commands: `` `git status` ``
- Keep alphabetical/logical order within a table where possible
- If a command has a commonly-used shorthand or flag combo, prefer that over the verbose form (e.g. `git switch -c` over separate `branch` + `checkout` steps) — but feel free to note alternatives if genuinely useful
- Match the tone of existing entries: plain, direct, no fluff

## Pull Request Checklist

- [ ] Our addition follows the existing table format
- [ ] We don't duplicate an existing entry
- [ ] We checked the command actually works as described
- [ ] Our description is one line and clear to a newer developer

## Code of Conduct

This project follows a [Code of Conduct](./CODE_OF_CONDUCT.md). Be respectful, be constructive, and assume good intent. Disagreements about content are fine — just keep it about the content.

---

Questions or ideas that don't fit a PR? Open an issue — happy to discuss.