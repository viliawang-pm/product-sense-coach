# Product Sense Coach

[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-compatible-blue)]()
[![License](https://img.shields.io/badge/license-MIT-green)]()

A thinking partner for product managers. Before you build a Demo, Website, or App, this skill helps you articulate the intuition behind your idea, sharpen problem definition, and find the fastest path to validation — through guided conversation, not interrogation.

## What It Does

When you share a product idea, the skill walks you through five natural conversations:

| Conversation | Core Question | What You Get |
|-------------|--------------|-------------|
| **The Origin Story** | What did you observe that others missed? | A clear articulation of your core insight |
| **The Opportunity Space** | How big could this be? | A feel for the scale and shape of the market |
| **The First 100 Users** | Who shows up on Day 1? | A tangible growth path starting from real people |
| **The Movie Scene** | Walk me through a user's experience | Vivid, second-by-second usage scenarios |
| **The Landscape** | Who else has tried, and what can we learn? | Competitive intelligence framed as learning |

The output is a **Clarity Map** — not a judgment of whether your idea is good or bad, but a clear picture of what you already understand and where to dig deeper.

## Philosophy

Inspired by the product thinking of Zhang Xiaolong (WeChat), this skill emphasizes:

- **Human nature first** — great products satisfy emotional needs, not just functional ones
- **Simplicity as discipline** — find the "one-action moment" that captures your product's essence
- **Trust the user** — design simple rules and let behavior emerge

## Install

**Option 1: Global install (all projects)**

```bash
git clone https://github.com/viliawang-pm/product-sense-coach.git
cp -r product-sense-coach ~/.codebuddy/skills/
```

**Option 2: Project-level install**

```bash
git clone https://github.com/viliawang-pm/product-sense-coach.git
cp -r product-sense-coach .claude/skills/
```

## Usage

In any conversation with your AI coding assistant, say something like:

> "Use the product-sense-coach skill. I want to build a mini-program that shows
> nightclub events on a map, filterable by music genre. Help me think this through."

Or simply describe your idea — if the skill is installed, it will guide the conversation naturally.

## Example

**You say**: "I want to build an app where neighbors can share homemade food."

**The skill responds**: "I love that you're thinking about food and community together — those are two deeply human things. What made you think of this? Was there a specific moment where you wished this existed?"

**You reveal**: "Last Sunday I made way too much curry and my neighbor mentioned she hates cooking for one person."

**Together you arrive at**: "I noticed that single people living alone often cook too much or don't cook at all, while their neighbors are in the exact same situation. There's an opportunity to turn apartment buildings into informal dinner communities."

The skill then guides you through market sizing, growth paths, usage scenarios, and competitive landscape — all in a supportive, curiosity-driven tone.

## License

MIT
