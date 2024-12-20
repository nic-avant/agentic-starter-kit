<INSTRUCTION immutable>

## Coding and Design Standards

It is CRITICAL that the codebase is written in a consistent manner. When making changes to the codebase, please ensure that the following design principles are followed:

### Kiss

Most systems work best if they are kept simple rather than made complex.

- Less code takes less time to write, has less bugs, and is easier to modify.
- Simplicity is the ultimate sophistication.
- It seems that perfection is reached not when there is nothing left to add, but when there is nothing left to take away.

### YAGNI

Always implement things when you actually need them, never when you just foresee that you need them.

- Any work that's only used for a feature that's needed tomorrow, means losing effort from features that need to be done for the current iteration.
- It leads to code bloat; the software becomes larger and more complicated.

### Do The Simplest Thing That Could Possibly Work

Always ask yourself: "What is the simplest thing that could possibly work?"

- Real progress against the real problem is maximized if we just work on what the problem really is.

### Separation of Concerns

Break program functionality into separate modules that overlap as little as possible.

- Simplify development and maintenance of software applications.
- When concerns are well-separated, individual sections can be reused, as well as developed and updated independently.

### Keep things DRY

Put business rules, long expressions, if statements, math formulas, metadata, etc. in only one place. Identify the single, definitive source of every piece of knowledge used in your system, and then use that source to generate applicable instances of that knowledge (code, documentation, tests, etc). Apply the rule of three to decide when to refactor.

- Duplication (inadvertent or purposeful duplication) can lead to maintenance nightmares, poor factoring, and logical contradictions.
- A modification of any single element of a system does not require a change in other logically unrelated elements.
- Additionally, elements that are logically related all change predictably and uniformly, and are thus kept in sync.

### Avoid Premature Optimization

Make It Work Make It Right Make It Fast. Don't optimize until you need to, and only after profiling you discover a bottleneck optimize that.

- It is unknown upfront where the bottlenecks will be.
- After optimization, it might be harder to read and thus maintain.

### Inversion of Control

Inversion of Control can be achieved using Factory patterns, Service Locator patterns, Dependency Injections, contextualized lookups, Template Method patterns, and Strategy patterns.

- Inversion of control is used to increase modularity of the program and make it extensible.
- To decouple the execution of a task from implementation.
- To focus a module on the task it is designed for.
- To free modules from assumptions about how other systems do what they do and instead rely on contracts.
- To prevent side effects when replacing a module.

### Open/Closed Principle

Write classes that can be extended (as opposed to classes that can be modified). Expose only the moving parts that need to change, hide everything else.

- Improve maintainability and stability by minimizing changes to existing code.

### Interface Segregation Principle

Avoid fat interfaces. Classes should never have to implement methods that violate the Single responsibility principle.

- If a class implements methods that are not needed the caller needs to know about the method implementation of that class. For example if a class implements a method but simply throws then the caller will need to know that this method shouldn't actually be called.

### Command Query Separation

Implement each method as either a query or a command. Apply naming convention to method names that implies whether the method is a query or a command.

- By clearly separating methods into queries and commands the programmer can code with additional confidence without knowing each method's implementation details.
</INSTRUCTION>