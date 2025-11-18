# AI-Driven Development — 30-Day Challenge
## Task 2 — Official Submission

---

## Part A — Theory (Short Questions)

### 1. Nine Pillars Understanding

#### Why is using AI Development Agents (like Gemini CLI) for repetitive setup tasks better for your growth as a system architect?

AI Development Agents automate repetitive setup tasks, allowing developers to shift focus from routine, mechanical work to higher-level architectural decisions. When agents handle tasks like project scaffolding, dependency management, and boilerplate code generation, architects dedicate cognitive resources to system design, scalability, and long-term maintainability. This frees developers from getting bogged down in implementation details and enables them to think about the bigger picture—how components interact, how layers communicate, and how systems evolve. By delegating repetitive work, developers naturally grow into architects who design systems rather than just write code.

#### Explain how the Nine Pillars of AIDD help a developer grow into an M-Shaped Developer.

The Nine Pillars of AI-Driven Development create an integrated ecosystem that enables developers to master multiple complementary domains. Each pillar addresses a different aspect of development. As developers work within this framework, they gain depth in each pillar and naturally develop skills across multiple related domains. For example, mastering TDD gives depth in testing practices, learning AI CLI provides expertise in automation, and understanding specifications develops system-thinking skills. Over time, developers accumulate deep expertise in 2–4 complementary areas rather than remaining specialists in just one. This combination of deep, complementary skills is what defines an M-Shaped Developer.

---

### 2. Vibe Coding vs Specification-Driven Development

#### Why does Vibe Coding usually create problems after one week?

Vibe Coding relies on intuition and feeling rather than clear planning, which works initially because the scope is small and the developer holds everything in memory. However, after about a week, the codebase grows, complexity accumulates, and the developer begins forgetting initial decisions. Without documented specifications or clear architecture, extending the code becomes difficult. Other developers cannot understand the rationale behind design choices. Bugs emerge because assumptions made during vibing were never explicitly stated. The architecture becomes fragile and hard to modify because there was no intentional design—just reactive coding. This is why Vibe Coding creates problems after one week: the costs of unclear design compound as the codebase grows.

#### How would Specification-Driven Development prevent those problems?

Specification-Driven Development prevents these problems by formalizing human intent before any code is written. By writing clear, executable specifications upfront, developers explicitly define requirements, expected behaviors, and architectural decisions. These specifications act as a contract that guides implementation and serve as reference documentation for future changes. When specifications are clear, extending the codebase becomes straightforward because developers understand the original intent. Code becomes maintainable because decisions are documented, not buried in implementation details. Bugs are caught earlier because specifications define expected behavior, and tests can verify compliance. Most importantly, SDD creates architecture that is inherently easier to extend and modify because it was designed intentionally, not accumulated through vibes.

---

### 3. Architecture Thinking

#### How does architecture-first thinking change the role of a developer in AIDD?

Architecture-first thinking elevates the developer's role from a code writer to a system designer. In traditional development, developers write code first, and architecture emerges (or fails to emerge) as a byproduct. In AIDD with architecture-first thinking, developers begin by designing the system structure, defining layers (Models, IDEs, Agents), clarifying how components communicate, and planning for scalability and maintainability. This mindset shift means developers think in abstractions and systems before touching code. The developer's primary role becomes designing the blueprint rather than implementing details. This is powerful in AIDD because it aligns with how AI agents work—they execute based on clear specifications and instructions. When developers think architecturally first, they can write better specifications for agents to execute.

#### Explain why developers must think in layers and systems instead of raw code.

Developers must think in layers and systems because this mirrors how complex software actually works. The 3-Layer Architecture (Models, IDEs, Agents) demonstrates that no meaningful system is monolithic; it requires separation of concerns. Models handle intelligence, IDEs provide the workspace, and Agents orchestrate execution. If developers think only in raw code, they lose sight of these critical separations and end up with tangled, unmaintainable systems. Thinking in layers ensures each component has a clear responsibility and boundary. Thinking in systems means understanding dependencies, data flow, and how changes in one layer affect others. This systems thinking is essential in AI-Driven Development because agents themselves are system-level orchestrators—they coordinate between layers. Developers who think in layers and systems write better specifications, design more scalable architectures, and collaborate more effectively with AI agents.

---

## Part B — Practical Task (Screenshot Required)

### Task Description
Using any AI CLI tool, generate a 1-paragraph specification for an email validation function.

**Specification Generated by AI CLI:**  
![task description](gemini_task2.jpg)


---

## Part C — Multiple Choice Questions

1. **What is the main purpose of Spec-Driven Development?**  
   Answer: **B**

2. **What is the biggest mindset shift in AI-Driven Development?**  
   Answer: **B**

3. **Biggest failure of Vibe Coding?**  
   Answer: **B**

4. **Main advantage of using AI CLI agents (like Gemini CLI)?**  
   Answer: **B**

5. **What defines an M-Shaped Developer?**  
   Answer: **C**
