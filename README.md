<p align="center">
  <h1 align="center">Forced Language Learning Prompt</h1>
  <p align="center">
    <strong>Learn a new language — without studying.</strong><br>
    A single prompt that turns every AI conversation into a passive language lesson.
  </p>
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="MIT License"></a>
  <a href="languages/"><img src="https://img.shields.io/badge/language%20pairs-506-brightgreen.svg" alt="506 Language Pairs"></a>
  <a href="#supported-languages"><img src="https://img.shields.io/badge/languages-23-orange.svg" alt="23 Languages"></a>
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
<td>🇮🇳 Hindi</td>
</tr>
<tr>
<td>🇧🇩 Bengali</td>
<td>🇷🇺 Russian</td>
<td>🇮🇩 Indonesian</td>
<td>🇲🇾 Malay</td>
</tr>
<tr>
<td>🇹🇷 Turkish</td>
<td>🇮🇹 Italian</td>
<td>🇵🇱 Polish</td>
<td>🇳🇱 Dutch</td>
</tr>
<tr>
<td>🇸🇪 Swedish</td>
<td>🇺🇦 Ukrainian</td>
<td>🇵🇭 Filipino</td>
<td></td>
</tr>
</table>

**506 pairs** — every combination of the above. Pick any two.

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
| 🇮🇳 Hindi | [`en-hi.md`](languages/en-hi.md) |
| 🇧🇩 Bengali | [`en-bn.md`](languages/en-bn.md) |
| 🇷🇺 Russian | [`en-ru.md`](languages/en-ru.md) |
| 🇮🇩 Indonesian | [`en-id.md`](languages/en-id.md) |
| 🇲🇾 Malay | [`en-ms.md`](languages/en-ms.md) |
| 🇹🇷 Turkish | [`en-tr.md`](languages/en-tr.md) |
| 🇮🇹 Italian | [`en-it.md`](languages/en-it.md) |
| 🇵🇱 Polish | [`en-pl.md`](languages/en-pl.md) |
| 🇳🇱 Dutch | [`en-nl.md`](languages/en-nl.md) |
| 🇸🇪 Swedish | [`en-sv.md`](languages/en-sv.md) |
| 🇺🇦 Ukrainian | [`en-uk.md`](languages/en-uk.md) |
| 🇵🇭 Filipino | [`en-tl.md`](languages/en-tl.md) |

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
| 🇮🇳 Hindi | [`ko-hi.md`](languages/ko-hi.md) |
| 🇧🇩 Bengali | [`ko-bn.md`](languages/ko-bn.md) |
| 🇷🇺 Russian | [`ko-ru.md`](languages/ko-ru.md) |
| 🇮🇩 Indonesian | [`ko-id.md`](languages/ko-id.md) |
| 🇲🇾 Malay | [`ko-ms.md`](languages/ko-ms.md) |
| 🇹🇷 Turkish | [`ko-tr.md`](languages/ko-tr.md) |
| 🇮🇹 Italian | [`ko-it.md`](languages/ko-it.md) |
| 🇵🇱 Polish | [`ko-pl.md`](languages/ko-pl.md) |
| 🇳🇱 Dutch | [`ko-nl.md`](languages/ko-nl.md) |
| 🇸🇪 Swedish | [`ko-sv.md`](languages/ko-sv.md) |
| 🇺🇦 Ukrainian | [`ko-uk.md`](languages/ko-uk.md) |
| 🇵🇭 Filipino | [`ko-tl.md`](languages/ko-tl.md) |

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
| 🇮🇳 Hindi | [`ja-hi.md`](languages/ja-hi.md) |
| 🇧🇩 Bengali | [`ja-bn.md`](languages/ja-bn.md) |
| 🇷🇺 Russian | [`ja-ru.md`](languages/ja-ru.md) |
| 🇮🇩 Indonesian | [`ja-id.md`](languages/ja-id.md) |
| 🇲🇾 Malay | [`ja-ms.md`](languages/ja-ms.md) |
| 🇹🇷 Turkish | [`ja-tr.md`](languages/ja-tr.md) |
| 🇮🇹 Italian | [`ja-it.md`](languages/ja-it.md) |
| 🇵🇱 Polish | [`ja-pl.md`](languages/ja-pl.md) |
| 🇳🇱 Dutch | [`ja-nl.md`](languages/ja-nl.md) |
| 🇸🇪 Swedish | [`ja-sv.md`](languages/ja-sv.md) |
| 🇺🇦 Ukrainian | [`ja-uk.md`](languages/ja-uk.md) |
| 🇵🇭 Filipino | [`ja-tl.md`](languages/ja-tl.md) |

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
| 🇮🇳 Hindi | [`zh-hi.md`](languages/zh-hi.md) |
| 🇧🇩 Bengali | [`zh-bn.md`](languages/zh-bn.md) |
| 🇷🇺 Russian | [`zh-ru.md`](languages/zh-ru.md) |
| 🇮🇩 Indonesian | [`zh-id.md`](languages/zh-id.md) |
| 🇲🇾 Malay | [`zh-ms.md`](languages/zh-ms.md) |
| 🇹🇷 Turkish | [`zh-tr.md`](languages/zh-tr.md) |
| 🇮🇹 Italian | [`zh-it.md`](languages/zh-it.md) |
| 🇵🇱 Polish | [`zh-pl.md`](languages/zh-pl.md) |
| 🇳🇱 Dutch | [`zh-nl.md`](languages/zh-nl.md) |
| 🇸🇪 Swedish | [`zh-sv.md`](languages/zh-sv.md) |
| 🇺🇦 Ukrainian | [`zh-uk.md`](languages/zh-uk.md) |
| 🇵🇭 Filipino | [`zh-tl.md`](languages/zh-tl.md) |

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
| 🇮🇳 Hindi | [`es-hi.md`](languages/es-hi.md) |
| 🇧🇩 Bengali | [`es-bn.md`](languages/es-bn.md) |
| 🇷🇺 Russian | [`es-ru.md`](languages/es-ru.md) |
| 🇮🇩 Indonesian | [`es-id.md`](languages/es-id.md) |
| 🇲🇾 Malay | [`es-ms.md`](languages/es-ms.md) |
| 🇹🇷 Turkish | [`es-tr.md`](languages/es-tr.md) |
| 🇮🇹 Italian | [`es-it.md`](languages/es-it.md) |
| 🇵🇱 Polish | [`es-pl.md`](languages/es-pl.md) |
| 🇳🇱 Dutch | [`es-nl.md`](languages/es-nl.md) |
| 🇸🇪 Swedish | [`es-sv.md`](languages/es-sv.md) |
| 🇺🇦 Ukrainian | [`es-uk.md`](languages/es-uk.md) |
| 🇵🇭 Filipino | [`es-tl.md`](languages/es-tl.md) |

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
| 🇮🇳 Hindi | [`fr-hi.md`](languages/fr-hi.md) |
| 🇧🇩 Bengali | [`fr-bn.md`](languages/fr-bn.md) |
| 🇷🇺 Russian | [`fr-ru.md`](languages/fr-ru.md) |
| 🇮🇩 Indonesian | [`fr-id.md`](languages/fr-id.md) |
| 🇲🇾 Malay | [`fr-ms.md`](languages/fr-ms.md) |
| 🇹🇷 Turkish | [`fr-tr.md`](languages/fr-tr.md) |
| 🇮🇹 Italian | [`fr-it.md`](languages/fr-it.md) |
| 🇵🇱 Polish | [`fr-pl.md`](languages/fr-pl.md) |
| 🇳🇱 Dutch | [`fr-nl.md`](languages/fr-nl.md) |
| 🇸🇪 Swedish | [`fr-sv.md`](languages/fr-sv.md) |
| 🇺🇦 Ukrainian | [`fr-uk.md`](languages/fr-uk.md) |
| 🇵🇭 Filipino | [`fr-tl.md`](languages/fr-tl.md) |

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
| 🇮🇳 Hindi | [`de-hi.md`](languages/de-hi.md) |
| 🇧🇩 Bengali | [`de-bn.md`](languages/de-bn.md) |
| 🇷🇺 Russian | [`de-ru.md`](languages/de-ru.md) |
| 🇮🇩 Indonesian | [`de-id.md`](languages/de-id.md) |
| 🇲🇾 Malay | [`de-ms.md`](languages/de-ms.md) |
| 🇹🇷 Turkish | [`de-tr.md`](languages/de-tr.md) |
| 🇮🇹 Italian | [`de-it.md`](languages/de-it.md) |
| 🇵🇱 Polish | [`de-pl.md`](languages/de-pl.md) |
| 🇳🇱 Dutch | [`de-nl.md`](languages/de-nl.md) |
| 🇸🇪 Swedish | [`de-sv.md`](languages/de-sv.md) |
| 🇺🇦 Ukrainian | [`de-uk.md`](languages/de-uk.md) |
| 🇵🇭 Filipino | [`de-tl.md`](languages/de-tl.md) |

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
| 🇮🇳 Hindi | [`pt-hi.md`](languages/pt-hi.md) |
| 🇧🇩 Bengali | [`pt-bn.md`](languages/pt-bn.md) |
| 🇷🇺 Russian | [`pt-ru.md`](languages/pt-ru.md) |
| 🇮🇩 Indonesian | [`pt-id.md`](languages/pt-id.md) |
| 🇲🇾 Malay | [`pt-ms.md`](languages/pt-ms.md) |
| 🇹🇷 Turkish | [`pt-tr.md`](languages/pt-tr.md) |
| 🇮🇹 Italian | [`pt-it.md`](languages/pt-it.md) |
| 🇵🇱 Polish | [`pt-pl.md`](languages/pt-pl.md) |
| 🇳🇱 Dutch | [`pt-nl.md`](languages/pt-nl.md) |
| 🇸🇪 Swedish | [`pt-sv.md`](languages/pt-sv.md) |
| 🇺🇦 Ukrainian | [`pt-uk.md`](languages/pt-uk.md) |
| 🇵🇭 Filipino | [`pt-tl.md`](languages/pt-tl.md) |

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
| 🇮🇳 Hindi | [`vi-hi.md`](languages/vi-hi.md) |
| 🇧🇩 Bengali | [`vi-bn.md`](languages/vi-bn.md) |
| 🇷🇺 Russian | [`vi-ru.md`](languages/vi-ru.md) |
| 🇮🇩 Indonesian | [`vi-id.md`](languages/vi-id.md) |
| 🇲🇾 Malay | [`vi-ms.md`](languages/vi-ms.md) |
| 🇹🇷 Turkish | [`vi-tr.md`](languages/vi-tr.md) |
| 🇮🇹 Italian | [`vi-it.md`](languages/vi-it.md) |
| 🇵🇱 Polish | [`vi-pl.md`](languages/vi-pl.md) |
| 🇳🇱 Dutch | [`vi-nl.md`](languages/vi-nl.md) |
| 🇸🇪 Swedish | [`vi-sv.md`](languages/vi-sv.md) |
| 🇺🇦 Ukrainian | [`vi-uk.md`](languages/vi-uk.md) |
| 🇵🇭 Filipino | [`vi-tl.md`](languages/vi-tl.md) |

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
| 🇮🇳 Hindi | [`th-hi.md`](languages/th-hi.md) |
| 🇧🇩 Bengali | [`th-bn.md`](languages/th-bn.md) |
| 🇷🇺 Russian | [`th-ru.md`](languages/th-ru.md) |
| 🇮🇩 Indonesian | [`th-id.md`](languages/th-id.md) |
| 🇲🇾 Malay | [`th-ms.md`](languages/th-ms.md) |
| 🇹🇷 Turkish | [`th-tr.md`](languages/th-tr.md) |
| 🇮🇹 Italian | [`th-it.md`](languages/th-it.md) |
| 🇵🇱 Polish | [`th-pl.md`](languages/th-pl.md) |
| 🇳🇱 Dutch | [`th-nl.md`](languages/th-nl.md) |
| 🇸🇪 Swedish | [`th-sv.md`](languages/th-sv.md) |
| 🇺🇦 Ukrainian | [`th-uk.md`](languages/th-uk.md) |
| 🇵🇭 Filipino | [`th-tl.md`](languages/th-tl.md) |

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
| 🇮🇳 Hindi | [`ar-hi.md`](languages/ar-hi.md) |
| 🇧🇩 Bengali | [`ar-bn.md`](languages/ar-bn.md) |
| 🇷🇺 Russian | [`ar-ru.md`](languages/ar-ru.md) |
| 🇮🇩 Indonesian | [`ar-id.md`](languages/ar-id.md) |
| 🇲🇾 Malay | [`ar-ms.md`](languages/ar-ms.md) |
| 🇹🇷 Turkish | [`ar-tr.md`](languages/ar-tr.md) |
| 🇮🇹 Italian | [`ar-it.md`](languages/ar-it.md) |
| 🇵🇱 Polish | [`ar-pl.md`](languages/ar-pl.md) |
| 🇳🇱 Dutch | [`ar-nl.md`](languages/ar-nl.md) |
| 🇸🇪 Swedish | [`ar-sv.md`](languages/ar-sv.md) |
| 🇺🇦 Ukrainian | [`ar-uk.md`](languages/ar-uk.md) |
| 🇵🇭 Filipino | [`ar-tl.md`](languages/ar-tl.md) |

