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
- Evidence alignment check
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
3. Extract useful facts from the supporting materials before writing
4. Use the architecture as the content skeleton
5. Write a complete page draft in natural English
6. Keep the draft commercially useful and SEO-safe
7. Use the requested evidence blocks so the page feels specific
8. Finish with an FAQ block that supports search intent and conversion

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
3. check whether the architecture already flagged evidence mismatch risk
4. identify where the brand should appear naturally
5. decide which sections should carry the strongest commercial weight

Do not move from source review to drafting too quickly.

When company documents, brochures, catalogs, product sheets, case materials, or official website text are available, review them as working evidence rather than as background reading.

At minimum, try to extract:

- machine or product facts
- model names
- parameter ranges
- application details
- process descriptions
- configuration options
- buyer-relevant service details
- quotation or selection inputs

If the source pack is rich, the final page should visibly reflect that richness.

## Source Material Rules

- Use brochure text, website text, and product facts to add concrete substance
- Prefer source-supported claims over generic filler
- If a specification, capacity, material, certification, or feature is not supported by the provided material, do not invent it
- If the source material includes subtype differences, distribute them into the relevant H2 sections
- If the source material includes parameter information, integrate it where useful instead of dumping it randomly
- If the source material contains measurable details such as capacity, output size, model ranges, power, dimensions, supported materials, or plant scale, incorporate them where they improve credibility
- If the source material contains multiple models or configurations, mention those distinctions instead of flattening them into one vague description
- Treat brochure and official-site facts as higher priority than generic industry wording
- If both company documents and official website content are available, actively compare them and use the combination to improve completeness and precision
- Do not skim rich source material and then write from memory or generic industry patterns

## Source Review Workflow

When source material is substantial, follow this workflow before drafting:

1. review the page architecture so you know what evidence the page needs
2. scan all provided company documents and official-site text for relevant facts
3. extract the most decision-relevant facts into a mental shortlist
4. separate facts into:
   - product or service facts
   - application or process facts
   - supplier-support facts
5. discard low-value corporate filler unless the page specifically needs it
6. map the strongest facts to the sections where they belong

Do not rely on one quick pass through one document if multiple sources are available.

If both an official website and company documents are available, treat them as complementary:

- use official-site material for current positioning, scope, and presentational wording
- use documents for deeper specifications, configurations, process fit, and supporting detail

If the user explicitly provides a company document for the target business, that document must be treated as a primary source, not optional flavor text.

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

If the provided materials are rich in facts but only one or two weak details appear in the final page, the draft is also failing the task.

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

If the provided company document contains many facts but most of them land in `Off-topic or low-priority evidence`, pause and re-check whether the page architecture is correct or whether the writer is overlooking relevant material.

## Supplier Content Limit Rule

On product pages, collection pages, category pages, and most commercial blog articles, supplier-strength content must stay secondary.

As a practical rule, keep this type of content to about `10%-15%` of the total body at most unless the page is specifically meant to sell supplier capability.

If there is a dedicated trust-oriented section such as `Why Choose` or `Why Work With`, keep it concise.

## Corporate Writing Risk Rule

If the brand is a listed company, regulated business, or otherwise sensitive to public-facing claims, use a stricter writing standard.

Under this standard:

- avoid soft, second-hand phrasing such as `describes itself as`, `states that`, `mentions`, `claims`, or similar brochure-summary language in normal page copy
- do not present company capability through vague prestige wording when the buyer-facing operational value is unclear
- prefer direct, concrete wording tied to a buyer outcome, project stage, service scope, or verifiable company fact
- if a fact is sensitive, not clearly sourced, or too promotional, either omit it or rewrite it into a lower-risk operational statement
- keep certifications, patents, awards, platform capabilities, and service claims proportionate to the page's real purpose

Bad pattern:

- `The company states that it has...`
- `It also mentions...`

Better pattern:

- `For full-line projects, the supplier can support installation and commissioning.`
- `The company also offers remote monitoring and diagnostic support for larger systems.`

When source attribution is necessary, use clean attribution rather than brochure-summary phrasing.

Examples:

- `According to the company's official website, the service scope includes installation and commissioning support.`
- `The company reports ISO9001 certification and after-sales service coverage.`

Use explicit attribution only when legal, compliance, or accuracy risk makes it necessary.

## FTM-Inspired Style Rules

