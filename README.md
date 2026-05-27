# Competitive Intelligence Skill

A practical, methodology-focused skill for running defensible competitive intelligence (CI) projects with the help of an AI assistant. Built for junior-to-mid-level analysts, business development professionals, product marketers, strategy support staff, and consultants who have been handed a request to "get smart on" a market or competitor and need a repeatable way to deliver something rigorous.

## What it does

The skill walks an AI assistant (and the analyst working with it) through a CI project in one of two modes:

1. **Competitive Snapshot.** A one-time read of a market, an industry, or a specific competitor, delivered as a brief, slide deck, or memo.
2. **Ongoing Monitoring.** A standing system that watches a set of targets and surfaces signals on a cadence, with predefined tripwires for escalation. Built on Benjamin Gilad's Competitive Early Warning (CEW) framework.

The methodology is drawn from the established CI/MI literature: Porter's *Competitive Strategy*, Sharp's *Competitive Intelligence Advantage*, Gilad's *Early Warning*, Christensen's *Seeing What's Next*, and the MIBOK Guide (Market Intelligence Body of Knowledge).

## Who it's for

- Analysts asked to research a market or competitor and not sure where to start
- Managers tasked with setting up a monitoring program for the first time
- Consultants who want a repeatable, defensible methodology for client engagements
- Students learning competitive intelligence as a discipline
- Anyone who has been handed a request like "give me a read on Competitor X" or "we need to start tracking what's happening in this space"

## What's inside

```
competitive-intelligence/
├── SKILL.md            # Main workflow document
├── README.md           # This file
├── LICENSE             # MIT
└── references/
    ├── sources.md      # Tiered catalogue of CI sources
    ├── frameworks.md   # Five Forces, BIM, scenarios, profiling, etc.
    └── templates.md    # Intake protocols, brief templates, alert formats
```

The main `SKILL.md` is a complete workflow document. The three reference files in `references/` are pulled on demand when the workflow points to them, so the assistant only loads what it needs.

## Installation

### Option A: Install into Claude Code or Cowork as a skill

If you use Claude Code or Claude Cowork, you can install this as a skill that the assistant will trigger automatically when you ask about competitive intelligence work.

1. Download the `competitive-intelligence.skill` file from the latest release (or zip the `competitive-intelligence/` folder yourself).
2. In Claude Code or Cowork, open the skills manager and use the "Install skill" or "Import skill" option, pointing it at the `.skill` file.
3. Verify the skill is enabled. It should trigger on requests like "build a competitive snapshot of...", "set up monitoring on...", "profile competitor X", "we need to get smart on this market", etc.

### Option B: Use it as a methodology guide with any AI assistant

You don't need Claude or Cowork specifically. Open `SKILL.md` and the reference files, and paste the relevant sections into ChatGPT, Gemini, Claude.ai, or any other assistant when starting a CI project. The workflow is tool-agnostic; the skill has notes for both the "Claude with web search and file tools" path and the generic "any AI plus a browser" path.

### Option C: Use it as a printed methodology

`SKILL.md` and the reference files are readable on their own. You can use them as a personal playbook, a team training document, or a course handout without any AI in the loop.

## How to use it (with an AI assistant)

1. Read `SKILL.md` once. It is short by design.
2. Start any CI conversation with: *"I need to run a competitive intelligence project. Please walk me through the scoping conversation first."* The assistant should ask you the eight intake questions from Step 0.
3. Pick a mode (Snapshot or Monitoring) based on your request.
4. Work through the steps. The assistant will pull from the reference files as needed.

## What this skill does *not* do

- It is not a database of competitors or markets. It is a methodology.
- It is not a substitute for domain expertise. The assistant can apply the frameworks, but you (or someone in your organization) need to bring the judgment about what the findings mean for your specific situation.
- It is not a shortcut for primary research. The skill is candid that the highest-value source category (human conversations with industry experts, distributors, former employees) is the slowest and hardest. The skill helps you plan for it; it does not replace it.

## Ethical guardrails

The skill is explicit about the ethical boundaries that separate competitive intelligence from industrial espionage. The bright lines are: no misrepresentation of identity or purpose with sources, no theft or unauthorized access, no bribery, no violation of confidentiality agreements. Local laws (PIPEDA, GDPR, sector-specific regulation) apply on top.

If you use this skill in your work, you are responsible for ensuring your practice complies with these standards.

## Source material

The skill synthesizes from:

- *Competitive Strategy: Techniques for Analyzing Industries and Competitors* (Michael E. Porter, Free Press, 1980)
- *Competitive Intelligence Advantage: How to Minimize Risk, Avoid Surprises, and Grow Your Business in a Changing World* (Seena Sharp, Wiley, 2009)
- *Early Warning: Using Competitive Intelligence to Anticipate Market Shifts, Control Risk, and Create Powerful Strategies* (Benjamin Gilad, AMACOM, 2004)
- *Seeing What's Next: Using the Theories of Innovation to Predict Industry Change* (Clayton Christensen, Scott Anthony, Erik Roth, HBSP, 2004)
- *The Handbook of Market Intelligence* (Hans Hedin, Irmeli Hirvensalo, Markko Vaarnas, Wiley, 2014)
- *Thinking, Fast and Slow* (Daniel Kahneman, FSG, 2011)
- *A Guide to the Market Intelligence Body of Knowledge* (MIBOK Guide, v1.0)

If you find the skill useful, the underlying books are worth reading.

## Contributing

Suggestions, corrections, and pull requests are welcome. If you have a battle-tested template, source, or framework that fits the structure, open an issue or a PR.

## License

MIT. See `LICENSE`. Use it, modify it, redistribute it, teach with it, sell services built around it. Attribution appreciated but not required.

## Versions

- **v1.0** (initial release): Snapshot and Monitoring workflows, three reference files (sources, frameworks, templates), tool-agnostic with Cowork-specific notes.
