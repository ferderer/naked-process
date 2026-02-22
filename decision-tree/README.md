# The Naked Process Decision Tree

The decision tree is the core practical artifact of Naked Process. It takes your team's context as input and outputs the **minimal viable process** — the smallest set of practices that addresses your actual constraints.

## Dimensions

### 1. Team Capability

| Value | Description |
|---|---|
| **Uniformly strong** | All members operate at a high level. Shared mental models. Minimal need for guidance. |
| **Mixed with clear lead** | Range of skill levels, but a strong technical lead provides architectural direction. |
| **Junior-heavy / no lead** | Most members need guidance. No one capable of making reliable architectural calls. |

### 2. Deployment Capability

| Value | Description |
|---|---|
| **Continuous delivery** | Can deploy to production at any time. Automated pipeline, feature flags, rollback. |
| **Frequent but batched** | Regular releases (weekly/biweekly) but not continuous. Some manual steps. |
| **Infrequent / manual** | Releases are rare, painful, and risky. High coordination cost per deployment. |

### 3. Stakeholder Access

| Value | Description |
|---|---|
| **Direct and frequent** | Team can reach decision-makers quickly. Feedback loops measured in hours. |
| **Mediated** | Access through project managers, product owners, or other intermediaries. Days-scale latency. |
| **Absent or adversarial** | Stakeholders are unreachable, disengaged, or actively obstructive. |

### 4. Decision Authority

| Value | Description |
|---|---|
| **Team-autonomous** | Team can make and execute technical and scope decisions without external approval. |
| **Lead-autonomous** | A designated lead has authority. Team executes within the lead's architectural vision. |
| **Externally gated** | Decisions require approval from outside the team. Committee-driven or politically constrained. |

### 5. Problem Clarity

| Value | Description |
|---|---|
| **Genuinely emergent** | Requirements cannot be known upfront. True exploration, R&D, or novel domain. |
| **Discoverable** | Requirements exist but haven't been gathered yet. Common failure mode: teams running "Agile discovery" on problems that aren't actually uncertain. Needs upfront engineering discipline. |
| **Well-specified** | Requirements are clear and stable. Execution-focused. Minimal need for discovery ceremony. |

### 6. Coordination Need

| Value | Description |
|---|---|
| **Low** | Small team (3–5), co-located or well-aligned remote. Minimal integration points. |
| **Medium** | Mid-sized team (6–10) or multiple integration points. Some coordination overhead. |
| **High** | Large team, multiple sub-teams, distributed across time zones, complex integration. |

---

## How It Works

*The decision tree logic is currently being developed. The goal: for any combination of dimension values, output the minimal set of practices (communication channel, release cadence, feedback mechanism, decision structure) that addresses the team's actual constraints.*

*The tree subtracts. Given a strong team with CD, direct stakeholders, autonomous decisions, clear requirements, and low coordination — the output approaches zero formal process. Each constraint you add introduces only the practices needed to address that specific constraint.*

## Status

🔄 **In development.** The dimensions are stable. The practice decomposition (Step 2) and mapping (Step 3) are in progress.
