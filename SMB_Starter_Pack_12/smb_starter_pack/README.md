
# SMB Starter Pack (12 Workflows)

Includes the Top 10 plus two extras tailored for SMBs:
11. Content Brief Generator (Webhook → LLM → Doc → Slack)
12. Data Sync with Validation (Cron → A → LLM → B → Slack)

**Import & Setup**
1) Import JSONs into n8n (Menu → Import workflow → File).
2) Set Credentials for: Slack, OpenAI, Email (SMTP/Outlook), HTTP Request nodes.
3) For Webhook-based flows, click the **Webhook** node to see **Test** & **Production** URLs. Activate workflow to register production webhook.
4) For Slack approval nodes, update the channel IDs and ensure your Slack app has `chat:write` and related scopes.

**Environment Variables (recommended)**
- `SLACK_CHANNEL_ID`, `SLACK_APPROVAL_CHANNEL_ID`
- `FROM_EMAIL`, `TO_EMAIL`
- Any API base URLs and tokens you prefer to inject at runtime.

