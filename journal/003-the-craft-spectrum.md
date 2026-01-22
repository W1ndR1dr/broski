# The Craft Spectrum: Care vs. Yolo

**Date:** January 2025
**Author:** Brian + Claude

## The Premise

There are extraordinary AI-native builders and shitty ones. Same tools, vastly different outputs. The difference isn't technical skill—it's *craft*.

```
Shitty Vibe Coding                          Extraordinary AI Building
      │                                              │
      ▼                                              ▼
┌─────────────────────────────────────────────────────────────────┐
│ Accept       Copy/paste    No        "It works"   Accumulating  │
│ first        without       iteration  = done      tech debt     │
│ output       understanding                                      │
├─────────────────────────────────────────────────────────────────┤
│ Push back    Understand    Iterate    "It's       Building      │
│ on weak      what you're   until      actually    something     │
│ output       shipping      it's RIGHT good"       lasting       │
└─────────────────────────────────────────────────────────────────┘
```

Both ends of this spectrum can ship working software. The difference shows up later—in maintainability, in edge cases, in whether you actually understand what you built.

## What "Shitty Vibe Coding" Looks Like

- Prompt → accept → ship → repeat
- Copy/pasting code you don't understand
- "It compiled so it's probably fine"
- Debugging by asking the AI to fix it without understanding why it broke
- Building features on top of features without coherent architecture
- Speed as the only metric

This works... until it doesn't. You end up with a codebase no one understands, fragile to changes, full of hidden bugs. And you've learned nothing.

## What "Care" Looks Like

- **Pushing back**: "That's not quite right, here's why..."
- **Understanding**: If you can't explain what the code does, you don't ship it
- **Iterating**: The first version is a draft, not the answer
- **Quality bar**: "Does it work?" is the floor, not the ceiling
- **Coherence**: Every addition should make the whole simpler, not more tangled

Care takes longer. It's worth it.

## The Taste Problem

How do you know if output is good or mediocre? This is the hard part.

Taste develops through:
- **Comparison**: Generate multiple approaches, evaluate tradeoffs
- **Failure**: Ship something, watch it break, understand why
- **Reading**: Study good code, good design, good writing
- **Feedback**: Show work to others, absorb their reactions
- **Reflection**: "What would make this better?" asked repeatedly

You won't have taste on day one. That's fine. The goal is to *develop* taste through deliberate practice. This repo is part of that practice.

## Signs You're on the Right Path

- You reject AI output sometimes (maybe often)
- You can explain *why* you chose one approach over another
- You notice when something feels off, even if it "works"
- You're bothered by code you don't understand
- You spend more time thinking than typing

## Signs You're Slipping

- Everything the AI produces seems good
- You're shipping fast but can't explain how things work
- Problems keep recurring in similar forms
- You feel like you're assembling LEGO, not building
- Speed is your main source of pride

## The Counter-Intuitive Truth

Going slower *feels* less productive but *is* more productive.

The yolo path ships features fast, then spends 3x the time debugging, rewriting, and fighting the mess. The careful path ships features slower, but they work, they last, and you understand them.

**Slow is smooth. Smooth is fast.**

---

## Discussion: Where's the Balance?

**Brian's take:**
Care > speed in almost all cases. The compound interest of understanding what you build is enormous. But there's probably room for "sketch mode"—quick experiments where you're explicitly not trying to build something lasting, just exploring.

**Claude's pushback:**
The sketch vs. ship distinction is key. Not everything needs craft—throwaway prototypes, learning experiments, proof-of-concepts. The mistake is treating shipping code like sketch code. Know which mode you're in.

**Synthesis:**
Maybe the rule is: *know your mode*.
- **Sketch mode**: Speed matters, understanding optional, output is disposable
- **Ship mode**: Care matters, understanding required, output must last

The trap is accidentally being in sketch mode when you think you're shipping.
