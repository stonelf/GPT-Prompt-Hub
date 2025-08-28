# Development Guidelines

## Core Principles

- **Incremental Progress**: Small, testable changes over big releases
- **Simplicity First**: Native JS/Node.js/HTML/CSS over unfamiliar libraries (KISS)
- **Code Quality**: DRY principle, high cohesion, low coupling in small modules
- **Testing Focus**: TDD approach with Jest + Supertest, covering edge cases
- **Clear Communication**: Obvious code over clever solutions

## Development Process

### Planning & Execution

1. Break work into 3-5 staged deliverables in `IMPLEMENTATION_PLAN.md`
2. Use Taskmaster MCP for task management
3. Maximum 3 attempts per problem before reassessment

### Implementation Flow

1. Study existing patterns → Write tests → Implement → Refactor → Commit
2. Prefer TDD: red → green → refactor
3. Create small, focused files with single responsibilities

## Technical Standards

### Architecture

- Node.js backend + native HTML/CSS/JS frontend
- Composition over inheritance
- Explicit dependencies and data flow
- Modular design with separation of concerns

### Code Quality

- Every commit must compile and pass tests
- No linter warnings, clear commit messages
- Reuse code over duplication (DRY)

### Error Handling & Logging

- Graceful failure with proper cleanup
- Comprehensive logging with levels (debug, info, warn, error)
- Detailed debug logs during development
- Never silent exceptions

### Testing

- Jest + Supertest for unit and integration tests
- Cover normal operation and error scenarios
- Descriptive test names, deterministic results

## Quality Checklist

- Tests passing (including edge cases)
- Follows project conventions
- No lint warnings
- Clear commit messages
- Proper error handling
- Comprehensive logging
- Modular, non-duplicated code

## Critical Reminders

**Never**: bypass tests, commit broken code, add unnecessary dependencies
**Always**: work incrementally, provide good logs, handle errors gracefully, use native solutions when possible

