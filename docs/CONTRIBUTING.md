# 贡献指南与命名规范

---

## 📁 文件命名规范

```
[动词]-[对象]-[修饰词].md

示例：
write-email-formal.md
analyze-data-pandas.md
generate-image-portrait.md
summarize-article-bullet.md
```

- 全部小写
- 用连字符 `-` 分隔，不用下划线或空格
- 动词开头：write / generate / analyze / summarize / convert / review / explain...

---

## 📂 放哪个目录？

```
问自己：
1. 这个提示词只适合某个工具？  → by-tool/
2. 这个提示词适合某类任务？    → by-task/
3. 这个提示词面向某个行业？    → by-industry/
4. 跨类别？                   → 三个都放，用软链接或直接复制
```

---

## ✅ 提交 PR 前的自查清单

- [ ] 文件命名符合规范
- [ ] 放在正确的目录下
- [ ] 使用了 `templates/PROMPT_TEMPLATE.md` 格式
- [ ] 包含至少一个完整的使用示例
- [ ] 在对应目录的 `README.md` 中登记了新文件

---

## 🔖 提交信息格式

```
feat: add [提示词名称] to [目录]
fix: improve [提示词名称] clarity
docs: update [目录] README
```
