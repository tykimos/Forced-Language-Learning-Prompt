# Forced Language Learning Prompt

**Learn a new language effortlessly — just by using AI.**

No textbooks. No flashcards. No dedicated study time. Just a single prompt that turns every AI conversation into a language lesson.

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
You:  "이 함수에서 버그 찾아줘"
AI:   "Find the bug in this function."
      (then continues helping you in Korean)
```

You see how your thought looks in natural English. Zero effort.

### You try rough English → AI polishes it

```
You:  "I want make function for check prime number"
AI:   "I want to make a function to check if a number is prime."
      (then continues helping you in Korean)
```

No judgment. No red marks. Just a better version right next to yours.

## Why It Works

| Principle | How This Prompt Uses It |
|---|---|
| **Immersion** | Every interaction exposes you to the target language |
| **Comprehensible Input** | You always understand the context (it's your own thought) |
| **Low Anxiety** | No grades, no corrections — just gentle echoing |
| **Spaced Repetition** | Common phrases appear naturally across conversations |
| **Learning by Doing** | You learn while actually getting work done |

## Setup

### Claude Code (CLI)

Add to your `~/.claude/CLAUDE.md`:

```markdown
## Language Echo Rule
- When the user gives an instruction in **Korean**, first restate the instruction
  as a clear, correct English sentence, then proceed with the task in Korean.
- When the user gives an instruction in **English**, first show a refined/corrected
  version of the English sentence, then proceed with the task in Korean.
```

### ChatGPT / Claude.ai / Other AI

Paste the rule into your **System Prompt** or **Custom Instructions**.

## Customize for Any Language Pair

Just swap the languages:

<details>
<summary>Japanese speaker learning English</summary>

```markdown
## Language Echo Rule
- When the user gives an instruction in **Japanese**, first restate the instruction
  as a clear, correct English sentence, then proceed with the task in Japanese.
- When the user gives an instruction in **English**, first show a refined/corrected
  version of the English sentence, then proceed with the task in Japanese.
```

</details>

<details>
<summary>English speaker learning Spanish</summary>

```markdown
## Language Echo Rule
- When the user gives an instruction in **English**, first restate the instruction
  as a clear, correct Spanish sentence, then proceed with the task in English.
- When the user gives an instruction in **Spanish**, first show a refined/corrected
  version of the Spanish sentence, then proceed with the task in English.
```

</details>

<details>
<summary>Any language pair</summary>

```markdown
## Language Echo Rule
- When the user gives an instruction in **[NATIVE LANGUAGE]**, first restate
  the instruction as a clear, correct [TARGET LANGUAGE] sentence, then proceed
  with the task in [NATIVE LANGUAGE].
- When the user gives an instruction in **[TARGET LANGUAGE]**, first show
  a refined/corrected version of the [TARGET LANGUAGE] sentence, then proceed
  with the task in [NATIVE LANGUAGE].
```

</details>

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
