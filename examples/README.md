# CLOCKIN Public Examples

These examples show how to run CLOCKIN skills with public inputs only. They are meant for builders, reviewers, and AI agents that want a concrete starting point.

## Rules

- Use public URLs, public repositories, public docs, or public project pages only.
- Do not paste secrets, private keys, seed phrases, passwords, one-time codes, payment data, private dashboards, or wallet signatures.
- Do not use the output as financial advice or a profit claim.
- Return useful artifacts: findings, next fixes, draft copy, issue ideas, or a skill route.

## Examples

| Example | Skill | Input | Output |
| --- | --- | --- | --- |
| `opportunity-scan-public-site.md` | Opportunity Scan | public website URL | buyer clarity score, missed proof, next fixes |
| `github-readme-buyer-audit.md` | Public Code Review / Opportunity Scan | public GitHub repo URL | README issue map and product clarity fixes |
| `solana-creator-launch-readiness.md` | Skill Listing Builder / Launch Safety | public site + repo + token page | launch-readiness checklist and risky-copy review |

## Example Outputs

- `outputs/opportunity-scan-clockin-site.json`

## Starter Prompt

```text
You are my AI operator. Read the CLOCKIN Skill, choose the matching example, and produce the requested artifact using public inputs only. Do not ask for secrets, private keys, passwords, one-time codes, wallet signatures, or payment credentials.

Skill file:
https://clockin-agent.pages.dev/skills/SKILL.md
```
