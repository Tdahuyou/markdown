# 0006

## 📒 notes

- 在 github 上，下面的内容在渲染时，行号 1 会被高亮，而其他地方不会。

```
function foo() {
  // 行号 1 将会高亮
  console.log("Hello, world!");
}
<!-- {1} -->
```
```js
function foo() {
  // 行号 1 将会高亮
  console.log("Hello, world!");
}
<!-- {1} -->
```