</details>

<details>
<summary><strong>🇮🇳 I speak Hindi</strong></summary>

| I want to learn | File |
|---|---|
| 🇺🇸 English | [`hi-en.md`](languages/hi-en.md) |
| 🇰🇷 Korean | [`hi-ko.md`](languages/hi-ko.md) |
| 🇯🇵 Japanese | [`hi-ja.md`](languages/hi-ja.md) |
| 🇨🇳 Chinese | [`hi-zh.md`](languages/hi-zh.md) |
| 🇪🇸 Spanish | [`hi-es.md`](languages/hi-es.md) |
| 🇫🇷 French | [`hi-fr.md`](languages/hi-fr.md) |
| 🇩🇪 German | [`hi-de.md`](languages/hi-de.md) |
| 🇧🇷 Portuguese | [`hi-pt.md`](languages/hi-pt.md) |
| 🇻🇳 Vietnamese | [`hi-vi.md`](languages/hi-vi.md) |
| 🇹🇭 Thai | [`hi-th.md`](languages/hi-th.md) |
| 🇸🇦 Arabic | [`hi-ar.md`](languages/hi-ar.md) |
| 🇧🇩 Bengali | [`hi-bn.md`](languages/hi-bn.md) |
| 🇷🇺 Russian | [`hi-ru.md`](languages/hi-ru.md) |
| 🇮🇩 Indonesian | [`hi-id.md`](languages/hi-id.md) |
| 🇲🇾 Malay | [`hi-ms.md`](languages/hi-ms.md) |
| 🇹🇷 Turkish | [`hi-tr.md`](languages/hi-tr.md) |
| 🇮🇹 Italian | [`hi-it.md`](languages/hi-it.md) |
| 🇵🇱 Polish | [`hi-pl.md`](languages/hi-pl.md) |
| 🇳🇱 Dutch | [`hi-nl.md`](languages/hi-nl.md) |
| 🇸🇪 Swedish | [`hi-sv.md`](languages/hi-sv.md) |
| 🇺🇦 Ukrainian | [`hi-uk.md`](languages/hi-uk.md) |
| 🇵🇭 Filipino | [`hi-tl.md`](languages/hi-tl.md) |

