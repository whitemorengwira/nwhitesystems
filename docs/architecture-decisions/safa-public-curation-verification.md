# Architecture Decision: SAFA Public Curation and Verification

## Decision

Keep SAFA ProMax public as the strongest source-level proof repository, but curate the public default branch so it reads as a deliberate portfolio artifact rather than a raw delivery workspace.

## Why This Matters

SAFA ProMax gives reviewers evidence of full-stack delivery, protected presentation surfaces, CMS/workflow thinking, public deployment, TypeScript structure, and local verification. It needs to remain inspectable without exposing unnecessary delivery noise.

## Public Pattern

- Keep essential source, configuration, public assets, README, security, support, copyright, and maintenance notes visible.
- Keep noisy process material out of the public default branch.
- Use CodeQL and GitHub Free hygiene as public verification signals.
- Preserve no-open-source-license posture with explicit copyright and usage boundaries.

## Tradeoff

The public repository is more curated than a raw project folder, but that makes it more useful for recruiter and technical review.

## Verification

The public source was verified with lint, typecheck, production build, and production-dependency audit checks before this conversion layer.

