# 0002. 在 GitHub 上编写内联公式需要和中文字符区分开

## 📝 summary

- 该笔记记录了在 GitHub 上渲染数学公式的一个注意事项。

## 🔗 links

- https://docs.github.com/zh/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions
  - GitHub doc - 编写数学表达式 - 使用 Markdown 在 GitHub 上显示数学表达式。

## 📒 notes - 公式在 GitHub 上无法正常渲染的情况

- 如果你在使用 Latex 格式来书写内联公式，那么可以使用 `$` 来包裹公式。但是需要注意的是，在 GitHub 上如果要正常渲染，需要确保 `$` 和中文字符区分开，即 —— 加空格。

- 不加空格的写法：
```
时间复杂度：$O(n)$
```
时间复杂度：$O(n)$
- 在本地看到的结果：![](md-imgs/2024-10-20-22-16-49.png)
- 在 GitHub 上看到的结果：![](md-imgs/2024-10-20-22-19-50.png)

---

- 加空格的写法：
```
时间复杂度： $O(n)$
```
时间复杂度： $O(n)$
- 在本地看到的结果：![](md-imgs/2024-10-20-22-17-04.png)
- 在 GitHub 上看到的结果：![](md-imgs/2024-10-20-22-19-54.png)
