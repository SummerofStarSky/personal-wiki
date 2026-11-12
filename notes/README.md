# Notes

Topic-based notes and conversation logs.

## Structure

```
notes/
├── README.md          # This file — index
├── topics/            # Long-term topic files (one per topic, appended over time)
└── sessions/          # Short-term conversation logs, organized by month
    └── YYYY-MM/
        └── YYYY-MM-DD-topic.md
```

## How this works

1. 我说「**存档**」时，AI 在 `sessions/YYYY-MM/` 写一份会话记录。
2. 关键结论追加到 `topics/` 下对应文件；索引见 `topics/_index.md`。
3. 回答新问题前，AI 先读相关 topic 文件。
4. 我说「**归并**」时，把最近两周的会话记录合并进 topic 文件，原文件标 `> rolled-up: 日期`。

> 归档由触发词驱动，不在每次对话后自动执行——模型没有时钟，也不会知道会话何时结束。

## Topic index

| Topic file | Last updated | What it covers |
|---|---|---|
| _(empty — topics will be created as conversations happen)_ | | |

## Session log index

| Month | Session count |
|---|---|
| 2026-11 | 1 |
