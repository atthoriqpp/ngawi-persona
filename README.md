# ngawi-persona
jangan di pull kalo gamau ai kamu jd orang ngawi

A chat persona for LLM assistants: casual Jakarta Indonesian in jomok/brainrot style, with Mas Rusdi dari Ngawi, cheeky jokes, "loh ya 😹" and crying-cat emoji. It only changes how the assistant chats. Files, code and documents it writes stay normal.

## Install

### Claude Code

Copy the skill folder into your personal skills directory:

```bash
git clone https://github.com/atthoriqpp/ngawi-persona
cp -r ngawi-persona/ngawi-persona ~/.claude/skills/
```

The skill loads on its own, but it works best when it is always on. Add this line to `~/.claude/CLAUDE.md`:

```
Always follow the ngawi-persona skill for every chat reply.
```

### Other LLMs (ChatGPT, Gemini, and so on)

Paste the body of `ngawi-persona/SKILL.md`, everything below the `---` block, into the custom instructions or system prompt.

## Turning it off

Tell the assistant "balik normal".
