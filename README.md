<div align="center">

<img src="https://monify.cloud/images/monify-favicon.svg" alt="Monify" width="80" />

# Monify Cloud

**Modern Infrastructure Monitoring Platform**

[Website](https://monify.cloud) · [Dashboard](https://dash.monify.cloud) · [Get Started](#quick-start)

</div>

---

Monify is an all-in-one infrastructure monitoring platform designed for engineering teams. Monitor servers, set intelligent alerts, and resolve incidents—all from a single unified dashboard.

## Overview

|                                 |                                                          |
| ------------------------------- | -------------------------------------------------------- |
| **30-second setup**             | Single command deployment with zero configuration        |
| **Real-time metrics**           | 15-second collection interval for all system vitals      |
| **Intelligent alerting**        | Threshold-based rules with breach duration and cooldowns |
| **Multi-channel notifications** | Email, Slack, Telegram, and custom webhooks              |
| **Team collaboration**          | Role-based access control with complete audit trails     |

## Platform Features

### Monitoring

Comprehensive visibility into your infrastructure:

- **CPU** — Usage, per-core metrics, load averages (1m, 5m, 15m)
- **Memory** — Used, free, available, cached, buffers, swap
- **Disk** — Space per partition, read/write throughput, IOPS
- **Network** — Public/private bandwidth, errors, packet drops
- **System** — Uptime, process count, kernel version

### Alerting

Reduce noise and focus on real issues:

- Define thresholds with flexible conditions (greater than, less than, equal)
- Set breach durations to filter transient spikes
- Apply rules globally, by tag, or to individual servers
- Automatic incident resolution when metrics recover

### Notifications

Receive alerts where your team works:

| Channel      | Capabilities                            |
| ------------ | --------------------------------------- |
| **Email**    | Rich HTML templates via SendGrid        |
| **Slack**    | Formatted messages with server details  |
| **Telegram** | Bot notifications with markdown         |
| **Webhook**  | Custom HTTP endpoints with JSON payload |

### Collaboration

Built for teams:

- **Organizations** — Isolated workspaces with dedicated resources
- **Role-based access** — Owner, Admin, Member, Viewer permissions
- **Audit logging** — Immutable record of all configuration changes
- **Custom dashboards** — Personalized views with drag-and-drop widgets

## Quick Start

```bash
curl -sSL https://monify.cloud/install.sh | sudo bash -s -- YOUR_TOKEN
```

Get your token at [dash.monify.cloud](https://dash.monify.cloud)

## Plans

|                   |  Free  | Starter |   Pro   |  Pro Max  |
| :---------------- | :----: | :-----: | :-----: | :-------: |
| Monthly           |   $0   |   $12   |   $39   |    $99    |
| Servers           |   2    |    5    |   25    |    100    |
| Team Members      |   1    |    1    |   10    | Unlimited |
| Alert Channels    |   3    |    5    |   15    | Unlimited |
| Daily Emails      |   20   |   100   |   500   |   2,000   |
| Dashboards        |   1    |    3    |   10    | Unlimited |
| Data Retention    | 7 days | 30 days | 90 days |  90 days  |
| Custom Dashboards |   —    |    ✓    |    ✓    |     ✓     |
| Audit Logs        |   —    |    —    |    ✓    |     ✓     |
| RBAC              |   —    |    —    |    ✓    |     ✓     |
| Priority Support  |   —    |    —    |    —    |     ✓     |

## Community

This repository is the official channel for community feedback and support.

### Bug Reports

Found an issue? Help us improve:

1. Check [existing issues](https://github.com/monify-labs/monify/issues) to avoid duplicates
2. Create a [new bug report](https://github.com/monify-labs/monify/issues/new?template=bug_report.yml)
3. Include steps to reproduce, expected behavior, and screenshots if applicable

### Feature Requests

Have an idea? We prioritize based on community feedback:

1. Review the [roadmap](https://github.com/monify-labs/monify/issues?q=label%3Aenhancement)
2. Submit a [feature request](https://github.com/monify-labs/monify/issues/new?template=feature_request.yml)
3. Describe the problem, your proposed solution, and alternatives considered

### Guidelines

- **Search first** — Avoid duplicate issues
- **Be specific** — Include relevant context and details
- **One topic per issue** — Keep discussions focused
- **Stay constructive** — We're building this together

## Roadmap

We're continuously improving Monify. Here's what's coming:

### In Progress

| Feature                | Description                                                                |
| ---------------------- | -------------------------------------------------------------------------- |
| **Enhanced Dashboard** | Additional metric cards, improved visualizations, and customizable layouts |
| **Uptime Monitoring**  | HTTP/HTTPS endpoint monitoring with global check locations                 |

### Planned

| Feature                  | Description                                                       |
| ------------------------ | ----------------------------------------------------------------- |
| **Mobile App**           | iOS and Android apps with push notifications for real-time alerts |
| **Status Pages**         | Public status pages to communicate service health to your users   |
| **Log Management**       | Centralized log collection and search                             |
| **APM Integration**      | Application performance monitoring with trace analysis            |
| **Multi-region Metrics** | Distributed metrics storage for global infrastructure             |
| **SSO/SAML**             | Enterprise single sign-on integration                             |

### Under Consideration

| Feature                  | Description                                               |
| ------------------------ | --------------------------------------------------------- |
| **Synthetic Monitoring** | Scripted browser tests and API monitoring                 |
| **On-premise Agent**     | Self-hosted metrics collector for air-gapped environments |
| **Custom Metrics API**   | Push custom application metrics via SDK                   |
| **PagerDuty/Opsgenie**   | Native integrations with incident management platforms    |

Have a feature request? [Submit an issue](https://github.com/monify-labs/monify/issues/new?template=feature_request.yml) — community feedback directly influences our priorities.

## Security

To report security vulnerabilities:

- Do **not** create public issues
- Email [security@monify.cloud](mailto:security@monify.cloud)
- We respond within 48 hours

## Contact

|           |                                                     |
| --------- | --------------------------------------------------- |
| Website   | [monify.cloud](https://monify.cloud)                |
| Dashboard | [dash.monify.cloud](https://dash.monify.cloud)      |
| Support   | [support@monify.cloud](mailto:support@monify.cloud) |

---

<div align="center">

**Monify Labs**

</div>
