# unity-project

Unity game project for Ruler of Wisdom and SACS.

## Repository status

The repository has been initialized for Unity development. The Unity project files have not been added yet.

## Getting started

1. Install the Unity Editor version recorded in `ProjectSettings/ProjectVersion.txt` after the project is added.
2. Clone this repository.
3. Open the repository folder from Unity Hub.
4. Let Unity restore packages and generate local cache files.
5. Read [docs/HANDOFF.md](docs/HANDOFF.md) before continuing development.
6. Use [docs/TODO.md](docs/TODO.md) to track the next concrete tasks.

## Version-control rules

Commit Unity source and settings, including:

- `Assets/` and matching `.meta` files
- `Packages/manifest.json` and `Packages/packages-lock.json`
- `ProjectSettings/`

Do not commit generated folders such as `Library/`, `Temp/`, `Logs/`, `Obj/`, or local IDE files. The included `.gitignore` handles the usual Unity-generated clutter.

## Project structure

Once the Unity project is added, the expected top-level layout is:

```text
Assets/
Packages/
ProjectSettings/
docs/
.gitignore
README.md
```

## Documentation

- [Handoff notes](docs/HANDOFF.md)
- [Project TODO](docs/TODO.md)
