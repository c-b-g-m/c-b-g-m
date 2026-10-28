# Profile refresh change record

Date: 2026-10-28
Published commit: `92e8770` (`feat: refresh profile around GTM automation work`)

## What happened

The profile refresh was committed and pushed directly to `main` instead of being delivered through a topic branch and pull request. That bypassed the required review and merge-permission step.

The published commit remains on `main`. The repository owner explicitly chose not to rewrite or revert the live history solely to recreate the change through a pull request. This record documents the exception; it does not make direct-to-main delivery an accepted workflow.

## Repository edits in `92e8770`

- Rewrote `README.md` around Christen George-McFerrin's current positioning as an AI automation builder for GTM teams.
- Replaced the animated, Claude-specific introduction and activity widgets with a static value proposition, selected open work, anonymized production-system patterns, a capability-based stack, and direct calls to action.
- Rebuilt `banner.svg` with the updated headline, operating principles, demand AI studio attribution, and the existing light violet/teal visual identity.
- Preserved `divider.svg`, `NOTICE.md`, and the unrelated untracked `CLAUDE.md` without modification.

## Public GitHub metadata edited during the same task

- Set the profile name, bio, company, location, and website.
- Updated descriptions, homepage URLs where applicable, and topics for:
  - `automation-process-builder`
  - `gha-automation-patterns`
  - `pov-pipeline-template`
  - `narrative-brief-engine-template`
  - `html-social-graphic-card-render`
  - `dead-habits`
- Profile repository pins were discussed and attempted, but GitHub's API verification showed that no pins had been saved at wrap-up.

## Verification performed

- Validated `banner.svg` and `divider.svg` as XML.
- Rendered and visually inspected the new banner.
- Confirmed all profile, repository, deployment, studio, and LinkedIn links returned HTTP 200 responses.
- Verified the published `main` commit and public profile/repository metadata through GitHub's API.

## Corrective rule

All future changes to this repository must use a topic branch and pull request. A pull request must not be merged without the repository owner's explicit permission.
