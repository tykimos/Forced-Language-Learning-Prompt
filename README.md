<p align="center">
  <h1 align="center">Forced Language Learning Prompt</h1>
  <p align="center">
    <strong>Learn a new language — without studying.</strong><br>
    A single prompt that turns every AI conversation into a passive language lesson.
  </p>
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="MIT License"></a>
  <a href="languages/"><img src="https://img.shields.io/badge/language%20pairs-110-brightgreen.svg" alt="110 Language Pairs"></a>
  <a href="#supported-languages"><img src="https://img.shields.io/badge/languages-11-orange.svg" alt="11 Languages"></a>
  <a href="#works-with"><img src="https://img.shields.io/badge/works%20with-Claude%20%7C%20ChatGPT%20%7C%20Gemini-purple.svg" alt="Works with Claude, ChatGPT, Gemini"></a>
</p>

<p align="center">
  <img src="example.png" alt="Forced Language Learning Prompt in action" width="700">
</p>

---

## How It Works

You talk to AI in your native language. AI **echoes your thought in the target language** before responding. You absorb the language passively — no flashcards, no grammar drills.

```
You:    "이 함수에서 버그 찾아줘"
Claude: "Find the bug in this function."
        42번 줄에 버그가 있습니다...
```

You try rough target language. AI **polishes it** without judgment.

```
You:    "I want make function for check prime number"
Claude: "I want to make a function to check if a number is prime."
        소수를 확인하는 함수를 만들어 보겠습니다...
```

Every conversation. Every day. Language skills compound.

## Quick Start

### One command setup (Claude Code)

```bash
# Pick your pair: {native}-{target}.md
cp languages/ko-en.md ~/.claude/CLAUDE.md
```

Done. Every Claude Code session now includes passive language learning.

> **Already have a `CLAUDE.md`?** Append instead:
> ```bash
> cat languages/ko-en.md >> ~/.claude/CLAUDE.md
> ```

### Other AI tools

Copy the prompt from any file in [`languages/`](languages/) into your **System Prompt** or **Custom Instructions**.

## Supported Languages

<table>
<tr>
<td>🇺🇸 English</td>
<td>🇰🇷 Korean</td>
<td>🇯🇵 Japanese</td>
<td>🇨🇳 Chinese</td>
</tr>
<tr>
<td>🇪🇸 Spanish</td>
<td>🇫🇷 French</td>
<td>🇩🇪 German</td>
<td>🇧🇷 Portuguese</td>
</tr>
<tr>
<td>🇻🇳 Vietnamese</td>
<td>🇹🇭 Thai</td>
<td>🇸🇦 Arabic</td>
<td></td>
</tr>
</table>

**110 pairs** — every combination of the above. Pick any two.

## Find Your Pair

Files are named `{native}-{target}.md`. Find yours:

<details>
<summary><strong>🇺🇸 I speak English</strong></summary>

| I want to learn | File |
|---|---|
| 🇰🇷 Korean | [`en-ko.md`](languages/en-ko.md) |
| 🇯🇵 Japanese | [`en-ja.md`](languages/en-ja.md) |
| 🇨🇳 Chinese | [`en-zh.md`](languages/en-zh.md) |
| 🇪🇸 Spanish | [`en-es.md`](languages/en-es.md) |
| 🇫🇷 French | [`en-fr.md`](languages/en-fr.md) |
| 🇩🇪 German | [`en-de.md`](languages/en-de.md) |
| 🇧🇷 Portuguese | [`en-pt.md`](languages/en-pt.md) |
| 🇻🇳 Vietnamese | [`en-vi.md`](languages/en-vi.md) |
| 🇹🇭 Thai | [`en-th.md`](languages/en-th.md) |
| 🇸🇦 Arabic | [`en-ar.md`](languages/en-ar.md) |

</details>

<details>
<summary><strong>🇰🇷 I speak Korean</strong></summary>

