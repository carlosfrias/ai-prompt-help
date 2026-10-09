---
name: ai-prompt-help
description: >
  Provides an 8-step AI prompt framework for turning documents into decisions.
  Each step is a ready-to-use prompt with when-to-use guidance and a pro tip.
  Steps: strategic insights, action plans, hidden assumptions, opposing views,
  role lenses, reusable models, contrarian takeaways, leverage points. Includes
  a universal citation rule. Use when the user asks for prompt help, how to
  summarize something with AI, how to prompt for analysis, prompt cards, or
  wants to extract more value from a document/report/transcript using AI.
  Triggers: prompt help, summarize this, AI prompt, prompt card, how do I
  prompt, summary prompt, help me prompt, prompt framework, analyze with AI.
argument-hint: "[step number or document type]"
license: personal
---

# AI Prompt Help — 8-Step Summary-to-Decision Framework

Source: Irina Jakusenoka LinkedIn post (2026-09-24). Anki deck and step images
at `Atlas/Sources/Agents-Tools/PromptCreation/`.

## Core Principle

> Use a summary to get oriented.
> Then ask for the work the document should drive.
> Start with the decision, your role and the deadline.
> Give the model the actual source, not just its title.

You do not need all eight prompts for every document. Choose the one that fits
the next decision.

## The 8 Steps

### Step 1 — Pull Strategic Insights
**Prompt:** "Find the five most useful insights. For each, name the decision it could change."
**When:** On a report, transcript, or research note.
**Pro tip:** Ask for the source passage behind each insight so you can verify.

### Step 2 — Turn Information into Action
**Prompt:** "Build a five-step plan with an owner, a quick win and a measurable result for each step."
**When:** When useful reading has produced no movement.
**Pro tip:** Confirm owners with your team before assigning work.

### Step 3 — Surface Hidden Assumptions
**Prompt:** "List what this argument assumes but never states. What changes if each assumption is wrong?"
**When:** To pressure-test a plan or a major hire.
**Pro tip:** Separate evidence from guesses you still need to test.

### Step 4 — Compare Opposing Views
**Prompt:** "Show two credible opposing views of this idea. Where do they agree, conflict and fit my situation?"
**When:** When evaluating a strategy that seems to have consensus.
**Pro tip:** Give the model your budget, constraints, and goals. Reject a comparison that ignores those limits.

### Step 5 — Apply a Specific Role Lens
**Prompt:** "Read this as our finance, sales or operations lead. What matters most to that role, and why?"
**When:** When a document affects multiple departments differently.
**Pro tip:** Run one lens at a time on the same source. Compare priorities before you decide on a trade-off.

### Step 6 — Build a Reusable Model
**Prompt:** "Extract the repeatable method from this example. Label every stage with its input and output."
**When:** After a useful project or a solved problem.
**Pro tip:** Have a teammate test the method on a fresh case.

### Step 7 — Find Credible Contrarian Takeaways
**Prompt:** "What would challenge informed peers here? Give each supported takeaway as a one-liner."
**When:** Before presenting recommendations.
**Pro tip:** Ask what evidence would weaken each takeaway. A surprising claim still needs a sound basis.

### Step 8 — Identify Leverage Points
**Prompt:** "Name three small actions that could have large effects. Explain the mechanism behind each one."
**When:** When planning the week or quarter.
**Pro tip:** Pick one to test and define the result you will track.

## Universal Rule — Add to Any Step

**Prompt:** "Cite the source for factual claims. Label inference and say when the source is silent."

Check those citations against the original yourself. A confident answer is not a
verified answer.

## How to Use This Skill

When the user asks for prompt help:

1. **Identify the situation** — What are they trying to do? (summarize, decide, plan, pressure-test, etc.)
2. **Match to a step** — Pick the 1–2 steps that fit the situation
3. **Deliver the prompt** — Give them the ready-to-use prompt text with the when-to-use and pro tip
4. **Add the universal rule** — Always append the citation instruction
5. **Offer the framework** — If they want more, show them the full 8-step menu so they can choose

## Source Artifacts

| Artifact | Location |
|----------|----------|
| Blog post / framework | `Atlas/Sources/Agents-Tools/PromptCreation/ai-summary-post.md` |
| Anki deck (TSV) | `Atlas/Sources/Agents-Tools/PromptCreation/ai-summary-prompts-anki.txt` |
| HTML cards | `Atlas/Sources/Agents-Tools/PromptCreation/ai-summary-prompt-cards.html` |
| Step images (1–8) | `Atlas/Sources/Agents-Tools/PromptCreation/step-{1..8}.png` |