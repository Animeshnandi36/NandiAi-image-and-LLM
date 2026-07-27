# How to run this repo on Replit

This repo is configured to run on Replit using the PNPM workspace. See `.replit` for run configuration.

- Use `pnpm install` to install dependencies.
- Use `pnpm build` to build the workspace.
- Use `pnpm -w` to run workspace commands across packages.

Notes:
- The workspace contains subpackages under `artifacts/` and `lib/`.
- The `pnpm-lock.yaml` is included to ensure consistent installs on Replit.
