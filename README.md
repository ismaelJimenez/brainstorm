# Brainstorm

A collaborative brainstorming skill that turns ideas into clarity. Guides you through structured dialogue — exploring project context, asking focused questions one at a time, proposing approaches with trade-offs, and producing approved brainstorm documents ready for specification.

## What It Does

Brainstorm is a skill that helps you think before you build. Instead of jumping straight into code, it walks you through a structured conversation to explore your idea, consider alternatives, and arrive at a clear decision.

The workflow:

1. **Explore project context** — understands your codebase, docs, and recent changes
2. **Ask clarifying questions** — one at a time, focused on purpose, constraints, and success criteria
3. **Propose approaches** — 2–3 options with trade-offs and a recommendation
4. **Present findings** — problem framing, recommendations, and open questions for your approval
5. **Write brainstorm document** — saves a structured record of the decision to `brainstorm/`
6. **Suggest next step** — transition to specification

## Installation

Install with [Summon](https://github.com/ai-summon/summon):

```
summon install brainstorm
```

## Usage

Invoke the skill when starting any creative work — creating features, building components, adding functionality, or modifying behavior:

```
/brainstorm
```

Or simply describe what you want to build. The skill will be automatically invoked before diving into implementation.

## Brainstorm Documents

Each session produces a markdown document saved to `brainstorm/NN-topic-slug.md` with:

- **Problem Framing** — what's being explored and why
- **Approaches Considered** — options with pros and cons
- **Decision** — what was chosen and why
- **Open Threads** — unresolved questions for future exploration

Documents are tracked with a status: `active`, `parked`, `abandoned`, or `completed`.

## Key Principles

- **One question at a time** — never overwhelms with multiple questions
- **Multiple choice preferred** — easier to answer when possible
- **YAGNI ruthlessly** — removes unnecessary features from consideration
- **Explore alternatives** — always proposes 2–3 approaches before settling
- **Incremental validation** — presents sections and gets approval before moving on

## Acknowledgements

Inspired by [Superpowers](https://github.com/obra/superpowers) and [Spex](https://github.com/rhuss/cc-spex).

## License

[MIT](LICENSE)
