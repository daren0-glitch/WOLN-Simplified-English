# WOLN — Simplified English

**World Open Language for the Internet and AI Era**

**V0.8 Draft · 2026-11-11**

WOLN is an open proposal for a simplified form of English for international communication on the Internet and with AI. It keeps familiar English words and word order while reducing the grammar changes and long forms a writer needs to use. The project develops a language specification through public research and community review.

## How it works

| Standard English | Canonical WOLN |
| --- | --- |
| She sent two files yesterday. | She send 2 file yday. |
| I will send the photo tomorrow. | I send photo tmr. |
| Please send me that message. | Pls send me that msg. |

Use familiar English vocabulary and the subject–verb–object order where the sentence has an object. Use a base verb form across subjects and times, a number plus a singular noun for explicit counts, and time words or dates where timing matters. Canonical WOLN usually omits articles and uses words such as `this` and `that` for specific references. Full English words are always accepted. Standard English sentences are also compatible input, including their ordinary articles and inflections.

The examples illustrate the draft. The [starter lexicon](lexicon/core-words.csv) records each short form as a candidate for community review. WOLN is a research proposal with no claim of formal international adoption.

## Read the draft

- [Vision](docs/vision.md)
- [V0.8 grammar](docs/grammar-v0.8.md)
- [Short words](docs/short-words.md) and [starter lexicon](lexicon/core-words.csv)
- [Basic conversations](examples/basic-conversations.md) and [English–WOLN comparisons](examples/english-woln-comparison.md)
- [Spoken-language roadmap](docs/spoken-language-roadmap.md)
- [Language Skill prototype](skills/woln-language/SKILL.md) (runtime validation `NOT RUN`)

## Roadmap

1. Refine the written rules and candidate forms using examples from international readers.
2. Research English-like short readings, then test human comprehension and automatic speech recognition (ASR) separately.
3. Record proposed changes, test evidence and review outcomes in GitHub and the [changelog](CHANGELOG.md).

## Contribute

Open a GitHub Issue with the source sentence, a proposed WOLN rendering and any ambiguity you observe. For substantial changes, use a separate branch and pull request for review. See [Contributing](CONTRIBUTING.md) and the [MIT License](LICENSE).

## 繁體中文簡介

WOLN 是面向網路與 AI 時代的簡化英語公開草案。它保留常見英語詞彙與語序，允許原本的英文全形，並以時間詞、日期及數量表達關鍵資訊。V0.8 先整理書寫用法。口語短讀將另做跨語言理解與語音辨識測試。