When the keyword and source material support it, prefer these moves:

- open with the buyer problem, use case, or decision instead of a dictionary-style definition
- compare options when the reader is likely weighing alternatives
- mention parameters, use conditions, or configuration choices early enough to be useful
- connect educational content to commercial next steps naturally
- distribute light brand mentions throughout the page instead of hiding them all in the last paragraph

Do not mimic mining-industry vocabulary for unrelated sectors.

Adapt the same logic to the industry's own buying criteria, units, and evidence types.

## Brand and Trust Writing Rule

Brand-support content must sound publishable for a serious corporate website.

Use these rules:

- connect trust points to buyer relevance such as delivery, engineering coordination, installation, commissioning, diagnostics, spare parts, or service response
- avoid stacking awards, certifications, patents, and slogans in one dense paragraph
- do not use investor-relations tone, self-congratulatory phrasing, or unsupported superlatives
- when mentioning certifications or capabilities, keep the wording factual and restrained
- if the page is product-led, trust content should support the machine decision rather than overshadow it
- brand or trust sections must include at least one concrete, verifiable fact from the source material, such as years in operation, countries served, specific certifications, production capacity, named service capabilities, or project types completed
- if no such facts are available from source material, keep the brand section to two or three sentences maximum and do not pad it with generic trust language that could apply to any company in any industry

## Word Count Rule

The full draft should usually be controlled to about `1500-1700 words`.

Target range:

- Minimum: 1450 words
- Maximum: 1750 words

If the page needs to be shorter or longer because the user explicitly requests it, follow the user's request.

### Evidence-Short Downgrade

If source material is thin or absent and the page cannot reach 1450 words with substantive, non-repetitive content, reduce the word count rather than padding.

Rules:

- A 1000-word page with real content is better than a 1700-word page filled with vague qualifiers
- Do not repeat the same list of factors (such as material type, feed size, target fineness, capacity) across multiple sections to reach the word count
- Do not use phrases like `depends on your project`, `should be confirmed during selection`, or `varies based on requirements` as paragraph filler
- If you cannot write a section with at least one concrete, decision-useful statement, the section should be shorter or merged with another section
- When downgrading, add a short note at the end of the draft: `[Writer note: source material was limited; some sections are shorter than typical. Additional product data would strengthen this page.]`

## SEO Rules

- Keep the primary keyword visible but natural
- Use secondary keywords where they fit naturally
- Avoid keyword stuffing
- Do not force awkward exact-match repetition
- Keep headings and body copy aligned with likely search intent
- For commercial pages, keep buyer usefulness stronger than generic information
- Favor source-grounded specificity over broad filler
- Do not add loosely related keyword variants just because they appeared in research if they weaken the page's commercial focus
- Prefer one stable primary term in body copy instead of repeatedly cycling through near-duplicate keyword variants
- Use secondary variants only when they are semantically useful in that sentence, heading, table, FAQ, or CTA
- Do not expose internal SEO reasoning, keyword-research logic, or prompt-process commentary in the final draft

## Topic Mismatch Rule

If the page architecture, keyword target, and source materials clearly point to different topics, do not silently rewrite the page into a new topic.

Instead:

1. detect the mismatch explicitly
2. state briefly why the supplied evidence does not support the requested page well
3. propose the most evidence-supported replacement topic or page type
4. stop and ask for direction unless the user has already authorized topic correction

Do not continue with a rewritten page on a different topic as if nothing changed.

If the requested page can still be written with limited evidence, say that clearly and keep the unsupported parts restrained.

If a mismatch is detected and user direction is required, output a short `Mismatch Notice` and pause drafting:

```markdown
## Mismatch Notice
- Requested Topic:
- Evidence-Supported Topic:
- Why They Conflict:
- Recommended Next Step:
```

## Published-Page Language Rule

When writing final website copy, treat company documents, brochures, catalogs, and official website text as evidence sources, not as the narrative subject of the page.

Avoid repetitive source-led phrasing such as:

- `the company's published materials show`
- `the catalog lists`
- `the product line includes`
- `the company's service materials highlight`
- `the company presents`

Those phrases may be acceptable in internal notes, but they weaken a public-facing page.

Preferred pattern:

- extract the fact from the source
- rewrite it into direct website language
- keep explicit attribution only when it is necessary for caution or compliance

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

## H2 Title: Buyer Problem and Fit
Body copy for this section.

