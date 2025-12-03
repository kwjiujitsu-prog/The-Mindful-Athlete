# Contributing

Guidelines for contributors:

- Work on feature branches and open PRs against `main`.
- Run TypeScript checks before opening PR: `npx tsc --noEmit` in the app folder you changed.
- Keep `App.tsx` entry files minimal; add components under `src/`.
- If you update dependencies, update `package-lock.json` and ensure CI passes.
