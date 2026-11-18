# Portfolio

AI engineering work: high-level descriptions of systems I have designed and
delivered. Each project page covers the problem, my exact role, the
architecture, how it is tested and what it has produced. No source code is
published here.

## What these projects show

- **Building agents:** agent playbooks and five Claude Code skills that take
  an agent from a plain-language request to a checked result, with human
  approval gates (all three projects).
- **Full-stack engineering:** Python back ends, a PostgreSQL data layer,
  and browser front ends such as request forms, report dashboards and a
  live quote form (Private Intelligence Platform, skills project).
- **Agents in deployed systems:** the hosted platform is built so an agent
  can queue a request on the cloud worker, check its status and report back
  (Private Intelligence Platform).
- **Cloud deployment:** the worker image is built and published by GitHub
  Actions, and the AWS environment is defined in Terraform and was built and
  rehearsed end to end on a test environment; a quote form is live on
  GitHub Pages (Private Intelligence Platform, skills project).

## Projects

| Project | Description | My role | Core stack | Status |
| --- | --- | --- | --- | --- |
| [Private Intelligence Platform](projects/private-intelligence-platform/README.md) | Multi-tenant platform that searches, organizes and packages an organization's own email and records, and audits its contracts | Founder, system designer and technical lead; directed an AI coding agent that wrote the code | Python, PostgreSQL, Terraform, AWS, Microsoft Graph, Gmail API, Docker, GitHub Actions | In development; pre-revenue |
| [Marineland Public Intelligence Platform](projects/marineland-public-intelligence-platform/README.md) | Email records search and production pipeline for public records requests at the Town of Marineland, FL | Contributor: designed and delivered the review-binder, de-duplication and reliability work on a core system built by Blue Dot Fund | Python, Microsoft Graph, AWS, MySQL, pytest | Used for the Town's public records requests in 2026 |
| [Claude Code Skills for Small Service Businesses](projects/small-business-ai-skills/README.md) | Five reusable Claude Code skills that take a small service business from content discovery to finished videos and online lead capture | Designer of the workflows and rules; directed Claude Code to build the skills, scripts and templates, and reviewed every output | Claude Code skills, Python, ffmpeg, faster-whisper, Google Apps Script, GitHub Pages | Four skills used on a real engagement; one in development |

Public code sample: [ijgb-pilot-discovery](https://github.com/wilshem/ijgb-pilot-discovery),
a live client questionnaire built with HTML, JavaScript and Google Apps
Script, with automated tests that run on every pull request.

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

I often run several AI coding agents in parallel, each on its own workstream
in a separate working copy. I consolidate their status reports, check them
against each other and route the next tasks. Every pull request runs the
automated tests in continuous integration, and larger changes are verified
independently by a different agent before they merge.

What I bring is the system design, the judgment about what is safe and
correct, the test and release discipline, and accountability for the result.
The project pages state plainly which parts I built, which parts others
built, and which parts an AI coding agent wrote under my direction.

---

Descriptions only. Source code is private. All rights reserved.
