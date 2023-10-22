# bumping

[![NPM version](https://img.shields.io/npm/v/bumping?color=a1b858&label=)](https://www.npmjs.com/package/bumping)

Forked from [`version-bump-prompt`](https://github.com/JS-DevTools/version-bump-prompt)

###### Changes in this fork

- Renamed to `bumping` - so you can use `npx bumping` directly.
- Ships ESM and CJS bundles.
- Add a new argument `--execute` to execute the command before committing.
- Use current version's `preid` when avaliable.
- Confirmation before bumping.
- Enable `--commit` `--tag` `--push` by default. (opt-out by `--no-push`, etc.)
- `-r` or `--recursive` to bump all packages in the monorepo.
- Conventional Commits by default. 
- Supports config file `bumping.config.ts`:

```ts
import { defineConfig } from 'bumping'

export default defineConfig({
  // ...options
})
```
