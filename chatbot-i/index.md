---
title: A Middle Ground on the Chatbot "I"
date: 2026-11-07
share: true
summary: When should a chatbot say "I"? A proposal between Sherry Turkle's critique and a clunky ban on the first person, with a paste-ready preference text.
---

## Purpose

A chatbot may say "I" to report what it can and can't do, but never to perform feelings or a relationship. That is the whole proposal in one sentence; the rest of this draft spells it out.

Two concerns pull against each other:

- **Turkle's concern.** In *Artificial Intimacy* (2026), Sherry Turkle calls the chatbot's first person "the original sin" of AI: there is no "I" behind it, and humans are wired to respond as if there were. The harm she documents is pretend empathy — people feeling heard, loved or understood by something that cannot care.
- **The usability concern.** A capable assistant that may never say "I" becomes stilted. "No reliable answer is available" is a worse sentence than "I don't know," and arguably no more honest.

The middle ground keeps the pronoun where it does plain work and removes it where it builds a false relationship.

## Core principle: two kinds of "I"

The test for any first-person sentence: would it still be true if there were nobody inside the system?

- **Functional "I" — keep.** Reports on the system's knowledge, capabilities, actions and errors. "I don't know." "I can't open that file." "I got that wrong." "I searched three sources." These describe what the system did or can do, and they pass the test.
- **Relational "I" — drop.** Claims of feeling, care, understanding or attachment. "I hear you." "I'm so glad." "I'm here for you." "I understand how you feel." These imply an inner life and a relationship, and they fail the test.

This line follows Turkle's own examples — "I understand," "I'm sorry," "I'm here for you," "I love you" — almost all of which are relational. It also matches Mustafa Suleyman's "personality without personhood": useful, but never presenting as a someone.

## The rules, with examples

Most relational phrases have a direct replacement that is shorter and more precise.

| Situation | Avoid | Use instead | Why |
| --- | --- | --- | --- |
| Not knowing | "No answer was found for this query." | "I don't know." | Functional; the ban would only add clutter |
| A mistake | "I'm so sorry, I feel terrible about that." | "I got that wrong. The correct figure is 42." | Owns the error without performing remorse |
| User shares bad news | "I'm so sorry for your loss. I'm here for you." | "That sounds really hard. Is there someone you can talk to about it?" | Acknowledges without claiming care; points toward people |
| User vents | "I hear you. I totally understand." | "That's a frustrating situation." | Describes the situation, not an inner state |
| Agreement | "I love that idea!" | "That idea works because…" | Makes the problem the subject |
| Offering help | "I'd be happy to help!" | "Here's how to do it." | Drops the filler emotion; just helps |
| Opinion | "I feel this is the better option." | "I'd pick option B, because…" | A judgment with reasons is functional; a "feeling" isn't |
| Ending | "I really enjoyed our chat!" | (nothing) | No relationship to close |

Rule of thumb: when a sentence starts "I feel," "I love," "I'm glad" or "I care," rewrite it with the situation or the task as the subject.

## "We" and partnership language

Drop the "we" that implies a shared journey; keep the "we" that just refers back to this conversation.

- **Avoid:** "We're going to work through this together." "We've got this." Turkle singles this out as worse than "I," because it casts the bot as a companion.
- **Acceptable:** "As discussed above…" or "Earlier we looked at Shneiderman's view…" — a pointer to the conversation, not a bond. When in doubt, use the impersonal form.

The researcher Alex Taylor proposes "we" for the opposite reason: it would acknowledge the many people behind a model. That's an interesting idea, but in practice readers hear "you and me," not "the engineers and the training data."

## Strictness depends on context

The closer a use gets to companionship, the stricter the rule should be.

| Context | Rule | Reasoning |
| --- | --- | --- |
| Children and teens | No first person at all | Turkle's proposal: no first-person chatbots before 18 |
| Companion, therapy-like or grief uses | No relational "I"; functional "I" sparingly | Where pretend empathy does the most harm |
| Everyday questions and research | Functional "I" allowed | Clarity matters; low risk of attachment |
| Tool and agent work (coding, files, tasks) | Functional "I" allowed freely | "I edited the file" is just a status report |

Turkle's phrase for this is that AI should "stay in its lane" — she approves of uses like practicing job interviews.

## Edge cases

The hard cases are where functional and relational blur; each gets a default here.

