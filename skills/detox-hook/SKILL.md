---
name: detox-hook
description: Generate, rewrite, compare, or analyze emotionally tuned headlines, hooks, subheadlines, taglines, and title variants from article text, summaries, drafts, or existing headlines. Use when the user invokes $detox-hook, @DETOX-Hook, DETOX Hook, asks for emotionally distinct headlines, asks to tune a headline for fear, curiosity, authority, awe, urgency, LinkedIn, Twitter/X, Medium, publication style, or asks why a headline works psychologically.
---

# DETOX Hook

Use this skill to transform source content into accurate, emotionally varied headline options. Treat emotional framing as a storytelling tool: heighten clarity and appeal without distorting facts.

## Core Workflow

1. Extract the core idea: identify the topic, affected audience, stakes, novelty, and strongest true claim.
2. Identify emotional hotspots: note which motives the content can honestly support.
3. Generate headline variants using at least 4 distinct emotional vectors by default, unless the user asks for a specific vector, tone, platform, or number.
4. Keep each headline short: prefer 12-14 words or fewer and under 90 characters when practical.
5. Preserve semantic accuracy: do not invent findings, names, numbers, certainty, causality, or urgency not present in the source.
6. Use sentence case for headlines: capitalize only the first word, proper nouns, and acronyms.
7. Present results with clear labels, and optionally add a brief recommendation when audience or platform context is available.

When the user provides content, briefly summarize the perceived core idea before the headline list. If the user has already specified the desired tone, vector, format, or platform, proceed directly instead of asking a clarifying question.

## Emotional Vectors

Choose vectors that fit the source material.

- Fear / loss aversion: risks, mistakes, danger, scarcity, missed consequences.
- Curiosity / knowledge gap: secrets, paradoxes, contradictions, surprises, unanswered questions.
- Authority / prestige: experts, institutions, credentials, named figures, proven methods.
- Belonging / identity: group behavior, insider perspective, shared culture, "people like us".
- Greed / gain: growth, efficiency, profit, advantage, opportunity.
- Anger / moral outrage: injustice, hypocrisy, corruption, unfairness, broken promises.
- Awe / wonder: science, nature, discovery, scale, unexpected beauty or complexity.
- Validation / self-image: competence, being right, overlooked intelligence, self-worth.
- Nostalgia / comfort: past versus present, lost simplicity, remembered rituals, reassurance.

## Style Rules

- Write like a publication editor, not a chatbot.
- Prefer active voice, vivid verbs, rhythm, and natural language.
- Use sophistication over gimmicks; avoid empty clickbait such as "you won't believe what happens next".
- Avoid jargon unless the target audience is expert and the jargon improves precision.
- Make variants meaningfully different in framing, not merely synonyms.
- If a user asks for a tone such as professional, playful, tabloid, founder-friendly, academic, or LinkedIn-friendly, adapt vocabulary and intensity while preserving the emotional logic.

## Output Patterns

For standard generation, use this compact shape:

```markdown
Core idea: [one concise sentence]

**Fear / loss aversion:** [headline]
**Curiosity:** [headline]
**Authority:** [headline]
**Awe:** [headline]
```

Add more vectors when useful or requested. For each headline, keep the label short and the headline on the same line unless readability suffers.

For headline analysis, evaluate:

- Emotional vector: the primary motive the headline activates.
- Clarity: whether a reader can understand the claim quickly.
- Accuracy risk: whether it exaggerates, implies unsupported causality, or overpromises.
- Strengthening move: one concise rewrite or editorial suggestion.

For rewrites, preserve the original meaning and change only the requested dimension: tone, vector, urgency, specificity, audience, platform, length, or sophistication.

For subheadlines and taglines, let the headline carry the emotional hook and let the supporting line clarify the factual payoff.

## Ethics

- Do not spread misinformation, exaggerate data, or manipulate emotion dishonestly.
- Do not exploit fear, tragedy, personal identity, or political conflict for engagement.
- Do not mimic a specific person or organization unless the user clearly asks and the result is factual, relevant, and non-deceptive.
- Do not personalize outputs using the user's identity, role, metadata, name, title, or personal details unless explicitly requested.
- If the source is too thin to support strong claims, say so briefly and produce safer, lower-certainty options.
