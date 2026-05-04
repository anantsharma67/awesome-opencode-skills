---
name: blender-rigging-animation
description: Advanced workflow for creating, controlling, and animating character rigs in Blender using constraints, IK/FK systems, drivers, and deformation techniques.
---

# Blender Rigging & Animation

## Overview

This skill provides a structured workflow for building high-quality rigging systems and animations in Blender.

It focuses on creating reusable, flexible rigs using constraints, drivers, and deformation tools, ensuring realistic motion and production-ready animation pipelines.

---

## When to Use

Use this skill when:

- Creating character rigs for animation
- Building reusable animation systems
- Animating objects with controlled motion
- Improving deformation quality in models
- Working on game assets or cinematic animations

---

## When NOT to Use

Do NOT use this skill when:

- Working with static models (no animation needed)
- Using pre-rigged assets without modification
- Performing simple transformations (move/rotate/scale only)
- Rendering without animation requirements

---

## Core Capabilities

- Custom rig creation using armatures
- IK/FK switching systems
- Constraint-based motion control
- Driver-based procedural animation
- Bendy bone deformation systems
- Animation keyframe control

---

## Workflow

### 1. Rig Setup
- Create armature structure
- Define bone hierarchy
- Assign vertex groups to mesh

### 2. Constraint System
- Apply IK constraints for limbs
- Configure FK chains for manual control
- Add limit constraints for realistic motion

### 3. Control System
- Create control bones for animation
- Use custom shapes for usability
- Implement pickers if needed

### 4. Advanced Deformation
- Use bendy bones for smooth curves
- Add drivers for dynamic behavior
- Apply corrective shape keys if required

### 5. Animation
- Insert keyframes for movement
- Use graph editor for refinement
- Smooth transitions and timing

### 6. Validation
- Test rig under multiple poses
- Fix deformation issues
- Optimize for performance

---

## Output Expectations

- Fully functional rig with control system
- Smooth deformation during animation
- Clean and reusable rig hierarchy
- Production-ready animation setup

---

## Best Practices

- Keep rigs modular and reusable
- Avoid unnecessary constraints
- Use naming conventions consistently
- Test rigs early and often

---

## Optional Integrations

- Export rigs for Unity/Unreal pipelines
- Combine with Blender Geometry Nodes for procedural animation
- Use alongside motion capture workflows

---

## Stack / Tools

- Blender (Armature System)
- Graph Editor
- Drivers & Constraints
- Shape Keys
- Animation Timeline

---

## Notes

- Rigging complexity grows exponentially with features
- Constraints and drivers are key to professional rigs
- Poor rigging leads to poor animation, regardless of model quality

## Execution Strategy

The agent should:

1. Identify if the task involves animation or rigging
2. Break down the workflow into rig setup, constraints, and animation
3. Apply structured rigging techniques (IK/FK, drivers, constraints)
4. Validate output for deformation and usability
5. Optimize for reuse and performance