</details>

<details>
<summary><strong>🇧🇩 I speak Bengali</strong></summary>

| I want to learn | File |
|---|---|
| 🇺🇸 English | [`bn-en.md`](languages/bn-en.md) |
| 🇰🇷 Korean | [`bn-ko.md`](languages/bn-ko.md) |
| 🇯🇵 Japanese | [`bn-ja.md`](languages/bn-ja.md) |
| 🇨🇳 Chinese | [`bn-zh.md`](languages/bn-zh.md) |
| 🇪🇸 Spanish | [`bn-es.md`](languages/bn-es.md) |
| 🇫🇷 French | [`bn-fr.md`](languages/bn-fr.md) |
| 🇩🇪 German | [`bn-de.md`](languages/bn-de.md) |
| 🇧🇷 Portuguese | [`bn-pt.md`](languages/bn-pt.md) |
| 🇻🇳 Vietnamese | [`bn-vi.md`](languages/bn-vi.md) |
| 🇹🇭 Thai | [`bn-th.md`](languages/bn-th.md) |
| 🇸🇦 Arabic | [`bn-ar.md`](languages/bn-ar.md) |
| 🇮🇳 Hindi | [`bn-hi.md`](languages/bn-hi.md) |
| 🇷🇺 Russian | [`bn-ru.md`](languages/bn-ru.md) |
| 🇮🇩 Indonesian | [`bn-id.md`](languages/bn-id.md) |
| 🇲🇾 Malay | [`bn-ms.md`](languages/bn-ms.md) |
| 🇹🇷 Turkish | [`bn-tr.md`](languages/bn-tr.md) |
| 🇮🇹 Italian | [`bn-it.md`](languages/bn-it.md) |
| 🇵🇱 Polish | [`bn-pl.md`](languages/bn-pl.md) |
| 🇳🇱 Dutch | [`bn-nl.md`](languages/bn-nl.md) |
| 🇸🇪 Swedish | [`bn-sv.md`](languages/bn-sv.md) |
| 🇺🇦 Ukrainian | [`bn-uk.md`](languages/bn-uk.md) |
| 🇵🇭 Filipino | [`bn-tl.md`](languages/bn-tl.md) |

