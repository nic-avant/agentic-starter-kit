# Agent Workspace

This directory serves as the primary workspace for AI agents collaborating on this project. It is structured to optimize AI-human interaction and maintain clear context across development sessions.

## Directory Structure

- `context/` - Core project context and constraints
  - `architecture.md` - System architecture and design decisions
  - `constraints.md` - Project constraints and limitations
  - `goals.md` - Project objectives and success criteria
  
- `memory/` - Persistent knowledge across sessions
  - `decisions/` - Key technical decisions and their rationales
  - `progress/` - Development progress and milestones
  - `learnings/` - Insights and lessons learned
  
- `workspace/` - Active development artifacts
  - `current/` - Current task context and state
  - `planning/` - Task breakdown and implementation plans
  - `validation/` - Testing and verification criteria

## Usage Guidelines

1. All AI agents should review the `/context` directory before starting work
2. Development decisions and progress are tracked in `/memory`
3. Active work happens in `/workspace`
4. Each directory contains an index.md file explaining its specific purpose and usage

## Best Practices

1. Keep context files concise and focused
2. Update progress regularly
3. Document decisions as they are made
4. Maintain clear task states in workspace