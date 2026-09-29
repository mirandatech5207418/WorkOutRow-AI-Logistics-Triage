# AI Governance

## Closed-domain classifier
Allowed categories: Tracking, Pickup, Documentation, Complaint and Human Triage.

## Output contract
```text
Category: [category]
Summary: [factual summary, max. 20 words]
Ambiguous: [true|false]
```

## Guardrails
1. Never create a new category.
2. Never invent shipment status, dates, protocols, identifiers or operational data.
3. Competing intents without a clear priority go to Human Triage with ambiguity flagged.
4. Keep summaries factual.
5. Operational facts come from system records.

## Validation limitation
AI classification was configured, but complete execution validation could not be performed because credits were unavailable in the project environment. The capability is therefore **implemented / validation pending**, not validated.
