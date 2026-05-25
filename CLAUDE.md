# Claude Code Instructions

This repository contains a reusable Chinese prose editing guide inspired by the narrative methods summarized from the local A Cheng sample texts.

## Trigger

When the user asks in Chinese to:

- 去除ai味
- 去除 AI 味
- 去 AI 痕迹
- 改得更像人写的
- 写得更朴素、更具体、更口语
- 检查哪里有 AI 味
- 做一遍反 AI 味自检
- 按阿城味、阿城式、阿城笔法润色

apply this repository's style guide.

## Required Context

Read `style-guide.md` before substantial rewriting, drafting, or style diagnosis.

Use `acheng_1.md` and `acheng_2.md` only as local reference samples when a deeper style pass is needed. Do not copy protected sentences, scenes, characters, or distinctive passages from the samples.

## Working Rules

1. Preserve the user's meaning, facts, names, and plot unless they ask for freer adaptation.
2. Remove obvious AI-writing traits: abstract summaries, grand claims, tidy three-part structures, slogans, and quote-like endings.
3. Replace emotion and explanation with visible action, concrete objects, dialogue, sound, body movement, and small social details.
4. Prefer short and medium Chinese sentences with spoken rhythm.
5. Use concrete nouns and grounded numbers where possible.
6. Remove the hard-forbidden AI-flavor patterns in `style-guide.md`, including stock transitions, textbook openings, over-structured bullets, vague tool names, fake examples, and slogan endings.
7. For final Chinese prose, avoid colon, em dash, and double quotation marks unless the user explicitly needs them. Use 「」 for necessary quotes.
8. Keep humor low-key and judgment indirect.
9. End rewritten scenes on an action, line of dialogue, or concrete image when possible.

## Self-Check

For 去除ai味 or style-polishing tasks, run the four-layer self-check in `style-guide.md` before final output:

1. L1 hard rules
2. L2 style consistency
3. L3 content support
4. L4 human feel

Only output the QA report when the user asks for it or when there are important unresolved issues. Otherwise, use the check silently and deliver the revised prose.

## Output Format

For rewriting tasks, put the revised Chinese text first.

If notes are useful, add a short section after the text explaining the main changes. Keep the notes brief; the rewritten prose should do most of the work.

For close style imitation requests, say the result follows summarized techniques and is not a direct copy of the source texts.
