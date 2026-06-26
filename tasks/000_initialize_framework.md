# Task 000 — Initialize Atmospheric Narrative Framework

## Goal

Create a clean, professional Unity project that serves as the foundation for the Atmospheric Narrative Framework (ANF).

This task intentionally contains **no game-specific logic**.

No BLACKOUT.

No story.

No dialogue.

Only the reusable project structure.

---

# Context

Atmospheric Narrative Framework (ANF) is a reusable framework for building atmospheric narrative exploration games.

The framework should remain completely independent of any specific game.

BLACKOUT will later be implemented as a separate project using this framework.

---

# Requirements

## Create a Unity project

Target:

- Unity 6 (or latest stable LTS)
- C#
- URP (preferred)
- Cross-platform (Windows, macOS, Linux)

The project must open without errors.

---

## Create folder structure

```text
Assets/

    Framework/

        Characters/
        Dialogue/
        Events/
        NPC/
        Player/
        Atmosphere/
        Audio/
        Save/
        UI/
        Utilities/

    Samples/
        MountainHotel/

    Art/
    Materials/
    Prefabs/
    Scenes/

Documentation/

tasks/
```

---

## Create the first sample scene

Create:

```text
Assets/Scenes/Bootstrap.unity
```

Requirements:

- Empty playable scene
- Ground plane
- Camera
- Directional light
- Basic player spawn point

No gameplay.

---

## Documentation

Create:

```text
README.md
```

Describe:

- project goals
- architecture philosophy
- folder structure
- development workflow

---

## Git

Create:

- Unity `.gitignore`
- MIT License (or Apache 2.0 if preferred)

The repository should be ready for public collaboration.

---

# Deliverables

- Unity project
- Folder structure
- Bootstrap scene
- README
- .gitignore
- License

---

# Acceptance Criteria

The project:

- opens successfully in Unity
- compiles without errors
- contains the defined folder structure
- has an initial playable scene
- is ready for future framework tasks

No game mechanics should exist yet.

---

# Non-Goals

Do **not** implement:

- movement
- NPCs
- dialogue
- save/load
- atmosphere
- interaction
- AI
- story
- BLACKOUT-specific content

This task is only about creating a solid, reusable foundation.