| I want to learn | File |
|---|---|
| 🇺🇸 English | [`ko-en.md`](languages/ko-en.md) |
| 🇯🇵 Japanese | [`ko-ja.md`](languages/ko-ja.md) |
| 🇨🇳 Chinese | [`ko-zh.md`](languages/ko-zh.md) |
| 🇪🇸 Spanish | [`ko-es.md`](languages/ko-es.md) |
| 🇫🇷 French | [`ko-fr.md`](languages/ko-fr.md) |
| 🇩🇪 German | [`ko-de.md`](languages/ko-de.md) |
| 🇧🇷 Portuguese | [`ko-pt.md`](languages/ko-pt.md) |
| 🇻🇳 Vietnamese | [`ko-vi.md`](languages/ko-vi.md) |
| 🇹🇭 Thai | [`ko-th.md`](languages/ko-th.md) |
| 🇸🇦 Arabic | [`ko-ar.md`](languages/ko-ar.md) |

</details>

<details>
<summary><strong>🇯🇵 I speak Japanese</strong></summary>

| I want to learn | File |
|---|---|
| 🇺🇸 English | [`ja-en.md`](languages/ja-en.md) |
| 🇰🇷 Korean | [`ja-ko.md`](languages/ja-ko.md) |
| 🇨🇳 Chinese | [`ja-zh.md`](languages/ja-zh.md) |
| 🇪🇸 Spanish | [`ja-es.md`](languages/ja-es.md) |
| 🇫🇷 French | [`ja-fr.md`](languages/ja-fr.md) |
| 🇩🇪 German | [`ja-de.md`](languages/ja-de.md) |
| 🇧🇷 Portuguese | [`ja-pt.md`](languages/ja-pt.md) |
| 🇻🇳 Vietnamese | [`ja-vi.md`](languages/ja-vi.md) |
| 🇹🇭 Thai | [`ja-th.md`](languages/ja-th.md) |
| 🇸🇦 Arabic | [`ja-ar.md`](languages/ja-ar.md) |

</details>

<details>
<summary><strong>🇨🇳 I speak Chinese</strong></summary>

| I want to learn | File |
|---|---|
| 🇺🇸 English | [`zh-en.md`](languages/zh-en.md) |
| 🇰🇷 Korean | [`zh-ko.md`](languages/zh-ko.md) |
| 🇯🇵 Japanese | [`zh-ja.md`](languages/zh-ja.md) |
| 🇪🇸 Spanish | [`zh-es.md`](languages/zh-es.md) |
| 🇫🇷 French | [`zh-fr.md`](languages/zh-fr.md) |
| 🇩🇪 German | [`zh-de.md`](languages/zh-de.md) |
| 🇧🇷 Portuguese | [`zh-pt.md`](languages/zh-pt.md) |
| 🇻🇳 Vietnamese | [`zh-vi.md`](languages/zh-vi.md) |
| 🇹🇭 Thai | [`zh-th.md`](languages/zh-th.md) |
| 🇸🇦 Arabic | [`zh-ar.md`](languages/zh-ar.md) |

</details>

<details>
<summary><strong>🇪🇸 I speak Spanish</strong></summary>

| I want to learn | File |
|---|---|
| 🇺🇸 English | [`es-en.md`](languages/es-en.md) |
| 🇰🇷 Korean | [`es-ko.md`](languages/es-ko.md) |
| 🇯🇵 Japanese | [`es-ja.md`](languages/es-ja.md) |
| 🇨🇳 Chinese | [`es-zh.md`](languages/es-zh.md) |
| 🇫🇷 French | [`es-fr.md`](languages/es-fr.md) |
| 🇩🇪 German | [`es-de.md`](languages/es-de.md) |
| 🇧🇷 Portuguese | [`es-pt.md`](languages/es-pt.md) |
| 🇻🇳 Vietnamese | [`es-vi.md`](languages/es-vi.md) |
| 🇹🇭 Thai | [`es-th.md`](languages/es-th.md) |
| 🇸🇦 Arabic | [`es-ar.md`](languages/es-ar.md) |

