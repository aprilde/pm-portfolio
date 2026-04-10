# Weighted Scoring Prioritization Framework

A practical framework I use to evaluate and rank competing feature requests when there are more good ideas than capacity to build them. Built from real experience managing a backlog across multiple stakeholder groups (product, engineering, marketing, finance, and external partners).

## When to Use This

- Quarterly or sprint planning when you need to justify what gets built next
- Stakeholder alignment conversations where everyone has a "top priority"
- Evaluating a set of 5-20 feature candidates against each other

## The Framework

### Step 1: Define Your Scoring Criteria

Pick 4-6 criteria that reflect what actually matters for your product right now. These shift depending on company stage, team goals, and the planning horizon.

Here's a set I've used for a B2B2C marketplace platform:

| Criteria | Weight | Why It Matters |
|---|---|---|
| Revenue Impact | 30% | Does this directly drive new revenue or protect existing revenue? |
| User Pain Severity | 25% | How painful is the current experience? Are users dropping off, contacting support, or finding workarounds? |
| Strategic Alignment | 20% | Does this move us toward a stated company or product goal for this quarter/year? |
| Effort to Build | 15% | How much engineering, design, and QA time does this realistically take? (Inverse scored — lower effort = higher score) |
| Data Confidence | 10% | How strong is the evidence that this will work? Do we have user research, analytics, or A/B test results backing it up? |

**The weights aren't decoration.** Revenue impact at 30% vs. data confidence at 10% means you're explicitly saying "we'd rather bet on high-impact features with decent evidence than wait for perfect data." That's a product leadership decision, and it should be a conversation with your team — not a default.

### Step 2: Score Each Feature (1-5 Scale)

| Score | Meaning |
|---|---|
| 5 | Strong positive signal — clear data, high impact, directly tied to goals |
| 4 | Good signal — solid reasoning, some data to back it up |
| 3 | Moderate — reasonable case but gaps in evidence or unclear scope |
| 2 | Weak — speculative, nice-to-have, or unclear who it benefits |
| 1 | Minimal — low impact, misaligned with goals, or very high effort |

### Step 3: Calculate Weighted Score

`Weighted Score = (Revenue × 0.30) + (Pain × 0.25) + (Strategy × 0.20) + (Effort × 0.15) + (Data × 0.10)`

### Example: Scoring Three Features

Say you're deciding between these three:

| Feature | Revenue (30%) | Pain (25%) | Strategy (20%) | Effort (15%) | Data (10%) | **Weighted Score** |
|---|---|---|---|---|---|---|
| Smart waitlist notifications | 4 | 5 | 5 | 3 | 4 | **4.25** |
| Bulk upload tool for organizers | 3 | 4 | 3 | 4 | 3 | **3.40** |
| Social sharing from confirmation page | 2 | 2 | 4 | 5 | 2 | **2.85** |

Smart waitlist notifications win here — high pain, strong strategic alignment, and decent revenue signal. The bulk upload tool is a solid second because organizers feel real friction, even though the revenue case is less direct.

## What This Framework Doesn't Do

This is a starting point for conversation, not a replacement for judgment. A few things to watch for:

- **Dependencies matter.** A feature might score a 4.5 but require another team's API that won't be ready for six months. The score doesn't capture that — you need to layer in roadmap reality.
- **Effort estimates are guesses.** Engineers will refine these during grooming. Use T-shirt sizing (S/M/L/XL) early on and convert to a 1-5 score.
- **Stakeholder politics are real.** Sometimes the CFO's pet feature scores a 2.8 but still needs to get built. The framework helps you show what you're trading off when that happens.
- **Revisit the weights.** If your company shifts from growth mode to profitability, revenue impact might jump from 30% to 45%. The weights should evolve with your strategy.

## How I Use This in Practice

1. **Fill it out solo first** with my best estimates to get a rough stack rank
2. **Bring it to a cross-functional review** (eng lead, design, data) and adjust scores based on their input — this is where the real alignment happens
3. **Present the top 5-7 candidates** to leadership with the scoring visible, so the conversation is about tradeoffs, not opinions
4. **Keep a running backlog sheet** with scores updated quarterly as new data comes in

---

*Part of my [PM Portfolio](../README.md). Built from real prioritization work across event tech and marketplace products.*
