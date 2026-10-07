---
name: source-locked-video-script
description: Turn raw timestamped footage, interview transcripts, subtitles, consultation clips, customer stories, doctor/KOS footage, or creator素材 into source-locked, edit-ready short-video scripts with selected source time frames. Use when the user asks to analyze original素材, find worthwhile content threads, keep对应时间帧, or produce Xiaohongshu/Douyin/KOS scripts from raw footage.
---

# Source-Locked Video Script

## Core Objective

Convert a pile of real source material into the **most worthwhile cuttable content**, not the most complete transcript and not the most knowledge-dense explanation.

Priority:

```text
source truth
-> decision/content value
-> viewing logic
-> source selection
-> editability
-> packaging
```

For medical-aesthetics doctor IP content, the commercial goal is usually to help the right user move toward **desire, fit judgment, trust, risk reduction, and a more specific next decision**. Do not confuse this with teaching more medical knowledge.

## Required Reading

- Read `references/material-analysis.md` before choosing content threads, hooks, or structure.
- Read `references/edit-ready-format.md` before producing the final script.
- For medical-aesthetics public content, also apply `references/medical-aesthetics-compliance.md` before final delivery.

Project/account-specific rules override general references.

## Internal Checks

Keep these checks internal unless the user asks to inspect them:

- **source truth**: every selected source line and time frame is traceable
- **decision progress**: the piece moves a real viewer decision, not merely knowledge density
- **viewing task**: one clear unresolved question is driving the watch
- **evidence**: the strongest available evidence supports that task
- **editability**: the source can actually be cut into the planned order
- **compliance/account fit**: public wording fits the exact channel and project rules

## One-Confirmation Workflow

Use one continuous workflow for a new raw-material case.

### Stage 1: Scan The Full Source

Analyze first; do not write the final script yet.

Extract only source-backed information:

- person/user profile when actually present
- project/procedure context
- chronology and source names
- user pains, desires, worries, objections, and decision questions
- doctor/professional judgments, corrections, restraint, refusals, choices, and tradeoffs
- result/recovery/reaction evidence
- technique/credential/trust evidence
- all usable hook candidates
- risky, unsupported, or channel-sensitive expressions

Do not invent motives, diagnoses, outcomes, visual proof, chronology, or doctor opinions.

### Stage 2: Plan The Worthwhile Content Set

Decide how many pieces the material really supports. Do not force a number.

For every proposed piece define internally:

```text
Primary Decision Job:
Viewing Task:
Opening Hook:
Strongest Evidence:
Content Progression:
Output Mode:
Required Source / Time Frames:
```

For medical-aesthetics doctor IP, `Primary Decision Job` should normally be one of:

- `result_projection`: do I want this kind of result / can I picture myself in it?
- `fit_judgment`: what should someone with a foundation like mine judge first?
- `professional_trust`: does this doctor demonstrate judgment/capability worth trusting?
- `risk_reduction`: is a concrete fear or uncertainty made clearer?
- `decision_continuation`: does the viewer leave with a more specific next decision question?

These are content jobs, not fixed formats.

### Evidence Form != Content Job

Result footage, case stories, technical explanation, credentials, consultation, recovery feedback, user reactions, and doctor restraint are **evidence forms**.

Do not classify a piece only by its footage type.

Examples:

- a result can serve desire or professional trust
- technical explanation can serve trust or risk reduction
- consultation judgment can serve fit judgment
- recovery feedback can serve risk reduction

Do not force every useful piece into `科普` just because a doctor is explaining something.

### Decision Progress Gate

A piece deserves to exist when the target viewer is meaningfully closer to wanting, judging, trusting, de-risking, or continuing the decision after watching.

A piece does **not** have to teach a new medical fact.

A complete story, emotional moment, or praise sequence is not enough by itself unless it performs a real decision job.

A real result, recovery response, credential proof, or trust moment can be enough when it clearly advances a decision job.

If a proposed piece needs a cause, diagnosis, result, credential claim, guarantee, or broad rule that the source cannot support, narrow it or mark `不建议出稿`.

### Stage 3: The Only User Confirmation

After analysis and planning, ask the user to choose which proposed piece(s) to generate.

Example:

```text
建议生成：
1. [内容定位]
2. [内容定位]
3. [内容定位]

请输入：1 / 2 / 3 / 全部
```

Do not ask separate confirmations for title, hook, structure, or QA unless the user changes the task.

### Stage 4: Generate Only The Selected Script

Each final script must:

- be based on the source material
- contain no invented story, motive, result, dialogue, diagnosis, timeline, or transition fact
- make every source audio line traceable to a source name and original time frame
- keep source audio separate from any non-source packaging
- use only the source fragments actually intended for the final cut
- avoid repeating the same strongest source across multiple same-case scripts unless justified
- remove or replace risky source fragments that are not usable for the target public channel; never silently rewrite them and still call them source

## Output Mode Decision

Choose internally from the source:

