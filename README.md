# youyou-deliberate-practice

A Codex skill that turns the methods of *Peak: Secrets from the New Science of Expertise* by Anders Ericsson and Robert Pool into practical learning workflows: observe a baseline, choose a specific weakness, practice with feedback, correct, retest, and check transfer.

[中文说明](README.zh-CN.md) · [Iteration history](ITERATIONS.md)

## Use it when

- Practice takes time but progress is unclear.
- You need a focused training plan or better feedback.
- You want to choose a coach, practice independently, or address a plateau.
- You need to connect individual skills to real performance.

## Capabilities

One entrypoint routes to 11 capability cards: practice audit, practice design, mental representations, mentor selection, independent practice, plateau diagnosis, attention management, motivation support, workplace training, long-term growth, and memory encoding.

The main execution entrypoint is in English. Detailed cards, source notes, glossary, and the practice sheet are in Chinese. The agent should reply in the user's language.

## Install

Clone into your Codex skills directory, provided the target does not already exist:

```sh
git clone https://github.com/ruoruochen/youyou-deliberate-practice.git ~/.codex/skills/youyou-deliberate-practice
```

If you already have a local installation, compare and back it up before updating. Start a new Codex conversation to discover the installed skill.

## Use

```text
$youyou-deliberate-practice I have 20 minutes a day to practice public speaking. Help me establish a baseline and design a session with feedback and a transfer test.
```

No runtime scripts, API keys, paid services, or original book PDF are required. Use the [practice sheet](resources/practice-sheet.md) to organize a session. Plans stay in the conversation unless the user asks to save them; saved records support viewing, editing, and reversible archival/restoration.

## Evidence and limits

The source basis is the 2016 Chinese edition, translated by Wang Zhenglin. Page references are physical PDF page numbers in the edition used during extraction and may differ from your copy. This repository contains derived workflows, commentary, and short attributed excerpts, not the source PDF or its full extracted text.

The original Chinese entrypoint and cards completed 22 synthetic output cases, 10 routing checks, and 2 explicit installed-path checks. The publication edition translates the entrypoint and adds documentation; it received structural, link, privacy, and translation-consistency checks, not a fresh independent 22-case evaluation. These checks do not demonstrate real-world training effectiveness.

No guarantees of mastery, championships, audience growth, or success after 10,000 hours. This skill does not replace a qualified coach or medical guidance, and it is not an updated systematic review of expertise research.

Distilled using [cangjie-skill](https://github.com/kangarooking/cangjie-skill). The book's authors and publisher have not endorsed this project. Source-book quotations remain attributed to their respective rights holders; no license to the original book is granted by this repository.
