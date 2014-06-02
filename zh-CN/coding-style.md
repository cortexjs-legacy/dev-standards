# 编程风格

## 缩进与 tab

- 除了 Makefile 文件，禁止使用 tab 来进行缩进

```
// Set to true to insert spaces when tab is pressed
"translate_tabs_to_spaces": true,
```

- 代码使用 **两个空格** 来缩进，包括 json 文件

```js
// The number of spaces a tab is considered equal to
"tab_size": 2,
```

## 函数定义

函数不使用 `var` 来定义，比如

```js
var noop = function(){}; // 不要这么做

function noop () {} // 推荐
```

