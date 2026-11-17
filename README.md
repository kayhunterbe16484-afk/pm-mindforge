# PM MindForge

一个**引导型**的产品经理面试训练器：三层能力画像 + 七阶段训练 + 思维/表达双轨评分。

## 它解决什么问题

| 常见做法 | 它怎么做 |
|---|---|
| 直接给参考答案 | 先引导你拆，答完才公开意图与参考 |
| 一次抛一堆问题 | 一次只问一个，卡住才给方向 |
| 一个总分 | 思维 100 + 表达 100，分开算 |
| 换题就崩 | 用迁移题检验“会不会”，记 M0–M3 |

## 快速开始

```bash
mkdir -p ~/.dsh/skills
cp pm-mindforge.md ~/.dsh/skills/
```

其他环境：

| 环境 | 放哪 | 文件名 |
|---|---|---|
| DSH（用户级） | `~/.dsh/skills/` | `pm-mindforge.md` |
| DSH（项目级） | `<项目>/.dsh/skills/` | `pm-mindforge.md` |
| 支持 `SKILL.md` 的 Agent | `<skills>/pm-mindforge/` | 改名 `SKILL.md` |
| 自定义指令 | 粘贴正文 | 保留 `name` / `description` |

## 怎么调用

```text
/pm-mindforge 开始训练，岗位 C 端，中级，文本作答
```

或直接说：“用 pm-mindforge 面我”。

## 它会怎么对你

1. **出题不给考点**，先让你猜面试官想考什么；
2. **一次只问一个问题**；
3. **引导优先**：卡住时给 L1–L3 方向，不替你写答案；
4. **两个分数**，思维与表达不互相补偿；
5. **必须重答**，讲完不算学会。

## 内容

单文件 262 行、15 节：七阶段流程、意图解码六字段、追问 P0–P5、四状态 A–D、三层画像、八类问题、双轨评分、边界规则、长期成长、22 题题库、模板与自检。

## 版本与校验

| 项 | 值 |
|---|---|
| 版本 | v1.0 |
| 校验 | 见 `CHECKSUM.md` |

```bash
shasum -a 256 pm-mindforge.md
```

## 许可证

[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)：可自由使用与修改，需署名、非商业、相同方式共享。详见 `LICENSE`。

## 来源

由目录版 skill（27 个 references + 6 个 templates）压缩生成；本仓库只分发单文件便携版。
