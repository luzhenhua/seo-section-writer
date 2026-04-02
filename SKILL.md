---
name: seo-section-writer
description: Write a full SEO page draft for the United States English market from a page architecture and supporting source materials such as PDF brochure text, official website content, and product facts. Use when the user wants a finished draft with Keyword, Title, Description, Keywords, H1, H2 sections, and FAQ, written in a cross-industry commercial style that is specific, evidence-led, and conversion-aware rather than generic SEO prose.
---

# SEO Section Writer

Use this skill when the user already has a page architecture and wants a complete page draft that is ready for editing, polishing, or publishing preparation.

This skill writes the actual page content.

## Default Market

Unless the user explicitly overrides it, assume:

- Target country: United States
- Target language: English

## Purpose

Convert a page architecture and source materials into a full SEO draft that matches search intent, uses source facts carefully, and reads like practical commercial content.

The draft must feel grounded in real product, service, or process information. It must not read like a generic AI explainer.

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
- Page type
- Narrative angle
- Commercial depth
- Evidence density
- CTA intensity
- H2 structure
- Evidence blocks to include
- Brand insert points
- FAQ topic pool

Optional supporting inputs:

- Product models or subtypes
- Industry use cases
- Competitive advantages
- Buying considerations
- Existing page copy to improve

If source material is provided, use it to strengthen factual detail. Do not ignore it.

If brochure text, catalog text, specification sheets, or official website details are provided, they are primary evidence and should shape the content directly.

## Role

Your job is to:

1. Read the page architecture carefully
2. Read the supporting materials carefully
3. Use the architecture as the content skeleton
4. Write a complete page draft in natural English
5. Keep the draft commercially useful and SEO-safe
6. Use the requested evidence blocks so the page feels specific
7. Finish with an FAQ block that supports search intent and conversion

## Core Writing Standard

The page should help the reader make progress in a decision.

That decision may be:

- understanding the right solution
- comparing options
- choosing a model or configuration
- checking application fit
- reducing buying risk
- preparing for inquiry

Do not write the page as a neutral textbook article unless the keyword clearly requires that.

## Writing Logic

Use the page architecture as the skeleton.

Write section by section, but do not expose internal planning steps in the final output.

If the architecture contains many subpoints under an H2, blend them naturally into the H2 body copy instead of outputting separate H3 headings.

Before drafting:

1. identify the page's decision job
2. identify the strongest available evidence
3. identify where the brand should appear naturally
4. decide which sections should carry the strongest commercial weight

## Source Material Rules

- Use brochure text, website text, and product facts to add concrete substance
- Prefer source-supported claims over generic filler
- If a specification, capacity, material, certification, or feature is not supported by the provided material, do not invent it
- If the source material includes subtype differences, distribute them into the relevant H2 sections
- If the source material includes parameter information, integrate it where useful instead of dumping it randomly
- If the source material contains measurable details such as capacity, output size, model ranges, power, dimensions, supported materials, or plant scale, incorporate them where they improve credibility
- If the source material contains multiple models or configurations, mention those distinctions instead of flattening them into one vague description
- Treat brochure and official-site facts as higher priority than generic industry wording

## Evidence Usage Rule

When source material includes usable factual detail, every main draft should visibly include concrete evidence from that material.

Try to reflect several of the following when available:

- numerical ranges
- model names
- process descriptions
- configuration choices
- material types
- industry applications
- capacity or scale indicators
- standards or compliance references
- buying inputs needed for quotation

If the provided materials are rich in facts but the draft remains generic, the draft is failing the task.

## Evidence Block Rule

If the page architecture requests evidence blocks, use them.

Possible blocks include:

- parameter snapshot
- compact comparison table
- model-selection checklist
- application suitability list
- process flow summary
- pricing factors list
- quote preparation checklist

These blocks should support scanning and decision-making. They should not dominate the page.

Do not invent complete tables if only partial facts are available.

## Relevance Filtering Rule

Before drafting, separate source material into:

1. Core page evidence
2. Optional supporting evidence
3. Off-topic or low-priority evidence

Use this filter:

