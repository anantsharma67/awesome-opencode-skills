---
name: tdd-guard
description: Workflow for enforcing strict Test-Driven Development practices through incremental implementation, automated validation, regression prevention, and disciplined engineering execution.
---

# TDD Guard

## Overview

This skill enables Claude to operate as a strict Test-Driven Development (TDD) enforcement and workflow orchestration system.

The workflow focuses on:
- writing tests before implementation
- incremental development
- regression prevention
- disciplined engineering practices
- deterministic validation
- implementation safety
- edge-case coverage
- maintainable test architecture

The goal is to ensure software is built through small, validated iterations where behavior is defined through tests before production code is written.

This workflow prioritizes:
- correctness
- maintainability
- confidence
- long-term engineering stability

instead of fast but fragile implementation.

---

# Setup

Before starting:

1. Install project dependencies.

2. Configure the testing framework.

Examples:

JavaScript / TypeScript:

```bash
npm install vitest
```

or:

```bash
npm install jest
```

Python:

```bash
pip install pytest
```

3. Create project structure.

Recommended structure:

```plaintext
src/
tests/
```

4. Configure automated test execution.

Optional:
- CI/CD integration
- coverage reporting
- pre-commit hooks

Recommended tools:
- Vitest
- Jest
- Pytest
- Playwright
- GitHub Actions
- ESLint
- TypeScript

---

# Inputs Required

- Feature requirements
- Existing codebase
- Expected behavior
- Testing framework

Optional:
- Existing test suites
- API contracts
- Regression history
- Performance requirements

---

# When to Use This Skill

Use this skill when:
- building production software
- implementing critical systems
- preventing regressions
- refactoring large codebases
- validating APIs
- improving engineering discipline
- scaling maintainable systems
- enforcing reliable implementation workflows

---

# When NOT to Use

Do NOT use this skill for:
- throwaway prototypes
- purely experimental spikes
- temporary scripts
- tasks with no long-term maintenance value

---

# Example Use Case

> Implement a new authentication system using strict TDD workflows.

Claude should:

1. Define expected behavior
2. Write failing tests first
3. Implement the smallest valid solution
4. Run tests continuously
5. Refactor safely after passing tests
6. Add edge-case coverage
7. Prevent regressions before merging

Final result should:
- remain fully tested
- support safe refactoring
- reduce regression risk
- improve maintainability
- enforce engineering discipline

---

# Core TDD Principles

## 1. Tests Define Behavior First

The workflow should always begin with:
- expected behavior
- test definitions
- failure validation

Claude should:
- write failing tests first
- confirm failures are meaningful
- define requirements through tests

Avoid:
- implementation-first workflows
- retroactive testing
- unvalidated assumptions

Tests should drive implementation.

---

## 2. Implement the Smallest Possible Change

After writing a failing test:
- implement only enough code to pass
- avoid premature optimization
- avoid speculative abstractions

Small iterations improve:
- debugging
- maintainability
- reliability

Claude should prefer:
- tiny incremental progress
- highly controlled changes
- deterministic implementation steps

---

## 3. Refactor Only After Passing Tests

Refactoring should happen only when:
- tests pass
- behavior remains stable
- regressions are controlled

Good refactoring improves:
- readability
- maintainability
- architecture quality

Avoid:
- mixing implementation and refactoring simultaneously
- large uncontrolled rewrites

---

## 4. Edge Cases Are Part of the Workflow

Claude should proactively test:
- invalid inputs
- empty states
- async failures
- race conditions
- boundary conditions
- unexpected behavior

Strong edge-case coverage improves:
- production stability
- reliability
- long-term maintainability

---

## 5. Tests Should Remain Readable

Good tests should:
- explain behavior clearly
- remain easy to debug
- isolate failures cleanly

Avoid:
- overly complex test setups
- fragile mocks
- unclear assertions
- duplicated test logic

Readable tests improve:
- onboarding
- debugging
- team collaboration

---

# Workflow

## 1. Define Expected Behavior

Start by identifying:
- feature requirements
- expected outputs
- edge cases
- failure conditions

Translate requirements into:
- executable test cases
- validation rules
- deterministic assertions

Behavior should be explicit before implementation begins.

---

## 2. Write Failing Tests

Create:
- unit tests
- integration tests
- validation cases
- regression coverage

Validate:
- tests fail correctly
- assertions are meaningful
- behavior is clearly defined

Example workflow:

```plaintext
Write test
↓
Run test
↓
Confirm failure
```

---

## 3. Implement Minimal Code

Write only enough implementation to:
- satisfy the failing test
- pass validation
- preserve clarity

Avoid:
- unnecessary abstraction
- speculative architecture
- overengineering

Small implementations improve:
- reliability
- debugging
- iteration speed

---

## 4. Run Tests Continuously

Claude should:
- validate after every change
- monitor regressions
- preserve deterministic behavior
- confirm passing states frequently

Continuous validation improves:
- engineering confidence
- stability
- workflow discipline

---

## 5. Refactor Safely

Once tests pass:
- improve readability
- simplify logic
- reduce duplication
- optimize architecture

Ensure:
- behavior remains unchanged
- tests continue passing
- regressions do not appear

---

## 6. Expand Edge-Case Coverage

Add tests for:
- invalid states
- async behavior
- concurrency issues
- unexpected inputs
- scaling scenarios

Good edge-case coverage improves:
- robustness
- production reliability
- system confidence

---

## 7. Validate Before Merge

Before completion validate:
- all tests pass
- coverage remains meaningful
- no regressions appear
- implementation remains readable

Ensure:
- tests reflect actual behavior
- architecture remains maintainable
- workflows stay deterministic

---

# Output Expectations

The final output should include:
- failing-first tests
- incremental implementations
- regression coverage
- readable test architecture
- deterministic validation systems
- maintainable engineering workflows

The workflow itself should remain:
- disciplined
- incremental
- test-first
- scalable
- production-focused

---

# Execution Strategy (for AI agents)

The agent should:

1. Write tests before implementation
2. Implement the smallest valid solution
3. Validate continuously
4. Refactor only after passing tests
5. Detect edge cases proactively
6. Preserve deterministic engineering workflows

The workflow should optimize for:
- correctness
- maintainability
- reliability
- regression prevention
- engineering discipline

---

# Best Practices

- Always start with failing tests
- Keep implementation increments small
- Run tests continuously
- Refactor only after passing validation
- Prioritize readable test structures
- Cover edge cases aggressively
- Prevent regressions before optimization

---

# Notes

- TDD improves long-term engineering stability significantly
- Small iterations reduce debugging complexity
- Readable tests scale better than overly abstract test systems
- Edge-case coverage dramatically improves production reliability
- Disciplined validation workflows prevent fragile engineering systems
