# IT0123 DevNet Resource Validation Plan

## Student and Project

- Name: Liam Serrano
- Section: TN35
- Repository name: `it0123-devnet-resource-plan`

## Purpose

Selecting the correct Cisco DevNet resource ensures that the access model, privileges, setup requirements, and learning purpose match the network-automation task. Verifying an AI recommendation against official Cisco documentation prevents an unsupported suggestion from becoming part of the development plan.

## Validated Resource Decisions

### UC1 Quick read-only API exploration

- Selected resource: `always-on-sandbox`
- Decisive requirement: The team needs immediate shared access for safe, non-administrative API practice and cannot wait for provisioning.
- Rationale: Cisco states that Always-On Sandboxes are immediately available, require no reservation, are shared, and restrict administrative access, which matches this use case.
- Official evidence: <https://developer.cisco.com/docs/sandbox/>
- Verification status: `verified`

### UC2 Private configuration testing

- Selected resource: `reservation-sandbox`
- Decisive requirement: The team needs private access and administrative control for configuration testing and accepts scheduling, setup time, and VPN use.
- Rationale: Cisco describes Reservation Sandboxes as private environments with administrative access that require a reservation and VPN connection.
- Official evidence: <https://developer.cisco.com/docs/sandbox/>
- Verification status: `verified`

### UC3 Guided API concept practice

- Selected resource: `learning-lab`
- Decisive requirement: A beginner needs structured, step-by-step instruction before attempting independent API work.
- Rationale: Cisco DevNet Learning provides organized learning content and guided labs, while a Sandbox alone is an execution environment rather than a structured learning path.
- Official evidence: <https://developer.cisco.com/learning/>
- Verification status: `verified`

### UC4 Reusable automation example

- Selected resource: `code-exchange`
- Decisive requirement: The developer wants to inspect existing Cisco and community code repositories before designing a new solution.
- Rationale: Cisco Code Exchange provides a curated, searchable collection of code repositories and automation examples that can help start application and integration development.
- Official evidence: <https://developer.cisco.com/codeexchange/>
- Verification status: `verified`

## AI Evaluation

The AI recommendations for all four scenarios were accepted after verification. The Always-On and Reservation Sandbox claims were checked against Cisco's documentation describing their access, isolation, reservation, VPN, and administrative-privilege differences. The Learning Lab recommendation was retained because the scenario prioritizes guided instruction, and the Code Exchange recommendation was retained because the scenario asks for existing reusable automation examples. The official evidence supported the resource categories, but no specific sandbox product, account, repository, or credential was assumed.

## Validation Evidence

- Validator result: `VALIDATION COMPLETE: 9/9 checks passed.`
- Command used: `python3 validate_plan.py`
- Official Cisco pages reviewed:
  - <https://developer.cisco.com/docs/sandbox/>
  - <https://developer.cisco.com/learning/>
  - <https://developer.cisco.com/codeexchange/>
- AI prompt record: `ai_prompt_transcript.md`

## Git Evidence

- Initial commit message: `Initialized repo & README`
- Student-plan commit message: `Completed student plan`
- Validation commit message: `Added successful validation`
- Output of `git log --oneline` at the time this README was completed:

```text
e32900f Added successful validation
a5bf51d Completed student plan
39fb425 Initialized repo & README
```

## AI-Use Disclosure

ChatGPT was used to recommend one allowed Cisco DevNet resource category for each fictional scenario, summarize the reasoning, draft the structured plan, and help prepare this README and a reconstructed prompt record. The access, isolation, setup, privilege, learning, and code-repository claims were independently compared with official pages on `developer.cisco.com`, and `validate_plan.py` was run locally until all nine checks passed. The prompt record is clearly identified as reconstructed rather than presented as a verbatim export of the original conversation.
