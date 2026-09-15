# Repository Agent Instructions
 
For changes related to file-upload resource controls, terminal chat authorization,
terminal credential forwarding, or terminal proxy error handling, follow
[`docs/SECURITY_HARDENING_WORKFLOW.md`](docs/SECURITY_HARDENING_WORKFLOW.md).
 
Before committing code, tests, configuration, or security-hardening changes, use
the repository-local [`code-review`](.agents/skills/code-review/SKILL.md) skill.
The review must complete successfully before the commit is created. If the review
is unavailable or blocked, leave the changes uncommitted and report the blocker.
 
The workflow is a required gate for this hardening effort. Do not start a later
phase until the preceding phase's exit criteria are met. Preserve unrelated
workspace changes, keep each work package independently reviewable, and do not
publish unverified security claims or proof-of-concept details.
 