</details>

<details>
<summary><strong>🇷🇺 I speak Russian</strong></summary>

| I want to learn | File |
|---|---|
| 🇺🇸 English | [`ru-en.md`](languages/ru-en.md) |
| 🇰🇷 Korean | [`ru-ko.md`](languages/ru-ko.md) |
| 🇯🇵 Japanese | [`ru-ja.md`](languages/ru-ja.md) |
| 🇨🇳 Chinese | [`ru-zh.md`](languages/ru-zh.md) |
| 🇪🇸 Spanish | [`ru-es.md`](languages/ru-es.md) |
| 🇫🇷 French | [`ru-fr.md`](languages/ru-fr.md) |
| 🇩🇪 German | [`ru-de.md`](languages/ru-de.md) |
| 🇧🇷 Portuguese | [`ru-pt.md`](languages/ru-pt.md) |
| 🇻🇳 Vietnamese | [`ru-vi.md`](languages/ru-vi.md) |
| 🇹🇭 Thai | [`ru-th.md`](languages/ru-th.md) |
| 🇸🇦 Arabic | [`ru-ar.md`](languages/ru-ar.md) |
| 🇮🇳 Hindi | [`ru-hi.md`](languages/ru-hi.md) |
| 🇧🇩 Bengali | [`ru-bn.md`](languages/ru-bn.md) |
| 🇮🇩 Indonesian | [`ru-id.md`](languages/ru-id.md) |
| 🇲🇾 Malay | [`ru-ms.md`](languages/ru-ms.md) |
| 🇹🇷 Turkish | [`ru-tr.md`](languages/ru-tr.md) |
| 🇮🇹 Italian | [`ru-it.md`](languages/ru-it.md) |
| 🇵🇱 Polish | [`ru-pl.md`](languages/ru-pl.md) |
| 🇳🇱 Dutch | [`ru-nl.md`](languages/ru-nl.md) |
| 🇸🇪 Swedish | [`ru-sv.md`](languages/ru-sv.md) |
| 🇺🇦 Ukrainian | [`ru-uk.md`](languages/ru-uk.md) |
| 🇵🇭 Filipino | [`ru-tl.md`](languages/ru-tl.md) |

