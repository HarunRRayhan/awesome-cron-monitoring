# Awesome Cron Monitoring [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of tools for monitoring cron jobs, scheduled tasks, and background processes.

## Contents

- [SaaS Services](#saas-services)
- [Self-Hosted](#self-hosted)
- [Language-Specific Libraries](#language-specific-libraries)
- [Guides](#guides)
- [Comparison](#comparison)

## SaaS Services

- [Crontiq](https://crontiq.io) - Free cron monitoring with auto JSON metric extraction and zero-config anomaly detection. 20 monitors free.
- [Healthchecks.io](https://healthchecks.io) - Simple and effective heartbeat monitoring. Open source. 20 monitors free.
- [Cronitor](https://cronitor.io) - Monitoring for cron jobs, background tasks, and heartbeats. 5 monitors free.
- [Dead Man's Snitch](https://deadmanssnitch.com) - Monitoring for cron jobs and scheduled tasks.
- [Better Stack](https://betterstack.com) - Uptime monitoring with heartbeats. 1 free heartbeat.
- [Honeybadger](https://www.honeybadger.io) - Check-ins for cron jobs with exit code and output capture.
- [Sentry Crons](https://sentry.io/for/cron-monitoring/) - Monitor and fix cron job and scheduled task issues.
- [Crontinel](https://crontinel.com) - Laravel-native cron, queue & Horizon monitoring. Detects silent supervisor failures, queue bottlenecks, and missed cron runs. Open-source package + optional SaaS. Free tier available.
- [Apprise](https://github.com/caronc/apprise) - Push notifications for your cron jobs.

## Self-Hosted

- [Uptime Kuma](https://github.com/louislam/uptime-kuma) - Self-hosted monitoring tool with push monitors.
- [Healthchecks](https://github.com/healthchecks/healthchecks) - Self-hosted version of Healthchecks.io.
- [minicron](https://github.com/jamesrwhite/minicron) - Monitor cron jobs on multiple servers.

## Language-Specific Libraries

### Python
- [cronitor-python](https://github.com/cronitorio/cronitor-python) - Cronitor Python client.

### JavaScript/Node.js
- [cronitor-js](https://github.com/cronitorio/cronitor-js) - Cronitor Node.js client.
- [node-cron](https://github.com/node-cron/node-cron) - Cron for Node.js (no monitoring built-in).

### Java
- Spring Boot @Scheduled + [Crontiq curl](https://crontiq.io/integrations/spring-boot-scheduled)

### Bash
- Simple curl integration with any heartbeat service: `curl https://ping.crontiq.io/p/API_KEY/my-job`

## Guides

- [How to Monitor Cron Jobs in 2026](https://crontiq.io/guides/monitor-cron-jobs)
- [What to Do When Cron Jobs Fail Silently](https://crontiq.io/guides/cron-job-failed-silently)
- [How to Monitor JSON Payloads from Cron Jobs](https://crontiq.io/guides/json-payload-monitoring)
- [How to Add a Cron Monitoring Badge to Your GitHub README](https://crontiq.io/guides/github-badge-cron-monitoring)
- [Monitor GitHub Actions with Crontiq](https://crontiq.io/integrations/github-actions)
- [Monitor Kubernetes CronJobs with Crontiq](https://crontiq.io/integrations/kubernetes-cronjobs)
- [Monitor Spring Boot @Scheduled Tasks](https://crontiq.io/integrations/spring-boot-scheduled)

## Comparison

| Service | Free Monitors | JSON Metrics | Anomaly Detection | Public Badges |
|---------|--------------|-------------|-------------------|--------------|
| [Crontiq](https://crontiq.io) | 20 | Auto-extract | Zero-config (avg+2σ) | Live data |
| [Healthchecks.io](https://healthchecks.io) | 20 | Text only | No | Status only |
| [Cronitor](https://cronitor.io) | 5 | Manual format | Manual thresholds | No |
| [Better Stack](https://betterstack.com) | 1 | No | No | No |
| [Sentry Crons](https://sentry.io) | Varies | No | No | No |

## Contributing

Contributions welcome! Please submit a pull request to add tools, libraries, or guides.

---

*Part of the [AZMORIS](https://azmoris.io) ecosystem.*
