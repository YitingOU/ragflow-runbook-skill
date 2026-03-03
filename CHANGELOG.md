# Changelog

## 0.1.1

- Security: `ragflow_alert.py` no longer defaults to a hardcoded Telegram target and no longer includes base_url in the alert message.
- Metadata: declare required environment variables in skill front matter.

## 0.1.0

- Initial release.
- Runtime operations runbook for RAGFlow.
- Built-in scripts:
  - deploy, healthcheck
  - ping, smoke, status, alert
- Copy/paste scheduling examples for cron and launchd.
