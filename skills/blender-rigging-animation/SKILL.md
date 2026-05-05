---
name: blender-rigging-animation
description: Workflow for setting up, rigging, and animating characters in Blender with a clear execution pipeline for generating animation outputs.
---

# Blender Rigging & Animation

## Overview

This skill enables Claude to guide users through setting up Blender, creating rigs, and producing animation-ready assets.

It focuses on transforming a static model into a fully rigged and animated output.

---

## Setup

Before using this skill:

1. Install Blender (latest version)
2. Open a new project
3. Import or create a 3D model
4. Switch to "Animation" workspace

---

## When to Use This Skill

- Creating character animations
- Preparing assets for games or videos
- Building reusable rig systems

---

## When NOT to Use

- Static modeling tasks
- Simple transformations without animation
- Non-3D workflows

---

## Example Use Case

> “Animate a simple character waving”

Claude should:
- Load the model
- Create a basic armature
- Add IK constraints for arms
- Insert keyframes for waving motion
- Render animation output

---

## Workflow

### 1. Model Preparation
- Ensure mesh is clean and properly scaled
- Apply transforms

### 2. Rig Creation
- Add armature
- Define bone hierarchy
- Bind mesh using automatic weights

### 3. Constraint Setup
- Apply IK for limbs
- Add rotation limits
- Configure FK controls

### 4. Animation
- Insert keyframes for movement
- Adjust timing in timeline
- Refine using graph editor

### 5. Render Output
- Set camera and lighting
- Configure render settings
- Export animation

---

## Output Expectations

- Fully rigged model
- Smooth animation
- Exportable video or asset

---

## Best Practices

- Keep rigs simple initially
- Test animations early
- Use consistent naming

---

## Notes

- Rigging complexity increases quickly
- IK systems improve natural movement
