# jest-expo/universal ignores setupFilesAfterEnv

How to reproduce:

1) Run `yarn` and `yarn test`
2) Observe that test fails
3) Change jest preset from `jest-expo` to `jest-expo/universal` in `package.json`

Expected behaviour:

- Specs fail

Actual behavious:

- Specs pass
