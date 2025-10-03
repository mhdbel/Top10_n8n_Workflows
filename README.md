
# Top 10 Ready-to-Import n8n Workflows

Each JSON is a self-contained n8n workflow. Import via **Menu → Import workflow → From file**.

> ⚙️ After import, open nodes with red credentials badges and connect your accounts (Slack, OpenAI, Email, HTTP endpoints). Set environment variables (e.g., `SLACK_CHANNEL_ID`, `FROM_EMAIL`).

**List**
1. Lead Router (Webhook → Enrich → LLM Score → Slack)
2. Helpdesk RAG (Webhook → Vector Search → LLM → Slack Approval)
3. Executive Daily Briefing (Cron → Pull Data → LLM → Slack)
4. AP Invoice OCR → Slack Approval → ERP
5. Meeting Assistant (Webhook → ASR → LLM → Tasks → Slack)
6. E‑commerce Returns Agent (Webhook → Lookup → LLM → Email)
7. Review Responder (Webhook → LLM → Slack HITL → Post)
8. PR Summarizer (Webhook → Fetch → LLM → Slack)
9. Onboarding Orchestrator (Webhook → LLM → Accounts → Slack/Email)
10. KPI Snapshot to Email (Cron → Fetch → LLM)
