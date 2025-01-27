# Active Development Workspace

This directory contains the current development state and work in progress. It is organized to support clear task boundaries and state management.

## Directory Structure

### `/current`
Active task context and state. Each task should have:
- `task.md` - Current task description and status
- `context.md` - Relevant context for the task
- `notes.md` - Working notes and observations

### `/planning`
Task breakdown and implementation plans:
- `requirements.md` - Task requirements and constraints
- `approach.md` - Implementation approach and steps
- `risks.md` - Potential issues and mitigations

### `/validation`
Testing and verification criteria:
- `criteria.md` - Success criteria and validation steps
- `results.md` - Test results and observations
- `issues.md` - Found issues and resolutions

## Templates

### Task Template
```markdown
# Task: [Title]

## Objective
[Clear description of the task goal]

## Context
[Relevant background information]

## Requirements
- [ ] Requirement 1
- [ ] Requirement 2

## Approach
1. Step 1
2. Step 2

## Validation
- [ ] Test case 1
- [ ] Test case 2

## Notes
- Working notes
- Observations
```

### Planning Template
```markdown
# Implementation Plan

## Requirements Analysis
- Key requirements
- Constraints
- Dependencies

## Approach
1. Phase 1
   - Step 1.1
   - Step 1.2
2. Phase 2
   - Step 2.1
   - Step 2.2

## Risk Assessment
- Risk 1
  - Impact
  - Mitigation
- Risk 2
  - Impact
  - Mitigation
```

### Validation Template
```markdown
# Validation Plan

## Success Criteria
1. Criterion 1
2. Criterion 2

## Test Cases
- Test 1
  - Input
  - Expected output
  - Actual result
- Test 2
  - Input
  - Expected output
  - Actual result

## Issues
- [ ] Issue 1
  - Description
  - Resolution
```

## Usage Guidelines

1. Create a new task directory for each task
2. Copy relevant templates for the task
3. Update progress in real-time
4. Document decisions and issues
5. Validate against requirements
6. Clean up after task completion