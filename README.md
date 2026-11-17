# Portfolio

High-level descriptions of systems I have designed and delivered. Each project
page covers the problem, my exact role, the architecture, how it is tested
and what it has produced. No source code is published here.

## Projects

| Project | Description | My role | Core stack | Status |
| --- | --- | --- | --- | --- |
| [Private Intelligence Platform](projects/private-intelligence-platform/README.md) | Multi-tenant platform that searches, organizes and packages an organization's own email and records, and audits its contracts | Founder, system designer and technical lead; directed an AI coding agent that wrote the code | Python, PostgreSQL, Terraform, AWS, Microsoft Graph, Gmail API, Docker, GitHub Actions | In development; pre-revenue |
| [Marineland Public Intelligence Platform](projects/marineland-public-intelligence-platform/README.md) | Email records search and production pipeline for public records requests at the Town of Marineland, FL | Contributor: designed and delivered the review-binder, de-duplication and reliability work on a core system built by Blue Dot Fund | Python, Microsoft Graph, AWS, MySQL, pytest | Used for the Town's public records requests in 2026 |

## How I build

I design the system, write the requirements and decide the security controls.
An AI coding agent (Claude Code) then implements the code, writes the tests
and debugs failures under my direction. I work in small, reviewable changes:
one feature or fix per branch, with the full automated test suite run before
anything is merged.

Every output is reviewed by a person. I review the agent's code and test
results, larger changes get an independent review before merge, and the
products themselves follow the same rule: the software proposes, and a person
approves anything that goes to a client or the public.

What I bring is the system design, the judgment about what is safe and
correct, the test and release discipline, and accountability for the result.
The project pages state plainly which parts I built, which parts others
built, and which parts an AI coding agent wrote under my direction.

---

Descriptions only. Source code is private. All rights reserved.
