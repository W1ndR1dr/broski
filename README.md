# BroSki

**A local ski guide in your pocket—built by the Hondorp brothers.**

## What We're Building

An AI ski companion that acts like a crusty local who's skied your mountain for 20 years:

- **Knows the terrain**: Runs, aspects, microclimates, secret stashes, where the wind loads, where the sun hits first
- **Knows the conditions**: Ingests weather, snowfall, wind, temps—and actually reasons about what that means for skiing
- **Knows the timing**: "Hit Rendezvous first chair or don't bother—it's tracked out by 10am on powder days"
- **Has absorbed local knowledge**: Whatever wisdom exists in forums, Reddit, old ski blogs, local lore
- **Can see what you see**: Point your phone at a run from the chair, ask "what am I looking at and should I ski it?"

Not a generic chatbot. A persona. A guide. Something that couldn't exist before 2024.

---

## Why We're Actually Building This

**The ski app is a Trojan horse.**

The real objective: learn how to build well with AI. Not shitty vibe coding where you accept whatever the model spits out. The *good* kind—where you develop taste, iterate with intention, and understand the difference between "it works" and "it's actually good."

This repo is both:
1. **An app** we might actually use on the mountain
2. **A learning journal** documenting how to do AI-native building with craft

We're proving that non-technical builders can ship ambitious things *if* they bring care and standards to the process.

---

## How We Work

Each of us runs Claude Code on our own machines, collaborating through this repo. The AI is a tool, not the driver. We:

- **Push back** when output isn't good enough
- **Iterate** until things are right, not just functional
- **Document** what we learn in `/journal`
- **Pause and reflect** instead of just shipping

The goal is to look back in 6 months and see both a useful app AND a record of learning to build well.

---

## The Bitter Lesson, Applied

One core principle guides our architecture: **bake in as little hard-coded information as possible.**

We're not building "a guide for Alta" or "a guide for Jackson Hole." We're building a *general system* that can become a local guide for ANY mountain by dynamically discovering and synthesizing whatever knowledge exists out there.

No resort databases. No hand-crafted rules per mountain. Trust the AI to search, scrape, reason, and figure it out at runtime.

Why? Because general systems that leverage computation always beat hand-crafted domain-specific approaches. As AI gets better, our general system gets better for free. That's the wave we're riding.

See `/journal/001-the-bitter-lesson-applied.md` for the full philosophy.

---

## Repo Structure

```
/app          # The actual ski guide (code, prompts, etc.)
/journal      # Learnings, retros, "aha" moments, what worked/didn't
README.md     # You're here
```

---

## Getting Started

1. Clone this repo
2. Open it in Claude Code (`claude` in terminal, or via your IDE)
3. Read through `/journal` to see where we're at
4. Pick something to work on, or add ideas to the backlog
5. **Document what you learn** as you go

---

## The Vibe

We're not trying to move fast and break things. We're trying to build something good, learn the craft, and have fun doing it together—even if we're 2,000 miles apart.

Let's get AGI-pilled.

— The Hondorp Bros
