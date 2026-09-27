# Agent Interlock

**An independent authority for preventing conflicting actions between autonomous agents.**

> **Identity says who. Interlock says when.**

Your AI agents act on their own — some you built, some you bought — and two of them can reach the
same listing, order or customer record. Nobody owns that collision. Interlock does.

Before an agent acts on a shared resource, it asks Interlock. Interlock checks **who** is asking —
the agent's own identity, proved with X.509 (with or without mTLS), OAuth 2.0 or an API key — then
**when** it may act. The answer is an MCP tool response: **grant**, **wait** or **deny**. Where a
receiving system must check for itself, the grant is also issued as a short-lived signed JWT that it
verifies offline. Interlock decides; your systems enforce the decision.

**Consider it when**

- Agents from more than one team, framework or vendor act on the same records
- Agents have already collided, and a customer saw the result
- You need proof of which agent was allowed to act, on what and when

`MCP` · `X.509` · `OAuth 2.0` · `JWT`

## Pending general availability

Interlock is a hosted service in pre-release. Documentation, the client SDK and integration
examples will be published here at general availability.

**Follow this organization for the GA release** · [agent-interlock.co.uk](https://agent-interlock.co.uk/)
