# humanizer-zh 依赖

`teach-yourself-skill` 把中文学生可见内容的自然表达作为质量闸门，因此依赖 [op7418/Humanizer-zh](https://github.com/op7418/Humanizer-zh) 提供的可调用 `humanizer-zh` Skill。它不是 Node 或 npm 依赖，也不会被 `SKILL.md` 的 frontmatter 自动安装。

## 安装约定

将两个 Skill 安装到同一个 skills 根目录：

```text
<skills-root>/
├── teach-yourself-skill/
└── humanizer-zh/
    └── SKILL.md
```

开始任何中文学生可见文本的生成或改写前，确认 `humanizer-zh/SKILL.md` 可读并完整遵循其流程。若安装位置不相邻，先通过当前运行环境的 skill 清单定位它；不要假定本仓库的相对路径。

## 缺失时的处理

缺少 `humanizer-zh` 时，仍可完成课程规划、资料整理、结构生成和第一阶段确定性质检；但中文学生可见文本不得宣称已经通过完整质量闭环。请安装该 Skill，或由维护者明确批准替代的语言质量流程并记录例外。

开源发布时，请在仓库 README 的依赖段落链接到 [op7418/Humanizer-zh](https://github.com/op7418/Humanizer-zh)，并按需要记录使用的版本或提交哈希。
