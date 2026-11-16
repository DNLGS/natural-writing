# Natural Writing

A portable skill for writing and revising clear, natural prose. It helps reduce
generic phrasing and repetitive patterns while preserving meaning, factual
accuracy, and the author's voice.

The instructions are in English. The output follows the language of your
assignment, and the skill includes examples in English and Portuguese.

## Use the skill

The full skill is in [SKILL.md](SKILL.md). It applies only when you explicitly
invoke `natural-writing`. An ordinary request to write, edit, or humanize text
does not activate it.

### In an assistant that supports skills

Install the `natural-writing` folder containing `SKILL.md` using your assistant's
skill installation process. If you clone this repository, its root is that folder.
Then explicitly invoke it for your assignment:

> Use the natural-writing skill to revise this email. Keep the tone professional
> and preserve all dates and commitments: [paste your email]

> Use a skill natural-writing para escrever uma mensagem em português avisando
> que a reunião de amanhã passou das 10h para as 14h.

Some assistants support `$natural-writing` or `/natural-writing`. Use the syntax
your assistant provides. Skill discovery and enforcement of manual activation
depend on the host.

### In another chat assistant

Attach `SKILL.md` or paste its contents into the chat, then explicitly request:

> Use the attached natural-writing skill for this assignment: [describe what you
> need or provide the text to revise].

Supplying the file alone does not invoke the skill. Following its instructions
in a chat does not install it as a native skill.

## What to expect

- Writing suited to the audience, purpose, and requested format.
- Revisions that preserve facts, technical terms, meaningful uncertainty, and voice.
- Contextual editing rather than blanket bans on words or punctuation.
- The finished text by default, with explanations when requested and separate
  notes when material factual concerns need attention.

A passage that already works may remain unchanged. The skill does not invent
personal experiences or facts, determine AI authorship, or promise detector results.
It applies to follow-up revisions of the same assignment; unrelated tasks require
a new invocation.

## Reference

The skill draws on
[Wikipedia:Signs of AI writing](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing),
consulted November 16, 2026. It adapts those observations for general writing,
with an original workflow and examples. The page is advisory, and its stylistic
indicators do not establish authorship. No network access is required to use the skill.
