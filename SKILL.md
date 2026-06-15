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
   - Confirm the three required news elements before drafting: time, location, and event. If any of these are missing, ask for them instead of drafting around the gap.
   - Confirm event name, location/platform, organizer, participants, speaker names/titles, and key actions.
   - Confirm whether the target is a concise news release or a freer push-article style draft.
   - If any leadership title is unclear, ask the user instead of guessing.

2. Draft or revise:
   - For academic, competition, research, meeting, or other formal news releases, use a concise three-paragraph structure by default: what happened, what results or outcomes were achieved, and what the participation means or what was gained.
   - Keep formal news short and direct. Emphasize that New Materials teachers and students participated, plus their results and gains. Avoid long exposition that leadership reviewers are likely to delete.
   - For class-style, youth-style, or group-character showcase push articles, allow fuller content and a more lively tone when appropriate.
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
   - Put the original image files in the same output directory as the Word document. Do not place them in a separate image subfolder.

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
- Package layout: Word document and original image files must be side by side at the package root, not inside an `原图` or image subfolder.

Do not claim a document is ready for submission unless the exact date, title, images, and required review information have been verified.
