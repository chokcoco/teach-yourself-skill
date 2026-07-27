# 案例：高质量 AI Code Review

`teach-yourself-skill` 的完整课程案例，展示一门 9 章静态课程的最终交付形态。

## 内容

```text
examples/high-quality-ai-code-review/
├── index.html               # 课程首页（目录、进度、导航）
├── course.json              # 课程元数据
├── lessons/                 # 逐章 Markdown + HTML
├── reference/               # 术语表等参考资料
└── assets/                  # CSS、JS、主题
```

## 阅读方式

在浏览器中打开 `index.html` 即可阅读全部 9 章内容。

## 验证

从仓库根目录运行：

```bash
node scripts/validate-course.mjs examples/high-quality-ai-code-review
```

## 发布边界

案例基于工程实践写作。公开发布前，维护者需确认课程正文不包含非公开信息或受限资料。
