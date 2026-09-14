---
name: text-compressor
description: Compresses long text (reports, articles, case studies, meeting transcripts, research papers, lecture notes, policy documents) into a clear 1-2 page summary that preserves the key facts, numbers, decisions, and conclusions. Use this skill whenever the user asks to summarize, condense, shorten, compress, boil down, or "give me the short version" of any long document, or pastes a wall of text and asks what it says, even if they don't use the word "summary."
---

# Text Compressor

Turn a long piece of text into a summary that fits on one or two pages, so a busy reader gets everything that matters without reading the original.

## Why this matters

People ask for a summary because they don't have time for the full text. A good summary lets them make the same decision they would have made after reading the whole thing. That means the summary must be *faithful* (nothing invented, nothing distorted) and *complete on the essentials* (the reader is not blindsided later by something the summary left out). Length discipline matters too: a "summary" that runs three pages defeats the purpose.

## Step 1: Read the whole text before writing anything

Read the entire input first. Long documents often bury the most important point near the end (a recommendation, a final decision, a caveat that changes everything). Writing as you go produces summaries that overweight the opening and miss the conclusion.

While reading, note:

- The main purpose of the document (what is it trying to tell or persuade the reader?)
- The 3 to 7 most important points
- Every concrete number, date, name, dollar figure, or deadline that a reader would need
- Any decisions made, recommendations given, or actions required
- Anything the author flags as a risk, caveat, or open question

## Step 2: Decide the target length

Pick a target based on the length of the input, then stick to it.

| Input length | Target summary length |
|---|---|
| Under about 1,500 words (a few pages) | About half a page, 200 to 300 words |
| About 1,500 to 4,000 words | One page, 400 to 500 words |
| Over about 4,000 words, or dense with data and multiple sections | Two pages, 800 to 1,000 words |

Never exceed two pages (roughly 1,000 words). If the source is enormous, compress harder rather than writing longer. If you can cover everything essential in less space than the target, do that. Shorter is better as long as nothing important is lost.

If the user names a length ("half a page," "one paragraph," "two pages"), their instruction wins over this table.

## Step 3: Write the summary

Use this structure. Adapt the section names to fit the document, but keep the order: the bottom line always comes first.

```
# [Title of the original document, or a short descriptive title]

**Bottom line:** One or two sentences stating the single most important takeaway.

## Key points
- 3 to 7 bullets, each one complete idea, each carrying its own facts and numbers.

## Decisions, recommendations, or next steps
- What was decided, recommended, or needs to happen. Include owners and deadlines if the source has them.
- Skip this section only if the source genuinely contains none.

## Details worth knowing
Short paragraphs or bullets covering supporting facts, context, and caveats that a
careful reader would want. This is where the two-page version grows; the one-page
version keeps it brief.
```

For the half-page version, drop the headers and use the bottom line followed by a short bulleted list.

## Rules for the writing itself

**Stay faithful to the source.** Every claim in the summary must come from the text. Don't add outside knowledge, don't guess at what the author "probably meant," and don't soften or strengthen conclusions. If the source is uncertain about something, the summary should be too.

**Keep the specifics.** Numbers, dates, names, and amounts are usually the most valuable content in a document and the easiest to lose. "Revenue grew 18% to $4.2M in Q3" is a summary; "revenue grew a lot" is not.

**Cut the padding, not the substance.** Remove repetition, throat-clearing, background the reader already knows, examples that illustrate a point already made, and transitional filler. Keep the points themselves.

**Use plain language.** Write in short, direct sentences. Replace jargon with plain words unless the term is the standard one the reader would expect. Prefer active voice.

**Preserve structure when it helps.** If the source has a clear structure (three options, five findings, a timeline), reflect it in the summary. Readers find it easier to trust a summary that mirrors the shape of the original.

**Don't editorialize.** The summary reports what the document says. It doesn't comment on whether the document is right, unless the user asked for an evaluation.

## Step 4: Check before delivering

Before handing over the summary, ask yourself:

1. Could a reader make the same decision from this summary as from the full text?
2. Is every number and name accurate to the source?
3. Is it within the length target?
4. Does the first sentence state the most important point?

If any answer is no, revise.

## Examples

**Example 1: Short input, half-page output**

Input: A 900-word internal memo announcing that the marketing team will move from quarterly to monthly campaign planning starting in January, listing three reasons (faster response to competitors, better use of the new analytics tool, and feedback from the sales team), and asking managers to submit their first monthly plan by December 15.

Output:

> **Bottom line:** Marketing moves from quarterly to monthly campaign planning starting in January; managers must submit their first monthly plan by December 15.
>
> - The change is driven by three factors: faster response to competitor moves, better use of the new analytics tool, and requests from the sales team.
> - Quarterly planning continues through the end of December.
> - Questions go to the marketing operations lead.

**Example 2: Long input, one-page output**

Input: A 3,000-word consulting report analyzing whether a regional grocery chain should open a delivery service, with sections on market size, three cost scenarios, competitor analysis, and a final recommendation to pilot in two cities.

Output: A one-page summary with a title, a bottom line stating the recommendation to pilot in two cities and the expected cost, five key points covering market size, the three cost scenarios with their dollar figures, and the competitive picture, a recommendations section listing the pilot cities and timeline, and a short details section noting the report's stated risks and assumptions.

**Example 3: The user gives a length**

If the user says "summarize this in one paragraph," write one paragraph, no headers, leading with the bottom line and packing in the key numbers. The user's length instruction always overrides the default table.