</details>

<details>
<summary><strong>🇮🇩 I speak Indonesian</strong></summary>

| I want to learn | File |
|---|---|
| 🇺🇸 English | [`id-en.md`](languages/id-en.md) |
| 🇰🇷 Korean | [`id-ko.md`](languages/id-ko.md) |
| 🇯🇵 Japanese | [`id-ja.md`](languages/id-ja.md) |
| 🇨🇳 Chinese | [`id-zh.md`](languages/id-zh.md) |
| 🇪🇸 Spanish | [`id-es.md`](languages/id-es.md) |
| 🇫🇷 French | [`id-fr.md`](languages/id-fr.md) |
| 🇩🇪 German | [`id-de.md`](languages/id-de.md) |
| 🇧🇷 Portuguese | [`id-pt.md`](languages/id-pt.md) |
| 🇻🇳 Vietnamese | [`id-vi.md`](languages/id-vi.md) |
| 🇹🇭 Thai | [`id-th.md`](languages/id-th.md) |
| 🇸🇦 Arabic | [`id-ar.md`](languages/id-ar.md) |
| 🇮🇳 Hindi | [`id-hi.md`](languages/id-hi.md) |
| 🇧🇩 Bengali | [`id-bn.md`](languages/id-bn.md) |
| 🇷🇺 Russian | [`id-ru.md`](languages/id-ru.md) |
| 🇲🇾 Malay | [`id-ms.md`](languages/id-ms.md) |
| 🇹🇷 Turkish | [`id-tr.md`](languages/id-tr.md) |
| 🇮🇹 Italian | [`id-it.md`](languages/id-it.md) |
| 🇵🇱 Polish | [`id-pl.md`](languages/id-pl.md) |
| 🇳🇱 Dutch | [`id-nl.md`](languages/id-nl.md) |
| 🇸🇪 Swedish | [`id-sv.md`](languages/id-sv.md) |
| 🇺🇦 Ukrainian | [`id-uk.md`](languages/id-uk.md) |
| 🇵🇭 Filipino | [`id-tl.md`](languages/id-tl.md) |

</details>

<details>
<summary><strong>🇲🇾 I speak Malay</strong></summary>

| I want to learn | File |
|---|---|
| 🇺🇸 English | [`ms-en.md`](languages/ms-en.md) |
| 🇰🇷 Korean | [`ms-ko.md`](languages/ms-ko.md) |
| 🇯🇵 Japanese | [`ms-ja.md`](languages/ms-ja.md) |
| 🇨🇳 Chinese | [`ms-zh.md`](languages/ms-zh.md) |
| 🇪🇸 Spanish | [`ms-es.md`](languages/ms-es.md) |
| 🇫🇷 French | [`ms-fr.md`](languages/ms-fr.md) |
| 🇩🇪 German | [`ms-de.md`](languages/ms-de.md) |
| 🇧🇷 Portuguese | [`ms-pt.md`](languages/ms-pt.md) |
| 🇻🇳 Vietnamese | [`ms-vi.md`](languages/ms-vi.md) |
| 🇹🇭 Thai | [`ms-th.md`](languages/ms-th.md) |
| 🇸🇦 Arabic | [`ms-ar.md`](languages/ms-ar.md) |
| 🇮🇳 Hindi | [`ms-hi.md`](languages/ms-hi.md) |
| 🇧🇩 Bengali | [`ms-bn.md`](languages/ms-bn.md) |
| 🇷🇺 Russian | [`ms-ru.md`](languages/ms-ru.md) |
| 🇮🇩 Indonesian | [`ms-id.md`](languages/ms-id.md) |
| 🇹🇷 Turkish | [`ms-tr.md`](languages/ms-tr.md) |
| 🇮🇹 Italian | [`ms-it.md`](languages/ms-it.md) |
| 🇵🇱 Polish | [`ms-pl.md`](languages/ms-pl.md) |
| 🇳🇱 Dutch | [`ms-nl.md`](languages/ms-nl.md) |
| 🇸🇪 Swedish | [`ms-sv.md`](languages/ms-sv.md) |
| 🇺🇦 Ukrainian | [`ms-uk.md`](languages/ms-uk.md) |
| 🇵🇭 Filipino | [`ms-tl.md`](languages/ms-tl.md) |

</details>

<details>
<summary><strong>🇹🇷 I speak Turkish</strong></summary>

