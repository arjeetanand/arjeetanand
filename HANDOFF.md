# Profile link handoff

The Pitchroom AI link in the profile README now targets the public Briefly repository. The former target returned a GitHub 404 when checked on 15 November 2026.

- Branch: `codex/fix-pitchroom-profile-link`; base commit: `a4d7299f4f2791a81c056787a528326e864102bb`.
- Link-fix commit: `a286a57`; use `git log --oneline` for the complete task-branch history.
- Verification: the GitHub repository list showed Briefly as public; the old URL returned 404. The local README contains exactly one new target and no old target.
- Run method: the profile is a GitHub-rendered README; no local server is required.
- The authorized task branch targets a pull request to `main`. Check the pull request for current remote status; merging requires explicit approval after the required checks. The public profile remains unchanged until merged.
