# servicenow-ai-incident-agent
An AI agent that reads ServiceNow incidents, auto-classifies them, and drafts resolution responses.
## What it does

- Ingests new ServiceNow incidents via REST API and parses the description and details.
- Classifies each incident's category and priority with an LLM, then routes it to the right assignment group.
- Drafts a suggested first response / resolution for a human agent to review and send.
