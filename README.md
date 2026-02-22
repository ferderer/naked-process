# Naked Decision Process
*– Process is perfect when nothing can be taken away.*

Naked Process (formally: **Naked Decision Process / NDP**) is a subtractive methodology for software development. Instead of prescribing what to do, it provides a decision tree that strips process down to what your specific team actually needs — and removes everything else.

Most frameworks add. Naked Process removes.

---

## The Problem

The software industry spends billions annually on certifications, frameworks, and tooling that optimize the least important variable in the equation. Decades of research — from Sackman (1968) to DeMarco & Lister (1987) to the Standish Group (2020) — consistently show that **developer quality** is the dominant predictor of project success, not process adherence.

Scrum, Kanban, SAFe, and their derivatives all assume that better rules produce better outcomes. The evidence says otherwise: better people produce better outcomes, and the right amount of process depends entirely on context.

## The Approach

Naked Process takes every known process element — from Scrum, Kanban, XP, classical project management, and beyond — and subjects each to a single question:

> *Under which conditions does this actually help?*

What survives becomes a **decision tree**. Given your team's specific context — capability, deployment maturity, stakeholder access, decision speed, problem clarity — the tree outputs the **minimal viable process**: the smallest set of practices that addresses your actual constraints.

Nothing more. Nothing less.

## Core Principles

1. **Subtractive, not additive.** Start with everything, remove what doesn't earn its place.
2. **Context-dependent.** There is no universal best process. There are only fitness conditions.
3. **People over ceremony.** Process exists to serve capable people, not to compensate for incapable ones.
4. **Decision speed over ritual.** The co-creator of Scrum's own data shows that decision latency < 1 hour predicts success at 68% — independent of methodology.
5. **Transparent accountability.** Process that distributes accountability to the point of invisibility is camouflage, not management.

## The Decision Tree

The core of Naked Process is a decision tree built on six dimensions:

| Dimension | What It Captures |
|---|---|
| **Team Capability** | Uniformly strong / mixed with clear lead / junior-heavy |
| **Deployment Capability** | Continuous delivery possible vs. batched releases |
| **Stakeholder Access** | Direct and frequent vs. mediated through layers |
| **Decision Authority** | Where decisions are made and how fast |
| **Problem Clarity** | Genuinely emergent vs. understood upfront vs. unexamined |
| **Coordination Need** | Team size, distribution, integration complexity |

The tree doesn't output "use Scrum" or "use Kanban." It outputs a minimal set of context-dependent practices — communication channel, release cadence, feedback mechanism, decision authority — assembled from whatever source survives the removal test.

→ See [`decision-tree/`](decision-tree/) for the current working model.

## Documentation

| Document | Description |
|---|---|
| [The Manifesto](docs/manifesto.md) | Why Naked Process exists — the philosophical foundation |
| [Points Don't Matter](articles/Points%20Don't%20Matter%20–%20Why%20Developer%20Quality%20Beats%20Process%20Every%20Single%20Time.md) | The research-backed argument that developer quality beats process |
| [The Decision Tree](decision-tree/README.md) | The practical tool — how to find your minimal viable process |
| [Methodology](docs/methodology.md) | How the decision tree was built: dimensions, decomposition, and validation |

## Origin

Naked Process grew out of two observations across 30 years of software delivery:

1. Every successful project shared one trait: the right people making fast decisions with minimal overhead.
2. Every failed project shared one trait: process was present, but judgment was absent.

The manifesto article, *"Points Don't Matter: Why Developer Quality Beats Process Every Time,"* provides the research foundation. The decision tree is the constructive counterpart — not just tearing down, but building what replaces ceremony.

## Contributing

This is a living framework. If you have data — empirical research, case studies, or concrete experience — that challenges or refines any dimension, open an issue or PR. Opinions without evidence will be politely ignored.

## License

[CC BY-SA 4.0](LICENSE) — Share and adapt freely, with attribution, under the same terms.

---

*"Economists already know this. Psychologists already know this. DeMarco and Lister wrote it down in 1987. Sackman measured it in 1968. Points don't matter. People do."*
