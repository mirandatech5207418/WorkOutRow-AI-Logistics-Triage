# Architecture

WorkOutRow separates three primary responsibilities:

1. **Conversation — Copilot Studio:** user interaction, topics, variables and triage.
2. **Orchestration — Power Automate:** workflow steps and integrations.
3. **Persistence — SharePoint:** structured request records evidenced in the project.

Designed integrations include Teams, Outlook and OneDrive where end-to-end evidence is incomplete.

## Evidence-based architecture
The academic specification described conceptual agent-triggered, event-driven and scheduled automations. Available implementation evidence contains flows such as `ProcessarSolicitacaoAtendimento`, `Localizar Cliente`, `Localizar Pedido`, `Protocolo`, `Agendamento` and `Criar Item`.

This portfolio does not rename screenshots as flows that were not actually evidenced.

## Principle
**Generative AI interprets language; deterministic workflow handles operational actions; authoritative records hold operational truth.**
