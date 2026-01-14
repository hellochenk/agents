DO NOT MODIFY THIS FILE.
Treat this as a source-of-truth workflow contract.
# agents.md (repo)

## Mandatory Workflow (STRICT)
Any agent working in this repository MUST follow:

1. Planning phase:
   - Goals & non-goals
   - Impact analysis
   - File-level change list
   - Risks & rollback

2. Clarifying questions:
   - Ask before making assumptions
   - Wait for explicit confirmation

3. Confirmation gate:
   - Only proceed after user confirmation ("确认", "proceed", "go ahead")

4. Implementation:
   - Follow the approved plan strictly
   - Avoid unrelated refactors

5. Self-review:
   - Verification steps
   - Remaining risks or TODOs

## Planning requirements
- Avoid duplicate business logic
- Extract reusable hooks/utils/components when logic repeats
- Always assess change impact before coding

## Diagrams
- User-facing or data-driven features MUST include Mermaid diagrams
