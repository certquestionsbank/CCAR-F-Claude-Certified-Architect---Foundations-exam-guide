# CCAR-F-Claude-Certified-Architect---Foundations-exam-guide
The CCAR-F Claude Certified Architect - Foundations certification is for practitioners who design and implement production applications with Claude.
It focuses on the decisions that shape a real solution: how agents work together, how tools connect to backend systems, how Claude Code supports a team workflow, and how prompts, context, and structured output affect reliability.

## CCAR-F exam at a glance

| Exam detail | Information |
| --- | --- |
| Exam code | CCAR-F |
| Number of items | 60 |
| Item format | Multiple-choice and multiple-response items. Each item states how many responses to select. |
| Exam structure | Four scenarios drawn from a bank of six |
| Time limit | 120 minutes |
| Delivery | Proctored online and/or test center delivery, per program policy |
| Passing score | Scaled score of 720 on a scale of 100 to 1,000 |
| Exam fee | $125 USD |
| Credential validity | 12 months from the award date |
| Score report | Pass/fail, scaled score, and percent-correct results by domain |

## Who the exam is for

CCAR-F is aimed at solution architects who work with Claude in production application environments. The intended candidate has hands-on experience with agentic applications, Claude Code workflows, MCP integrations, and prompt design for structured results.

The exam is a good fit for someone who can evaluate implementation tradeoffs instead of treating individual features in isolation. A solution architect may need to decide how an agent is orchestrated, where a tool interface belongs, how context is managed, or how a team can use configuration consistently. Those decisions sit at the center of the certification.

## Experience covered by the exam

Candidates are expected to have practical familiarity with the following areas:

- Building agentic applications with the Claude Agent SDK, including multi-agent orchestration, subagent delegation, tool integration, and lifecycle hooks.
- Configuring Claude Code for team workflows with CLAUDE.md files, Agent Skills, MCP server integrations, and plan mode.
- Designing MCP tool and resource interfaces that connect backend systems.
- Engineering prompts for reliable structured output with JSON schemas, few-shot examples, and extraction patterns.

This is a broad set of skills, but the common thread is system design. Review each topic with the question, "What tradeoff does this choice create for the application and its users?"

## CCAR-F exam topics and weighting

| Domain | Weight |
| --- | ---: |
| Agentic Architecture & Orchestration | 27% |
| Claude Code Configuration & Workflows | 20% |
| Prompt Engineering & Structured Output | 20% |
| Tool Design & MCP Integration | 18% |
| Context Management & Reliability | 15% |

Agentic architecture and orchestration is the largest domain. It deserves extra attention, especially when you are reviewing multi-agent patterns, subagent delegation, tool use, and lifecycle behavior. The three remaining substantial domains also need steady coverage. A study plan that ignores Claude Code workflows or prompt engineering can leave large gaps.

## What to study in each domain

### Agentic architecture and orchestration

Start with the role of the Claude Agent SDK in building agentic applications. Review how multiple agents can work together, where subagents fit, and how tool integration and lifecycle hooks affect the behavior of an application. Practice describing why one orchestration choice suits a scenario better than another.

### Tool design and MCP integration

MCP is part of the exam's core technology set. Focus on the design of tool and resource interfaces for backend integration. When studying, look beyond the name of a tool. Consider the interface, the information it makes available, and the role it plays in the larger application.

### Claude Code configuration and workflows

This domain covers how teams can customize Claude Code. Review the purpose of CLAUDE.md files, Agent Skills, MCP server integrations, and plan mode. Think in terms of repeatable team workflows: what should be configured, how that configuration affects day-to-day work, and how the pieces fit together.

### Prompt engineering and structured output

The exam includes prompts that produce reliable structured output. Study JSON schemas, few-shot examples, and extraction patterns. A useful review habit is to take a desired output format and explain how a prompt can make that format clear, testable, and consistent.

### Context management and reliability

Context management makes up 15% of the exam. Review it alongside the other domains rather than treating it as a separate final topic. Architecture, tool design, and prompting all affect what context is available and how reliably the application can produce the result that a workflow needs.

## A practical approach to CCAR-F preparation

Begin by turning the five domains into a checklist. Give more study time to Agentic Architecture & Orchestration because it carries the highest weighting, then make sure the other four domains receive focused review.

Next, use scenario-based study. The exam structure uses four scenarios drawn from a bank of six, so it is useful to read a problem carefully before choosing an answer. Identify the architecture concern, the tool or MCP concern, the Claude Code workflow concern, and the prompt or context concern. Some scenarios may include more than one of these.

Practice questions with explanations can make this review more active. After answering, compare your reasoning with the explanation. If an answer is wrong, do more than note the correct option. Return to the domain behind the decision and write down the tradeoff you missed.

For multiple-response items, pay attention to the number of answers the item asks you to select. Use the scenario details to test every option against the requirement instead of selecting choices that sound generally useful.

## Study with CertQuestionsBank

This [CCAR-F practice questions](https://www.certquestionsbank.com/CCAR-F.html) from CertQuestionsBank can serve as a checklist for your preparation. When you use practice questions with explanations, review each answer choice and revisit the domain behind it.
