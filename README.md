# Awesome-Automated-Machine-Learning-Automl

# Awesome-Automated-Incident-Response 🚨 🤖

<p align="center">
  <img src="assets/banner.svg" alt="Awesome Automated Incident Response Banner" width="100%">
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Automated-Incident-Response"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Automated-Incident-Response?style=social" alt="GitHub_Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Automated-Incident-Response/fork"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Automated-Incident-Response?style=social" alt="GitHub Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Automated-Incident-Response/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Automated-Incident-Response?color=blue" alt="License"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 🌟 Top Automated Incident Response Ecosystem

**Curated List of Commercial Incident Management Platforms & Open-Source SOAR/On-Call Tools**  
*Focused on Alert Ingestion, On-Call Scheduling, Automated Remediation, AI-Powered Root Cause Analysis & Self-Hosted Incident Command*

**Last updated: October 2026** 📅

---

### 📌 Overview & SEO Summary
Welcome to the ultimate curated directory of **automated incident response platforms**, **open-source SOAR frameworks**, and **on-call management tools**. Whether you are looking for enterprise-grade commercial solutions (such as *PagerDuty*, *BigPanda*, and *Torq*), or self-hostable open-source alternatives (like *Regen*, *PagerLite*, and *StackStorm*), this list covers category leaders, AI-powered diagnostics, and privacy-respecting incident orchestration.

**Key Market Context:**
- **Regen (FluidifyAI)** is the **leading open-source, self-hosted PagerDuty alternative**, offering **unlimited alerts, incidents, on-call schedules, and AI postmortems** with **1-click migration from Grafana OnCall/PagerDuty**, **BYO-AI key** (OpenAI/Anthropic/Ollama), and **SSO/SAML free** [citation:3].
- **Sentinel Framework** is an **AI-powered incident response framework** that confirms failures via **3-signal cross-check**, runs a **5-step root cause analysis pipeline** (recent commits → RAG query → LLM RCA → runbook), and posts to a live dashboard in **under two minutes**, plugging into **any cloud, git provider, or LLM** [citation:2].
- **AutoSRE** is an **autonomous SRE agent** that cuts **45-minute investigations to 5 minutes** with **multi-agent investigation** (triage → contain → investigate → resolve → learn), **episodic memory** for learning from past incidents, and **SLO-driven operations** with error budgets [citation:7].
- **StackStorm** is the **leading open-source event-driven automation platform** for incident response, acting as the **reactive brain** of your incident pipeline — "If a CPU alert fires for more than five minutes, run the auto-scale script and post to the incident channel" [citation:17].
- **SOARCA** is an **open-source SOAR orchestrator with native CACAO v2 and OpenC2 support**, enabling **standardized, machine-readable playbook execution** for threat and incident response workflows [citation:9].
- **AlertChain** is a **simple SOAR framework leveraging OPA (Open Policy Agent)** to define alert and action policies in **Rego**, making security policy updates flexible and expressive [citation:4].

---

