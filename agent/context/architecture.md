# System Architecture

<INSTRUCTION immutable>
This document defines the architectural patterns and design principles for agent-assisted development.

## Directory Structure

```
project-root/
├── agent/                     # AI agent workspace
│   ├── context/              # Core project context
│   │   ├── architecture.md   # This file
│   │   ├── constraints.md    # Project limitations
│   │   └── goals.md         # Project objectives
│   ├── memory/              # Persistent knowledge
│   │   ├── decisions/       # Technical decisions
│   │   ├── progress/        # Development tracking
│   │   └── learnings/       # Insights gained
│   └── workspace/           # Active development
│       ├── current/         # Current task state
│       ├── planning/        # Implementation plans
│       └── validation/      # Testing criteria
├── src/                     # Source code
└── docs/                    # Project documentation
```

## Core Principles

1. **Context Persistence**
   - All context is stored in version-controlled text files
   - Clear separation between immutable and mutable content
   - Explicit tracking of decisions and progress

2. **Agent Collaboration**
   - Well-defined interaction patterns
   - Clear task boundaries
   - Explicit state management
   - Progress tracking mechanisms

3. **Knowledge Management**
   - Hierarchical context organization
   - Clear update patterns
   - Version-controlled history
   - Searchable documentation

## Implementation Patterns

1. **Task Processing**
   ```
   1. Review context
   2. Plan implementation
   3. Execute changes
   4. Document progress
   5. Validate results
   ```

2. **Documentation Structure**
   ```
   1. Immutable sections (<INSTRUCTION immutable>)
   2. Append-only logs (<LOG append>)
   3. Task lists (- [ ] format)
   4. Progress tracking
   ```

3. **State Management**
   ```
   1. Context files (immutable)
   2. Memory updates (append-only)
   3. Workspace state (mutable)
   4. Progress tracking (append-only)
   ```

## Best Practices

1. **Context Management**
   - Always review relevant context first
   - Update progress after each significant change
   - Document decisions as they're made
   - Maintain clear task boundaries

2. **Documentation**
   - Use markdown for all documentation
   - Follow consistent formatting
   - Keep files focused and organized
   - Use clear, descriptive names

3. **Development Flow**
   - Incremental changes
   - Clear validation steps
   - Explicit state transitions
   - Regular progress updates
</INSTRUCTION>

<LOG append>
# Architecture Updates

Record any updates or clarifications to the architecture here:

</LOG>