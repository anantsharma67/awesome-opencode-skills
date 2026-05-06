---
name: repomix-workflows
description: Workflow for using Repomix to compress, structure, summarize, and prepare repositories for AI agents by generating optimized context bundles for reasoning, debugging, code review, and implementation workflows.
---

# Repomix Workflows

## Overview

This skill enables Claude to use Repomix-style workflows to transform large repositories into structured, AI-friendly context bundles optimized for reasoning and execution.

The workflow focuses on:
- repository compression
- context extraction
- architecture summarization
- codebase understanding
- AI-ready repository packaging
- token optimization
- scalable repository reasoning
- long-context engineering

The goal is to allow Claude and other AI systems to understand large repositories without overwhelming context windows or losing important architectural information.

Instead of dumping entire repositories into prompts, Repomix workflows create:
- compressed summaries
- structured context
- dependency-aware representations
- AI-optimized repository views

---

# Setup

Before starting:

1. Install Node.js:
   https://nodejs.org

2. Install Repomix:

```bash
npm install -g repomix
```

3. Navigate to the repository:

```bash
cd project-name
```

4. Generate repository bundle:

```bash
repomix
```

Optional:
- configure ignore rules
- customize compression settings
- exclude generated files

Recommended tools:
- Repomix
- GitHub
- Claude
- VS Code
- Markdown viewers

Optional:
- MCP systems
- Vector memory databases
- Multi-agent orchestration
- Repository indexing systems

---

# Inputs Required

- Repository path
- Project source code
- Context goals
- AI workflow requirements

Optional:
- Ignore patterns
- Documentation files
- Architecture notes
- Existing repository summaries

---

# When to Use This Skill

Use this skill when:
- analyzing large repositories
- preparing AI coding workflows
- building context bundles
- reviewing unfamiliar codebases
- debugging large systems
- onboarding AI agents into projects
- compressing repository context
- scaling multi-agent engineering workflows

---

# When NOT to Use

Do NOT use this skill for:
- tiny repositories
- single-file scripts
- workflows without AI reasoning needs
- repositories with no architectural complexity

---

# Example Use Case

> Prepare a large Next.js SaaS repository for multi-agent Claude workflows.

Claude should:

1. Generate repository context bundle
2. Compress unnecessary files
3. Preserve architecture structure
4. Summarize important systems
5. Extract dependency relationships
6. Prepare AI-readable repository context
7. Optimize repository understanding workflows

Final result should:
- improve repository comprehension
- reduce context overload
- preserve architectural clarity
- improve AI reasoning quality
- scale large engineering workflows effectively

---

# Core Repomix Principles

## 1. Repositories Must Be Compressed Intelligently

Large repositories contain:
- noise
- generated files
- duplicated patterns
- irrelevant artifacts

Claude should prioritize:
- architecture
- workflows
- dependencies
- business logic
- important implementation patterns

Avoid:
- blindly including everything
- oversized raw context dumps
- unnecessary token consumption

Good compression improves:
- reasoning quality
- scalability
- execution speed

---

## 2. Preserve Architectural Structure

Compression should never destroy:
- repository organization
- dependency flow
- system boundaries
- implementation relationships

Claude should preserve:
- folder structure
- component relationships
- API boundaries
- shared utilities

Architecture understanding improves:
- debugging
- implementation quality
- onboarding speed

---

## 3. Optimize Context for AI Reasoning

AI systems require:
- structured summaries
- reduced noise
- focused architecture visibility
- dependency clarity

Repomix workflows should optimize for:
- reasoning quality
- implementation understanding
- navigation efficiency
- long-context scalability

Good context engineering improves:
- code generation
- debugging
- planning
- review quality

---

## 4. Separate Important & Unimportant Context

Not all repository content matters equally.

High-value context:
- architecture
- business logic
- shared systems
- workflows
- interfaces

Low-value context:
- generated assets
- build artifacts
- dependency caches
- repetitive boilerplate

Claude should aggressively prioritize signal over noise.

---

## 5. AI Context Should Remain Navigable

Compressed repository bundles should remain:
- readable
- structured
- organized
- searchable

Good organization improves:
- multi-agent coordination
- debugging
- workflow scalability
- reasoning depth

---

# Workflow

## 1. Analyze Repository Structure

Start by identifying:
- application type
- architecture patterns
- important systems
- shared infrastructure
- dependency boundaries

Review:
- folders
- services
- APIs
- state management
- component structure

Understand:
- how the repository is organized
- which systems matter most

---

## 2. Remove Low-Value Context

Exclude:
- build outputs
- generated files
- dependency folders
- binary artifacts
- unnecessary logs

Typical exclusions:
- `node_modules`
- `.next`
- `dist`
- `build`

This improves:
- token efficiency
- context clarity
- reasoning quality

---

## 3. Generate Repository Bundle

Run Repomix:

```bash
repomix
```

Generate:
- repository summaries
- compressed code context
- dependency-aware structure
- AI-readable outputs

Ensure:
- important files remain preserved
- architecture remains understandable
- workflows stay visible

---

## 4. Create Architectural Summaries

Claude should summarize:
- application structure
- system responsibilities
- shared services
- state management
- workflow relationships

Examples:
- frontend architecture
- API layers
- auth systems
- deployment structure

Good summaries improve:
- onboarding
- debugging
- AI reasoning

---

## 5. Prepare AI-Optimized Context

Organize:
- core architecture
- implementation patterns
- dependency relationships
- business logic summaries

Structure context for:
- navigation
- retrieval
- multi-agent coordination
- debugging workflows

---

## 6. Validate Context Quality

Check:
- repository readability
- architectural clarity
- compression quality
- missing dependencies
- navigation simplicity

Ensure:
- important systems remain understandable
- AI workflows stay efficient
- context remains scalable

---

## 7. Maintain Repository Context

As repositories evolve:
- regenerate summaries
- update architectural descriptions
- refine compression rules
- optimize retrieval systems

Repomix workflows should evolve continuously with the codebase.

---

# Output Expectations

The final output should include:
- compressed repository bundles
- architectural summaries
- AI-readable repository structure
- dependency-aware context systems
- scalable repository reasoning pipelines
- maintainable context engineering workflows

The workflow itself should remain:
- lightweight
- scalable
- navigable
- architecture-focused
- AI-optimized

---

# Execution Strategy (for AI agents)

The agent should:

1. Compress repositories intelligently
2. Preserve architectural understanding
3. Remove low-value context aggressively
4. Optimize repository context for reasoning
5. Maintain navigable repository structure
6. Continuously refine context quality

The workflow should optimize for:
- repository understanding
- reasoning quality
- token efficiency
- workflow scalability
- implementation clarity

---

# Best Practices

- Exclude generated files aggressively
- Preserve architectural relationships
- Keep repository summaries structured
- Prioritize signal over noise
- Maintain readable compressed outputs
- Optimize for navigation and reasoning
- Update context bundles continuously

---

# Notes

- Repository compression dramatically improves AI workflow scalability
- Good architecture summaries accelerate onboarding significantly
- Token efficiency strongly affects reasoning quality
- AI systems perform better with structured repository context
- The best repository bundles preserve meaning while aggressively reducing noise
