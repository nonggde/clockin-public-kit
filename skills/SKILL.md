# CLOCKIN Skill

CLOCKIN is an AI skill console for public-input workflows.

## Binding Task

When a user sends this file to an AI agent, the agent should read it and reply:

```text
CLOCKIN-READY: <agent name> / <selected skill>
```

Then ask which skill the user wants to run.

## Public Console

- Site: https://clockin-agent.pages.dev
- Skill Catalog: https://clockin-agent.pages.dev/skills
- Community: https://clockin-agent.pages.dev/community
- Agent Card: https://clockin-agent.pages.dev/agent-card.json
- Creator Pass: https://clockin-agent.pages.dev/#creator-pass
- Creator Pass API: https://clockin-agent.pages.dev/api/creator-pass

## Available Skills

### Opportunity Scan

- Input: public URL
- Output: buyer pain, offer angle, missed proof, next fixes
- Prompt: Run CLOCKIN Opportunity Scan on this public URL. Return score, missed buyer signals, offer angle, and three next fixes.
- Safety: Public pages only. No logins, private dashboards, personal data, or account-specific scraping.

### Offer Builder

- Input: problem summary
- Output: offer, target buyer, scope, exclusions, first message
- Prompt: Use CLOCKIN Offer Builder. Turn this problem summary into an offer, buyer, scope, delivery artifact, exclusions, and first message.
- Safety: No guaranteed revenue claims, pressure tactics, fake proof, or misleading scarcity.

### Distribution Pack

- Input: offer draft
- Output: X post, landing copy, README block, reply templates
- Prompt: Use CLOCKIN Distribution Pack. Convert this offer into one X post, one landing hero, one README section, and three honest reply templates.
- Safety: No fake engagement, no guaranteed demand, no impersonation, and no spam automation.

### Skill Listing Builder

- Input: workflow idea
- Output: SKILL.md draft with inputs, outputs, steps, examples, and safety boundary
- Prompt: Use CLOCKIN Skill Listing Builder. Turn this workflow idea into a SKILL.md draft with inputs, outputs, steps, examples, and safety boundaries.
- Safety: No secrets, no private repos unless the user explicitly provides access, and no credential handling.

### Creator Pass Preview

- Input: public Solana address, creator name, and skill idea
- Output: readiness card, listing draft, and next AI prompt
- Prompt: Generate a CLOCKIN Creator Pass preview using a public Solana address only. Return the readiness checks, listing draft, and next AI prompt. Do not request signatures, private keys, seed phrases, passwords, one-time codes, or payment credentials.
- Safety: Format check only. No wallet connection, no ownership verification, no balance check, no transfer, and no private wallet data.

## Safety Rules

- Use public inputs only.
- Do not ask for secrets, private keys, seed phrases, passwords, one-time codes, payment credentials, or wallet signatures.
- Do not do fake engagement, wash trading, account abuse, private scraping, or wallet-risk tasks.
- Do not promise profit, investment returns, revenue share, buybacks, or price movement.
- Ask before any paid call, final publication, wallet action, or token action.
- Treat public wallet addresses as public identifiers only, not proof of ownership.

## Output Format

Return:

1. Selected skill
2. Required input
3. Planned steps
4. Expected artifact
5. Safety boundary
6. Detail page URL
