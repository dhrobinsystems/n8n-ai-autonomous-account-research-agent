# ⚠️ Disclaimer & Liability Limitation

**Use at your own risk.** The code, workflows, and scripts in this repository (`n8n-ai-autonomous-account-research-agent`) are provided for educational and architectural demonstration purposes.

## No Liability

The author and dhRobin Systems accept no responsibility or liability for any direct, indirect, incidental, or consequential damages that result from using, misusing, or deploying these scripts. This includes, without limitation, lost revenue, lost or corrupted CRM data, duplicate or inaccurate notes on company records, unintended disclosure of information, outreach based on incorrect research, service interruptions, and charges incurred with third-party providers.

## No Warranty

All software, n8n JSON blueprints, JavaScript modules and prompts are provided "AS IS", without warranty of any kind, express or implied. This includes, but is not limited to, warranties of merchantability, fitness for a particular purpose, and non-infringement.

No warranty is given that web research results are complete, current or about the intended company; that AI-generated summaries, tech-stack conclusions, executive changes or outbound hooks are accurate; that citation validation will catch every error; or that domain filtering and contact-detail scrubbing will detect every case.

## Production Testing Required

Always test thoroughly in an isolated staging environment, such as a HubSpot developer test account or sandbox, with `SANDBOX_MODE=true`, `DRY_RUN=true` and `WRITE_TO_HUBSPOT=false` enabled, before you connect live HubSpot, Exa, Perplexity or OpenAI credentials. Enable live research, live synthesis, CRM writes and Slack notifications one step at a time, reviewing the output of each step before the next.

Treat every generated account brief as a draft that a person must verify before it's relied on or used in outreach.

## Third-Party APIs & Compliance

You alone are responsible for complying with the terms of service, rate limits, data privacy regulations (GDPR/CCPA), and security policies of HubSpot, Exa, Perplexity, OpenAI, Slack and any connected services. That includes:

- confirming a lawful basis for collecting and processing public information about companies and their executives, and documenting any legitimate-interest assessment;
- reviewing the data retention, training and sub-processor terms of each research and AI provider before sending any data to it;
- keeping personal data, including personal contact details, out of CRM notes and Slack alerts;
- honouring opt-out, objection and deletion requests that relate to people named in generated briefs;
- securing, rotating and restricting access to every API key, client secret, token and webhook URL;
- reviewing every automatically created or updated record.

## No Affiliation

HubSpot, Exa, Perplexity, OpenAI, Slack and n8n are trademarks of their respective owners. This project is independent and is not affiliated with, endorsed by, or sponsored by any of them. All companies, domains, identifiers, people and events in the fixtures and pinned data are fictitious.

## Not Professional Advice

Nothing in this repository constitutes legal, privacy, security, or financial advice. Consult qualified professionals for your specific circumstances.

---

Released under the MIT License. Copyright (c) 2026 DH Robin (dhRobin Systems). See [LICENSE](LICENSE).

Full text: DISCLAIMER.md · Licensed under the MIT License. License: MIT © 2026 dhRobin Systems · Provided as-is, see the disclaimer.
