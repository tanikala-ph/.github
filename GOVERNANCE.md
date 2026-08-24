# Tanikala governance

This document defines how engineering work and access are managed across the
Tanikala organization.

## Roles and access

- Organization owners manage billing, organization policy, and emergency
  access. Owner access is kept to the minimum practical number of people.
- Maintainers coordinate releases, review cross-cutting changes, and maintain
  repository settings.
- Product teams own implementation and review for their application area.
- Triage members classify issues, reproduce reports, and keep the roadmap
  current without receiving write access to source code.

Access is granted through teams wherever possible and reviewed when a member's
responsibilities change. Repository base permissions are disabled, so every
grant is explicit.

## Decisions and delivery

Product work begins as a GitHub issue and is tracked on the organization
roadmap. Material code changes use pull requests and the repository's required
checks. Architecture or data-contract decisions that future work depends on are
recorded in repository documentation.

Maintainers decide routine implementation matters. Changes affecting privacy,
security, legal commitments, shared contracts, or multiple applications require
an organization owner to approve the direction before release.

## Releases

Milestones describe readiness stages. A release is created only from a tested,
reviewed tag and includes user-visible changes, migrations, deployment notes,
and known limitations when applicable.

## Security and conduct

Security reports follow `SECURITY.md` and must not be opened as public issues.
Community participation follows `CODE_OF_CONDUCT.md`. Organization owners may
restrict access immediately when needed to protect users or project systems.
