# Methodology

## How the Decision Tree Was Built

Naked Process follows a four-step methodology:

### Step 1: Identify Dimensions
Identify the contextual dimensions that actually change what process you need. Each dimension must pass the validation test:

> *"Can I name a concrete scenario where changing **only** this dimension — holding all others constant — would change the minimal process I'd recommend?"*

Six dimensions survived this test. See the [Decision Tree README](../decision-tree/README.md) for the full specification.

### Step 2: Decompose Existing Processes
Take all known process models — Scrum, Kanban, XP, classical project management, Lean, SAFe, and others — and decompose them into their **atomic practices**: the smallest indivisible process elements.

Examples: daily standup, sprint boundary, WIP limit, retrospective, pair programming, code review, deployment pipeline, backlog refinement, etc.

### Step 3: Map Practices to Conditions
For each atomic practice, determine under which dimension values it provides measurable benefit. Practices that provide benefit under all conditions are universal. Practices that provide benefit under no conditions are waste. Most fall somewhere in between — they help under specific constraints and add friction otherwise.

### Step 4: Build the Decision Tree
Assemble the surviving practices into a decision tree. Given a team's context (their values on each dimension), the tree outputs the minimal set of practices they need.

The tree subtracts. It never adds without justification.

---

## Current Status

- ✅ Step 1: Dimensions identified and validated
- 🔄 Step 2: Process decomposition in progress
- ⬜ Step 3: Practice-to-condition mapping
- ⬜ Step 4: Decision tree assembly

## Open Questions

- **Regulatory/compliance environment** — independent dimension or captured by deployment + problem clarity?
- **Team size** — independent dimension or modifier on team capability?
- **Geographic distribution** — independent dimension or modifier on coordination need?
- **Organizational culture** — input dimension (what the immune system tolerates) or out of scope (what *should* be)?
- **Stakeholder technical literacy** — independent or folded into decision authority / problem clarity?
