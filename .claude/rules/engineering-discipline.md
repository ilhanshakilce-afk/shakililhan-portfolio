# Engineering Discipline (Karpathy, Ponytail, Addy Osmani, Matt Pocock, ECC)

Synthesized from the 5 core AI Agent engineering repositories:
- `multica-ai/andrej-karpathy-skills`
- `DietrichGebert/ponytail`
- `addyosmani/agent-skills`
- `mattpocock/skills`
- `affaan-m/everything-claude-code`

## 1. Think Before Coding (Karpathy)
- State assumptions explicitly. Never assume or hide confusion.
- Surface tradeoffs upfront.
- If multiple interpretations exist, present them rather than picking silently.
- If a simpler approach exists, advocate for it.

## 2. The Smallest Complete Change (Ponytail / YAGNI)
- The best code is the code never written. Solve the whole problem with the least new code.
- No speculative abstractions, wrappers, or "for later" features nobody asked for.
- Deletion beats addition.
- Match existing conventions and file structures.

## 3. Spec → Plan → Build → Verify → Ship (Addy Osmani)
- Break features down into verifiable increments.
- Verify each step before proceeding to the next.
- Validate in the browser / runtime environment with zero console errors.

## 4. Surgical Precision & Clean Architecture (Matt Pocock & ECC)
- Touch only what must be touched.
- Keep components modular, self-contained, and easily extensible.
- Make it simple for the user to add, edit, or remove sections with clean data structures.
