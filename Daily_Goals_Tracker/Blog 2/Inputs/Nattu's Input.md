https://drive.google.com/drive/folders/15AzXJYnzj3mNM_JPCnd5k7-g48yFRMnM

What are the signs and signals of a project that is truly agentic in its development lifecycle? When we need to make this assessment, we look at two, three dimensions. One, is the repository agentified? Meaning, is there a cloud.md, agents.md, architecture document.md, diagrams.md— sorry, domain.md, coding standards.md, so that when I walk in as a developer, I don't look at other developers and ask, what are the architectural practices here? The architecture is defined within the repository. Same way, I don't ask what are the coding standards you guys follow? It is within the repository. So one is repository check. Second is developer tooling. Does the developer have adequate token budget with the good quality models? Secondly, is there CLI connectivity or MCP connectivity to the supporting systems like GitHub, Jira, and all that? Third, we look for whether there are adequate end-to-end tests so that if we unleash an agent, we have a way to catch regression issues. Fourth, we look for quality gates at every stage so that there are guardrails preventing a rogue agent from inserting wrong code and sneaking it into production. So we need hooks at the commit stage, at the merge stage, at the release stage, and more. So if we see adequate quality gates, if we see adequate tooling, we see clearly agentified repository and good end-to-end tests, we'll be more confident of helping or certifying it as an agentic system or agentic project.

This gives us a strong assessment framework. I would describe it as four core dimensions, with a fifth dimension needed to close the learning loop.

Signs of a truly agentic development lifecycle

1. The repository is agent-ready

The repository itself contains the knowledge an agent needs to work safely and consistently:

* CLAUDE.md and/or AGENTS.md
* architecture.md
* domain.md
* coding-standards.md
* Architecture and domain diagrams
* Build, test and deployment instructions
* Clear repository structure and ownership boundaries

A developer or agent should not have to depend on tribal knowledge to understand how the system must be changed.

2. Developers have agentic tooling

Engineers have:

* Access to capable models
* Adequate token budgets
* IDE and CLI-based agent access
* Secure connectivity to GitHub, Jira, documentation, CI/CD and observability systems
* Appropriate permissions and sandboxing

Having an AI subscription alone does not make a team agentic. The agent must be connected to the development workflow.

3. Tests provide a dependable safety net

The project has sufficient automated tests, especially end-to-end and integration tests, to detect unintended changes.

These tests must:

* Cover critical user journeys
* Run reliably
* Produce actionable evidence
* Detect functional and non-functional regressions

Agents can move quickly only when the system can quickly prove whether their changes are safe.

4. Quality gates control agent-generated change

Guardrails operate throughout the lifecycle:

* Pre-commit hooks
* Commit-time checks
* Pull-request and merge-readiness gates
* Security, architecture and coding-standard checks
* Release gates
* Human approval for high-risk changes
* Production deployment controls

No agent should be able to move code into production merely because it generated code that compiles.

5. Production creates a learning loop

A genuinely agentic lifecycle does not end at deployment. It includes:

* Observability and correlation IDs
* Production health and business outcome monitoring
* Automated issue detection
* Traceability from requirement to code, test, release and production behaviour
* Feedback that improves instructions, tests, quality gates and agent evaluations

The simplest certification principle could be:

A project is agentic when agents can understand the system, make changes, prove those changes, pass enforceable quality gates and learn from production—without depending heavily on undocumented human knowledge.

The maturity test is therefore not “Are developers using AI?” It is:

“Can an agent safely take a meaningful engineering outcome from intent to production evidence?”