# The Bitter Lesson, Applied

**Date:** January 2025
**Author:** B

## The Insight

Rich Sutton's "Bitter Lesson" from AI research: general methods that scale with computation always win over hand-crafted domain-specific approaches. Every time researchers tried to bake in human knowledge, they eventually got beaten by simpler systems with more compute.

This applies directly to how we build.

## What This Means for BroSki

The wrong approach:
- Hard-code "Alta's Baldy Chutes hold powder until 11am"
- Build a database of tips per resort
- Hand-craft rules for each mountain
- Create resort-specific modules

The right approach:
- Build a *general system* that can become a local guide for ANY mountain
- Trust the AI to synthesize knowledge dynamically from whatever's out there
- Let it scrape, search, reason, and figure it out at runtime
- The "local knowledge" isn't stored—it's *discovered*

## Why This Matters

1. **Scalability**: Works for Alta, Jackson Hole, some random hill in Michigan—without us coding each one
2. **Freshness**: Always pulling current info, not stale hard-coded tips
3. **Riding the wave**: As AI gets better, our general system gets better for free
4. **Less maintenance**: No database of 500 resorts to maintain

## The Philosophical Stance

As AI-native builders, our job isn't to encode knowledge. It's to build systems that *find and synthesize* knowledge. We're not competing with the AI's capabilities—we're leveraging them.

Bake in as LITTLE hard-coded information as possible. Trust that more compute and better models will solve most problems.

This is maybe the most important mindset shift for building in this era.

## Practical Implications

When you're tempted to add a special case, a hardcoded rule, a manual database—stop and ask:

> "Can I instead build something general that figures this out dynamically?"

Usually the answer is yes. And that's the better path.
