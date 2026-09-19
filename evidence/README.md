# Synthetic before/after evidence

Dummy-data captures only. No real workspace, session, profile or path appears in
any frame — the pages are driven against an isolated state directory and a stub
agent, and the transcript/settings content is fixed placeholder text.

- `6712/` — PR #6712, Control Center -> Preferences, desktop (1280x900) and narrow (390x800).
  `before` = `master` `dd69bfd9`; `after` = the PR head.
- `7047/` — PR #7047, markdown table rendering with a deliberately wide dummy table,
  desktop (1280x800) and narrow (390x800). Same before/after pairing.
