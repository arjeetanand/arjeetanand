# Profile link handoff

The Pitchroom AI link in the profile README now targets the public Briefly repository. The former target returned a GitHub 404 when checked on 15 November 2026.

- Branch: `codex/fix-pitchroom-profile-link`; base commit: `a4d7299f4f2791a81c056787a528326e864102bb`.
- Task commit: `docs: fix Pitchroom profile link` (resolve its current ID with `git log -1`).
- Verification: the GitHub repository list showed Briefly as public; the old URL returned 404. The local README contains exactly one new target and no old target.
- Run method: the profile is a GitHub-rendered README; no local server is required.
- Next: with authorization, push the task branch and open a pull request targeting `main`. The public profile remains unchanged until merged.