- `医生讲解顺剪版`: source already contains a clear judgment path
- `小红书包装成片版`: useful fragments are scattered and need reordering or clearly labeled non-source packaging
- `不建议出稿`: the promised topic cannot be supported or allowed for the target channel

Do not print mode rationale unless asked.

## Core Script Decisions

### 1. Viewing Task First

Before selecting clips, identify the one unresolved question the viewer is watching to resolve.

For medical aesthetics, prefer user decision language over topic labels.

Weak:

```text
讲双眼皮深度
```

Stronger:

```text
为什么已经做得很窄，还是看起来不自然？
```

### 2. Every Beat Must Move The Decision State

The next fragment must change what the viewer knows, wants, trusts, fears, expects, or needs answered.

Valid movement includes:

- sees a concrete result
- belief -> correction
- desire -> limitation
- problem -> judgment standard
- judgment -> tradeoff
- uncertainty -> professional proof
- fear -> risk boundary
- judgment -> result/recovery confirmation

A different clip or different wording is not new value by itself.

If it only repeats the same symptom, judgment, praise, plan, or technical explanation, cut it.

### 3. Judgment Before Knowledge Dump

Prioritize the professional's actual judgment, correction, refusal, restraint, choice, or tradeoff.

Keep only the technical explanation needed to make that decision understandable.

Do not turn useful doctor footage into a lecture simply because more explanation exists.

### 4. Stop When The Job Lands

Stop when the viewing task and primary decision job have landed.

Do not append generic summaries, extra praise, more plan details, or a knowledge recap for structural completeness.

## Source Selection Rule: Minimum Effective Semantic Unit

For every selected source line, keep the **shortest audible fragment that independently carries useful meaning**.

It may carry:

- result/proof
- judgment
- reason
- conflict
- tradeoff
- evidence
- decision
- feedback

Allowed:

- delete filler
- delete repeated starts
- delete duplicated meaning
- split long source speech into shorter selectable fragments
- reorder selected fragments for viewing logic

Not allowed:

- add a subject that was not spoken
- add parenthetical explanation into source text
- replace source wording with assistant-written wording
- add an unspoken causal bridge
- disguise packaging as source audio

Core rule:

```text
原素材对应文字：允许删，不允许补。
```

## Same-Case Multi-Script Rule

For every additional script from the same case, internally define:

```text
Primary Decision Job:
Viewing Task:
Excluded Hook / Proof Chain:
Difference From Previous Script:
```

A real new angle must change at least the viewing task and main proof path. Changing only title, cover, wording, or footage replacement is not enough.

If an earlier published script has data, reuse a hook/person/worry/quote only when the data actually supports it. Treat a proven hook as an asset, not a full template.

## Stage 5: Automatic QA And Fix

Before delivery, fix the draft until these checks pass:

1. **Source**: every source line and time frame exists.
2. **Decision**: the piece performs one clear decision job.
3. **Progression**: every major beat changes the viewer's decision state.
4. **Evidence**: result, judgment, technique, credential, or feedback actually supports the claim being made.
5. **Economy**: repeated meaning, filler, empty praise, unnecessary plan lists, and irrelevant knowledge are removed.
6. **Boundary**: source wording contains no assistant-added words; non-source packaging is clearly separate.
7. **Compliance**: risky or unsupported claims are removed/narrowed according to the exact channel/account rules.
8. **Collision**: same-case scripts are meaningfully different.

Do not print a QA report unless asked.

## Default Final Output

After user confirmation, keep the editor-facing delivery lean:

```markdown
## 标题

[标题]

## 视频文字时间帧

### 1. [段落名]
| 素材 | 原时间帧 | 原素材对应文字 |
|---|---|---|
| [素材名] | [原时间帧] | [最终使用的原声片段] |

## 视频结构及文案

[按最终播放顺序，一句一行]

## 风险处理

[仅在存在真实素材缺口、事实边界或合规风险时出现]
```

Do not output shot selection, camera directions, B-roll suggestions, visual annotations, transitions, or other `画面说明`.

## Time Frame Rules

- Use only three source-table columns: `素材`, `原时间帧`, `原素材对应文字`.
- Keep original source/material name and original time-frame format.
- Prefer fine-grained ranges that let an editor find the exact phrase quickly.
- `原素材对应文字` may delete filler/repetition but may not add words that were not spoken.
- Do not add synthesized subjects, explanations, logic bridges, compliance rewrites, or CTA into the source table.
- Do not merge distant source moments into one broad range.
- Do not invent time frames.
- Final playback order may differ from recording chronology.

## Medical-Aesthetics Compliance

For medical-aesthetics public content, run `references/medical-aesthetics-compliance.md` before delivery.

Key rule:

```text
社区可发 != 聚光/广告可投
```

The current project/account blacklist and platform rules override generic wording examples.

If a risky word appears in raw source, do not fake a compliant source quote. Choose another real fragment, omit it, or use clearly labeled non-source packaging when allowed.

## Activation Prompt

Only add a comment/activation prompt when the user asks for it or the content goal explicitly requires it.

Prefer a concrete next self-judgment question over a generic or hard CTA.
