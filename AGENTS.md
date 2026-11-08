# AGENTS.md - Developer & AI Agent Guide for githubActions 🤖

## 🎯 Repository Overview
**githubActions**: Core repository for githubActions.

---

## 🏗️ Repository Architecture
Key directories and entrypoints: `.github/, LICENSE, README.md, mvnw, mvnw.cmd, pom.xml, src/`.

### Tech Stack & Runtime
- **Language & Build:** Java / Maven (`pom.xml`, `./mvnw`)

## ⚙️ Executable Verification Commands

### 1. Compile & Execute Tests
```bash
./mvnw clean test
```

---

## 🛡️ Coding & Safety Guidelines for Autonomous Agents

1. **Documentation Integrity:** Preserve all existing docstrings, header comments, and licensing banners. Never delete context unless specifically instructed.
2. **Zero Hardcoded Secrets:** Never embed API keys, OAuth tokens, personal access tokens, or sensitive credentials in committed files. Read credentials exclusively from environment variables or secure credential paths.
3. **Git Hygiene:**
   - Do not force-push (`git push --force`) or execute destructive resets.
   - Never modify root git configurations or harness infrastructure outside task scope.
   - Keep git diffs atomic, focused, and verified before committing.
4. **Agent Workflow Protocol:**
   - **Plan:** Inspect codebase architecture and dependencies before editing.
   - **Act:** Make minimal, clean, high-precision changes.
   - **Verify:** Run the appropriate verification commands listed above.
   - **Reflect:** Confirm zero regressions and review `git diff`.

---
*Maintained by Ayyappa Pravin • Built for Antigravity, Claude, Cursor & Autonomous AI Agents.*
