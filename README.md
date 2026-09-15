# bus-4040-week-3-homework-skill

A Claude skill called **text-compressor** for BUS 4040, Week 3.

## What it does

Compresses long text (reports, articles, case studies, transcripts, research papers) into a faithful 1-2 page summary. The summary leads with the bottom line, keeps every important number and decision, and cuts padding rather than substance. Length scales with the input: about half a page for short documents, one page for medium ones, and two pages for long or data-heavy ones.

## How it works

The skill can be activated by running /text-compressor or asking it to summarize a text (It can pick up on that automatically). What it does from there is Claude reads the text, picks a target shortened length based on the original word count. It then picks the most important points, keeps numbers, and cuts fluff.

## Why I created this skill

I created this skill because I was slightly stumped on what to make so I went on to my philosophy homework, and realized I could get it done faster by compressing text. I often find myself crunched on time or unwanting to read large texts, and this will help with that.

## How the skill can be useful later

This skill can be useful for classes that assign long homework readings or for helping someone else quickly understand something I wrote. It can also help you decide at a glance if a source is worth reading and using for a project, or even summarize notes quickly before a test.

## Files

- `SKILL.md` - the skill itself. The header tells Claude when to use it; the body tells Claude how.
- `examples/plato-republic-summary.md` - a real one-page summary the skill produced from a six-page PDF excerpt of Plato's *Republic*.

## How to use it

1. Copy this folder into your Claude skills directory (for Claude Code, that's `.claude/skills/` inside a project or `~/.claude/skills/` for all projects). The folder should be named `text-compressor`.
2. Paste or attach a long document and ask Claude to summarize, condense, or shorten it.
3. Claude will follow the steps in `SKILL.md` and return a summary in the standard format.

## Example prompt

> Here's the 20-page market analysis my team put together. Can you boil it down to something I can send to my manager?