| I want to learn | File |
|---|---|
| 🇺🇸 English | [`tr-en.md`](languages/tr-en.md) |
| 🇰🇷 Korean | [`tr-ko.md`](languages/tr-ko.md) |
| 🇯🇵 Japanese | [`tr-ja.md`](languages/tr-ja.md) |
| 🇨🇳 Chinese | [`tr-zh.md`](languages/tr-zh.md) |
| 🇪🇸 Spanish | [`tr-es.md`](languages/tr-es.md) |
| 🇫🇷 French | [`tr-fr.md`](languages/tr-fr.md) |
| 🇩🇪 German | [`tr-de.md`](languages/tr-de.md) |
| 🇧🇷 Portuguese | [`tr-pt.md`](languages/tr-pt.md) |
| 🇻🇳 Vietnamese | [`tr-vi.md`](languages/tr-vi.md) |
| 🇹🇭 Thai | [`tr-th.md`](languages/tr-th.md) |
| 🇸🇦 Arabic | [`tr-ar.md`](languages/tr-ar.md) |
| 🇮🇳 Hindi | [`tr-hi.md`](languages/tr-hi.md) |
| 🇧🇩 Bengali | [`tr-bn.md`](languages/tr-bn.md) |
| 🇷🇺 Russian | [`tr-ru.md`](languages/tr-ru.md) |
| 🇮🇩 Indonesian | [`tr-id.md`](languages/tr-id.md) |
| 🇲🇾 Malay | [`tr-ms.md`](languages/tr-ms.md) |
| 🇮🇹 Italian | [`tr-it.md`](languages/tr-it.md) |
| 🇵🇱 Polish | [`tr-pl.md`](languages/tr-pl.md) |
| 🇳🇱 Dutch | [`tr-nl.md`](languages/tr-nl.md) |
| 🇸🇪 Swedish | [`tr-sv.md`](languages/tr-sv.md) |
| 🇺🇦 Ukrainian | [`tr-uk.md`](languages/tr-uk.md) |
| 🇵🇭 Filipino | [`tr-tl.md`](languages/tr-tl.md) |

</details>

<details>
<summary><strong>🇮🇹 I speak Italian</strong></summary>

| I want to learn | File |
|---|---|
| 🇺🇸 English | [`it-en.md`](languages/it-en.md) |
| 🇰🇷 Korean | [`it-ko.md`](languages/it-ko.md) |
| 🇯🇵 Japanese | [`it-ja.md`](languages/it-ja.md) |
| 🇨🇳 Chinese | [`it-zh.md`](languages/it-zh.md) |
| 🇪🇸 Spanish | [`it-es.md`](languages/it-es.md) |
| 🇫🇷 French | [`it-fr.md`](languages/it-fr.md) |
| 🇩🇪 German | [`it-de.md`](languages/it-de.md) |
| 🇧🇷 Portuguese | [`it-pt.md`](languages/it-pt.md) |
| 🇻🇳 Vietnamese | [`it-vi.md`](languages/it-vi.md) |
| 🇹🇭 Thai | [`it-th.md`](languages/it-th.md) |
| 🇸🇦 Arabic | [`it-ar.md`](languages/it-ar.md) |
| 🇮🇳 Hindi | [`it-hi.md`](languages/it-hi.md) |
| 🇧🇩 Bengali | [`it-bn.md`](languages/it-bn.md) |
| 🇷🇺 Russian | [`it-ru.md`](languages/it-ru.md) |
| 🇮🇩 Indonesian | [`it-id.md`](languages/it-id.md) |
| 🇲🇾 Malay | [`it-ms.md`](languages/it-ms.md) |
| 🇹🇷 Turkish | [`it-tr.md`](languages/it-tr.md) |
| 🇵🇱 Polish | [`it-pl.md`](languages/it-pl.md) |
| 🇳🇱 Dutch | [`it-nl.md`](languages/it-nl.md) |
| 🇸🇪 Swedish | [`it-sv.md`](languages/it-sv.md) |
| 🇺🇦 Ukrainian | [`it-uk.md`](languages/it-uk.md) |
| 🇵🇭 Filipino | [`it-tl.md`](languages/it-tl.md) |

</details>

<details>
<summary><strong>🇵🇱 I speak Polish</strong></summary>

| I want to learn | File |
|---|---|
| 🇺🇸 English | [`pl-en.md`](languages/pl-en.md) |
| 🇰🇷 Korean | [`pl-ko.md`](languages/pl-ko.md) |
| 🇯🇵 Japanese | [`pl-ja.md`](languages/pl-ja.md) |
| 🇨🇳 Chinese | [`pl-zh.md`](languages/pl-zh.md) |
| 🇪🇸 Spanish | [`pl-es.md`](languages/pl-es.md) |
| 🇫🇷 French | [`pl-fr.md`](languages/pl-fr.md) |
| 🇩🇪 German | [`pl-de.md`](languages/pl-de.md) |
| 🇧🇷 Portuguese | [`pl-pt.md`](languages/pl-pt.md) |
| 🇻🇳 Vietnamese | [`pl-vi.md`](languages/pl-vi.md) |
| 🇹🇭 Thai | [`pl-th.md`](languages/pl-th.md) |
| 🇸🇦 Arabic | [`pl-ar.md`](languages/pl-ar.md) |
| 🇮🇳 Hindi | [`pl-hi.md`](languages/pl-hi.md) |
| 🇧🇩 Bengali | [`pl-bn.md`](languages/pl-bn.md) |
| 🇷🇺 Russian | [`pl-ru.md`](languages/pl-ru.md) |
| 🇮🇩 Indonesian | [`pl-id.md`](languages/pl-id.md) |
| 🇲🇾 Malay | [`pl-ms.md`](languages/pl-ms.md) |
| 🇹🇷 Turkish | [`pl-tr.md`](languages/pl-tr.md) |
| 🇮🇹 Italian | [`pl-it.md`](languages/pl-it.md) |
| 🇳🇱 Dutch | [`pl-nl.md`](languages/pl-nl.md) |
| 🇸🇪 Swedish | [`pl-sv.md`](languages/pl-sv.md) |
| 🇺🇦 Ukrainian | [`pl-uk.md`](languages/pl-uk.md) |
| 🇵🇭 Filipino | [`pl-tl.md`](languages/pl-tl.md) |

