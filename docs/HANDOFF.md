# Project handoff

## Current state

- Repository initialized for a Unity project.
- ChatGPT Codex Connector installed for this repository with read/write access.
- Unity-appropriate `.gitignore` added.
- Project README and task tracker added.
- No Unity project files were present at initialization.

## What the next contributor should do

1. Locate the authoritative Unity project working copy.
2. Confirm the project opens cleanly in Unity before copying or committing it.
3. Add `Assets/`, `Packages/`, and `ProjectSettings/` while preserving every Unity `.meta` file.
4. Record the exact Unity editor version from `ProjectSettings/ProjectVersion.txt`.
5. Open the project from a clean clone and confirm packages resolve.
6. Update this document with the actual game loop, scenes, controls, build target, dependencies, and known issues.

## Before every handoff

- Confirm `git status` contains no generated Unity cache or build output.
- Run the project’s available Edit Mode and Play Mode tests.
- Open all changed scenes and check the Console for errors.
- Document unfinished work and reproducible bugs in `docs/TODO.md`.
- Keep commits small enough that the next person can understand what changed.

## Unknowns to resolve

- Unity editor version
- Render pipeline
- Primary build platform
- Current playable scenes
- Input system and control scheme
- Third-party assets and licenses
- Build and test procedure
- Current owner of the authoritative local Unity project
