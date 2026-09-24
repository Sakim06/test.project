# Test.Project

A small Node.js starter project set up in Cursor.

## Requirements

- Node.js 24 or later
- npm 11 or later

## Setup

```bash
npm install
```

This installs project dependencies, including [`dotenv`](https://www.npmjs.com/package/dotenv) for loading environment variables from a `.env` file.

## Project files

| File | Purpose |
| --- | --- |
| `package.json` | Project name, scripts, and dependencies |
| `cursor.md` | Notes and context for Cursor |
| `.env` | Local secrets (create this yourself; do not commit it) |

The main entry file is `index.js` (`package.json` → `"main"`). Add that file when you start writing application code.

## Scripts

```bash
npm test
```

No tests are defined yet. Replace the placeholder `test` script in `package.json` when you add tests.

## PowerShell note (Windows)

If `npm` fails with **running scripts is disabled on this system**, PowerShell is blocking `npm.ps1`. Use:

```powershell
npm.cmd install
```

Or open a new terminal after setting the current-user execution policy to `RemoteSigned`.

## License

ISC