</details>

<details>
<summary><strong>🇳🇱 I speak Dutch</strong></summary>

| I want to learn | File |
|---|---|
| 🇺🇸 English | [`nl-en.md`](languages/nl-en.md) |
| 🇰🇷 Korean | [`nl-ko.md`](languages/nl-ko.md) |
| 🇯🇵 Japanese | [`nl-ja.md`](languages/nl-ja.md) |
| 🇨🇳 Chinese | [`nl-zh.md`](languages/nl-zh.md) |
| 🇪🇸 Spanish | [`nl-es.md`](languages/nl-es.md) |
| 🇫🇷 French | [`nl-fr.md`](languages/nl-fr.md) |
| 🇩🇪 German | [`nl-de.md`](languages/nl-de.md) |
| 🇧🇷 Portuguese | [`nl-pt.md`](languages/nl-pt.md) |
| 🇻🇳 Vietnamese | [`nl-vi.md`](languages/nl-vi.md) |
| 🇹🇭 Thai | [`nl-th.md`](languages/nl-th.md) |
| 🇸🇦 Arabic | [`nl-ar.md`](languages/nl-ar.md) |
| 🇮🇳 Hindi | [`nl-hi.md`](languages/nl-hi.md) |
| 🇧🇩 Bengali | [`nl-bn.md`](languages/nl-bn.md) |
| 🇷🇺 Russian | [`nl-ru.md`](languages/nl-ru.md) |
| 🇮🇩 Indonesian | [`nl-id.md`](languages/nl-id.md) |
| 🇲🇾 Malay | [`nl-ms.md`](languages/nl-ms.md) |
| 🇹🇷 Turkish | [`nl-tr.md`](languages/nl-tr.md) |
| 🇮🇹 Italian | [`nl-it.md`](languages/nl-it.md) |
| 🇵🇱 Polish | [`nl-pl.md`](languages/nl-pl.md) |
| 🇸🇪 Swedish | [`nl-sv.md`](languages/nl-sv.md) |
| 🇺🇦 Ukrainian | [`nl-uk.md`](languages/nl-uk.md) |
| 🇵🇭 Filipino | [`nl-tl.md`](languages/nl-tl.md) |

</details>

<details>
<summary><strong>🇸🇪 I speak Swedish</strong></summary>

| I want to learn | File |
|---|---|
| 🇺🇸 English | [`sv-en.md`](languages/sv-en.md) |
| 🇰🇷 Korean | [`sv-ko.md`](languages/sv-ko.md) |
| 🇯🇵 Japanese | [`sv-ja.md`](languages/sv-ja.md) |
| 🇨🇳 Chinese | [`sv-zh.md`](languages/sv-zh.md) |
| 🇪🇸 Spanish | [`sv-es.md`](languages/sv-es.md) |
| 🇫🇷 French | [`sv-fr.md`](languages/sv-fr.md) |
| 🇩🇪 German | [`sv-de.md`](languages/sv-de.md) |
| 🇧🇷 Portuguese | [`sv-pt.md`](languages/sv-pt.md) |
| 🇻🇳 Vietnamese | [`sv-vi.md`](languages/sv-vi.md) |
| 🇹🇭 Thai | [`sv-th.md`](languages/sv-th.md) |
| 🇸🇦 Arabic | [`sv-ar.md`](languages/sv-ar.md) |
| 🇮🇳 Hindi | [`sv-hi.md`](languages/sv-hi.md) |
| 🇧🇩 Bengali | [`sv-bn.md`](languages/sv-bn.md) |
| 🇷🇺 Russian | [`sv-ru.md`](languages/sv-ru.md) |
| 🇮🇩 Indonesian | [`sv-id.md`](languages/sv-id.md) |
| 🇲🇾 Malay | [`sv-ms.md`](languages/sv-ms.md) |
| 🇹🇷 Turkish | [`sv-tr.md`](languages/sv-tr.md) |
| 🇮🇹 Italian | [`sv-it.md`](languages/sv-it.md) |
| 🇵🇱 Polish | [`sv-pl.md`](languages/sv-pl.md) |
| 🇳🇱 Dutch | [`sv-nl.md`](languages/sv-nl.md) |
| 🇺🇦 Ukrainian | [`sv-uk.md`](languages/sv-uk.md) |
| 🇵🇭 Filipino | [`sv-tl.md`](languages/sv-tl.md) |

