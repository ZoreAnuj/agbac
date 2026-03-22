# AGent Based Access Control (AGBAC)

AGBAC is an open specification for enabling AI agents to securely perform actions on behalf of users using existing Identity and Access Management (IAM) systems. This project explores the implementation of zero-trust authentication, authorization, and auditing principles specifically for autonomous AI agents.

## Key Features
*   Defines a protocol for AI agents to request and use delegated user permissions.
*   Integrates with standard OAuth 2.0 and OpenID Connect flows.
*   Provides a framework for auditing agent actions and maintaining security boundaries.
*   Enables fine-grained, just-in-time access control for agent operations.

## Tech Stack
*   Python
*   OAuth 2.0 / OpenID Connect
*   JWT (JSON Web Tokens)

## Getting Started
1.  Clone the repository: `git clone https://github.com/zoreanuj/agbac.git`
2.  Install dependencies: `pip install -r requirements.txt`
3.  Run the example agent and authorization server to explore the protocol flow.