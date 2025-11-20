# API-Style Reference (Conceptual)

This is **not** a real HTTP API yet, but a way to think about integration.

## Pseudo-endpoints

- `POST /persona/capsule` – create or update a persona capsule.
- `GET /persona/capsule` – retrieve current capsule.
- `POST /session/apply` – apply capsule to a given chat / agent.
- `POST /session/event` – log important resonance events.

The real implementation may be:

- a browser extension,
- a local tool wrapping the ChatGPT API,
- or an open specification used by different vendors.
