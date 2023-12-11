it reproduces the following stylelint issue: https://github.com/stylelint/stylelint/issues/7393

1. `yarn install`
2. `yarn lint`

---

Expected: It runs

Actual behavior:

```
$ stylelint 'src/**/*.scss'
TypeError: Cannot read properties of undefined (reading 'rejected')
```
