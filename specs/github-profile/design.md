# GitHub Profile Repo Design

## Repository Shape

```text
.
├── README.md
├── specs/
│   └── github-profile/
│       ├── requirements.md
│       ├── design.md
│       └── tasks.md
└── AGENTS.md
```

## README Structure

The profile README should use plain Markdown and GitHub-compatible HTML only when Markdown cannot express the layout.

Recommended order:

1. Header: name, short identity line, location or remote availability if relevant.
2. Focus: current technical interests and what kind of problems you work on.
3. Stack: concise list of languages, frameworks, tools, and platforms.
4. Featured work: three to five selected repositories with one-line descriptions.
5. Activity or stats: optional GitHub stats, streaks, or language cards.
6. Contact: GitHub, LinkedIn, email, portfolio, or other verified channels.

## Visual Direction

- Keep the design clean and readable inside GitHub's native README renderer.
- Use badges sparingly for stack and contact links.
- Avoid oversized banners unless there is a real brand direction or image asset.
- Keep emoji optional and minimal; icons or badges should not replace clear labels.
- Prefer a balanced, professional tone over a novelty-heavy profile.

## Content Model

Use this data before writing the final README:

- `name`: display name.
- `github_username`: repository and profile handle.
- `headline`: one-line professional identity.
- `location`: optional.
- `current_focus`: two to four bullets.
- `tech_stack`: grouped by practical use.
- `featured_projects`: repo URL, name, description, highlight.
- `contact_links`: label and URL.

## Optional Dynamic Sections

Dynamic widgets are allowed only if they add signal:

- GitHub stats card.
- Top languages card.
- Contribution streak.
- WakaTime or similar coding activity, if already configured.

Use stable third-party providers and keep dynamic cards below the main profile content.

## Risks

- Too many badges can make the profile harder to scan.
- Dynamic widgets can fail or slow rendering.
- Generic copy weakens the profile; project descriptions should mention actual outcomes.
