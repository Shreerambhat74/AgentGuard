# AgentGuard — Zero-Trust Firewall for AI Agents

## Overview
AgentGuard is a proposed security layer that checks AI agent tool calls before they reach external systems. It uses security policies, AI-assisted risk assessment, and human approval to help prevent unauthorized or potentially harmful actions.

## Problem Statement
**PS 2.1 — AI Agent Safety and Control**

AI agents can interact with databases, APIs, and other business systems. Incorrect decisions, prompt injection, or excessive permissions may lead to unsafe actions. AgentGuard aims to provide runtime monitoring and control over these actions.

## Key Features
- **Action Interception:** Captures tool calls before execution.
- **Policy Validation:** Checks permissions, security rules, and transaction limits.
- **AI-Assisted Risk Assessment:** Helps identify suspicious or potentially harmful requests.
- **Human-in-the-Loop Approval:** Pauses sensitive actions for approval.
- **Action Blocking:** Rejects actions that violate configured security policies.
- **Audit Dashboard:** Displays action decisions and security logs.

## How It Works
1. An AI agent requests a tool action.
2. AgentGuard intercepts the request.
3. The policy engine evaluates permissions and potential risks.
4. The action is allowed, sent for human approval, or blocked.
5. The system records the decision and outcome.

## Technology Stack
- **Frontend:** Next.js, Tailwind CSS
- **Backend:** FastAPI, Python
- **AI Layer:** Gemini API
- **Database:** SQLite or Supabase

## Expected Benefits
- Helps prevent unauthorized tool actions.
- Improves visibility into AI agent activities.
- Adds human oversight for sensitive operations.
- Supports security auditing through action logs.

## Evaluation Metrics
The prototype can be evaluated using:
- Percentage of unauthorized test actions blocked.
- Average policy-check latency.
- Accuracy of risk classification.
- Percentage of tool calls recorded in audit logs.
- Successful completion rate of human approval workflows.

Performance targets will be validated through controlled testing.

## Future Scope
- Integration with additional AI agent frameworks.
- Role-based access control.
- Custom security policies for different industries.
- Improved monitoring and reporting.

## Project StatuHackathon project proposal / prototype in development. Features and performance claims should be updated as implementation and testing progress.
