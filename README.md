# ESLint demo

## Setting

```
$ npx install typescript
$ npm install -D eslint @typescript-eslint/parser @typescript-eslint/eslint-plugin
$ touch tsconfig.eslint.json
$ touch .eslintrc.js
```

## Run lint

```
npm run lint {file_name}
```

## Invalid rules

部分的にルールを無効にするには、その行の前にコメント eslint-disable-next-line を追加します。

```
// eslint-disable-next-line camelcase
export const hello_world = "Hello World";
```

## Documents

### Rules

- ESLint Rules Reference
  https://eslint.org/docs/latest/rules/
  https://eslint.org/docs/latest/rules/camelcase

- ESLint で TypeScript のコーディング規約チェックを自動化
  https://typescriptbook.jp/tutorials/eslint