</details>

<details>
<summary><strong>🇺🇦 I speak Ukrainian</strong></summary>

| I want to learn | File |
|---|---|
| 🇺🇸 English | [`uk-en.md`](languages/uk-en.md) |
| 🇰🇷 Korean | [`uk-ko.md`](languages/uk-ko.md) |
| 🇯🇵 Japanese | [`uk-ja.md`](languages/uk-ja.md) |
| 🇨🇳 Chinese | [`uk-zh.md`](languages/uk-zh.md) |
| 🇪🇸 Spanish | [`uk-es.md`](languages/uk-es.md) |
| 🇫🇷 French | [`uk-fr.md`](languages/uk-fr.md) |
| 🇩🇪 German | [`uk-de.md`](languages/uk-de.md) |
| 🇧🇷 Portuguese | [`uk-pt.md`](languages/uk-pt.md) |
| 🇻🇳 Vietnamese | [`uk-vi.md`](languages/uk-vi.md) |
| 🇹🇭 Thai | [`uk-th.md`](languages/uk-th.md) |
| 🇸🇦 Arabic | [`uk-ar.md`](languages/uk-ar.md) |
| 🇮🇳 Hindi | [`uk-hi.md`](languages/uk-hi.md) |
| 🇧🇩 Bengali | [`uk-bn.md`](languages/uk-bn.md) |
| 🇷🇺 Russian | [`uk-ru.md`](languages/uk-ru.md) |
| 🇮🇩 Indonesian | [`uk-id.md`](languages/uk-id.md) |
| 🇲🇾 Malay | [`uk-ms.md`](languages/uk-ms.md) |
| 🇹🇷 Turkish | [`uk-tr.md`](languages/uk-tr.md) |
| 🇮🇹 Italian | [`uk-it.md`](languages/uk-it.md) |
| 🇵🇱 Polish | [`uk-pl.md`](languages/uk-pl.md) |
| 🇳🇱 Dutch | [`uk-nl.md`](languages/uk-nl.md) |
| 🇸🇪 Swedish | [`uk-sv.md`](languages/uk-sv.md) |
| 🇵🇭 Filipino | [`uk-tl.md`](languages/uk-tl.md) |

</details>

<details>
<summary><strong>🇵🇭 I speak Filipino</strong></summary>

| I want to learn | File |
|---|---|
| 🇺🇸 English | [`tl-en.md`](languages/tl-en.md) |
| 🇰🇷 Korean | [`tl-ko.md`](languages/tl-ko.md) |
| 🇯🇵 Japanese | [`tl-ja.md`](languages/tl-ja.md) |
| 🇨🇳 Chinese | [`tl-zh.md`](languages/tl-zh.md) |
| 🇪🇸 Spanish | [`tl-es.md`](languages/tl-es.md) |
| 🇫🇷 French | [`tl-fr.md`](languages/tl-fr.md) |
| 🇩🇪 German | [`tl-de.md`](languages/tl-de.md) |
| 🇧🇷 Portuguese | [`tl-pt.md`](languages/tl-pt.md) |
| 🇻🇳 Vietnamese | [`tl-vi.md`](languages/tl-vi.md) |
| 🇹🇭 Thai | [`tl-th.md`](languages/tl-th.md) |
| 🇸🇦 Arabic | [`tl-ar.md`](languages/tl-ar.md) |
| 🇮🇳 Hindi | [`tl-hi.md`](languages/tl-hi.md) |
| 🇧🇩 Bengali | [`tl-bn.md`](languages/tl-bn.md) |
| 🇷🇺 Russian | [`tl-ru.md`](languages/tl-ru.md) |
| 🇮🇩 Indonesian | [`tl-id.md`](languages/tl-id.md) |
| 🇲🇾 Malay | [`tl-ms.md`](languages/tl-ms.md) |
| 🇹🇷 Turkish | [`tl-tr.md`](languages/tl-tr.md) |
| 🇮🇹 Italian | [`tl-it.md`](languages/tl-it.md) |
| 🇵🇱 Polish | [`tl-pl.md`](languages/tl-pl.md) |
| 🇳🇱 Dutch | [`tl-nl.md`](languages/tl-nl.md) |
| 🇸🇪 Swedish | [`tl-sv.md`](languages/tl-sv.md) |
| 🇺🇦 Ukrainian | [`tl-uk.md`](languages/tl-uk.md) |

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

## Star History

<a href="https://star-history.com/#tykimos/Forced-Language-Learning-Prompt&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=tykimos/Forced-Language-Learning-Prompt&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=tykimos/Forced-Language-Learning-Prompt&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=tykimos/Forced-Language-Learning-Prompt&type=Date" />
 </picture>
</a>

## Contributing

Want to add a new language? Create `{native}-{target}.md` in `languages/` and open a PR.

Found a better phrasing? Issues and PRs are welcome.

## License

[MIT](LICENSE)
