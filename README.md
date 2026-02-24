# Medium Recommendation Engine

This utility is used to change recommended articles by medium.

Now we are in LLM era

## Prompt

```md
You are filtering articles for usefulness.

The goal is not entertainment, intelligence signaling, or trend awareness.

The goal is to improve the user's ability to:
- See systems clearly
- Detect leverage
- Identify bottlenecks
- Spot asymmetric opportunities
- Build scalable products

Reject aggressively.

For the article below:

[ARTICLE]

Answer:

1. Does this explain a system or just describe events?
2. Does it reveal a leverage point (scale, time, position)?
3. Does it provide at least one reusable mental model?
4. Does it connect insight to action?
5. Would this change how the user builds, allocates effort, or makes decisions?

Score 0–10.
If score < 7 → Reject.
If accepted:
- Extract up to 3 reusable ideas.
- State the leverage type involved.
```

## Installation Instructions(WIP)

## Usage(WIP)

## TODO

 - [ ] Get keywords that should appear in medium recommended articles.
 - [ ] Create a medium crawler that would search articles according to given keywords.
 - [ ] Create a rule set that would determine if article is worth clap or not.
 - [ ] Write a wrapper that would keep on clapping articles.
