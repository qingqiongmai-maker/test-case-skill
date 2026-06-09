# test-case-skill

本仓库用于保存 Codex 测试用例生成相关 skill。

## 包含内容

- `skills/camera-app-testcases/SKILL.md`：监控摄像机 App 需求测试分析 Skill。
- `skills/camera-app-testcases/agents/openai.yaml`：Skill 展示信息和默认提示。
- `docs/使用文档.docx`：给测试同事使用的 WPS/Word 兼容使用文档。

## 使用方式

在 Codex 中输入：

```text
使用 camera-app-testcases 处理需求文档：
需求文档：填写需求文档完整路径
输出目录：填写输出目录
```

测试点文件会以 XMind 可导入的 Markdown 标题大纲形式输出。
