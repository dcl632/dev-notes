# dev-notes

Auto-generated daily logs from my automation fleet (3 nodes: mbp / fw / air).

Content covers:
- Multi-site content-mill publishing stats (lifeplusdaily / techtodaily / shiftautomate)
- Fleet infrastructure decisions & incidents
- Pipeline health events

## Why this exists

Public log of a private, always-on automation setup. Commits reflect actual
fleet activity — days without real activity don't show up.

## Stack highlights

- Python orchestration + cron schedulers
- Local LLM (Ollama) + Claude API for content
- Multi-site static generation + headless publishing
- OpenClaw agent fleet for task routing
