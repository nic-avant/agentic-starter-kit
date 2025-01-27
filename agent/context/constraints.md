# Project Constraints

<INSTRUCTION immutable>
This document outlines the key constraints and limitations that all agents must consider during development.

## Technical Constraints

1. **Simplicity**
   - Minimize dependencies
   - Prefer standard libraries over third-party packages
   - Keep configuration minimal

2. **Portability**
   - Must work across different operating systems
   - No system-specific dependencies
   - Platform-agnostic file paths

3. **Documentation**
   - All files must be text-based (markdown preferred)
   - No binary documentation formats
   - Clear structure for AI parsing

## Process Constraints

1. **Agent Interaction**
   - One tool use per interaction
   - Explicit state management
   - Clear progress tracking

2. **Memory Management**
   - Append-only logs for progress
   - Immutable core documentation
   - Version-controlled decision history

3. **Context Boundaries**
   - Clear separation of concerns
   - Well-defined responsibility areas
   - Explicit context switching

## Implementation Constraints

1. **Code Structure**
   - No unit tests unless requested
   - Minimal boilerplate
   - Clear file organization

2. **Development Flow**
   - Incremental changes
   - Document-first approach
   - Explicit validation steps

3. **Tooling**
   - CLI-first approach
   - Standard development tools
   - No specialized IDEs required
</INSTRUCTION>

<LOG append>
# Constraint Updates

Record any updates or clarifications to project constraints here:

</LOG>