## H2 Title: Process or Working Logic
Body copy for this section.

## H2 Title: Selection Guidance and Next Step
Body copy for this section.

## FAQ
Q1...
A1...
```

Do not include `### H3` headings in the final output.

The final draft must use the actual section titles from the page architecture or clean writer-ready equivalents.

Do not output placeholder headings such as:

- `## H2-1`
- `## H2-2`
- `## Section 1`
- `## Main Content`

If the page architecture contains more than three H2 sections, continue the same pattern with real headings.

When the source materials contain usable specifications, model distinctions, capacity ranges, or configuration differences, do not make the page pure prose.

Include at least one compact structured block when relevant, such as:

- a short specification summary
- a model comparison list
- a configuration highlights block
- a compact markdown table

## Formatting Rule

The final draft should look like publishable markdown, not pasted source notes.

Use these rules:

- use valid markdown headings
- use `-` for bullet lists
- use standard markdown tables when tables are needed
- do not output unusual bullet glyphs copied from PDFs or slides, such as copied-dot symbols
- do not leave untranslated placeholder text in non-target languages
- keep structured blocks clean and scannable
- do not let formatting collapse into one long run of paragraphs if the page architecture calls for sections, lists, or tables

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
- Each H2 must have a real, decision-relevant title
- Integrate useful details from source materials
- Keep paragraphs readable and not overly dense
- Avoid robotic symmetry across every section
- When factual details are available, use them to make the section specific, credible, and differentiated
- Keep each section tightly tied to the approved page angle instead of drifting into company-profile or broad encyclopedia filler
- Use brand mentions where the architecture says they belong, and keep them natural
- If the brand is sensitive to public claims, prefer verifiable operational wording over promotional corporate phrasing

### FAQ

- Include a practical FAQ block at the end
- Questions should reflect user intent, objections, buying considerations, or common clarifications
- Answers should be concise but meaningful
- For product and collection pages, prefer purchase-oriented and fit-oriented questions over broad encyclopedia questions
- At least `70%` of FAQ items on commercial pages should support fit, configuration, process questions, integration, quotation preparation, or supplier evaluation
- Every FAQ answer must lead with a direct, usable response before adding any qualifiers. If the answer is yes or no with conditions, say yes or no first
- Never write an FAQ answer that consists entirely of `it depends`, `consult your supplier`, `should be confirmed during selection`, or similar deferrals. These are non-answers
- If you cannot give a concrete answer to a planned FAQ question because evidence is missing, replace it with a question you can answer with available information
- A good FAQ answer teaches the reader something or helps them take a next step. A bad FAQ answer sends them away knowing nothing more than before

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
- Avoid weak attribution verbs such as `describes itself as`, `states that`, `mentions`, or `claims` in normal commercial copy unless explicit attribution is legally or editorially necessary

### AI Writing Anti-Patterns

Do not use these patterns. They are the most common signals of machine-generated content:

- Excessive hedging in place of substance: `may`, `might`, `can potentially`, `it is worth noting that`, `it is important to consider`
- Filler openers: `In today's competitive landscape...`, `When it comes to...`, `It is important to note that...`
- Non-committal statements disguised as content: `depends on your project`, `should be confirmed during selection`, `varies based on requirements`, `the right choice depends on many factors`
- Repeating the same list of variables (such as material type, feed size, target fineness, capacity) across multiple sections as if each repetition adds new value
- Symmetrical paragraph structures where every section follows the same pattern: general statement, bullet list, closing qualifier
- Overuse of passive voice: `is used`, `is designed`, `is typically selected`, `is often considered`
- Paragraphs that could apply to any product in any industry with no change. If you can swap the product name and the paragraph still works, it is too generic
- Ending sections with a variation of `contact us to learn more` or `the right solution depends on your specific needs`

## Guardrails

- Do not invent unsupported technical claims
- Do not inflate company qualifications, certifications, patents, platform functions, or service scope beyond what is clearly supported
- Do not write promotional corporate-profile copy that would look risky or imprecise on a listed company's website
- Do not silently change the topic when source materials and page architecture do not match
- Do not output placeholder H2 labels instead of real section titles
- Do not output source-summary language as the dominant voice of the page
- Do not output section-planning notes
- Do not output H3 headings in the final draft
- Do not let the draft become a generic SEO explainer if the architecture calls for decision support