## 📑 Table of Contents
- [🏢 SaaS & Commercial Platforms](#-saas--commercial-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🛠️ How to Contribute](#%EF%B8%8F-how-to-contribute)
- [📊 Star History](#-star-history)
- [🤝 Support & Sponsorship](#-support--sponsorship)
- [⚠️ Disclaimer](#%EF%B8%8F-disclaimer)

---

## 🏢 SaaS / Commercial Platforms

The automated incident response market spans **incident management platforms** (PagerDuty, FireHydrant, Rootly) that provide **on-call scheduling, escalation, and incident command**, **AIOps platforms** (BigPanda, Moogsoft) that focus on **alert correlation and noise reduction**, and **security orchestration platforms** (Torq, Palo Alto Cortex XSOAR) that automate **threat response and remediation**. **PagerDuty** starts at **$21/user/month** for Professional. **Opsgenie** offers a **free tier for up to 5 users** with Standard at **~$9.50/user/month**. **BigPanda** uses **custom enterprise pricing**.

| SaaS / Commercial Platform | Company / Owner | Valuation / Market Cap | Standard Edition Starting Price | Free Tier / Free Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[Salesforce Active Response](https://www.salesforce.com/)** ☁️ | Salesforce | ~$250 Billion | **Included with Salesforce licenses** | **Free with Salesforce subscription** | **CRM-native incident response** — **Automated response workflows integrated with Salesforce platform** . |
| **[PagerDuty](https://www.pagerduty.com/)** 🚨 | PagerDuty Inc. | ~$2 Billion | **$21/user/month** (Professional) | **14-day free trial**; no permanent free tier | **Incident response platform** — **Alert routing, on-call schedules, escalation policies** . **700+ integrations with monitoring tools** . **The industry standard for on-call management** . |
| **[Opsgenie (Atlassian)](https://www.atlassian.com/software/opsgenie)** 🔵 | Atlassian | ~$50 Billion | **~$9.50/user/month** (Standard) | **Free tier for up to 5 users** | **Incident management and alerting** — **On-call scheduling, escalations, and multi-channel notifications** . **Integrates with Jira Service Management** . |
| **[xMatters](https://www.xmatters.com/)** 📡 | Everbridge | ~$1 Billion | **Custom enterprise pricing** | **Free trial available** | **Digital operations management** — **Intelligent alerting and incident response** . **Integration with DevOps and ITSM tools** . |
| **[FireHydrant](https://firehydrant.com/)** 🔥 | FireHydrant | Private | **Custom pricing** | **Free trial available** | **Incident management platform** — **Runbooks, incident command, and retrospectives** . |
| **[Rootly](https://rootly.com/)** 🌱 | Rootly | Private | **Custom pricing** | **Free trial available** | **Slack-native incident management** — **Automated workflows and retrospectives** . |
| **[Incident.io](https://incident.io/)** ⚡ | Incident.io | Private | **Custom pricing** | **Free trial available** | **Slack-native incident management** — **Declare incidents, assemble responders, automate workflows** . |
| **[BigPanda](https://www.bigpanda.io/)** 🐼 | BigPanda | Private | **Custom enterprise pricing** | **Demo available** | **AIOps platform** — **Alert correlation and noise reduction** . **Incident intelligence and automated root cause** . |
| **[Torq](https://torq.io/)** ⚙️ | Torq | Private | **Custom enterprise pricing** | **Free trial available** | **Hyperautomation security platform** — **No-code security automation and incident response** . **SOC automation** . |

---

## 🔓 Open-Source GitHub Projects

*Sorted by GitHub_Stars_Count (Descending)* 🌟

- **[StackStorm](https://github.com/StackStorm/st2)** [![Stars](https://img.shields.io/github/stars/StackStorm/st2?style=social&color=white)](https://github.com/StackStorm/st2/stargazers)  
  **Event-driven automation platform for incident response**, Apache-2.0 licensed. **The leading open-source automation platform** — **acts as the reactive brain of your incident pipeline** . **Sensor-based rules trigger diagnostic scripts** the moment an alert appears, delivering results to the incident channel automatically . **Workflows mix Python, bash, and webhooks** in a single chain, unified by a YAML-based rule engine . **Strong ChatOps support** via Slack, Mattermost, and Microsoft Teams . **Centralized audit trail** for action executions and rule firings . **Massive integration packs** for common monitoring and chat tools . **Not an alerting or on-call tool on its own** — **complements your existing monitoring stack** . 🧠

- **[Regen](https://github.com/FluidifyAI/Regen)** [![Stars](https://img.shields.io/github/stars/FluidifyAI/Regen?style=social&color=white)](https://github.com/FluidifyAI/Regen/stargazers)  
  **Open-source on-call management, alerts, incidents, and AI post-mortems**, AGPLv3 licensed. **The leading self-hosted PagerDuty alternative** — **unlimited alerts, incidents, on-call schedules, and AI postmortems** with **BYO-AI key** (OpenAI/Anthropic/Ollama) [citation:3]. **Incident lifecycle with immutable timeline** . **Escalation policies with multi-step timeouts** . **Alert ingestion from Prometheus, Grafana, CloudWatch, and generic webhooks** . **Slack and Microsoft Teams integration** with Adaptive Cards and bot commands . **1-click migration from Grafana OnCall and PagerDuty** . **SSO/SAML free** (Okta, Azure AD, Google Workspace) . **Docker Compose and Kubernetes Helm deployment** . **PostgreSQL HA + Redis Sentinel support** . **Benchmark: webhook ingestion p99 < 10ms, 3,917 RPS peak throughput, 0 × 5xx** [citation:3]. 🚀

- **[Sentinel Framework](https://github.com/VishalVinayRam/Project-KEMM)** [![Stars](https://img.shields.io/github/stars/VishalVinayRam/Project-KEMM?style=social&color=white)](https://github.com/VishalVinayRam/Project-KEMM/stargazers)  
  **AI-powered incident response framework**, open-source. **Watches production alerts, confirms they are real failures via 3-signal cross-check** (health endpoint + smoke test + metrics), **runs a 5-step root cause analysis pipeline** (recent commits → RAG query → LLM RCA → runbook), and **posts everything to a live dashboard in under two minutes** [citation:2]. **Plugs into any cloud (AWS, GCP), any git provider (GitHub, GitLab), and any LLM** (KServe/Ollama bridge, OpenAI, Anthropic, Gemini, Ollama) . **LLM fallback chain** — if primary unavailable, automatically tries gemini-1.5-flash → gpt-4o-mini → claude-haiku . **Also ships a PR Security Agent** — every pull request is scanned for OWASP issues, missed edge cases, and structural bugs before merge . **FastAPI dashboard with 15-second auto-refresh** . **Docker-based quick start in 60 seconds** . 🤖

- **[AutoSRE](https://github.com/autosre-ai/autosre)** [![Stars](https://img.shields.io/github/stars/autosre-ai/autosre?style=social&color=white)](https://github.com/autosre-ai/autosre/stargazers)  
  **Autonomous SRE agent system**, open-source. **Cuts 45-minute investigations to 5 minutes** with **multi-agent investigation** (triage → contain → investigate → resolve → learn) [citation:7]. **Episodic memory** — learns from every investigation and recalls similar incidents with **SQLite-based FTS5 search** . **SLO-driven operations** — error budgets, multi-window burn rates, deployment gating built-in . **AI safety built-in** — confidence scoring (0.0-1.0) on every decision, human-in-the-loop for remediation, full audit trails . **Extensible skills system** — Kubernetes, metrics analysis, log analysis, traces, infrastructure . **Automated postmortems** with auto-generated timelines, metrics snapshots, and action items . **Integrations: Prometheus, Grafana, Datadog, PagerDuty, Slack, OpsGenie, Kubernetes, AWS, GCP, GitHub, GitLab, Jira, Linear** . **No Neo4j, no Postgres, no infrastructure** — just `pip install autosre-ai` . 🎯

- **[PagerLite](https://github.com/pagerlite/pagerlite-laravel)** [![Stars](https://img.shields.io/github/stars/pagerlite/pagerlite-laravel?style=social&color=white)](https://github.com/pagerlite/pagerlite-laravel/stargazers)  
  **Dead-simple, self-hosted on-call and paging system for Laravel**, open-source. **In the spirit of Horizon and Telescope** — **install the package, visit `/pagerlite`, add your team, and drag someone onto the calendar** [citation:8]. **When an incident comes in, PagerLite notifies whoever is on call and escalates until somebody acknowledges** . **Everything lives in your own database** — no data ever leaves your app . **Features**: incident ingestion via single POST endpoint + `PagerLite::notify()` facade, drag-and-drop on-call calendar, escalation chain with timeouts, acknowledge/resolve with full timeline, member insights, embeddable read-only calendar, live updates, email notifications through your app's existing mail configuration . **PHP 8.4+ / Laravel 12 required** . **The simplest open-source on-call system for Laravel teams** . 🚨

- **[AlertChain](https://github.com/secmon-lab/alertchain)** [![Stars](https://img.shields.io/github/stars/secmon-lab/alertchain?style=social&color=white)](https://github.com/secmon-lab/alertchain/stargazers)  
  **Simple SOAR framework leveraging OPA (Open Policy Agent)**, Apache-2.0 licensed. **Accepts structured event data via HTTP** and **determines actions based on policies written in Rego** [citation:4]. **Alert Policy** determines whether incoming event data should be treated as an alert . **Action Policy** determines appropriate response — e.g., stop instance, restrict communication, notify administrator, query ChatGPT for summary, post to Slack . **Actions are Go code with unique IDs** — `chatgpt.comment_alert` creates a summary and recommended response . **The most policy-driven open-source SOAR framework** . 🔗

- **[SOARCA](https://github.com/COSSAS/SOARCA)** [![Stars](https://img.shields.io/github/stars/COSSAS/SOARCA?style=social&color=white)](https://github.com/COSSAS/SOARCA/stargazers)  
  **Open-source SOAR orchestrator with CACAO v2 and OpenC2 support**, Apache-2.0 licensed. **Developed for research and innovation** — allows SOC, CERT, and CTI professionals to **experiment with playbook-driven security automation** [citation:9]. **Native support for CACAO v2 (machine-readable security playbooks) and OpenC2 (standardized command and control for cyber defense technologies)** . **Ingests, validates, and executes CACAOv2 security playbooks via JSON API** . **Native HTTP(s), SSH, and OpenC2 capabilities** to interface with external tools . **MQTT interface for custom integrations** . **The most standards-compliant open-source SOAR platform** . 📜

- **[Catalyst](https://github.com/mshehata-dev/catalyst)** [![Stars](https://img.shields.io/github/stars/mshehata-dev/catalyst?style=social&color=white)](https://github.com/mshehata-dev/catalyst/stargazers)  
  **Open-source SOAR system for alert handling and incident response**, open-source. **Tickets are the core** — represent alerts, incidents, forensics investigations, threat hunts . **Tasks as smallest unit of work** — assignable to users with status tracking . **Reactions for automation** — each reaction is a trigger + action; triggers for HTTP/Webhooks and Collection Hooks, actions for Python and HTTP/Webhooks . **Timelines for documenting investigation progress** . **Dashboards for at-a-glance information** . **Ticket Types with custom fields** for MITRE ATT&CK information and custom data . 🎫

- **[OpenNMS Horizon](https://github.com/OpenNMS/opennms)** [![Stars](https://img.shields.io/github/stars/OpenNMS/opennms?style=social&color=white)](https://github.com/OpenNMS/opennms/stargazers)  
  **Network management platform with incident correlation**, AGPL-3.0 licensed. **Network operations centers and IT teams managing hundreds of devices** where **correlation and topology matter most** [citation:17]. **Free and open source**; **Meridian offers LTS releases and paid subscription** . **Interface feels dated compared to modern SPA dashboards** . **Primarily network-focused; application monitoring requires additional plugins** . 🌐

- **[Netdata](https://github.com/netdata/netdata)** [![Stars](https://img.shields.io/github/stars/netdata/netdata?style=social&color=white)](https://github.com/netdata/netdata/stargazers)  
  **Real-time infrastructure monitoring with 1-second granularity**, GPL-3.0 licensed. **Collects thousands of metrics per server** with **powerful alerting engine** [citation:17]. **Sub-second collection and pre-built alarms** let you catch anomalies before they snowball . **Hundreds of pre-configured alarms** for MySQL, Nginx, etc. **Notification webhooks target different channels per alarm role** . **Zero-config installation** with **extremely low resource footprint** . **Limitations: no built-in on-call scheduling or escalation logic, incident collaboration features minimal** . **Free for up to 5 nodes on Cloud, then $3/node/month** . ⚡

- **[Zentral](https://github.com/zentralopensource/zentral)** [![Stars](https://img.shields.io/github/stars/zentralopensource/zentral?style=social&color=white)](https://github.com/zentralopensource/zentral/stargazers)  
  **Combines osquery's endpoint inventory with flexible notification and action framework**, open-source. **Identify and react to changes on OS X and Linux clients** [citation:1]. **The most complete open-source endpoint-driven incident response platform** . 🖥️

---

## 🛠️ How to Contribute

Contributions are welcome! Follow these steps to submit new automated incident response platforms or open-source SOAR software:

1. 🍴 **Fork** the repository.
2. 📝 **Add/edit** entries in `README.md` maintaining table/list structure and formatting.
3. 🔗 Include project title, official website/GitHub link, exact Stars_Count, license, and brief description.
4. 🚀 Submit a **Pull Request** with a descriptive summary of your changes.

---

## 📊 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Automated-Incident-Response&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Automated-Incident-Response&type=date&legend=top-left)

---

## 🤝 Support & Sponsorship

If you find this automated incident response repository useful, please consider supporting the project:

- ⭐ **Star** this repository to increase visibility!
- 🔀 **Fork** and share with fellow SREs, security operations teams, and open-source advocates.
- ☕ **Sponsor & Buy Me a Coffee**: Support ongoing open-source curation via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).

---

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement. ℹ️
- **Regen is the leading self-hosted PagerDuty alternative** with **unlimited alerts, incidents, on-call schedules, and AI postmortems** — **1-click migration from Grafana OnCall and PagerDuty** and **SSO/SAML free** [citation:3]. **Benchmark: webhook ingestion p99 < 10ms, 3,917 RPS peak throughput, 0 × 5xx** [citation:3].
- **AI-powered incident response is maturing** — **Sentinel Framework confirms failures via 3-signal cross-check and runs a 5-step RCA pipeline in under two minutes** [citation:2]. **AutoSRE cuts 45-minute investigations to 5 minutes with episodic memory and SLO-driven operations** [citation:7].
- **Open-source incident response tools are not turnkey** — **Regen requires Docker Compose or Kubernetes, PostgreSQL HA, and Redis Sentinel** [citation:3]. **PagerLite requires PHP 8.4+, Laravel 12, and a real queue driver** [citation:8]. **StackStorm requires infrastructure coding knowledge and has a complex setup** [citation:17]. **Always validate alert ingestion, escalation timing, and remediation safety with a proof-of-concept** before production deployment. 🚨

---

<p align="center">
  <b>Made with ❤️ for SREs, security operations teams, and open-source incident response advocates.</b>
</p>
