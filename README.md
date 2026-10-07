# Source-Locked Video Script

这是唯一主版本的短视频原素材脚本 Skill。

它把带时间帧的 SRT、采访、咨询、案例、跟拍、医生口播或其他原素材，整理成可直接剪辑的 source-locked 成片脚本。

## 核心目标

不是把素材讲得最完整，也不是把专业知识塞得最多，而是：

```text
真实原素材
-> 找到最值得成片的内容
-> 明确一个 Watching Task / 用户决策任务
-> 选择最强证据
-> 重排成观看逻辑
-> 保留精细时间帧
-> 做公开表达与合规检查
```

对医美医生 IP，内容价值优先看是否推进用户的：

- 结果代入
- 适配判断
- 专业信任
- 风险降低
- 下一步决策

效果、案例、技术、资质、恢复反馈、医生判断等都只是证据形式，不自动等于“科普”。

## Source-Locked 边界

- 每条原声必须能回到原素材和时间帧。
- 原素材对应文字：**允许删，不允许补**。
- 可以重排真实片段，但不能制造新的因果、动机、诊断、结果或承诺。
- 时间帧是剪辑定位层，不是叙事模板。
- 默认不输出画面说明、B-roll、转场或镜头指令。

## 默认工作流

1. 扫完整批原素材。
2. 判断真正值得做的内容线。
3. 给出建议选题并只进行一次用户确认。
4. 生成被选中的脚本。
5. 自动做来源、决策推进、重复、可剪辑性和合规检查。

## 默认成片输出

```text
标题
-> 视频文字时间帧
-> 视频结构及文案
-> 风险处理（仅在确有风险时）
```

时间帧表固定三列：

```text
素材 | 原时间帧 | 原素材对应文字
```

## 医美合规

医美公开内容额外读取：

`references/medical-aesthetics-compliance.md`

核心原则：

```text
社区可发 != 聚光/广告可投
```

项目、账号和当前平台规则优先于通用示例。

## 当前文件

```text
├── SKILL.md
├── README.md
├── agents/
│   └── openai.yaml
└── references/
    ├── material-analysis.md
    ├── edit-ready-format.md
    └── medical-aesthetics-compliance.md
```

旧版固定结构、Reviewer 展示层、Adapter 和历史案例已经从当前主版本移除；需要时可从 Git 历史恢复。

本仓库是脚本 Skill 的唯一事实源。后续脚本逻辑只在这里迭代。

## 安装

```bash
git clone https://github.com/wyuhan293-55/source-locked-video-script-public.git ~/.codex/skills/source-locked-video-script
```

调用：

```text
使用 $source-locked-video-script 分析这批原素材
```
