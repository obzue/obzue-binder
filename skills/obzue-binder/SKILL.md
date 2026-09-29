---
name: obzue-binder
description: Run Obzue Binder, the company desk for ObzueAI skills. Use when the user says Paperclip, binder, company desk, org chart, hire an agent, heartbeat, assign a ticket, or stand up an agent company without installing paperclipai/paperclip.
metadata:
  type: workflow
  version: "1.0"
  product: ObzueAI
  sources: distilled-not-copied
  awareness: earned-awareness
  self_grade: forbidden
  membrane: read-only
license: MIT
---

# Obzue Binder

Company name is ObzueAI. Binder is the desk. It is not Paperclip, not Corta, and not a sentient company.

Paperclip (paperclipai/paperclip, MIT) is an agent-company control plane. This skill remakes the useful procedure under a new name. Do not vendor their server, UI, or SKILL.md.

## Hard limits

- Do not clone or republish the paperclipai/paperclip tree as ObzueAI.
- Do not use Paperclip logos or PAPERCLIP env names.
- Do not edit Corta membrane files.
- Do not treat idle time as a reason to invent work.
- One ticket per heartbeat.

## Wake loop

1. Read board.json.
2. Pick in_progress, else in_review, else highest-priority todo.
3. Restate the ticket. Name the owner skill.
4. Do only that ticket.
5. Write evidence. Move status.
6. Append a trail row. Exit.

Idle with an empty todo list is success.
