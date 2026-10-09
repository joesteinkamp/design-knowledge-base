# Change Log

## 2026-10-09 (Claude)

**Added Local User Tester to the homepage Tools index as a shipped entry.**

- **What changed:** `index.html` gains entry 09, "Local User Tester", linking to `https://github.com/joesteinkamp/local-session-replay` with the type label "Library". The planned entries move to 10 and 11, and the header count changes from "8 shipped · 2 planned" to "9 shipped · 2 planned".
- **Original ask:** Add the new tool, `joesteinkamp/local-session-replay`, to the site as SHIPPED. The owner then specified the name "Local User Tester" and the description "an extension of your product that adds session recording for unmoderated user tests."
- **Why this approach:** It reuses the existing row markup, so the new entry matches its neighbours. The repo's own README calls the package "TestKit", but the owner asked for "Local User Tester", so the site uses that name.
- **Considered and rejected:**
  - Title "TestKit" from the README, or the repo name `local-session-replay`. Both were replaced by the owner's chosen name.
  - Type label "Repo", as used by Web to Figma (Playwright). "Library" was kept because the package installs as an npm/git dependency.
- **Note:** This is the first entry in this file, so `CHANGELOG.md` is new.
