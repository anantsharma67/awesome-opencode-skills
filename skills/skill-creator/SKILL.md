---
name: skill-creator
description: Workflow for automatically generating structured SKILL.md files and reusable skill directories from team SOPs, workflows, or process documentation.
---

# Skill Creator

## Overview

This skill enables Claude to transform workflows, SOPs, and repeated execution patterns into reusable skill packages.

It standardizes knowledge into structured `SKILL.md` files that can be reused by agents or teams.

---

## Setup

Before using this skill:

1. Collect source material:
   - SOPs
   - Workflow documentation
   - Team processes
   - Tutorials or guides

2. Define skill structure:
   - skill name
   - use cases
   - workflow steps
   - output expectations

3. Create target directory structure

Recommended tools:
- Markdown editor
- GitHub repository
- Documentation systems
- Internal process docs

---

## Inputs Required

- Workflow or SOP documentation
- Process descriptions
- Example outputs
- Tooling information

---

## When to Use This Skill

- Converting workflows into reusable skills
- Standardizing team processes
- Creating agent instruction packages
- Building internal knowledge systems
- Scaling repeated workflows

---

## When NOT to Use

- One-off undocumented tasks
- Unstructured brainstorming sessions
- Workflows without repeatable patterns

---

## Example Use Case

> “Convert a video editing SOP into an installable Claude skill”

Claude should:

1. Extract workflow steps from SOP
2. Identify:
   - setup
   - execution flow
   - outputs
3. Generate:
   - folder structure
   - SKILL.md
   - usage instructions
4. Validate formatting consistency

---

## Workflow

### 1. Analyze Source Material
- Read workflow or SOP
- Identify repeated execution patterns
- Extract goals and outputs

---

### 2. Define Skill Scope
- Determine use cases
- Identify required tools
- Clarify execution boundaries

---

### 3. Generate Structure
Create:
- skill directory
- `SKILL.md`
- supporting assets if needed

---

### 4. Build Instructions
Include:
- setup
- workflow steps
- output expectations
- best practices

---

### 5. Validate Skill
- Ensure consistency
- Verify formatting
- Confirm usability

---

## Output Expectations

- Structured skill directory
- Production-ready `SKILL.md`
- Reusable workflow package
- Standardized documentation

---

## Execution Strategy (for AI agents)

The agent should:

1. Extract repeatable workflows
2. Convert them into structured instructions
3. Organize outputs consistently
4. Ensure skills are reusable and scalable
5. Validate clarity before finalizing

---

## Best Practices

- Keep skills modular
- Avoid overly broad scopes
- Use consistent formatting
- Include practical examples

---

## Notes

- Standardized skills improve team consistency
- Reusable workflows reduce onboarding time
- Well-structured skills scale better across agents and teams
