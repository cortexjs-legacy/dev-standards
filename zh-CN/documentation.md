# 文档规范

所有的文档，一律使用 markdown，实际上这里讲的是 markdown 规范。

## 代码块

#### 非内联代码块统一使用三个 `，而不使用 Tab 缩进。

另外注意，已经使用三个 ` 的代码，不要再缩进了。

比如如下的代码块就是不正确的：

```js
  var path = require('path');
  var file = path.resolve('./abc');
```

#### 代码块中的代码，也请使用 **2** 个空格来缩进

```js
function foo (n) {
  console.log(n);
}
```

#### 非内联代码块请添加语言类型标识：


    ```bash
    // 这里是代码的内容，注意，如果代码中写的是 bash，
    // 则代码块开始应该写 ```bash
    ```
