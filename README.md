# ragflow-runbook Skill

End-to-end runbook for RAGFlow runtime operations (deploy, operate, troubleshoot, monitor).

Version: 0.1.0

---

## What You Get

- Deployment guidance (Windows/WSL2 + Linux)
- Service management commands
- Logs + troubleshooting workflow
- Backup/restore basics
- Ops API checks + examples (system endpoints only)
- Health check helpers

---

## How To Use

This is a documentation-style skill. No installation needed.

```bash
# Reference the skill in OpenClaw
openclaw skills ragflow-runbook
```

Or just read the doc:

```bash
cat skills/ragflow-runbook/SKILL.md
```

---

## File Layout

```
ragflow-runbook/
├── SKILL.md
├── README.md
├── CHANGELOG.md
├── scripts/
│   ├── deploy.sh
│   ├── healthcheck.sh
│   ├── ragflow_ping.py
│   ├── ragflow_smoke.py
│   ├── ragflow_status.py
│   └── ragflow_alert.py
└── examples/
    ├── api-examples.sh
    └── troubleshooting.md
```

---

## Quick Commands

| Action | Command |
|---|---|
| Start | `docker compose up -d` |
| Stop | `docker compose down` |
| Restart | `docker compose restart` |
| Logs | `docker compose logs -f` |
| Status | `docker compose ps` |

---

## Help

- Primary doc: `SKILL.md`
- Upstream docs: https://ragflow.io/docs/
- GitHub: https://github.com/infiniflow/ragflow
