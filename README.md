# IGCSE Speaking Examiner (AI-Powered)
An AI examiner that conducts and evaluates Cambridge IGCSE First Language English (0500) speaking tests — simulating the structure, prompts, and assessment criteria of the real exam.

## What it does
- Guides a student through a structured speaking test (prepared topic + conversation phase)
- Asks follow-up questions dynamically based on the student's responses
- Scores performance across the official Cambridge criteria (content, language, structure)
- Returns written feedback per criterion

## Tech Stack
| Layer | Technology |
|---|---|
| AI / LLM | Anthropic Claude API |
| Backend / Database | Supabase (auth + session storage) |
| Framework | Next.js |

## Status
- ✅ Core examiner loop working (tested end-to-end)
- ✅ Supabase integration live
- ⏳ Not yet deployed publicly (local only)

## Why I built this
Cambridge IGCSE speaking practice is hard to get outside of scheduled school sessions. I wanted a tool that could simulate a real examiner conversation — with genuine follow-up questions, not just a static quiz — and give structured feedback using the actual marking criteria.

## What I learned
- Prompt engineering for consistent persona and structured output from an LLM
- Managing multi-turn conversation context within API token limits
- Supabase schema design for session-based data

*Built by Aeden Bourges*