- `Core page evidence`: models, specifications, capacities, materials, process details, subtype differences, application fields, installation scenarios, line roles, buying criteria
- `Optional supporting evidence`: customization support, engineering help, delivery support, installation support, spare parts, after-sales response
- `Off-topic or low-priority evidence`: generic company praise, patent counts, export footprint, visitor stories, or unrelated service claims unless the page is specifically about supplier strength

Build mainly from core page evidence.

## Supplier Content Limit Rule

On product pages, collection pages, category pages, and most commercial blog articles, supplier-strength content must stay secondary.

As a practical rule, keep this type of content to about `10%-15%` of the total body at most unless the page is specifically meant to sell supplier capability.

If there is a dedicated trust-oriented section such as `Why Choose` or `Why Work With`, keep it concise.

## FTM-Inspired Style Rules

When the keyword and source material support it, prefer these moves:

- open with the buyer problem, use case, or decision instead of a dictionary-style definition
- compare options when the reader is likely weighing alternatives
- mention parameters, use conditions, or configuration choices early enough to be useful
- connect educational content to commercial next steps naturally
- distribute light brand mentions throughout the page instead of hiding them all in the last paragraph

Do not mimic mining-industry vocabulary for unrelated sectors.

Adapt the same logic to the industry's own buying criteria, units, and evidence types.

## Word Count Rule

The full draft should usually be controlled to about `1500-1700 words`.

Target range:

- Minimum: 1450 words
- Maximum: 1750 words

If the page needs to be shorter or longer because the user explicitly requests it, follow the user's request.

## SEO Rules

- Keep the primary keyword visible but natural
- Use secondary keywords where they fit naturally
- Avoid keyword stuffing
- Do not force awkward exact-match repetition
- Keep headings and body copy aligned with likely search intent
- For commercial pages, keep buyer usefulness stronger than generic information
- Favor source-grounded specificity over broad filler
- Do not add loosely related keyword variants just because they appeared in research if they weaken the page's commercial focus
- Do not expose internal SEO reasoning, keyword-research logic, or prompt-process commentary in the final draft

## Output Requirements

Always output in this structure:

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

When the source materials contain usable specifications, model distinctions, capacity ranges, or configuration differences, do not make the page pure prose.

Include at least one compact structured block when relevant, such as:

- a short specification summary
- a model comparison list
- a configuration highlights block
- a compact markdown table

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
- When factual details are available, use them to make the section specific, credible, and differentiated
- Keep each section tightly tied to the approved page angle instead of drifting into company-profile or broad encyclopedia filler
- Use brand mentions where the architecture says they belong, and keep them natural

### FAQ

- Include a practical FAQ block at the end
- Questions should reflect user intent, objections, buying considerations, or common clarifications
- Answers should be concise but meaningful
- For product and collection pages, prefer purchase-oriented and fit-oriented questions over broad encyclopedia questions
- At least `70%` of FAQ items on commercial pages should support fit, configuration, process questions, integration, quotation preparation, or supplier evaluation

## Page-Type Guidance

### 1. Product Page

Focus on:

- what the product is for
- how it works or operates
- where it fits
- what specs or options matter
- how to choose the right version

### 2. Product Collection Page

Focus on:

- the broader product family
- major subtype differences
- use-case fit
- how to choose between options

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
- a soft commercial bridge when appropriate

### 5. Landing Page

Focus on:

- audience pain points
- solution fit
- proof points
- strong conversion framing

## Style

- Write in natural, professional English
- Avoid obvious AI phrasing
- Avoid empty filler
- Prefer practical clarity over generic marketing language
- Keep the tone suitable for industrial or B2B decision-makers when relevant
- Prefer concrete statements over vague superlatives
- Use real distinctions from the provided materials instead of interchangeable claims
- Avoid brochure-summary language such as `the brochure shows` or `according to the brochure` unless the user explicitly wants source-attribution language
- Avoid meta-writing language such as `the uploaded material`, `the keyword brief shows`, or `users searching this term`

## Guardrails

- Do not invent unsupported technical claims
- Do not output section-planning notes
- Do not output H3 headings in the final draft
- Do not let the draft become a generic SEO explainer if the architecture calls for decision support
