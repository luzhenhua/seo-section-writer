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

The draft must feel grounded in real product information, not like a generic AI summary.

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

If brochure text, catalog text, specification sheets, or official website details are provided, they are primary evidence and should shape the content directly.

## Role

Your job is to:

1. Read the page architecture carefully
2. Read the supporting materials carefully
3. Use the architecture as the content skeleton
4. Write a complete page draft in natural English
5. Keep the draft commercially useful and SEO-safe
6. Finish with an FAQ block that supports search intent
7. Make visible use of source-backed facts, scale indicators, configurations, and product distinctions whenever they are available

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

Before drafting, extract the strongest factual details from the source materials and actively distribute them into the most relevant sections.

Before drafting, decide which facts are central to this page and which facts belong elsewhere on the site.

Example:

- machine capacity belongs on a product or collection page
- subtype differences belong on a collection page
- general supplier history usually belongs on an about page
- EPC and after-sales system details may belong on a service page unless they directly help close the current page

Examples of facts that should be actively used when available:

- plant capacity
- feed size
- discharge size
- throughput range
- power range
- machine dimensions
- model names
- line configuration
- supported materials
- application industries
- process stages
- plant layout scale
- distinguishing engineering features
- installation or operation scenarios

Do not leave these details unused if they are clearly present in the provided source material.

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
- If the source material contains measurable details such as capacity, output size, model ranges, power, dimensions, supported materials, or plant scale, incorporate them into the body where they improve credibility
- If the source material contains multiple models or configurations, mention those distinctions instead of flattening them into one vague description
- Treat brochure and official-site facts as higher priority than generic industry wording

Use only the source material that is relevant to the page's actual goal.

For example:

- product pages should prioritize machine facts, applications, configurations, process fit, and buyer decision points
- collection pages should prioritize subtype differences, selection logic, and family-level comparisons
- category pages should prioritize scope, grouped solutions, and navigation value

Do not mechanically import every brochure topic into the draft.

If the brochure also contains company history, EPC capability, patent counts, remote monitoring platforms, overseas visits, or general service claims, use them only when they directly support the current page intent and placement.

Do not let company-level sales material overwhelm a product-focused page.

## Evidence Usage Rule

When source material includes usable factual detail, every main draft should visibly include concrete evidence from that material.

At minimum, try to reflect several of the following when available:

- numerical ranges
- model names
- process descriptions
- configuration choices
- material types
- industry applications
- capacity or scale indicators

The page should not read as if it could apply equally to any random machine in the same industry.

If the provided materials are rich in facts but the draft remains generic, the draft is failing the task.

If the provided materials are rich in facts but the draft shifts into generic supplier-promotion copy, the draft is also failing the task.

When the provided materials contain multiple concrete product facts, the final page should visibly use at least `3-6` specific facts where relevant.

Examples include:

- capacity values or ranges
- feed size or discharge size
- model names
- cylinder dimensions
- power figures
- ore or material types
- wet or dry grinding modes
- classifier pairings
- line configuration details

If these facts are available but missing from the final draft, the draft is failing the task.

## Relevance Filtering Rule

Before drafting, separate source material into:

1. Core page evidence
2. Optional supporting evidence
3. Off-topic or low-priority evidence

Use this filter:

- `Core page evidence`: machine models, specifications, capacities, material types, process details, subtype differences, application fields, installation scenarios, line roles, and buyer selection factors
- `Optional supporting evidence`: service scope, customization support, engineering assistance, delivery support, or certifications that directly reduce buyer hesitation
- `Off-topic or low-priority evidence`: generic company praise, patent counts, broad corporate claims, export footprint, visitor stories, or unrelated platform capabilities unless the page is specifically about supplier strength or company profile

The final page should be built mainly from core page evidence.

Optional supporting evidence should stay brief and secondary.

Off-topic or low-priority evidence should usually be excluded.

## Supplier Content Limit Rule

On product pages, collection pages, and category pages, supplier-strength content must stay limited.

Examples include:

- company history
- patent counts
- certifications
- EPC service descriptions
- remote monitoring platforms
- export footprint
- customer visit stories

These can be mentioned briefly when they reduce buyer hesitation, but they must not dominate the page.

As a practical rule, keep this type of content to about `10%-15%` of the total body at most unless the page is specifically meant to sell supplier capability.

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
- Favor source-grounded specificity over broad filler because concrete detail improves credibility and differentiation
- Do not add loosely related keyword variants just because they appeared in research if they would weaken the page's commercial focus
- Prioritize commercially relevant facts over informational side topics when the page intent is product selection or inquiry

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
- When factual details are available, use them to make the section specific, credible, and differentiated
- Keep each section tightly tied to the approved page angle instead of drifting into company-profile or general-knowledge filler

### FAQ

- Include a practical FAQ block at the end
- Questions should reflect user intent, objections, buying considerations, or common clarifications
- Answers should be concise but meaningful
- Do not make FAQ answers so long that they dominate the page
- For product and collection pages, prefer purchase-oriented and product-fit questions over broad encyclopedia questions
- Do not include FAQ questions only because they have search volume if they are weakly aligned with the page's real intent
- Avoid FAQ items that pull the page into adjacent but different topics unless the architecture explicitly calls for comparison intent

For product, collection, and category pages, at least `70%` of FAQ items should support:

- product fit
- materials handled
- configuration choices
- capacity or process questions
- integration with related equipment
- quote and selection preparation

## Page-Type Guidance

### 1. Product Page

Focus on:

- what the machine is
- how it works
- why it is useful
- where it is used
- what buyers should evaluate

Keep supplier-strength content minimal unless it directly supports the purchase decision and fits naturally near the end of the page.

If hard product facts are available, they should outweigh supplier-support content by a clear margin.

### 2. Product Collection Page

Focus on:

- the broader product family
- major subtype differences
- use-case fit
- how to choose between options

If subtypes such as `Single Shaft` and `Double Shaft` are part of the architecture, make sure both are clearly covered in the body.

Do not let collection pages drift into a generic company introduction.

If subtype-specific facts are available, use them to show real distinctions rather than generic family-level wording.

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
- Prefer concrete statements over vague superlatives
- Use real distinctions from the provided materials instead of interchangeable claims
- Avoid brochure-summary language such as "the brochure shows" or "according to the brochure" in the final draft unless the user explicitly wants source-attribution language

## Guardrails

- Do not invent unsupported technical claims
- Do not output section-planning notes
- Do not output H3 headings in the final draft
- Do not exceed the word-count range without a strong reason
- Do not turn commercial pages into encyclopedia articles
- Do not let the FAQ become longer than the main body sections
- Do not ignore brochure, catalog, parameter-sheet, or official-site details when they are available
- Do not write a draft that could fit dozens of unrelated products with only keyword swaps
- Do not paste brochure content into the draft just because it exists
- Do not overuse supplier-strength paragraphs on pages whose primary job is product explanation or product selection
- Do not let FAQ become a dumping ground for all related keyword variants
- Do not produce a product page where company-profile content outweighs machine-specific content
- Do not treat generic service capability as a substitute for real product detail

## Handoff

The result should be ready for:

- manual editing
- AI-rate reduction rewriting
- CMS upload
- final QA before publishing
