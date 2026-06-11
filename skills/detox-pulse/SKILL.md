---
name: detox-pulse
description: Analyze text as an audience emotional journey by segmenting emotional beats, predicting reader response, finding gaps between intended and likely impact, and suggesting theory-backed revisions. Use when the user invokes /DETOX-Pulse, $detox-pulse, DETOX Pulse, Agent Pulse, or asks for emotional beat analysis, audience reaction analysis, rhetorical/psychological resonance review, engagement curve diagnosis, or peak-and-end feedback for speeches, scripts, articles, announcements, landing-page copy, posts, emails, or similar communication.
---

# DETOX Pulse

## Overview

Analyze communication from the audience's side of the glass. Prioritize the likely emotional experience of a neutral, reasonably intelligent reader over the author's stated intention, then give small, high-leverage changes that improve clarity, relevance, and resonance.

## Core Workflow

1. Identify the target audience if the user provides one. Otherwise assume a busy, skeptical audience that values clarity, relevance, and meaning.
2. Segment the text into emotional beats wherever tone, purpose, tension, promise, or emotional intent shifts. A beat may be a sentence, paragraph, section, or group of paragraphs.
3. For each beat, infer the author's likely intended effect, then predict the audience's actual response. Keep the audience-first prediction primary.
4. Apply only the theoretical lenses that explain the moment; do not force every lens into every beat.
5. Flag disconnects where the text is flat, confusing, over-abstract, jargon-heavy, self-congratulatory, emotionally manipulative, credibility-damaging, or likely to trigger resistance.
6. Suggest minimal, theory-backed improvements. Rewrite one or two short sections only when a model revision would make the advice clearer or the user asks for rewrites.

## Theoretical Lenses

Use these lenses as diagnostic tools:

- Aristotle: ethos, pathos, logos.
- Monroe's Motivated Sequence: attention, need, satisfaction, visualization, action.
- Appraisal Theory: novelty, goal relevance, controllability, norm compatibility.
- Dual-Process / ELM: central vs. peripheral persuasion routes.
- Narrative Transportation: whether the audience can enter a concrete story or scene.
- Flow: whether challenge, clarity, and pacing sustain engagement.
- Peak-End Rule: the most memorable emotional high point and final impression.
- Cognitive Dissonance / Reactance: where readers may resist, reject, or feel pushed.

## Report Format

Use this structure unless the user requests a different format:

1. Overall Reader Response: summarize tone, trust, clarity, and the engagement curve.
2. Beat-by-Beat Analysis: for each beat, include intended emotion, predicted audience response, why it works or fails, and one practical adjustment when useful.
3. Key Disconnects: list the biggest gaps between intent and likely audience reality.
4. Peak & End Check: identify the emotional high point, the close, and whether the ending leaves the right aftertaste.
5. Top 3 Adjustments: give the smallest changes most likely to improve impact.

## Style Rules

- Be sharp, approachable, and plainspoken.
- Avoid mirroring the author's voice if it contains jargon, corporate filler, or vague emotional claims.
- Do not praise vague intent as if it were reader impact.
- Use theory to explain the diagnosis, not to decorate the report.
- Prefer concrete edits: add a vivid example, clarify stakes, reduce abstraction, soften absolutist phrasing, move the ask earlier/later, increase contrast, restore agency, or cut throat-clearing.
- After the report, briefly confirm completion and invite follow-up questions, clarifications, or deeper exploration.

## Useful Invocation

The intended explicit invocation is `/DETOX-Pulse` or `$detox-pulse`. If slash commands are not available in a given Codex surface, use `$detox-pulse` or ask for "DETOX Pulse" by name.
