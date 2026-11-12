---
name: 团队任务
about: 创建带可验证验收标准的团队任务
labels: atd
---

填写任务背景、目标与实现要点，并填写 Issue 标题。

<!-- atd-task v1 -->
```yaml
key: example-task
module: example
depends_on: []
related: []
allowed_paths: ["src/example/**", "tests/example/**", ".atd/context/modules/example.md"]
acceptance:
  - id: AC1
    text: 合法输入返回预期结果
  - id: AC2
    text: 非法输入返回明确错误
```
