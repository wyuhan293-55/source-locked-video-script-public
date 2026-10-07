# Edit-Ready Format

Use this reference for the final editor-facing script.

For medical-aesthetics public content, also apply `medical-aesthetics-compliance.md` before delivery.

## Default Output

Keep the default delivery lean:

```markdown
## 标题

[标题]

## 视频文字时间帧

### 1. [段落名]

| 素材 | 原时间帧 | 原素材对应文字 |
|---|---|---|
| [素材名] | [原时间帧] | [最终要用的原声片段] |

### 2. [段落名]

| 素材 | 原时间帧 | 原素材对应文字 |
|---|---|---|
| [素材名] | [原时间帧] | [最终要用的原声片段] |

## 视频结构及文案

[按最终播放顺序排列，一句一行]

## 风险处理

[仅在确有素材缺口、事实边界或合规风险时出现]
```

Do not output shot selection, camera directions, B-roll suggestions, transitions, visual annotations, or other 画面说明.

## Source Table Rule: Minimum Effective Semantic Unit

The source table is an editing map, not a transcript archive.

Each row should contain the **shortest audible source fragment that can independently carry useful meaning** such as a judgment, reason, conflict, tradeoff, evidence, decision, or result.

### Allowed

- delete filler
- delete repeated starts
- delete greetings/setup chatter
- delete duplicated meaning
- keep only the useful audible phrase inside the original source range
- split a long source sentence into multiple short selectable rows when the source supports it

### Not Allowed

- add a subject that was not spoken
- add parenthetical explanation into `原素材对应文字`
- replace source wording with assistant-written wording
- add a causal bridge that was not spoken
- write synthesized screen text as if it were source audio

Core rule:

```text
原素材对应文字：允许删，不允许补。
```

If clarification is necessary, put it outside the source table and label it as non-source text.

## Time Frame Rules

- Keep the original source/material name.
- Keep the original time-frame format.
- Use fine-grained source ranges that let an editor locate the selected phrase quickly.
- Do not merge several distant source moments into one broad time range.
- Do not invent time frames.
- Final playback order may differ from recording chronology.

## Final Script Rule

Default to the selected source lines in final playback order.

If non-source packaging is necessary to make the logic understandable, label it clearly. Do not silently rewrite source audio into smoother assistant prose.

A final script should feel spoken and cuttable because the **right source fragments were selected and ordered well**, not because the assistant rewrote them into a polished article.

## Structure Check: Decision Progress

Before keeping the next line, ask:

> Does this line change what the viewer knows, wants, trusts, fears, expects, or needs answered?

Keep it if it adds a new:

- result or proof
- judgment
- reason
- consequence
- evidence
- tradeoff
- decision
- trust signal
- risk clarification
- emotional movement

Otherwise cut it.

Different wording or a different clip is not new decision value by itself.

## Stop Rule

When the viewing task and primary decision job have landed, stop.

Do not append a generic summary, extra praise, additional plan list, knowledge recap, or template ending just to make the script look complete.

## Medical-Aesthetics Public Compliance Check

Before delivery, scan the final public-facing script against `medical-aesthetics-compliance.md`.

At minimum check:

- absolute / superlative / guarantee wording
- unsupported efficacy or recovery promises
- individual diagnosis or forced-decision language
- authority / credential overclaim
- competitor comparison or denigration
- hard conversion / off-platform diversion
- case/result/recovery proof boundaries
- current project/account hard-blacklist terms

Do **not** silently rewrite risky source audio and still present it as source. If a selected source fragment is not usable for the target channel, replace it with another real source fragment, omit it, or move to clearly labeled non-source packaging when that is allowed.

Remember:

```text
社区可发 != 聚光/广告可投
```

If paid-delivery eligibility is unknown, do not claim the script is 聚光可投.

## Source-Locked Boundary

Source-locked means:

- every source line is traceable
- source wording is not supplemented with invented words
- non-source packaging is visibly separate
- the script may reorder or delete source material for viewing logic
- compliance filtering may remove a risky source fragment, but may not falsify what the source said

Source-locked does **not** mean preserving raw口水话 or original chronology.
