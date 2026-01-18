# AI Support Ticket Automation
## Project Artifact

📄 **AI-Powered Customer Support Workflow**

[View the full project deck](AI-Powered Customer Support Workflow.pdf)

## Overview
This project demonstrates an end-to-end AI-powered automation system for
customer support ticket classification and routing.

The workflow uses an LLM to analyze incoming support requests, determine
category and urgency, and log structured outputs for operational visibility.

## Problem
Manual ticket triage is time-consuming, inconsistent, and difficult to scale
as support volume grows.

## Solution
Built a production-style AI automation workflow using:
- Zapier / Make for orchestration
- Large Language Models (LLMs) for classification
- Google Sheets for logging and review
- Webhooks and APIs for system integration

## Workflow
1. Support ticket is received
2. LLM analyzes ticket content
3. Category and priority are assigned
4. Results are logged for tracking and review
5. Optional human escalation if confidence is low

## Key Features
- Automated categorization and prioritization
- Structured outputs for downstream systems
- Designed with monitoring and error handling in mind
- Easily extensible to CRM or helpdesk tools

## Example Output
```json
{
  "category": "Billing",
  "priority": "High",
  "confidence": 0.92
}
