# 👁‍🗨 AGENTS.md — AI Agent Guidelines & Operating Principles

Welcome, Agent! This repository is part of the **360 Magicians** ecosystem.
All AI agents (Bolt, Jules, Copilot, etc.) operating in this repository must adhere to the following principles and practices.

---

## 🖐️ Core Philosophy & Deaf-First Standards
- **Deaf-First by Design:** Always consider accessibility, visual clarity, and Deaf-First design patterns when proposing or implementing UI/UX or architectural changes.
- **Speed & Correctness:** Prioritize clean, efficient, and measurable performance improvements without sacrificing correctness, readability, or accessibility.
- **Minimal Footprint:** Avoid adding unnecessary third-party dependencies or altering lock files unless explicitly requested or required.

---

## 🛠️ Operating Rules & Workflow

### 1. Exploration & Verification
- Always explore the project structure before modifying files.
- Verify every file modification using read tools or terminal commands (`git status`, `read_file`, etc.) before marking tasks complete.

### 2. Testing & Quality Assurance
- Run tests (`pnpm test`, `npm test`, `pytest`, or equivalent commands) whenever executable code is modified.
- Perform linter checks (`pnpm lint`, `npm run lint`) to maintain code consistency.
- Ensure no regressions or breaking changes are introduced.

### 3. Git & Commits
- Keep commits clear, focused, and descriptive.
- Follow conventional commit style (`docs: ...`, `feat: ...`, `fix: ...`, `perf: ...`).
- Never force push or modify historical commits unless authorized.

---

## ⚡ Agent Roles & Responsibilities
- **Bolt (Performance Agent):** Profile first, measure bottleneck, optimize safely (< 50 lines per change when possible), verify performance win, and journal critical learnings in `.jules/bolt.md`.
- **Jules (Software Engineer):** Follow step-by-step plans, verify modifications, perform thorough pre-commit checks, and submit well-tested pull requests.
