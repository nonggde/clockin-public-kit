# Example: Opportunity Scan For A Public Site

## Skill

Opportunity Scan

## Public Input

```text
https://clockin-agent.pages.dev
```

## Prompt

```text
Run CLOCKIN Opportunity Scan on this public URL:
https://clockin-agent.pages.dev

Return:
1. Buyer clarity score from 0-100
2. Target user hypothesis
3. Strongest proof already visible
4. Missing proof that blocks trust
5. Three next fixes
6. Safety boundary
```

## Expected Artifact

- A short score and explanation.
- A buyer/user hypothesis.
- A list of missing proof signals.
- A practical next-fix checklist.

## Safety Boundary

Public page only. No login pages, private dashboards, personal data, hidden scraping, payment actions, or wallet actions.
