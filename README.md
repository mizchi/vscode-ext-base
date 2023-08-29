# vscode-ext-base

2023/08/29

## Build

```bash
$ pnpm install
$ pnpm build

# Run
## F5

# build for publish
$ cp .env.example .env
# Get your vscode marketplace token and set VSCE_PAT="..."
$ pnpm build
$ pnpm package
$ pnpm publish
```

## LICENSE

MIT