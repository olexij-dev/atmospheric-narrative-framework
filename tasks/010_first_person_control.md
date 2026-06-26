# Task 010 — First Person Controller

## Goal

Implement a reusable first-person controller for Atmospheric Narrative Framework.

The controller must be generic and contain no game-specific logic.

## Requirements

Create:

```text
Assets/Framework/Player/FirstPersonController.cs
```

Features:

- WASD movement
- Mouse look
- Gravity
- Optional sprint
- Cursor lock/unlock with Escape
- Uses Unity CharacterController
- Exposes movement settings in Inspector

## Scene Integration

Update:

```text
Assets/Scenes/Bootstrap.unity
```

Add:

- Player object
- CharacterController
- Camera as child of player
- FirstPersonController attached

## Acceptance Criteria

- Project compiles without errors
- Player can move with WASD
- Mouse controls camera
- Player does not fall through ground
- Escape unlocks cursor
- No BLACKOUT-specific content

## Non-Goals

Do not implement:

- interaction
- stamina
- crouch
- head bob
- footsteps
- UI
- NPCs
- story logic
