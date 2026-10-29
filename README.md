# Client Needs Diagnosis

## Turn fragmented requests into a project that can actually start

Client briefs are often incomplete, scattered across documents and meetings, or already mixed with early internal ideas. This Skill turns those materials into a clear diagnosis before a team starts planning, designing, quoting, or delivering.

It does not merely summarize a brief. It separates what the client has actually confirmed, what later materials add, what the team still needs to investigate, and what can genuinely block scope, schedule, budget, approval, rights, safety, or delivery.

## What you get

After reading a brief, meeting notes or transcript, chat records, drawings, spreadsheets, and versioned materials, the Skill produces:

1. **A source-aware project understanding** — facts, later additions, internal drafts, hypotheses, and open decisions remain visibly distinct.
2. **Input readiness** — what is available, what is missing, why it matters, who should provide it, and at which stage it is needed.
3. **A focused confirmation list** — questions that materially change the project instead of an unfocused questionnaire.
4. **Team work items** — the research, strategy, content, design, or feasibility work that belongs to the team rather than the client.
5. **Real boundaries and risks** — only issues with concrete delivery impact, not every creative uncertainty.
6. **A next-action card** — ordered client and team actions required to enter the next stage.

## How it works

```text
Materials
  → source and version check
  → confirmed facts and missing inputs
  → client confirmation / client inputs / team work / real boundaries
  → project-start diagnosis and next-action card
```

The workflow uses two rounds of input gathering:

- **Before strategy or outline**: establish the objective, audience, subject matter, existing conditions, decision route, and hard constraints.
- **After strategy or outline**: gather module-specific assets, evidence, rights, interfaces, update owners, and approvers.

## Best for

- Exhibition, booth, spatial, brand, event, content, and digital projects.
- Projects that begin with an incomplete brief, several conflicting versions, or a need to align client and team before the next specialist workflow.
- Teams that need a client-facing confirmation document and an internal project-start handoff from the same materials.

## What it does not do

- Invent client requirements, factual claims, budgets, schedules, approvals, or final solutions.
- Treat internal concepts, temporary meeting ideas, or AI inferences as client-confirmed decisions.
- Replace legal, contractual, safety, engineering, regulatory, or other specialist sign-off.
- Store or expose customer materials in reusable skill resources.

## Use on different AI platforms

The core is plain Markdown plus YAML frontmatter and has no platform-specific configuration, tools, credentials, or external dependencies.

- On platforms that support Agent Skills, install or attach the `client-needs-diagnosis/` folder directly.
- On platforms that use project instructions or system prompts, provide `SKILL.md` as the working instruction and make the relevant files in `references/` available as knowledge documents.
- If a platform cannot transcribe audio, provide a transcript, meeting notes, or timestamps instead.

The skill is portable in logic and content. Automatic invocation, file-upload behavior, audio transcription, and user-interface fields are platform capabilities and may require local configuration.

## Folder layout

```text
client-needs-diagnosis/
├── SKILL.md
└── references/
    ├── input-and-source-ledger.md
    ├── exhibition-intake-and-handoff.md
    └── output-template.md
```

## Privacy

Use only materials authorized for the current task. Do not add client names, raw transcripts, private files, internal paths, or identifiable case details to this repository or other reusable resources.

## License

No license is included yet. Choose an explicit license before creating a public repository or inviting external contributors.

