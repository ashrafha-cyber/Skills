# Skills

Claude Code skills collected from the repos I've starred, gathered in one place as the `starred-skills` plugin.

## Install

In Claude Code (cloud sessions or your own computer), run:

```
/plugin install starred-skills --marketplace ashrafha-cyber/skills
```

On older Claude Code versions, add the marketplace first:

```
/plugin marketplace add ashrafha-cyber/Skills
/plugin install starred-skills@ashrafha-cyber
```

Skills then show up as `starred-skills:<name>`, for example `/starred-skills:stop-slop`. The skills themselves live in `skills/`.

Each skill keeps its upstream license. See `third_party_licenses/`.

## [mattpocock/skills](https://github.com/mattpocock/skills)

`ask-matt` `grill-with-docs` `implement-spec` `implement` `improve-codebase-architecture` `pr` `retro` `setup-matt-pocock-skills` `to-spec` `to-tickets` `triage` `wayfinder` `grill-me` `handoff` `teach` `to-questionnaire` `wait-what` `git-guardrails-claude-code` `migrate-to-shoehorn` `scaffold-exercises` `setup-pre-commit` 

## [hardikpandya/stop-slop](https://github.com/hardikpandya/stop-slop)

`stop-slop` 

## [pbakaus/impeccable](https://github.com/pbakaus/impeccable)

`impeccable` 

## [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem)

`babysit` `build` `build-and-release` `childhood` `design-is` `do` `learn-codebase` `make-plan` `oh-my-issues` `pathfinder` `release` `standup` `what-the` `wowerpoint` 

## [ai-job-search-dev/ai-job-search](https://github.com/ai-job-search-dev/ai-job-search)

`job-application-assistant` `job-scraper` `upskill` `freehire-search` `jobbank-search` `jobdanmark-search` `jobindex-search` `jobnet-search` `linkedin-search` 

## [cheaper-inference/OmniRoute](https://github.com/cheaper-inference/OmniRoute)

`cli-a2a` `cli-backup-sync` `cli-batches` `cli-chat` `cli-compression` `cli-contexts` `cli-cost-usage` `cli-eval` `cli-health` `cli-keys` `cli-mcp` `cli-models` `cli-plugins-skills` `cli-policy-audit` `cli-providers` `cli-resilience` `cli-routing` `cli-serve` `cli-setup` `cli-skill-collector` `cli-tunnel` `config-codex-cli` `omni-agents-a2a` `omni-api-keys` `omni-auth` `omni-budget` `omni-cache` `omni-cli-tools` `omni-combos-routing` `omni-compression` `omni-context-rtk` `omni-db-backups` `omni-github-skills` `omni-inference` `omni-mcp` `omni-models` `omni-providers` `omni-proxies` `omni-resilience` `omni-settings` `omni-sync-cloud` `omni-tunnels` `omni-usage-logs` `omni-version-manager` `omni-webhooks` `ponytail` 

## Not included here

- **mattpocock/skills**: `code-review`, `codebase-design`, `diagnosing-bugs`, `domain-modeling`, `grilling`, `prototype`, `research`, `tdd`, `wizard`, `writing-for-agents` are left out because the `mattpocock-skills` plugin already provides them. The drafts in `skills/in-progress/` are also left out.
- **thedotmack/claude-mem**: the memory skills (`mem-search`, `timeline-report`, `knowledge-agent`, `backup-setup`, `cloud-sync` and others) only work with the claude-mem background worker running. Install the full plugin to get them: `/plugin marketplace add thedotmack/claude-mem`. `handoff` is a duplicate of mattpocock's, and `version-bump` only applies to the claude-mem repo itself.
- **WorldFlowAI/everything-claude-code**: the upstream repo has no license, so its skills aren't copied here. Install it as a plugin instead: `/plugin marketplace add WorldFlowAI/everything-claude-code`.
- **codecrafters-io/build-your-own-x**: this is a list of tutorials. It has no skills.
- **OmniRoute**: its `cli-*` and `omni-*` skills only help if you run the OmniRoute gateway.
