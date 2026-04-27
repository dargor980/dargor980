# GitHub Profile Repo Requirements

## Purpose

Create a GitHub profile repository that introduces German Contreras clearly, shows current technical focus, and gives visitors a fast path to relevant projects, contact links, and work signals.

## Target Audience

- Recruiters or collaborators scanning the profile in under one minute.
- Engineers evaluating technical interests and project quality.
- Visitors coming from GitHub search, project links, or social profiles.

## Scope

The first version is a static GitHub profile `README.md`. It should work without a build step, external hosting, or JavaScript.

## Functional Requirements

1. The repository name must match the GitHub username so GitHub renders the profile README.
2. The root `README.md` must open with a concise identity statement.
3. The README must include:
   - Current role or focus area.
   - Core technologies.
   - Featured projects or repos.
   - Contact or social links.
   - Optional GitHub stats section.
4. The content must be easy to scan on desktop and mobile GitHub views.
5. Links must point to real public destinations before publishing.
6. Badges and dynamic widgets must degrade gracefully if their source is unavailable.

## Content Requirements

- Use first person or compact profile-style copy consistently.
- Prefer concrete work signals over broad claims.
- Keep the top section short enough that featured work is visible without much scrolling.
- Avoid long autobiographical paragraphs.
- Avoid unverified claims, stale status, or fake metrics.

## Non-Goals

- No personal website implementation in v1.
- No custom GitHub Action unless dynamic content is explicitly needed.
- No generated SVG banner unless the visual direction is defined.

## Acceptance Criteria

- Opening the repository on GitHub shows the profile README.
- The README has no broken internal links.
- Every external link has a clear label.
- The profile can be understood from the first screen without reading the whole file.
