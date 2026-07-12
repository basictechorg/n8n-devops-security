<div align="center">

<h1>DevOps, Security & Reliability</h1>

<h3>160 production-ready n8n workflows &mdash; every credential stripped, every model current</h3>

<p>
<img alt="Workflows" src="https://img.shields.io/badge/workflows-160-EA4B71?style=for-the-badge">
<img alt="Secrets" src="https://img.shields.io/badge/secrets-0-brightgreen?style=for-the-badge">
<img alt="License" src="https://img.shields.io/badge/license-MIT-3b82f6?style=for-the-badge">
</p>

<p><em>DevOps, security, monitoring, and backup workflows for n8n.<br>Sanitized of all secrets, modernized to current n8n nodes and AI models, and continuously scanned by CI.</em></p>

<p><b><a href="#-whats-inside">What's Inside</a> &nbsp;·&nbsp; <a href="#-categories">Categories</a> &nbsp;·&nbsp; <a href="#-featured-workflows">Featured</a> &nbsp;·&nbsp; <a href="#-quick-start">Quick Start</a> &nbsp;·&nbsp; <a href="#-security">Security</a></b></p>

</div>

---

## 📦 What's inside

This repository collects **160 ready-to-import workflows** across **3 categories**. Every file has been engineered to the same standard:

| | |
|---|---|
| 🔐 **Zero secrets** | No credentials, API keys, instance IDs, webhook secrets, or personal data. Verified by GitHub secret scanning + gitleaks. |
| 🔄 **Current stack** | Latest AI models (GPT-4o, Claude 4.x, Gemini 2.5) and current n8n node types &mdash; no deprecated nodes, no 2023-era models. |
| ✅ **CI-validated** | Every push runs JSON/structure validation and a full-history secret scan. |
| 📁 **Organized** | Grouped by category so you find the right workflow in seconds. |

### Built with

<p>
<img alt="n8n" src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white">
<img alt="GitHub" src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white">
<img alt="Google Sheets" src="https://img.shields.io/badge/Google%20Sheets-34A853?style=flat-square&logo=googlesheets&logoColor=white">
<img alt="Slack" src="https://img.shields.io/badge/Slack-4A154B?style=flat-square&logo=slack&logoColor=white">
<img alt="OpenAI" src="https://img.shields.io/badge/GPT--4o-412991?style=flat-square&logo=openai&logoColor=white">
<img alt="Google Drive" src="https://img.shields.io/badge/Google%20Drive-4285F4?style=flat-square&logo=googledrive&logoColor=white">
<img alt="Notion" src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white">
<img alt="Telegram" src="https://img.shields.io/badge/Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white">
<img alt="Gmail" src="https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white">
</p>

---

## 🗂️ Categories

| Category | Workflows | What it covers |
|---|:--:|---|
| ⚙️ DevOps & IT Ops | 97 | Deployments, monitoring, and infrastructure automation |
| 🔄 Data Sync & Backup | 51 | Two-way syncs, migrations, and exports |
| 🔐 Security Ops | 12 | Threat intel, phishing analysis, and cert lifecycle |

---

## ⭐ Featured workflows

*The most comprehensive automations in this collection.*

- **[Realtime Notion Todoist 2-way Sync Template](workflows/data-sync-backup/1897_Webhook_Filter_Sync_Webhook.json)** &mdash; `Webhook` trigger · 246 nodes · HTTP · Notion · Webhook · Todoist
- **[Notion to Clockify Sync Template](workflows/data-sync-backup/1498_Stopanderror_Limit_Sync_Webhook.json)** &mdash; `Webhook` trigger · 68 nodes · Webhook · Clockify · Notion · HTTP
- **[Workflow Importer](workflows/data-sync-backup/1169_Splitout_Code_Import_Webhook.json)** &mdash; `Form` trigger · 58 nodes · HTTP
- **[PUQ Docker NextCloud deploy](workflows/devops-it-ops/1832_Code_Webhook_Automation_Webhook.json)** &mdash; `Webhook` trigger · 44 nodes · Webhook · HTTP

---

## 📚 Browse by category


### ⚙️ DevOps & IT Ops

*Deployments, monitoring, and infrastructure automation — 97 workflows.*

