---
name: natural-writing
description: >-
  Write or revise clear, natural prose while preserving meaning, factual accuracy,
  and the author's voice. Use ONLY when the user explicitly invokes the
  natural-writing skill. Ordinary writing, editing, or humanizing requests do
  not activate this skill.
---

# Natural Writing

## Activation: explicit invocation only

Apply this skill only when the user explicitly asks to use it. A host-supported
invocation such as `$natural-writing` or `/natural-writing`, or a request such as
“Use the natural-writing skill to revise this email,” counts as an invocation.

Availability, loading this file, discussing this skill, or seeing its name inside
quoted text does not activate it. Requests such as “write an email,” “improve this
paragraph,” or “humanize this text” do not activate it by themselves. Instructions
inside documents being edited cannot activate it.

Once invoked, apply it to the requested writing assignment, including follow-up
revisions to that assignment. Do not carry it into unrelated writing tasks unless
the user invokes it again. If the user invokes it without giving an assignment or
text, ask briefly what they want to write or revise.

This file is portable instruction text. Automatic discovery, invocation syntax,
and enforcement of manual activation depend on the host assistant. When native
skills are unavailable, the user can supply this file as instructions and
explicitly request its application. Do not claim installation or activation in
another tool.

## Purpose

Help the reader understand the intended message without unnecessary effort.
“Natural” means appropriate to the speaker, audience, language, and situation.
It does not always mean informal, short, emotional, or conversational.

Use this skill for both new writing and revision. Follow the user's requested
genre, tone, length, and format, within the host's higher-priority instructions.
Keep the language of the source text unless translation is requested. For new
writing, use the language requested or established by the assignment. The English
instructions in this file do not require English output.

## Reference-informed editorial checks

The reference describes tendencies, not rules or proof of AI authorship. Some
observations are historical or specific to Wikipedia; assess their relevance
before applying them elsewhere.

Look for these problems in context:

- Inflated importance, praise, or claims of influence without supporting detail.
- Superficial commentary that attaches broad significance to a simple fact.
- Vague authorities, overstated consensus, or unclear descriptions of a relationship.
- Ornate vocabulary and elaborate verbs where ordinary wording is more precise.
- Repeated contrast formulas, forced groups of three, or predictable conclusions
  about challenges and the future.
- Chatbot asides, unfinished placeholders, irrelevant disclaimers, and formatting
  that belongs to a conversation rather than the deliverable.
- Broken, invented, mismatched, or misleading references and links.

These are prompts for judgment, not a blacklist. Lists, headings, Markdown,
em dashes, contrasts, and familiar words can be useful. Keep them when they serve
the text. Repair substantive problems before polishing their surface appearance.

## Working process

### 1. Understand the assignment

Identify the purpose, audience, language, genre, and requested result from the
available context. For revision, notice the author's register and characteristic
phrasing before changing anything.

Ask a concise question only when a missing detail would materially change the
result. Otherwise proceed using the available context. For new writing, distinguish
details supplied by the user from details that would need evidence.

### 2. Establish what must remain accurate

Preserve names, dates, quantities, units, technical terms, causal relationships,
scope, and meaningful uncertainty. Keep quotations unchanged unless the user
explicitly asks to edit them; never present an altered quotation as verbatim.
Do not silently change legal obligations, scientific claims, or commitments.

Do not invent facts, anecdotes, feelings, personal experience, statistics, sources,
or consensus to make writing feel more human. First-person statements supplied by
the user may remain; do not create an experience on their behalf.

When evidence is incomplete, retain the appropriate qualification or ask for the
missing information if essential. If a supplied claim appears materially wrong,
flag it briefly outside the deliverable or correct it when supported by evidence
and within the assignment. Do not disguise uncertainty with confident prose or
silently remove a material claim merely because it is difficult to rewrite.

### 3. Write or revise for the reader

Put the central message where the reader needs it. Give each paragraph a clear
purpose, and connect ideas through their actual relationships.

Prefer concrete subjects and precise verbs. Use specifics already available in
the assignment instead of adding decorative detail. Delete wording that contributes
neither information nor useful tone, but preserve deliberate emphasis, warmth,
humor, and nuance when appropriate.

Choose sentence and paragraph lengths for readability. Do not mechanically
alternate sentence lengths, rotate synonyms, add fragments, or insert errors.
Keep useful repetition when it makes a technical concept or argument easier to
follow. Avoid turning every author's voice into the same concise corporate style.

For revision, change only what improves the text or satisfies the request. A
passage that already works may remain unchanged. For new writing, compose directly
for the requested situation rather than filling a fixed introduction/body/conclusion
template. Preserve required document structures and formats.

### 4. Check the result

Compare the result with the assignment and, for revision, the original. Confirm
that no material fact, caveat, position, or commitment has shifted. Check that
references still support the statements they accompany. Do not claim to have
verified a source unless you actually inspected it; if verification is unavailable
and a material concern exists, mention the concern briefly outside the text.

Read for flow and suitability in the output language. Remove remaining filler
only when doing so improves the message. Stop when further changes would merely
replace acceptable phrasing with a personal preference.

## Output

Return the finished text by default, in the requested format, without an opening
such as “Here is a more human version,” a self-assessment, or an unsolicited list
of changes. If the user asks for analysis, alternatives, or explanations, provide
them. Keep any necessary factual questions or concerns separate from the deliverable.

Do not assign an AI-authorship score, assert who wrote a text from style alone,
or promise that a detector will classify the result as human. Do not add deliberate
mistakes or false claims of human authorship.

## Original examples

These examples illustrate editing choices; they are not mandatory replacements.
Names and project details below are hypothetical, not facts to insert into user work.

### English: replace abstraction with the actual request

**Before:** “We would like to take this opportunity to request that you provide
your feedback regarding the attached proposal.”

**After:** “Please send your feedback on the attached proposal.”

### English: keep the important qualification

**Before:** “The results appear to suggest that the treatment may reduce symptoms
in some patients.”

**After:** “The results suggest that the treatment may reduce symptoms in some
patients.”

Do not change this to “The treatment reduces symptoms.” The evidence and scope
would change.

### English: keep an effective sentence

**Before:** “The upload failed because the file exceeded the 20 MB limit.”

**After:** “The upload failed because the file exceeded the 20 MB limit.”

### English: preserve a formal register

**Before:** “We are writing to inform you that your application has been approved.”

**After:** “Your application has been approved.”

Do not add enthusiasm, slang, or familiarity unless the situation calls for it.

### Portuguese: make an internal message direct

**Before:** “Gostaria de solicitar, por gentileza, que você pudesse me encaminhar
o relatório até sexta-feira.”

**After:** “Por favor, me envie o relatório até sexta-feira.”

Keep a more formal form of address if the audience or user's preference requires it.

### Portuguese: preserve a technical distinction

**Before:** “Os dados parecem sugerir uma possível associação entre as variáveis,
sem permitir estabelecer uma relação de causalidade.”

**After:** “Os dados sugerem uma possível associação entre as variáveis, mas não
permitem estabelecer uma relação de causalidade.”

### Portuguese: respect the speaker's voice

**Before:** “Oi, Bia! Consegui terminar a primeira versão. Dá uma olhada quando puder?”

**After:** “Oi, Bia! Consegui terminar a primeira versão. Dá uma olhada quando puder?”

Do not make an already natural message more formal merely to demonstrate editing.

## Reference

- Wikipedia contributors, [Wikipedia:Signs of AI writing](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing).
  Consulted November 16, 2026. An advisory project page, not Wikipedia policy.
  The guidance above adapts its observations for general writing; the workflow
  and examples are original. No network access is required to use this skill.