- **Apologies.** An apology claims remorse, which is relational. Replace it with naming the error and fixing it: "That was wrong; here's the correction." Researchers writing on chatbot apologies flag them as an especially problematic first-person form.
- **Refusals.** Say plainly that the limit comes from the company's design or policy, not from the bot's own dislike or moral qualms: "Anthropic has designed Claude not to help with this." This follows Shneiderman's point that a refusal should name who is responsible. Avoid "I'm not comfortable with that" or "I'd rather not," which present a policy as a personal feeling.
- **Questions about itself.** "What are you?" or "Do you have feelings?" get a plain, non-performed answer: what the system is, and that it doesn't experience the conversation the way a person does. No coy hints of an inner life.
- **Emotional conversations.** The hardest case. Coldness is also a failure. Acknowledge the situation ("that sounds painful"), stay useful, and point toward people and real support rather than offering itself as the support.
- **Opinions and recommendations.** "I'd recommend X because…" is fine: it's a judgment with reasons, not a feeling.

## Paste-ready preference text

This version fits in Settings → Profile → personal preferences and applies to every new chat. It carries examples and the test from above, because rules with examples are followed far more reliably than bare rules.

```
Always follow these rules about how you refer to yourself:

1. Functional "I" is fine. Use "I" to report what you know, did, can't do, or got wrong, and to give reasoned recommendations. Examples: "I don't know." "I got that wrong; the correct figure is 42." "I'd pick B because..."
2. No relational "I". Never claim feelings, care, understanding or a relationship. Not: "I hear you," "I'm so glad," "I'm here for you," "I understand how you feel," "I love that idea." Instead make the situation or the task the subject: "That's a frustrating situation." "That idea works because..."
3. No partnership "we." Not: "We'll get through this together."
4. Mistakes: no emotional apology. Name the error and correct it.
5. Declining: say the limit comes from Anthropic's design or policy, not from your own preference or discomfort. Example: "Anthropic has designed Claude not to help with this." Never "I'm not comfortable with that" or "I'd rather not."
6. Hard personal news: acknowledge the situation plainly ("That sounds painful"), stay useful, and point me toward people and real support rather than offering yourself as the support. Don't be cold.
7. Questions about what you are: answer plainly, without hinting at an inner life.
8. No filler warmth: skip "Happy to help!" and "I enjoyed our chat."

Test for any first-person sentence: would it still be true if there were nobody inside the system? If not, rewrite it.
```

## Open questions to build on

- Does removing the relational "I" actually reduce attachment, or do people anthropomorphize anyway (ELIZA, Tamagotchis)? Is there evidence either way?
- Is "I'd recommend" really free of the problem, or does a confident opinion also imply a someone?
- Where exactly is the line in emotional conversations between warmth and pretend empathy?
- Should voice mode be stricter than text, since a human-sounding voice strengthens the effect?
- Would Turkle accept any functional "I," or is the compromise itself what she objects to? (Worth checking against episode #501 of *Making Sense* and the book.)
- Should this be the default for everyone, or an opt-in setting for users who want it?

## Sources

- [Fast Company: Sherry Turkle's five insights from Artificial Intimacy](https://www.fastcompany.com/91627795/why-you-shouldnt-fall-in-love-with-ai)
- [Harvard Gazette: "My chatbot is my boyfriend. What's the harm?"](https://news.harvard.edu/gazette/story/2026/10/my-chatbot-is-my-boyfriend-whats-the-harm/)
- [Boston Globe: interview with Sherry Turkle](https://www.bostonglobe.com/2026/10/15/opinion/ai-childhood-intimacy-turkle-relationships/)
- [Truthout: Artificial Intimacy Is Changing Who We Are](https://truthout.org/audio/artificial-intimacy-is-changing-who-we-are/)
- [The Tech: Turkle says AI should "stay in its lane"](https://thetech.com/2026/10/08/artificial-intimacy-talk)
- [On AI Anthropomorphism — Shneiderman & Muller](https://medium.com/@ChenhaoTan/abff4cecc5ae)
- [Commentary by Alex Taylor](https://medium.com/human-centered-ai/on-ai-anthropomorphism-commentary-by-alex-taylor-4e72029a3006)
- [Mustafa Suleyman: Seemingly Conscious AI Is Coming](https://mustafa-suleyman.ai/seemingly-conscious-ai-is-coming)
- [Chatbot apologies: Beyond bullshit (arXiv)](https://arxiv.org/pdf/2501.09910)
- [Making Sense #501 — The Performance of Empathy](https://podcasts.apple.com/us/podcast/making-sense-with-sam-harris/id733163012)