</details>

<details>
<summary><strong>🇫🇷 I speak French</strong></summary>

| I want to learn | File |
|---|---|
| 🇺🇸 English | [`fr-en.md`](languages/fr-en.md) |
| 🇰🇷 Korean | [`fr-ko.md`](languages/fr-ko.md) |
| 🇯🇵 Japanese | [`fr-ja.md`](languages/fr-ja.md) |
| 🇨🇳 Chinese | [`fr-zh.md`](languages/fr-zh.md) |
| 🇪🇸 Spanish | [`fr-es.md`](languages/fr-es.md) |
| 🇩🇪 German | [`fr-de.md`](languages/fr-de.md) |
| 🇧🇷 Portuguese | [`fr-pt.md`](languages/fr-pt.md) |
| 🇻🇳 Vietnamese | [`fr-vi.md`](languages/fr-vi.md) |
| 🇹🇭 Thai | [`fr-th.md`](languages/fr-th.md) |
| 🇸🇦 Arabic | [`fr-ar.md`](languages/fr-ar.md) |

</details>

<details>
<summary><strong>🇩🇪 I speak German</strong></summary>

| I want to learn | File |
|---|---|
| 🇺🇸 English | [`de-en.md`](languages/de-en.md) |
| 🇰🇷 Korean | [`de-ko.md`](languages/de-ko.md) |
| 🇯🇵 Japanese | [`de-ja.md`](languages/de-ja.md) |
| 🇨🇳 Chinese | [`de-zh.md`](languages/de-zh.md) |
| 🇪🇸 Spanish | [`de-es.md`](languages/de-es.md) |
| 🇫🇷 French | [`de-fr.md`](languages/de-fr.md) |
| 🇧🇷 Portuguese | [`de-pt.md`](languages/de-pt.md) |
| 🇻🇳 Vietnamese | [`de-vi.md`](languages/de-vi.md) |
| 🇹🇭 Thai | [`de-th.md`](languages/de-th.md) |
| 🇸🇦 Arabic | [`de-ar.md`](languages/de-ar.md) |

</details>

<details>
<summary><strong>🇧🇷 I speak Portuguese</strong></summary>

| I want to learn | File |
|---|---|
| 🇺🇸 English | [`pt-en.md`](languages/pt-en.md) |
| 🇰🇷 Korean | [`pt-ko.md`](languages/pt-ko.md) |
| 🇯🇵 Japanese | [`pt-ja.md`](languages/pt-ja.md) |
| 🇨🇳 Chinese | [`pt-zh.md`](languages/pt-zh.md) |
| 🇪🇸 Spanish | [`pt-es.md`](languages/pt-es.md) |
| 🇫🇷 French | [`pt-fr.md`](languages/pt-fr.md) |
| 🇩🇪 German | [`pt-de.md`](languages/pt-de.md) |
| 🇻🇳 Vietnamese | [`pt-vi.md`](languages/pt-vi.md) |
| 🇹🇭 Thai | [`pt-th.md`](languages/pt-th.md) |
| 🇸🇦 Arabic | [`pt-ar.md`](languages/pt-ar.md) |

</details>

<details>
<summary><strong>🇻🇳 I speak Vietnamese</strong></summary>

| I want to learn | File |
|---|---|
| 🇺🇸 English | [`vi-en.md`](languages/vi-en.md) |
| 🇰🇷 Korean | [`vi-ko.md`](languages/vi-ko.md) |
| 🇯🇵 Japanese | [`vi-ja.md`](languages/vi-ja.md) |
| 🇨🇳 Chinese | [`vi-zh.md`](languages/vi-zh.md) |
| 🇪🇸 Spanish | [`vi-es.md`](languages/vi-es.md) |
| 🇫🇷 French | [`vi-fr.md`](languages/vi-fr.md) |
| 🇩🇪 German | [`vi-de.md`](languages/vi-de.md) |
| 🇧🇷 Portuguese | [`vi-pt.md`](languages/vi-pt.md) |
| 🇹🇭 Thai | [`vi-th.md`](languages/vi-th.md) |
| 🇸🇦 Arabic | [`vi-ar.md`](languages/vi-ar.md) |

