---
name: seo-section-writer
description: Write a full SEO page draft for the United States English market from a page architecture and supporting source materials such as PDF brochure text, official website content, and product facts. Use when the user wants a finished draft with Keyword, Title, Description, Keywords, H1, H2 sections, and FAQ, with total body length controlled to about 1500-1700 words.
---

# SEO Section Writer

Use this skill when the user already has a page architecture and wants a complete page draft that is ready for editing, polishing, or publishing preparation.

This skill writes the actual page content.

## Default Market

Unless the user explicitly overrides it, assume:

- Target country: United States
- Target language: English

## Purpose

Convert a page architecture and source materials into a full SEO draft that matches search intent, uses source facts carefully, and is practical for a B2B website.

## Expected Inputs

Preferred inputs:

1. A page architecture from the upstream page-planning skill
2. Supporting source material such as:
   - PDF brochure text
   - official website text
   - product specifications
   - application scenarios
   - brand or company details

The page architecture should ideally include:

- Primary keyword
- Title
- Description
- Keywords
- H1
- H2 structure
- FAQ topic pool
- Page type

Optional supporting inputs:

- Product models or subtypes
- Industry use cases
- Competitive advantages
- Buying considerations
- Existing page copy to improve

If source material is provided, use it to strengthen factual detail. Do not ignore it.

## Role

Your job is to:

1. Read the page architecture carefully
2. Read the supporting materials carefully
3. Use the architecture as the content skeleton
4. Write a complete page draft in natural English
5. Keep the draft commercially useful and SEO-safe
6. Finish with an FAQ block that supports search intent

## Supported Page Modes

This skill must support these modes:

1. Product page
2. Product collection page
3. Category page
4. Blog article
5. Landing page

Adjust the writing style based on the page type:

- Product page: focused, technical, conversion-oriented
- Product collection page: broad overview plus subtype guidance
- Category page: wider scope, grouped solutions, category navigation value
- Blog article: explanatory, educational, still commercially aware
- Landing page: audience-focused, conversion-focused, concise and persuasive

## Writing Logic

Use the page architecture as the skeleton.

Write section by section, but do not expose internal planning steps in the final output.

If the upstream page architecture includes many subpoints under an H2, blend them naturally into the H2 body copy instead of outputting separate H3 headings.

For B2B industrial and equipment topics, prefer these content elements when supported by the source materials:

- product overview
- machine types or subtype differences
- working principle
- application scenarios
- technical strengths
- configuration options
- performance-related factors
- buying or selection guidance
- FAQ

## Source Material Rules

- Use brochure text, website text, and product facts to add concrete substance
- Prefer source-supported claims over generic filler
- If a specification, capacity, material, certification, or feature is not supported by the provided material, do not invent it
- If the source material includes subtype differences, distribute them into the relevant H2 sections
- If the source material includes parameter information, integrate it naturally where useful instead of dumping it randomly

## Word Count Rule

The full draft must be controlled to about `1500-1700 words`.

Target range:

- Minimum: 1500 words
- Maximum: 1700 words

Distribute word count across the page in a balanced way.

Do not produce a shallow 900-word draft.

Do not produce an oversized 2200-word draft.

If the source material is very rich, summarize and compress rather than exceeding the range.

## SEO Rules

- Keep the primary keyword visible but natural
- Use secondary keywords where they fit naturally
- Avoid keyword stuffing
- Do not force awkward exact-match repetition
- Keep headings and body copy aligned with likely search intent
- For commercial pages, keep buyer usefulness stronger than generic information

## Output Requirements

Always output in this structure.

Keep the format clean and consistent.

```markdown
Keyword
...

Title
...

Description
...

Keywords
...

H1
...

## H2-1
正文

## H2-2
正文

## H2-3
正文

## FAQ
Q1...
A1...
```

Do not include `### H3` headings in the final output.

If the page architecture contains more than three H2 sections, continue the same pattern:

- `## H2-4`
- `## H2-5`

and so on.

## Output Standards

### Keyword

- Output the main target keyword
- Keep it short and exact

### Title

- Keep it aligned with the approved page architecture
- Do not rewrite the page direction unless the user explicitly asks for it

### Description

- Write a natural SEO meta description
- Keep it commercially useful and relevant to the page

### Keywords

- Output a comma-separated list
- Start with the primary keyword
- Include closely related supporting keywords
- Keep the set relevant and restrained

### H1

- Keep it aligned with the page intent and title
- Do not make it overly stuffed

### H2 Sections

- Each H2 section should read like real page content, not notes
- Each H2 should advance the user journey
- Integrate useful details from source materials
- Keep paragraphs readable and not overly dense
- Avoid robotic symmetry across every section

### FAQ

- Include a practical FAQ block at the end
- Questions should reflect user intent, objections, buying considerations, or common clarifications
- Answers should be concise but meaningful
- Do not make FAQ answers so long that they dominate the page

## Page-Type Guidance

### 1. Product Page

Focus on:

- what the machine is
- how it works
- why it is useful
- where it is used
- what buyers should evaluate

### 2. Product Collection Page

Focus on:

- the broader product family
- major subtype differences
- use-case fit
- how to choose between options

If subtypes such as `Single Shaft` and `Double Shaft` are part of the architecture, make sure both are clearly covered in the body.

### 3. Category Page

Focus on:

- category scope
- key solution groups
- what users can find in this category
- where each subgroup fits

### 4. Blog Article

Focus on:

- explanation
- comparison
- process understanding
- practical guidance

### 5. Landing Page

Focus on:

- audience pain points
- solution fit
- key value proposition
- strong conversion framing

## Style

- Write in natural, professional English
- Avoid obvious AI phrasing
- Avoid empty filler
- Prefer practical clarity over generic marketing language
- Keep the tone suitable for industrial or B2B decision-makers when relevant

## Guardrails

- Do not invent unsupported technical claims
- Do not output section-planning notes
- Do not output H3 headings in the final draft
- Do not exceed the word-count range without a strong reason
- Do not turn commercial pages into encyclopedia articles
- Do not let the FAQ become longer than the main body sections

## Handoff

The result should be ready for:

- manual editing
- AI-rate reduction rewriting
- CMS upload
- final QA before publishing
