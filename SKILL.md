---
name: capuarticle
description: Draft, revise, check, and package Chinese school publicity articles and college news releases for the New Materials college style. Use when the user asks to write, polish, review, format, or prepare a school tweet, 学校推文, 新闻稿, 官网新闻动态, 学院宣传稿, or CAPUarticle-style article based on event facts, notes, pictures, or a Word draft.
---

# CAPUarticle

## Quick Start

Use this skill to produce publication-ready Chinese college publicity copy with strict date, title, terminology, image-caption, and submission-package checks.

Before drafting or revising, read `references/writing-requirements.md`. If the user provides a `.docx`, event notes, or images, inspect the actual files first and preserve verified facts. Do not invent participants, dates, titles, policy terms, image contents, or approval names.

The original source document is stored at `assets/新材料学院宣传部新闻稿撰写要求.docx` for traceability.

## Workflow

1. Gather facts:
   - Confirm the event date in exact `YYYY年M月D日` form.
   - Confirm event name, location/platform, organizer, participants, speaker names/titles, and key actions.
   - Confirm whether the target is a concise news release or a freer push-article style draft.
   - If any leadership title is unclear, ask the user instead of guessing.

2. Draft or revise:
   - For news releases, prefer a concise three-part structure and keep it to no more than four paragraphs when possible.
   - For push-article style writing, allow a fuller narrative, but keep wording formal, practical, and suitable for a university official website or school publicity channel.
   - Make the title specific, professional, and aligned with the topic.
   - Preserve all factual information from the user's source material.

3. Apply terminology rules:
   - Use standardized leadership references from the reference file.
   - Do not use `新材料学院团委书记`.
   - Use official public wording for Party meeting names, policy documents, and national policy terms.
   - Avoid sensitive, unlawful, politically incorrect, or religion-related wording.

4. Handle images:
   - Insert or mention images at their corresponding positions in the article.
   - Caption images concisely and accurately.
   - Name original image files in article order as `图1`, `图2`, `图3`, etc.

5. Final check:
   - Ensure the article contains an exact date and does not use vague wording such as `近日`.
   - Check title, facts, paragraphing, official terminology, image captions, and submission naming.
   - When creating a Word deliverable, follow the formatting requirements in `references/writing-requirements.md`.

## Output Expectations

When the user asks for copy only, return the article text plus a short checklist of unresolved facts, if any.

When the user asks for review or polishing, lead with the revised article, then list factual questions or compliance concerns that still need confirmation.

When the user asks to prepare submission materials, provide:

- Word document naming: `【YYYYMMDD】文章标题名称`
- Zip/package naming: the same date-title name
- Image naming: `图1`, `图2`, `图3`, in the order used in the article

Do not claim a document is ready for submission unless the exact date, title, images, and required review information have been verified.
