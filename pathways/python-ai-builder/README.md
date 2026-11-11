# Pathway: Python for AI Builders

This pathway is for a learner who understands AI terminology and uses AI assistants, but wants practical experience building agents, workflows, media tools, or automations.

The order is intentional: begin with deterministic Python, then APIs, then AI components. An “agent” is not the starting point when a small script or workflow solves the problem more reliably.

## Outcome

Build and explain a small workflow that accepts input, transforms it, calls at least one external capability when justified, handles failure, and produces a useful result.

## Project ladder

| Project | Build | Capability focus | Cloud required? |
| --- | --- | --- | --- |
| 1. File helper | Rename, organise, or summarise local files | Python basics, safe file handling, tests | No |
| 2. Narration pipeline | Turn a script into audio using a free/local or free-tier option | APIs/libraries, formats, cost comparison | No by default |
| 3. Media workflow | Combine text, images, and audio into a repeatable output | Workflow decomposition, error handling | No |
| 4. One-tool assistant | Let an LLM decide when to call one safe tool | Structured input/output, guardrails | Optional |
| 5. Useful agent | Add iteration only where observation and replanning create value | Agent design, evaluation, limits | Optional |

Each project must be useful on its own. Do not postpone all satisfaction until Project 5.

## Project 1 brief: organise a media project

Create a Python command-line tool that:

- reads a folder of draft media assets;
- reports file types and inconsistent names;
- proposes safe, predictable filenames;
- supports a dry-run before changing anything;
- produces a small summary log;
- never overwrites an existing file silently.

### Evidence required

- Run it on a temporary sample folder.
- Show one normal case, one duplicate-name case, and one unsupported file.
- Explain why dry-run matters.
- Change one rule after the first test.
- Write a 150-word teach-back: “How I used AI without surrendering the design.”

### AI use allowed

Use AI to explain syntax, compare designs, review a function, generate test cases, or diagnose an error. Record one suggestion you rejected or modified and why.

## Project 2 brief: compare speech options

Do not begin by buying cloud quota. First write a one-page comparison based on current primary documentation:

- language/accent support;
- free allowance and hard cost risk;
- local/open-source option;
- licensing and privacy;
- output quality needed for the actual use case.

Then build the smallest narration script with the chosen option. The evidence is not “Azure/Gemini/another platform worked.” The evidence is that the learner selected a fit-for-purpose route, made it work, tested it, and can explain when another route would be better.

## Readiness for an agent

Before Project 5, the learner should be able to answer:

1. What uncertain decision requires an LLM?
2. What deterministic code should remain outside the model?
3. What tools may the model call?
4. What inputs or actions are unsafe?
5. How will success be evaluated across several examples?
6. What is the simpler non-agent baseline?

If those answers are unclear, build a workflow first. That is engineering judgment, not a lesser achievement.
