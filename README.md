# Retention Hook Writer Skill

Turn flat scripts into high-retention voiceovers with stacked hooks, natural spoken rhythm, and soft-ad pacing.

This is a Codex skill for creators, marketers, indie hackers, and scriptwriters who want short-form content that sounds like a real person talking, not a polished essay. It is especially strong for Chinese voiceovers, TikTok/Reels/YouTube Shorts scripts, soft ads, creator monologues, product videos, and emotional storytelling.

The skill focuses on:

- 12 hook types: suspense, fear, desire, identity, number, comparison, conflict, hot-topic, urgency, interaction, progress, and easter-egg hooks.
- Hook stacking across the whole script, not just the first line.
- Spoken Chinese that sounds human, casual, and emotionally specific.
- Soft ads where the product enters naturally instead of sounding like a pitch.
- Retention pacing: hook, tension, value, payoff, and loop.

## Why Try It

Most scripts only have one hook at the beginning. Then the middle goes flat.

This skill treats a script as a retention system. It adds fresh hooks at the opening, transitions, examples, payoff, and ending, so the viewer keeps getting small reasons to continue.

Example:

```text
Identity hook: 你有没有遇到过这种人？
Conflict hook: 他说得没错，但你就是很累。
Progress hook: 这件事有 3 个处理办法。
Easter-egg hook: 最后一个办法有点幼稚，但真的有用。
Soft CTA: 不一定解决人生，但能让你轻松几分钟。
```

## Install

Copy the skill folder into your Codex skills directory:

```bash
cp -R retention-hook-writer ~/.codex/skills/
```

Then invoke it in Codex:

```text
Use $retention-hook-writer to rewrite this voiceover with stronger hooks and a more conversational Chinese style.
```

## Example Prompts

```text
Use $retention-hook-writer to rewrite this script into a 60-second Chinese voiceover. Make it more conversational, add stacked hooks, and keep the product placement very soft.
```

```text
Use $retention-hook-writer to create 10 opening hooks for this topic, then write a 3-minute script with hook stacking every 30 seconds.
```

```text
Use $retention-hook-writer to make this soft ad sound less like an ad and more like a friend talking.
```

## What It Produces

When useful, the skill can output:

- Hook options
- Recommended hook
- Full script
- Hook map
- Visual rhythm
- Caption beats
- Soft CTA variants

## Skill Folder

The installable skill is:

```text
retention-hook-writer/
├── SKILL.md
├── assets/
│   └── icon.svg
└── agents/
    └── openai.yaml
```