</details>

<details>
<summary><strong>🇹🇭 I speak Thai</strong></summary>

| I want to learn | File |
|---|---|
| 🇺🇸 English | [`th-en.md`](languages/th-en.md) |
| 🇰🇷 Korean | [`th-ko.md`](languages/th-ko.md) |
| 🇯🇵 Japanese | [`th-ja.md`](languages/th-ja.md) |
| 🇨🇳 Chinese | [`th-zh.md`](languages/th-zh.md) |
| 🇪🇸 Spanish | [`th-es.md`](languages/th-es.md) |
| 🇫🇷 French | [`th-fr.md`](languages/th-fr.md) |
| 🇩🇪 German | [`th-de.md`](languages/th-de.md) |
| 🇧🇷 Portuguese | [`th-pt.md`](languages/th-pt.md) |
| 🇻🇳 Vietnamese | [`th-vi.md`](languages/th-vi.md) |
| 🇸🇦 Arabic | [`th-ar.md`](languages/th-ar.md) |

</details>

<details>
<summary><strong>🇸🇦 I speak Arabic</strong></summary>

| I want to learn | File |
|---|---|
| 🇺🇸 English | [`ar-en.md`](languages/ar-en.md) |
| 🇰🇷 Korean | [`ar-ko.md`](languages/ar-ko.md) |
| 🇯🇵 Japanese | [`ar-ja.md`](languages/ar-ja.md) |
| 🇨🇳 Chinese | [`ar-zh.md`](languages/ar-zh.md) |
| 🇪🇸 Spanish | [`ar-es.md`](languages/ar-es.md) |
| 🇫🇷 French | [`ar-fr.md`](languages/ar-fr.md) |
| 🇩🇪 German | [`ar-de.md`](languages/ar-de.md) |
| 🇧🇷 Portuguese | [`ar-pt.md`](languages/ar-pt.md) |
| 🇻🇳 Vietnamese | [`ar-vi.md`](languages/ar-vi.md) |
| 🇹🇭 Thai | [`ar-th.md`](languages/ar-th.md) |

</details>

## Works With

| Platform | How to use |
|---|---|
| **Claude Code** | Copy file to `~/.claude/CLAUDE.md` |
| **Claude.ai** | Paste into Project Instructions or System Prompt |
| **ChatGPT** | Paste into Custom Instructions |
| **Gemini** | Paste into System Prompt |
| **Any LLM** | Paste into your system prompt |

## Why It Works

| Principle | Application |
|---|---|
| **Immersion** | Every interaction = target language exposure |
| **Comprehensible Input** | Context is always clear — it's your own thought |
| **Low Anxiety** | No grades, no red marks — just gentle echoing |
| **Spaced Repetition** | Common phrases recur naturally |
| **Learning by Doing** | You learn while getting real work done |

## The Prompt

The core mechanism is simple — two rules:

```markdown
## Language Echo Rule
- When the user gives an instruction in **[NATIVE]**, first restate the instruction
  as a clear, correct [TARGET] sentence, then proceed with the task in [NATIVE].
- When the user gives an instruction in **[TARGET]**, first show a refined/corrected
  version of the [TARGET] sentence, then proceed with the task in [NATIVE].
```

That's it. No complex setup. No dependencies. Just copy → paste → learn.

## Contributing

Want to add a new language? Create `{native}-{target}.md` in `languages/` and open a PR.

Found a better phrasing? Issues and PRs are welcome.

## License

[MIT](LICENSE)
