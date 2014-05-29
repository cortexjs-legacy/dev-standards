# 项目规范

如果你想偷懒，请直接使用 [nodeinit](http://www.npmjs.org/package/nodeinit) 来初始化项目

```bash
$ nodeinit <git-clone-url>
```

### 测试相关

- 项目必须包含 travis-ci 配置
- 与其他系统没有过多耦合的项目，必须通过 travis-ci 的测试
- README.md 中必须包含 travis-ci 的 badge

### package.json 规范

package.json 中以下属性必须包含，并且正确：

- 必须包含 repo url，且迁移项目之后记得更改
- issue 地址必须正确，且迁移项目之后记得更改
- keywords 必须包含，且尽量包含充分的关键字，使其容易被搜索到

### .gitignore

必须包含完整的，足以面对常见情况的 .gitignore 设置

### 必要的文档

至少包含：

- Public APIs 的必要说明
  - 方法，参数类型，可选情况，返回值，做了什么事情
- 最常见的使用例子
