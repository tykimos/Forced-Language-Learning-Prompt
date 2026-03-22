# Forced Language Learning Prompt

**Learn a new language effortlessly — just by using AI.**

No textbooks. No flashcards. No dedicated study time. Just a single prompt that turns every AI conversation into a language lesson.

![Example](example.png)

## The Problem

You want to learn English (or any language), but:
- You don't have time for formal study
- You forget what you learned in classes
- You're afraid of making mistakes
- Traditional methods feel boring and disconnected from real work

## The Solution

Add one simple rule to your AI assistant, and **every conversation becomes a language lesson** — whether you're coding, writing, or just chatting.

```markdown
## Language Echo Rule
- When the user gives an instruction in **Korean**, first restate the instruction
  as a clear, correct English sentence, then proceed with the task in Korean.
- When the user gives an instruction in **English**, first show a refined/corrected
  version of the English sentence, then proceed with the task in Korean.
```

## How It Works

### You write in Korean → AI echoes it in English

```
You:    "이 함수에서 버그 찾아줘"
Claude: "Find the bug in this function."
        (then continues helping you in Korean)
```

You see how your thought looks in natural English. Zero effort.

### You try rough English → AI polishes it

```
You:    "I want make function for check prime number"
Claude: "I want to make a function to check if a number is prime."
        (then continues helping you in Korean)
```

No judgment. No red marks. Just a better version right next to yours.

## Quick Start with Claude Code

### Step 1: Find your language pair

Browse the [`languages/`](languages/) folder. Folders are organized by **your native language**:

| I speak... | Folder | Available targets |
|---|---|---|
| 🇺🇸 English | [`languages/en/`](languages/en/) | ko, ja, zh, es, fr, de, pt, vi, th, ar |
| 🇰🇷 Korean | [`languages/ko/`](languages/ko/) | en, ja, zh, es, fr, de, pt, vi, th, ar |
| 🇯🇵 Japanese | [`languages/ja/`](languages/ja/) | en, ko, zh, es, fr, de, pt, vi, th, ar |
| 🇨🇳 Chinese | [`languages/zh/`](languages/zh/) | en, ko, ja, es, fr, de, pt, vi, th, ar |
| 🇪🇸 Spanish | [`languages/es/`](languages/es/) | en, ko, ja, zh, fr, de, pt, vi, th, ar |
| 🇫🇷 French | [`languages/fr/`](languages/fr/) | en, ko, ja, zh, es, de, pt, vi, th, ar |
| 🇩🇪 German | [`languages/de/`](languages/de/) | en, ko, ja, zh, es, fr, pt, vi, th, ar |
| 🇵🇹 Portuguese | [`languages/pt/`](languages/pt/) | en, ko, ja, zh, es, fr, de, vi, th, ar |
| 🇻🇳 Vietnamese | [`languages/vi/`](languages/vi/) | en, ko, ja, zh, es, fr, de, pt, th, ar |
| 🇹🇭 Thai | [`languages/th/`](languages/th/) | en, ko, ja, zh, es, fr, de, pt, vi, ar |
| 🇸🇦 Arabic | [`languages/ar/`](languages/ar/) | en, ko, ja, zh, es, fr, de, pt, vi, th |

**110 language pairs** are ready to use.

### Step 2: Copy the file for your pair

```bash
# Example: Korean speaker learning English
cp languages/ko/to-en.md ~/.claude/CLAUDE.md

# Example: English speaker learning Japanese
cp languages/en/to-ja.md ~/.claude/CLAUDE.md

# Example: Japanese speaker learning Korean
cp languages/ja/to-ko.md ~/.claude/CLAUDE.md
```

### Step 3: That's it. Start using Claude Code.

Every conversation now includes passive language learning. No extra setup needed.

> **What is `~/.claude/CLAUDE.md`?**
>
> It's Claude Code's global instruction file. Anything written here applies to **every conversation** automatically. It's the perfect place for the Language Echo Rule — you set it once and forget it. [Learn more about CLAUDE.md](https://docs.anthropic.com/en/docs/claude-code/memory)

### Append to existing CLAUDE.md

If you already have a `~/.claude/CLAUDE.md`, append the rule instead:

```bash
cat languages/ko/to-en.md >> ~/.claude/CLAUDE.md
```

## Other AI Tools

### ChatGPT / Claude.ai / Gemini

Paste the rule into your **System Prompt** or **Custom Instructions**.

### Project-level (Claude Code)

You can also add the rule to a project-specific `.claude/CLAUDE.md` to limit it to certain projects.

## Why It Works

| Principle | How This Prompt Uses It |
|---|---|
| **Immersion** | Every interaction exposes you to the target language |
| **Comprehensible Input** | You always understand the context (it's your own thought) |
| **Low Anxiety** | No grades, no corrections — just gentle echoing |
| **Spaced Repetition** | Common phrases appear naturally across conversations |
| **Learning by Doing** | You learn while actually getting work done |

## Customize for Any Language Pair

Don't see your language? Create your own:

```markdown
## Language Echo Rule
- When the user gives an instruction in **[YOUR NATIVE LANGUAGE]**, first restate
  the instruction as a clear, correct [TARGET LANGUAGE] sentence, then proceed
  with the task in [YOUR NATIVE LANGUAGE].
- When the user gives an instruction in **[TARGET LANGUAGE]**, first show
  a refined/corrected version of the [TARGET LANGUAGE] sentence, then proceed
  with the task in [YOUR NATIVE LANGUAGE].
```

Save it as `CLAUDE.md` and submit a PR to add it to the `languages/` folder!

## Real-World Results

After using this prompt daily:

- **Week 1** — You start noticing English patterns in the echoed sentences
- **Week 2** — You begin attempting more English inputs
- **Month 1** — Your English inputs need fewer corrections
- **Month 3** — You naturally switch between languages with confidence

## Contributing

Found a better phrasing? Want to add support for more language pairs? PRs welcome!

## License

MIT
