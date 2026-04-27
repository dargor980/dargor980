# Repository Guidelines

## Project Structure & Module Organization

This repository is intended to become a GitHub profile repo. Keep the profile content in the root `README.md` so GitHub can render it on the profile page. Project planning lives in `specs/github-profile/`, split into requirements, design, and implementation tasks.

## Build, Test, and Development Commands

There is no build system yet. Work with plain Markdown files and preview them with GitHub's README renderer or a local Markdown preview. Do not add a package manager, framework, or generated asset pipeline unless the profile README needs it.

## Content Guidelines

Use concise, specific profile copy. Prefer concrete projects, technologies, and contact links over broad claims. Keep the first screen focused on identity, current technical focus, and featured work. Use badges and dynamic GitHub widgets sparingly, and place any optional stats below the main profile content.

## Validation Guidelines

Before publishing, confirm that the repository name matches the GitHub username, because that is what makes the profile README render on the GitHub profile page. Check every external link in `README.md` manually after drafting it. If dynamic stats cards are added, keep the core profile readable even when those images fail to load.

## Commit & Pull Request Guidelines

This directory is not a Git repository yet, so no commit history conventions exist. Once initialized, use short imperative commit messages that describe visible profile changes, such as `Add profile README draft` or `Update featured projects`.
