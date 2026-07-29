# Public Portfolio Disclosure Policy

## Purpose

This policy protects client confidentiality, proprietary implementation work, operational security and personal information while preserving a strong public portfolio for recruiter, partner and stakeholder review.

## Default Rule

**Working repositories are private by default.**

A full application or client repository must not be made public merely to demonstrate capability. Public proof should be published through a separate, sanitised case study containing only information deliberately approved for external viewing.

## Approved Public Material

A public portfolio repository may contain:

- a concise project overview and the business problem addressed;
- Whitemore Ngwira's role and responsibilities;
- high-level architecture and capability descriptions;
- approved public URLs;
- generated portfolio visuals or approved public screenshots;
- non-sensitive outcomes, verification summaries and lessons;
- contact details for a controlled private walkthrough.

## Material That Must Remain Private

Do not publish:

- production or client source code unless there is explicit written approval;
- `.env` files or environment-variable inventories that reveal the integration surface;
- API keys, credentials, tokens, passwords, private endpoints or project identifiers;
- database schemas, migrations, seed data or row-level security implementation;
- authentication, authorisation, administrative or security-control logic;
- infrastructure configuration, deployment details, logs or internal monitoring data;
- client, student, investor, employee, stakeholder or user records;
- internal strategy, handover notes, commercial records, proposals or operational documents;
- agent instructions such as `AGENTS.md`, `CLAUDE.md` or internal automation prompts;
- unpublished product roadmaps, funding logic, pricing assumptions or proprietary workflows;
- source-level videos or screenshots that expose private dashboards or implementation details.

## Public Repository Standard

Every public portfolio repository should be deliberately small and easy to review. Its normal contents are:

1. `README.md`;
2. approved images or short public walkthrough media;
3. `COPYRIGHT.md` and `SECURITY.md` where useful;
4. no production application tree, database migrations, environment templates or internal working notes.

## Pre-Publication Check

Before making any repository public, confirm all of the following:

- it is a dedicated case-study repository rather than the working implementation repository;
- its full current tree and Git history have been reviewed;
- no secrets, private data or internal filenames are present;
- screenshots and videos contain no confidential information;
- links point to live public artefacts or sanitised case studies, not implementation repositories;
- the repository description does not advertise public source access;
- the GitHub profile and pinned repositories follow the same confidentiality boundary.

## Exposure Response

When an implementation repository is found to be public:

1. change it to **Private** immediately;
2. remove every public profile, website and case-study link to that repository;
3. review GitHub forks, releases, Actions artefacts and commit history;
4. rotate any credential or token that may have been exposed;
5. publish a separate sanitised case study instead of reopening the implementation repository;
6. verify the public GitHub profile in a signed-out browser session.

Changing a repository to private does not retract copies that another person may already have downloaded or forked. This is why the public/private decision must happen before implementation material is published.

## Private Technical Review

Where appropriate, source-level evidence can be shown through a controlled screen-share, time-limited review, private repository access or an agreed confidentiality arrangement. Public GitHub is not the default location for that evidence.
