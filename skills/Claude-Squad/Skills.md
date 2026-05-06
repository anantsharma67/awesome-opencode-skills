---
name: claude-squad-multi-agent
description: Workflow for coordinating multiple Claude agents to collaboratively execute complex tasks through role separation, task orchestration, parallel execution, and structured review systems.
---

# Claude Squad Multi-Agent

## Overview

This skill enables Claude to coordinate multiple specialized agents working together on large or complex workflows.

The workflow focuses on:
- task decomposition
- agent specialization
- parallel execution
- review systems
- coordination workflows
- context management
- multi-agent orchestration

The goal is to improve execution quality and scalability by dividing complex work into specialized responsibilities instead of relying on a single general-purpose workflow.

Each agent should focus on a clearly defined role while maintaining coordination with the broader system.

---

# Setup

Before starting:

1. Define the project goal.

2. Break the workflow into:
- research
- planning
- implementation
- review
- optimization
- documentation

3. Assign specialized roles to agents.

Example roles:
- Planner
- Researcher
- Engineer
- Reviewer
- Optimizer
- Documentation Agent

4. Create shared context files.

Recommended structure:

```plaintext
agents/
tasks/
memory/
reviews/
```

Recommended tools:
- Claude
- GitHub
- Markdown files
- Notion
- Task boards
- Shared documentation systems

Optional:
- Vector memory systems
- Task orchestration tools
- Shared repositories

---

# Inputs Required

- Project objective
- Workflow requirements
- Task complexity
- Available agents or contexts

Optional:
- Existing documentation
- Architecture diagrams
- Task dependencies
- Shared memory systems

---

# When to Use This Skill

Use this skill when:
- managing large projects
- coordinating parallel workflows
- building complex applications
- reviewing large codebases
- conducting multi-stage research
- scaling AI-assisted workflows
- separating planning and execution responsibilities

---

# When NOT to Use

Do NOT use this skill for:
- tiny one-step tasks
- extremely simple workflows
- isolated quick questions
- tasks with no meaningful decomposition

---

# Example Use Case

> Build a full-stack SaaS application using multiple specialized Claude agents.

Claude should:

1. Create a planning agent
2. Assign frontend architecture to one agent
3. Assign backend systems to another
4. Use a reviewer agent for validation
5. Maintain shared memory and documentation
6. Coordinate dependencies between agents
7. Merge outputs into a cohesive final system

Final result should:
- improve execution quality
- reduce workflow chaos
- scale large projects more effectively
- maintain clearer task ownership
- improve review quality

---

# Core Multi-Agent Principles

## 1. Separate Responsibilities Clearly

Each agent should have:
- a focused role
- limited scope
- defined outputs
- clear responsibilities

Examples:
- research agent
- implementation agent
- reviewer agent
- optimization agent

Good separation improves:
- clarity
- scalability
- debugging
- coordination

Avoid:
- overlapping responsibilities
- duplicated work
- unclear ownership

---

## 2. Use Parallel Execution

Multi-agent systems work best when independent tasks execute simultaneously.

Examples:
- frontend and backend development
- research and implementation
- documentation and testing

Parallel execution improves:
- speed
- scalability
- iteration cycles

Claude should identify:
- independent work streams
- dependency chains
- coordination checkpoints

---

## 3. Maintain Shared Context

Agents require structured shared memory.

Important shared context:
- project goals
- active tasks
- architecture decisions
- implementation status
- review feedback

Recommended structure:

```plaintext
memory/
  project-summary.md
  architecture.md
  tasks.md
  reviews.md
```

Good shared context prevents:
- duplicated work
- conflicting outputs
- inconsistent execution

---

## 4. Add Review Agents

Review systems significantly improve output quality.

Reviewer agents should:
- validate logic
- detect edge cases
- check consistency
- challenge assumptions
- identify missing work

Review loops improve:
- reliability
- maintainability
- execution quality

---

## 5. Coordinate Dependencies Carefully

Complex workflows often contain dependencies between agents.

Claude should:
- identify blockers
- sequence dependent work
- synchronize updates
- maintain workflow continuity

Poor coordination creates:
- conflicting outputs
- integration issues
- duplicated effort

---

# Workflow

## 1. Define the Global Objective

Start by identifying:
- overall project goal
- deliverables
- constraints
- workflow stages

Break large objectives into:
- independent systems
- specialized tasks
- review stages

---

## 2. Create Agent Roles

Assign clear responsibilities.

Example:
- Planner Agent
- Frontend Agent
- Backend Agent
- Reviewer Agent
- Documentation Agent

Each agent should:
- remain specialized
- avoid overlapping work
- produce structured outputs

---

## 3. Define Shared Context

Create:
- shared summaries
- task tracking
- architecture documentation
- workflow memory

Ensure all agents:
- reference updated context
- follow consistent goals
- maintain workflow alignment

---

## 4. Execute Tasks in Parallel

Identify tasks that can run simultaneously.

Examples:
- UI implementation
- API design
- documentation writing
- SEO optimization

Claude should:
- minimize bottlenecks
- reduce idle dependency waiting
- maximize parallel execution opportunities

---

## 5. Review & Validate Outputs

Reviewer agents should:
- inspect outputs
- validate correctness
- detect inconsistencies
- identify missing requirements

Review systems improve:
- stability
- maintainability
- production readiness

---

## 6. Merge Outputs Carefully

Combine:
- implementation work
- documentation
- reviews
- optimizations

Validate:
- compatibility
- consistency
- workflow alignment

Ensure:
- outputs integrate cleanly
- project structure remains coherent

---

## 7. Refine & Iterate

Multi-agent workflows should evolve continuously.

Claude should:
- improve coordination systems
- refine task decomposition
- optimize review pipelines
- reduce workflow friction

The system should improve over time through iteration.

---

# Output Expectations

The final output should include:
- structured agent responsibilities
- coordinated task execution
- shared workflow memory
- review systems
- scalable project orchestration
- production-ready collaboration structure

The workflow itself should remain:
- modular
- scalable
- maintainable
- coordination-friendly
- execution-focused

---

# Execution Strategy (for AI agents)

The agent should:

1. Break large tasks into specialized responsibilities
2. Coordinate parallel workflows effectively
3. Maintain shared memory systems
4. Validate outputs through review agents
5. Prevent duplicated or conflicting work
6. Optimize workflow scalability continuously

The workflow should optimize for:
- execution quality
- scalability
- coordination clarity
- review quality
- long-term maintainability

---

# Best Practices

- Keep agent responsibilities focused
- Use shared context consistently
- Add reviewer agents whenever possible
- Parallelize independent workflows
- Track dependencies carefully
- Maintain structured documentation
- Refine orchestration systems continuously

---

# Notes

- Multi-agent systems scale better than single-context workflows
- Review agents significantly improve output quality
- Shared memory is critical for coordination
- Clear task ownership reduces workflow chaos
- Parallel execution dramatically improves scalability for complex projects
