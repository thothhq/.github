# .github

## Org Identity

This entity's Org Identity Kit lives in the `.github-private` repo:

- **Quick start:** `../.github-private/START_HERE.md`
- **Machine-readable:** `../.github-private/org/org_context.yaml`
- **Brand strategy:** `../.github-private/org/01_brand_strategy.md`

> Read these files (in order) to onboard to this entity's identity, positioning, and voice.

## jeannAI Capabilities

Before building something new, check what the holding already provides.

- **Capability manifest:** `$JEANNAI_ROOT/hldg_jeannai/.github-private/org/capabilities.yml`
- **AI Toolkit:** `$JEANNAI_ROOT/hldg_jeannai/tooling/ai-toolkit/`
  - 9 skills, 38 agent roles, 7 workflow conventions
- **Docs:** `$JEANNAI_ROOT/hldg_jeannai/tooling/docs/source/reference/capability-catalog.rst`

> Parse `capabilities.yml` for the full machine-readable catalog of skills,
> agents, conventions, MCP servers, and infrastructure.

## Holding Capability Discovery (CAP-STD-001)

Before building, testing, verifying, or creating any artifact, consult the holding
capability manifest first -- reuse what `hldg_jeannai` provides instead of improvising:

- **Manifest:** `hldg_jeannai/.github-private/org/capabilities.yml` (org root = `N:\` = `D:\NexFolia`)
- **Standard:** `hldg_jeannai/engineering/standards/capability-discovery-standard.md` (CAP-STD-001)
- GUI / web-app testing -> `gui-testing-standard.md` (GUI-STD-001) + `agent-browser-dogfood` skill + `tooling/testing-toolkit`
- New files / repos -> `artifact-routing-standard.md` (ART-STD-001) + `repo-naming-standard.md`
- Planning / dispatching multi-step AI work (effort, model, subagents) -> `ai-execution-planning-standard.md` (AEP-STD-001)

If a capability exists, use it or justify the deviation. (Standardized per CAP-STD-001.)
