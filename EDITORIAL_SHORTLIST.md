# Editorial Shortlist

The next five posts are the committed editorial queue. The remaining five are ranked candidates whose order can change with research readiness and reader response. Interviews are excluded.

Every post should begin with a current engineering problem, explain one alternative mechanism, examine its trade-offs, and produce a lesson, technique, warning, diagnostic lens, or useful question for present work. Most posts should take 8–15 minutes to read; source dossiers and experiments can remain deeper.

## Committed queue

### FreeBSD Jails: What Does a Container Actually Need to Isolate?

Separate process isolation, filesystem views, networking, identity, privileges, resource limits, packaging, lifecycle management, and orchestration. Use jails to show which parts belong to the kernel mechanism and which belong to the modern container stack.

### Smalltalk: When the Running Program Is the Development Environment

Examine live objects, runtime inspection, modification, debugging, persistence, and the boundary between a program and its source files. Compare the model with source-centric development without turning the post into a Smalltalk tour.

### What Nix Actually Makes Reproducible

Test dependency closure, hidden environmental inputs, toolchains, time, locale, and network access. Distinguish reproducible builds from reproducible deployment and execution.

### Erlang Supervision Trees: Design Recovery Before Failure

Build a small service hierarchy with explicit restart relationships and failure boundaries. Compare dependency-aware recovery with ad hoc process restarts and deployment-level orchestration.

### Plan 9 Namespaces: A Different System View for Every Process

Demonstrate per-process namespaces and resource composition. Connect the mechanism to containers, dependency injection, secrets, service views, and interface design while keeping naming, rather than isolation, as the central lesson.

## Ranked candidates

### Deterministic Simulation: Make Distributed Failures Reproducible

Control time, scheduling, randomness, message delivery, and faults so a failing distributed execution can be replayed from a seed. Compare the technique with ordinary integration and chaos testing.

### Capsicum: Let Programs Give Up Authority After Startup

Show how a process can restrict itself to resources it already holds. Use the mechanism to explain object authority and application compartmentalization without compressing all capability systems into one survey.

### Array Languages: See the Data Dependencies That Loops Hide

Use one substantial data problem to compare whole-array operations with element-at-a-time code. Focus on shape, dependencies, data movement, vectorization, readability, and error behavior rather than terse syntax.

### DTrace: Ask New Questions of a Running System

Contrast dynamic investigation with telemetry that must be predicted before deployment. Focus on the observability model, runtime cost, safety, and its relationship to current tracing systems.

### TLA+: Check the Design Before You Write the Code

Model a small concurrent or distributed system with explicit states, transitions, and invariants. Show which design errors appear before implementation and where model checking stops helping.

## Deferred subjects

Tuple spaces, literate programming, crash-only software, OpenVMS clustering, broad capability surveys, CALM, CHERI, seL4, session types, and software transactional memory remain in the research backlog. Each needs either a sharper present-day payoff, more specialist review, or a narrower question before entering the committed queue.

The alternative-computing atlas remains internal editorial infrastructure until published work creates enough source-backed records to justify a public product.
