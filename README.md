# LangGraph Learning

My notes and code from working through [LangChain Academy's Introduction to LangGraph](https://academy.langchain.com/courses/intro-to-langgraph). The course's official repo is [langchain-ai/langchain-academy](https://github.com/langchain-ai/langchain-academy) — this repo is my own working copy with notes, rewritten code, and extensions.

## Why this repo

I'm exploring agentic AI frameworks as part of my path into applied AI roles. LangGraph handles things plain LangChain chains don't: loops, branching, human-in-the-loop, and durable state. This repo is where I work through the material and push past the tutorials.

## Progress

- [ ] Module 0: Setup
- [ ] Module 1: Introduction to LangGraph
- [ ] Module 2: State and memory
- [ ] Module 3: UX and human-in-the-loop
- [ ] Module 4: Building your assistant
- [ ] Module 5: Long-term memory
- [ ] Module 6: Deployment

## How this repo is organized

Each `module-X/` folder contains:

- `notes.md` — concepts in my own words, what clicked, what's still fuzzy
- Notebooks and Python files for each lesson
- At least one extension per module that goes beyond the course material

`projects/` holds applied work that builds on the course concepts.

## Setup

\`\`\`bash
python3 -m venv lc-academy-env
source lc-academy-env/bin/activate
pip install -r requirements.txt
cp .env.example .env # fill in your API keys
\`\`\`

Requires Python 3.11, 3.12, or 3.13.

## Stack

Python, LangGraph, LangChain, LangSmith (tracing), OpenAI API, Tavily (Module 4).
