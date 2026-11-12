# 2026-11-02: Building the personal-wiki repository

> **2026-11-12 更新**：本记录写于建仓当天。此后工作契约移到独立仓 `agent-contract`，仓库可被公开访问，会话归档改为触发词驱动。以下内容作为历史保留，不代表现状。

- **Date**: 2026-11-02
- **Background**: User wanted a private GitHub repository to store personal context for AI agents to read.
- **Topic**: Repository setup and initial profile.

## Content

1. Created a private GitHub repository `SummerofStarSky/personal-wiki`.
2. Built the skeleton: README, profile, now, preferences, projects, goals, notes/.
3. Filled in initial content based on user input:
   - Identity: HKUST freshman, Science Group A, in Hong Kong.
   - Courses: MATH1023, MATH2001, PHYS1112, COMP1023.
   - Interests: philosophy, Chinese traditional culture (medicine, I Ching), quantum tech, embodied AI, cybersecurity; archery, basketball, badminton, football.
   - Learning style: wants mentor/teacher mode; materials-based guidance; sometimes friend/debate mode.
   - Current projects: APMCM, multi-agent system idea, IRE track decision, ASC supercomputing exploration.
   - Goals: GPA 4.0+ this semester; math/CS breadth over the year; long-term direction undecided (~55% grad school).
4. Designed the session logging mechanism:
   - Every conversation produces a session log in `notes/sessions/YYYY-MM/`.
   - Key conclusions appended to `notes/topics/` files.
   - Bi-weekly rollup to prevent file count growth.
   - Repository is Obsidian-compatible.

## Key decisions

- Repository name: `personal-wiki`.
- Private, for personal AI context only.
- Structure: flat root files + notes/topics + notes/sessions.
