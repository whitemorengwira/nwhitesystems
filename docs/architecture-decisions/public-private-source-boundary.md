# Architecture Decision: Public and Private Source Boundary

## Decision

Use public repositories to show architecture, delivery, verification, and judgment while keeping production source, credentials, private dashboards, records, and confidential operations out of public GitHub unless a repository has been deliberately curated for public review.

## Why This Matters

The portfolio includes work across education, mining, insurance, investment, stakeholder communication, and controlled-access workflows. These domains need credible proof without exposing sensitive implementation detail or private stakeholder data.

## Public Pattern

- Publish sanitized case studies with role, architecture, technical proof, review context, and confidentiality boundary.
- Keep generated visuals clearly labeled as portfolio visuals.
- Use `safa-promax` as the primary public source-level proof surface.
- Link private walkthrough requests through professional contact where permissions allow.

## Tradeoff

This approach shows less raw private code, but it creates a cleaner and safer review path for recruiters and technical reviewers.

## Verification

Public copy scans check for internal coaching language, private-source wording, and embarrassing placeholders before publication.