| Workflow | Trigger | Built with | Nodes |
|---|:--:|---|:--:|
| [PUQ Docker NextCloud deploy](workflows/devops-it-ops/1832_Code_Webhook_Automation_Webhook.json) | `Webhook` | Webhook · HTTP | 44 |
| [Pyragogy AI Village - Orchestrazione Master (Architettura ](workflows/devops-it-ops/generate-collaborative-handbooks-with-gpt4o-multi-agent-orchestration-human-review.json) | `Event` | Webhook · Postgres · OpenAI · GitHub | 36 |
| [puq-docker-immich-deploy](workflows/devops-it-ops/1966_Code_Webhook_Automation_Webhook.json) | `Webhook` | Webhook | 35 |
| [Pyragogy AI Village - Orchestrazione Master (Architettura ](workflows/devops-it-ops/content-management__generate-collaborative-handbooks-with-gpt4o-multi-agent-orchestration-human-review.json) | `Event` | Webhook · Postgres · OpenAI · GitHub | 35 |
| [puq-docker-n8n-deploy](workflows/devops-it-ops/1825_Code_Webhook_Automation_Webhook.json) | `Webhook` | Webhook | 34 |
| [puq-docker-influxdb-deploy](workflows/devops-it-ops/1815_Code_Webhook_Automation_Webhook.json) | `Webhook` | Webhook | 33 |
| [puq-docker-minio-deploy](workflows/devops-it-ops/1500_Code_Webhook_Automation_Webhook.json) | `Webhook` | Webhook | 33 |
| [Build your first AI MCP Server](workflows/devops-it-ops/1184_Debughelper_HTTP_Create_Webhook.json) | `Manual` | HTTP | 32 |
| [automation__Code_GitHub_Create_Scheduled.json](workflows/devops-it-ops/automation__Code_GitHub_Create_Scheduled.json) | `Event` | HTTP · GitHub · Slack | 26 |
| [Manualtrigger Workflow](workflows/devops-it-ops/0182_Code_GitHub_Create_Scheduled.json) | `Event` | HTTP · GitHub · Slack | 26 |
| [Manualtrigger Workflow](workflows/devops-it-ops/0718_Code_GitHub_Create_Scheduled.json) | `Event` | HTTP · GitHub | 25 |
| [Code_GitHub_Create_Scheduled.json](workflows/devops-it-ops/Code_GitHub_Create_Scheduled.json) | `Event` | HTTP · GitHub | 25 |
| *…and 85 more* | | [`devops-it-ops/`](workflows/devops-it-ops/) | |


### 🔄 Data Sync & Backup

*Two-way syncs, migrations, and exports — 51 workflows.*

| Workflow | Trigger | Built with | Nodes |
|---|:--:|---|:--:|
| [Realtime Notion Todoist 2-way Sync Template](workflows/data-sync-backup/1897_Webhook_Filter_Sync_Webhook.json) | `Webhook` | HTTP · Notion · Webhook · Todoist | 246 |
| [Notion to Clockify Sync Template](workflows/data-sync-backup/1498_Stopanderror_Limit_Sync_Webhook.json) | `Webhook` | Webhook · Clockify · Notion · HTTP | 68 |
| [Workflow Importer](workflows/data-sync-backup/1169_Splitout_Code_Import_Webhook.json) | `Form` | HTTP | 58 |
| [Spotify Sync Liked Songs to Playlist](workflows/data-sync-backup/1867_Schedule_Filter_Sync_Scheduled.json) | `Event` | n8n core | 41 |
| [Spotify Sync Liked Songs to Playlist](workflows/data-sync-backup/Schedule_Filter_Sync_Scheduled.json) | `Event` | n8n core | 40 |
| [Splitout_Code_Export_Webhook.json](workflows/data-sync-backup/Splitout_Code_Export_Webhook.json) | `Event` | OpenAI Embeddings · HTTP · OpenAI · Google Sheets | 37 |
| [Import Productboard Notes, Companies and Features into Sno](workflows/data-sync-backup/0643_Splitout_Snowflake_Import_Scheduled.json) | `Scheduled` | HTTP · Snowflake · Slack | 35 |
| [Wait_Code_Export_Webhook_1_1_1.json](workflows/data-sync-backup/Wait_Code_Export_Webhook_1_1_1.json) | `Event` | HTTP · AI Agent · Qdrant | 33 |
| [Splitout_Filter_Import_Webhook.json](workflows/data-sync-backup/Splitout_Filter_Import_Webhook.json) | `Event` | HTTP | 26 |
| [Dialpad to Syncro](workflows/data-sync-backup/0347_HTTP_GoogleSheets_Sync_Webhook.json) | `Webhook` | HTTP · Webhook · Google Sheets | 23 |
| [Splitout_Schedule_Import_Webhook.json](workflows/data-sync-backup/Splitout_Schedule_Import_Webhook.json) | `Scheduled` | HTTP · HubSpot | 22 |
| [Credentials Transfer](workflows/data-sync-backup/1984_Code_Executecommand_Automation_Webhook.json) | `Form` | HTTP | 22 |
| *…and 39 more* | | [`data-sync-backup/`](workflows/data-sync-backup/) | |


### 🔐 Security Ops

*Threat intel, phishing analysis, and cert lifecycle — 12 workflows.*

| Workflow | Trigger | Built with | Nodes |
|---|:--:|---|:--:|
| [Venafitlsprotectcloud Workflow](workflows/security-ops/1733_Webhook_Slack_Automate_Webhook.json) | `Webhook` | HTTP · Slack · Webhook | 38 |
| [Venafi Cloud Slack Cert Bot.json](workflows/security-ops/Venafi Cloud Slack Cert Bot.json) | `Webhook` | HTTP · OpenAI · Slack · Webhook | 38 |
| [Venafitlsprotectcloud Workflow](workflows/security-ops/0581_Webhook_Slack_Create_Webhook.json) | `Webhook` | HTTP · Slack · Webhook | 38 |
| [Automate SIEM Alert Enrichment with MITRE ATT&CK, Qdrant &](workflows/security-ops/Automate SIEM Alert Enrichment with MITRE ATT&CK, Qdrant & Zendesk in n8n.json) | `Chat` | AI Agent · OpenAI · OpenAI Embeddings · Google Drive | 26 |
| [Phishing_analysis__URLScan_io_and_Virustotal_](workflows/security-ops/1600_Wait_Code_Automation_Scheduled.json) | `Event` | Slack · HTTP | 23 |
| [Enhance Security Operations with the Qualys Slack Shortcut](workflows/security-ops/Enhance Security Operations with the Qualys Slack Shortcut Bot!.json) | `Webhook` | HTTP · Webhook | 23 |
| [Analyze_Crowdstrike_Detections__search_for_IOCs_in_VirusTo](workflows/security-ops/monitoring__Wait_Schedule_Create_Webhook.json) | `Scheduled` | HTTP · Jira · Slack | 18 |
| [Analyze_Crowdstrike_Detections__search_for_IOCs_in_VirusTo](workflows/security-ops/1312_Wait_Schedule_Create_Webhook.json) | `Scheduled` | HTTP · Jira · Slack | 18 |
| [Production Workflow](workflows/security-ops/0055_Signl4_Interval_Create_Scheduled.json) | `Event` | Webhook · Notion | 14 |
| [TheHive](workflows/security-ops/0942_Webhook_Signl4_Automation_Webhook.json) | `Webhook` | Webhook | 8 |
| [TheHive](workflows/security-ops/Webhook_Signl4_Automation_Webhook_1.json) | `Webhook` | Webhook | 7 |
| [Manualtrigger Workflow](workflows/security-ops/1216_Manual_Schedule_Automate_Scheduled.json) | `Event` | n8n core | 6 |

---

## 🚀 Quick start

```text
1.  Pick a workflow from the categories above
2.  In n8n:  Workflows  →  ⋯  →  Import from File
3.  Open each node and add your own credentials
    (every credential slot is labelled  "Add your <service> credential")
4.  Activate — you're live
```

> **Nothing here can leak.** Every credential is blanked and labelled — you supply your own keys inside n8n's credential manager. No secret material ships in this repo.

---

## 🔒 Security

Security is enforced at three layers:

1. **At rest** — every workflow is stripped of credentials, `instanceId`, `pinData`, webhook UUIDs, emails, and hardcoded keys before it is committed.
2. **In CI** — each push runs structure validation plus a [gitleaks](https://github.com/gitleaks/gitleaks) scan across the full history and working tree. GitHub Actions are **pinned to commit SHAs** to prevent supply-chain tampering.
3. **On the platform** — **secret scanning**, **push protection**, **Dependabot**, and **branch protection** (required checks, linear history, no force-push) are enabled on this repository.

Report a concern via **Security → Report a vulnerability**. Full standard in [SECURITY.md](SECURITY.md).

---

## 🙏 Credits

Curated and modernized from the open-source **n8n community**, whose templates are MIT-licensed. Original authors retain rights to their workflow logic; the curation, security engineering, and modernization are original work. Source licenses in [THIRD_PARTY_LICENSES/](THIRD_PARTY_LICENSES/) · details in [NOTICE](NOTICE).

## 📄 License

Released under the [MIT License](LICENSE).

<div align="center">
<br><sub>Maintained by <a href="https://github.com/basictechorg">basictechorg</a></sub>
</div>