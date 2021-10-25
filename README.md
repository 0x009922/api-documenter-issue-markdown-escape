# issue: unexpected markdown escaping

## Expected output markdown

Like in VSCode:

![How it looks in VSCode](./vscode-demo.png)

## Actual output

You may look by yourself: [docs/...testinterface.md](./docs/api-documenter-issue-markdown-escape.testinterface.md):

![Actual demo](./actual-demo.png)

## Install & recompile

> use `pnpm`

```shell
pnpm i
pnpm compile-dts
pnpm api:extract
pnpm api:document
```