# standard

基于 eslint + stylelint + husky + lint-staged 的代码提交规范例子

```json
"husky": {
  "hooks": {
    "pre-commit": "lint-staged"
  }
},
"lint-staged": {
  "*.{js,jsx,ts,tsx}": "eslint --fix",
  "*.{css,less}": "stylelint --fix"
}
```
