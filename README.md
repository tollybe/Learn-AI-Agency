# AI Agency Lab

**Turn “I use AI” into “I can use AI to investigate, build, verify, and teach.”**

AI Agency Lab is a forkable mentoring system for people who have completed courses or certifications but still do not feel able to turn an idea into a working result. It treats AI as a thinking and building partner—not an answer vending machine.

The repository is deliberately project-led. A learner does not prove capability by finishing another playlist. They prove it by leaving behind three things:

1. a working artifact;
2. a short reasoning trail showing choices, tests, and corrections;
3. a teach-back that another person can follow.

The reference pathway is **Python for AI Builders**: small, useful projects that progress from scripting to APIs and lightweight AI workflows.

## The agency loop

Every project follows the same loop:

> **Frame → Investigate → Choose → Build → Verify → Explain → Reuse**

| Stage | Learner action | Evidence |
| --- | --- | --- |
| Frame | Define the user, need, constraints, and “done” | A one-paragraph project brief |
| Investigate | Ask focused questions and compare credible options | Research notes with sources |
| Choose | Make a decision and explain the trade-off | Decision log entry |
| Build | Produce the smallest useful version | Code, workflow, prompt, or demo |
| Verify | Test normal, edge, and failure cases | Test results and limitations |
| Explain | Teach the idea in plain language | README, demo, or short post |
| Reuse | Extract a pattern for the next problem | Reusable prompt, function, or checklist |

AI may assist at every stage. It may not silently erase the learner's judgment.

## Start here

- Learner: open [START_HERE.md](START_HERE.md).
- Mentor: read [MENTOR_GUIDE.md](MENTOR_GUIDE.md).
- Any AI assistant: use [prompts/AI_COACH.md](prompts/AI_COACH.md).
- Python learner: begin with [pathways/python-ai-builder/README.md](pathways/python-ai-builder/README.md).
- Facilitator: run [the 75-minute AI agency workshop](workshops/01-unlock-ai-agency.md).
- Writer/speaker: use [From AI knowledge to AI agency](docs/FROM_KNOWLEDGE_TO_AGENCY.md) as the design rationale.

## What this is—and is not

This is for someone who says:

- “I understand the concepts, but I don't know what to build.”
- “I ask Claude or ChatGPT, but I still need someone experienced to guide me.”
- “I want Python because I want to build agents and workflows.”
- “Cloud tools work, but cost or quota blocks me.”

It is not a fixed curriculum, a certification cram guide, or a leaderboard. The project adapts to the learner's goal, constraints, language, access needs, and available time. The standard remains concrete: can they independently make a useful thing work and explain why it works?

## Fork it for a learner

1. Select **Use this template** (or fork the repository).
2. Rename the fork for the learner or goal.
3. Complete `learner/PROFILE.md` and `learner/SKILL_MAP.md`.
4. Paste `prompts/AI_COACH.md` into the chosen AI tool, or let a repository-aware coding agent read `AGENTS.md`.
5. Create the first project issue using the **Agency Project** template.
6. Work in small branches and use pull requests as mentor checkpoints.

Keep the fork public only if its content is safe to share. Use a private repository for personal reflections, job-search details, immigration information, private conversations, access tokens, or employer/customer data.

## The cost gate

Before selecting a cloud service, answer:

1. Is learning that particular cloud service part of the goal?
2. Who pays, and what is the hard spending limit?
3. Is there a free, local, or open-source route that teaches the same underlying skill?
4. What requirement genuinely needs the cloud?

Personal experiments default to free/local tools when they meet the learning goal. Cloud services become a deliberate engineering choice—not the price of admission.

## Evidence levels

Avoid claims such as “mastered Python” after one generated script. Describe what the evidence actually supports:

| Level | What the learner can demonstrate |
| --- | --- |
| Encountered | Recognises the idea or tool |
| Reproduced | Can follow an example and make it run |
| Adapted | Can change it for a related need |
| Built | Can create a small solution from a brief |
| Debugged | Can investigate failure and justify a fix |
| Taught | Can explain the pattern and help someone reuse it |

These are evidence labels, not grades. A learner can be at different levels for different skills.

## Maintainers

Created by Victoria Eshelby as part of her mentoring practice. Contributions that strengthen learner agency, accessibility, verification, and responsible use are welcome.

## License

MIT. Reuse and adapt the framework, while preserving attribution where practical.
