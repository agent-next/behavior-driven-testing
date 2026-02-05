# Behavior-Driven Testing

A systematic testing methodology for exhaustive branch coverage, edge case identification, and production bug prevention.

## Installation

```bash
npx skills add robotlearning123/behavior-driven-testing
```

Or manually copy to your skills directory:
```bash
git clone https://github.com/robotlearning123/behavior-driven-testing.git ~/.agents/skills/behavior-driven-testing
```

## When to Use

- PR review reveals incomplete test coverage
- Tests pass but users report bugs
- Code changes break existing features
- Verifying all branches and edge cases before merge
- Analyzing "it works on my machine" issues
- Planning test strategy for new features
- Debugging flaky tests and race conditions

## Core Philosophy

**Start from user behavior, not code structure.** Every user-reachable path must be tested—no branch left uncovered, no edge case assumed.

## Key Features

- **Branch Matrix System** - Systematic tracking of all code branches
- **Progressive Disclosure** - Quick reference + detailed guides when needed
- **Copy-Paste Templates** - Ready-to-use Unit, Integration, and E2E test templates
- **Pre-Release Checklists** - Verify coverage before shipping

## Structure

```
behavior-driven-testing/
├── SKILL.md                    # Main entry point
├── LICENSE                     # MIT License
└── references/
    ├── analysis-phase.md       # Requirements, state machines, branch mapping
    ├── branch-matrices.md      # All branch coverage templates
    ├── design-phase.md         # Test case design, impact analysis
    ├── execution-phase.md      # Implementation, execution, coverage
    ├── test-templates.md       # Complete code templates
    └── testing-principles.md   # Mock vs Real, creating test conditions
```

## Quick Start

1. **Map branches** - Create a branch matrix for your code changes
2. **Design tests** - Apply equivalence partitioning and boundary analysis
3. **Implement** - Use the provided templates for Unit/Integration/E2E tests
4. **Verify** - Check all P0/P1 branches are covered before shipping

## License

MIT © Cong Wang
