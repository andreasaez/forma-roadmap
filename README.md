# forma-roadmap
A Claude skill for turning a messy backlog into a structured, outcome-based roadmap and the stakeholder communication to match

Forma Roadmap
A Claude skill for product managers who need to turn a messy backlog into a structured roadmap and communicate it in a way that earns buy-in.

Paid. Available on Gumroad: https://dreasaez.gumroad.com/l/forma-roadmap

---

## The problem

Most roadmaps are feature lists with dates attached. Leadership sees a backlog. Engineers see a task queue. Sales sees promises. Nobody sees a strategy.

The problem is structural. Features get prioritised before opportunities are understood. Opportunities get listed before themes are defined. And themes exist without objectives — so nobody knows what success looks like or why one thing comes before another.

This skill fixes the structure first, then builds the communication layer on top of it.

---

## What you get

- A structured workflow for organising your backlog into themes, objectives, opportunities, and ideas
- A Now/Next/Later roadmap sequenced by strategic priority and discovery status
- Three stakeholder outputs: roadmap document, narrative brief, and presentation structure
- Framing that connects every roadmap decision back to business outcomes

---

## Standalone vs. with Forma PM

There is an important distinction in how this skill works depending on what context is available.

**Without Forma PM:** the skill structures and maps your existing judgment. It organises your backlog, defines the hierarchy, and sequences based on what you tell it — active work goes to Now, discovery work goes to Next, everything else to Later. The value is structural clarity, not independent prioritisation.

**With Forma PM:** the skill makes independent prioritisation recommendations. Your positioning canvas tells it which opportunities reinforce your differentiation. Your ICP tells it whose problems matter most. Every sequencing decision comes with an explanation tied to those inputs. The value is structural clarity plus prioritisation intelligence.

If you want the full system, buy both.

- Forma PM: [Gumroad](https://andreasaez.gumroad.com/l/enwoc)
- Forma Roadmap: [Gumroad](https://andreasaez.gumroad.com/l/enwoc)

---

## How to install

1. Create a new Claude project
2. Upload `skill.md` as a knowledge file
3. If you have Forma PM, also upload your `positioning.md` and `icp.md` outputs as knowledge files in this project
4. Paste your raw backlog to start

---

## What you need before you start

- A raw backlog — a list of ideas, feature requests, bugs, and initiatives in any format
- A rough sense of your current strategic priorities (even informal is fine — Claude will help you sharpen them)
- Optionally: your Forma PM positioning and ICP outputs for richer prioritisation

---

## The methodology

**Backlog items are ideas.** They are not roadmap items until they are connected to an opportunity.

**Opportunities explain why something matters.** An opportunity is a user problem, a market gap, or a capability constraint. It is specific and observable — not a strategic ambition.

**Themes group opportunities.** A theme is the product area or domain the opportunity lives in. It is a lens for organising work, not a deliverable.

**Objectives measure theme success.** Each theme has one or two objectives — measurable outcomes that define what winning looks like in that area.

**Now/Next/Later sequences the work:**
- Now — ideas in active implementation
- Next — ideas in discovery or moving into discovery
- Later — ideas that are in scope but not yet prioritised

---

## Repo structure

```
stakeholder/
  README.md     ← you are here
  skill.md      ← load this into your Claude project
```

---

## Part of the Forma library

[getforma.co](https://getforma.co) — Claude skill bundles for product managers, CS teams, developers, and writers.

