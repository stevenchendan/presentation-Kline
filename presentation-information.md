# Our AI journey: from curiosity to an AI-enabled engineering capability

> Content source: user-provided presentation information. Prepared as a content reference for a future animated video or 3D presentation. Original narrative notes and source labels are retained; linked source materials have not been independently verified.

**Timeline:** August 2025–November 2026

---

## Chapter 1 | Aug-Sep 2025

### We started by learning, not by building

The journey actually starts earlier than we originally thought.

On 19 August 2025, you approached Saranya Nagarajan after an AI Agents discussion and asked for a show-and-tell of what she had learned using Claude Code for software development. [Grace Xu in chat | Teams]

On 28 August, Saranya Nagarajan and Alex Eisenmann shared their practical experimentation with the team. A key concept was using Markdown as a reusable way of giving AI engineering standards and context, including .instructions.md, .prompt.md, coding conventions, logging, error handling, API patterns and testing practices. [Claude Cod...Recording | Video], [Claude Cod...evelopment | Teams]

The supporting Future of Programming called this the "Markdown Bridge", addressing a real problem: individual developers could use coding agents, but scaling that consistently across a team required shared standards and reusable prompts. [Future of...rogramming | PowerPoint]

By 10 September, Steven Chen had already incorporated Markdown practice into the team's own short-term plan, while identifying development of AI Agents as the medium-term ambition. [Steven Chen in chat | Teams]

By 19 September, the team was designing its own Markdown-based coding, testing, review, security and integration principles for GitHub Copilot. [GitHub cop...t practice | Teams]

#### Behind the milestone

##### Challenge

We were interested in AI engineering, but didn't yet have our own established approach.

##### Learn

Instead of starting from zero, we deliberately learned from people already experimenting.

##### Pivot

We took those ideas and converted them into our own engineering standards and Markdown practices.

##### Unlock

Learning from others → team AI coding practice → reusable instructions → foundation for agents

#### The team-reflection message

> "Before we built an agent, we learned how to work with AI."

---

## Chapter 2 | Sep-Oct 2025

### From individual experimentation to a team AI engineering practice

What began as external learning quickly became internal practice.

By October, the team was formalising copilot-instructions.md, preparing demonstrations and planning how everyone could adopt the same approach. [AI agent practice | Teams]

The team wasn't simply asking Copilot to "write some code." It was asking:

How do we teach AI how our team engineers software?

The 23 October discussion shows custom instructions becoming the first layer, with patterns and prompt files being considered as additional context layers. [AI agent p...Recording | Video]

#### Behind the milestone

##### Challenge

Different developers using AI independently could produce inconsistent results.

##### Learn

AI needs engineering context, standards and expectations, not just good prompts.

##### Pivot

Move knowledge from people's individual prompts into reusable, version-controlled instructions.

##### Unlock

AI-assisted development could become a team capability, rather than an individual productivity trick.

#### Reflection line

> "We moved from people learning how to prompt AI to teaching AI how our team works."

---

## Chapter 3 | Oct-Nov 2025

### We discovered ASKnbn and stopped thinking we had to build everything ourselves

On 15 October, you pointed the group toward existing ASKnbn capabilities and the AI Sandpit. [AI agent practice | Teams]

Then the 23 October AI discussions shifted heavily toward agents. The team explored models, Confluence/API access, authentication and whether to build independently or leverage ASKnbn. [AI agent p...Recording | Video]

On 29 October, AskNBN - ATOM Assistant Development brought the team together with Guy Liyanage. The reasoning became much clearer: ASKnbn already provided models, framework, support and community, so the team did not need to reinvent the underlying foundation just to begin experimenting. [AskNBN - A...evelopment | Meeting], [AskNBN - A...Recording | Video]

#### Behind the milestone

##### Challenge

Do we build our own AI stack? Use open source? GitHub Copilot? ASKnbn?

##### Learn

Our differentiating value wasn't going to come from recreating an AI platform.

##### Pivot

Use ASKnbn as an accelerator and focus our effort on our use cases, knowledge and engineering problems.

##### Unlock

The team could move from conceptual debate into building.

---

## Chapter 4 | 5 Nov 2025

### "Team, our first Assistant is here."

This deserves to be one of the emotional high points of the retrospective.

On 5 November, Raghavendra Siddalingegowda wrote in AI agent practice:

> "Team, our first Assistant is here."

It was basic. It knew only a couple of documents, used gpt-5-global and had very limited RAG. The very next thought was already: let's give it richer knowledge. [AI agent practice | Teams]

#### Behind the milestone

##### Challenge

The first Assistant only knew a handful of documents.

##### Learn

A powerful model isn't sufficient. The quality of the knowledge surrounding the model matters.

##### Pivot

Start building richer RAG rather than focusing only on the model.

##### Unlock

The Assistant could start learning the actual BOB EVO world.

#### Reflection line

> "The first version knew almost nothing. But it worked. And suddenly the possibilities became real."

---

## Chapter 5 | Nov-Dec 2025

### We started teaching AI our world

This is where the story gets substantially richer.

On 13 November, the team was discussing workflow-specific knowledge pulling together:

Confluence + BOB EVO DB + API information + code context

to explain how a workflow actually worked. [AI agent practice | Teams]

Then the idea expanded into specialised capabilities:

- KT Assistant
- Doc Assistant
- API helper
- Testing Agent
- onboarding capability
- database lookup
- Jira and Confluence connections. [AI agent practice | Teams], [Set AI Mil...Recording | Video]

By 28 November, the KT Assistant was reading the team's actual BOB EVO transcripts from DocuHub. There were 35 documents in that knowledge source at the time. [AI assista...Recording | Video]

#### Behind the milestone

##### Challenge

Our knowledge wasn't in one place. It lived in code, Confluence, databases, meetings and people's heads.

##### Learn

AI became much more useful when it understood the team's history and system context.

##### Pivot

Feed transcripts and engineering artefacts into structured knowledge sources.

##### Unlock

AI could begin helping with onboarding, KT, design understanding and documentation.

#### Reflection line

> "We stopped teaching AI generic things and started teaching it our team's history."

---

## Chapter 6 | Nov 2025-Jan 2026

### One assistant becomes a team of specialised agents

By 18 November, the team was already discussing agents for testing, documentation, bug fixing and design. Critically, the discussion also introduced a Super Agent orchestration model. [AI agent practice | Teams]

Rather than attempting everything simultaneously, the team agreed to prove specialised agents first and consider orchestration as the longer-term scalable approach. [AI agent practice | Teams]

By December, the explicit January showcase target had become:

Testing Agent + KT Assistant + ATOM Doc Assistant. [AI agent practice | Teams]

#### Behind the milestone

##### Challenge

One generic assistant couldn't reliably be brilliant at every job.

##### Learn

Specialists could do individual jobs better, but that introduced another problem: users shouldn't need to understand which agent does what.

##### Pivot

Build specialist agents behind a common orchestration concept.

##### Unlock

Specialists → orchestration → Super Agent

---

## Chapter 7 | Jan-Feb 2026

### The Super Agent gets an identity: ASHA

On 29 January, AI Agents - Next Steps & Internal Demo made an important architectural decision:

The user-facing entry point would be the Super Agent rather than individual assistants. [AI Agents...ernal Demo | Meeting]

The team worked on the system prompt that would allow the Super Agent to decide which specialist should handle a request. [AI Agents...ernal Demo | Meeting]

Then the ATOM Assistants - Pack records the emerging family:

- ATOM Doc Assistant
- ATOM KT Assistant
- ATOM Mock Config Assistant
- ATOM Super Hybrid Agent (ASHA)
- ATOM GitHub Genie. [ATOM Assis...nts - Pack | PowerPoint]

And there is a lovely human detail preserved later in the AI Agents practice weekly check in : Ajay Cherthedath Viswanathan said "Asha literally means hope", and credited Raghavendra Siddalingegowda with suggesting the name. [AI Agents...y check in | Meeting]

#### Behind the milestone

##### Challenge

We were creating useful specialists, but users shouldn't have to understand our architecture.

##### Learn

The intelligence needed to decide which agent to use should sit inside the capability.

##### Pivot

Put a Super Agent in front of the specialist agents.

##### Unlock

ASHA became the front door.

#### Reflection line

> "Somewhere along the way, our technology stopped being 'an AI experiment' and got a name."

---

## Chapter 8 | Feb-Mar 2026

### We let people challenge ASHA

By 18 February, the team explicitly stated that ASHA would be the interface going forward, including for the ADM transition. [AI Agents practise | Teams]

Then on 19 February, the team launched the Ask ASHA Hackathon.

People were invited to:

- experiment with prompts
- assess answer quality
- identify issues
- provide feedback
- help improve ASHA. [BOBEvo Des...Practices | Teams]

The feedback exposed real weaknesses, including NetAssist business knowledge, project setup guidance, ServiceNow knowledge and GitHub Genie limitations. [AI Agents practise | Teams]

#### Behind the milestone

##### Challenge

A good internal demo does not prove an AI capability is trustworthy.

##### Learn

Trust is created by humans challenging the AI, not merely admiring it.

##### Pivot

Turn colleagues into testers and critics through the hackathon.

##### Unlock

ASHA moved from something the AI squad used → something other people could test and improve.

---

## Chapter 9 | Feb-Mar 2026

### We discovered what "enterprise AI" really means

This is an important chapter because it demonstrates persistence.

Moving ASHA beyond a POC exposed harder problems:

- sandbox access
- AD groups
- service accounts
- PAT permissions
- GitHub and Confluence restrictions
- data classification
- security approval
- Responsible AI requirements
- production-readiness testing. [Vincent Pa...ar in chat | Teams], [AI Agents...check in | Teams]

When GitHub tooling wasn't available in Sandbox, the team didn't simply stop. It explored an interim approach that converted codebases into knowledge documentation so ASHA could still consume useful engineering context. [AI Agents...check in | Meeting]

When Confluence and GitHub were unavailable, the system prompt was deliberately changed so ASHA referenced available RAG rather than implying access it did not have. [AI Agents...y check in | Meeting]

#### Behind the milestone

##### Challenge

The technology was easier than the enterprise integration.

##### Learn

Enterprise AI is also identity + security + access + evidence + governance.

##### Pivot

Rather than bypass controls, create controlled interim approaches while pursuing the right integration.

##### Unlock

The team learned how to move from AI experiment toward enterprise capability.

#### Reflection line

> "We learned that building an agent was only half the problem. Making it secure, governed and usable by others was the other half."

---

## Chapter 10 | 2026

### AI begins doing engineering work, not just answering questions

This is where I would visually change the story from ASHA the assistant to AI-enabled engineering.

The team's experimentation broadened into AI-assisted testing using Playwright, including plans, execution, trace/video capture and eventually more systematic automated testing. The February weekly forum shows hands-on exploration of Playwright CLI/agent browser approaches when other tooling wasn't usable. [AI Agents...check in | Teams], [AI Agents...Recording | Video]

This direction was already visible in November, when Playwright-based testing agents were being explored despite Citrix/proxy/environment problems. [AI agent practice | Teams], [AI agent practice | Teams]

#### Behind the milestone

##### Challenge

An assistant retrieving knowledge saves time, but doesn't fundamentally change software delivery.

##### Learn

Much greater value appears when AI can use tools and perform engineering tasks.

##### Pivot

Move beyond Q&A into testing, browser interactions and engineering workflows.

##### Unlock

Assistant → Agent → Engineering Agent

---

## Chapter 11 | 2026

### From "this looks good" to "can we prove this is good?"

This is a critical maturity shift in the journey.

As the capability expanded, the team increasingly focused on accuracy, validation, confidence and reproducible testing rather than simply whether an answer sounded convincing.

That mindset is visible even in February's MVP preparation, where the team deliberately planned repeatable prompts and pre-run results because generative outputs could vary between executions. [AI Agents...Recording | Video]

It later evolved into formal evaluation approaches and measurable AI quality.

#### Behind the milestone

##### Challenge

Generative AI can produce extremely convincing answers that are still incorrect.

##### Learn

AI quality cannot be based on someone's impression of a demo.

##### Pivot

Introduce validation, reference answers, controlled temperature, confidence and repeatable evaluation.

##### Unlock

AI quality becomes something we engineer, not something we hope for.

## Chapter 12 | Aug-Sep 2026

### AI starts entering the delivery lifecycle

The next shift was from individual AI capabilities into the actual engineering lifecycle.

The team explored AI turning meeting outcomes and requirements into structured Jira work, including requirements, acceptance criteria and code-aware reasoning.

And then came a very tangible milestone:

22 September: the first Jira ticket was created through the AI-agent workflow

The flow was:

```text
Meeting transcript
    ↓
AI interpretation
    ↓
Jira structure / CSV
    ↓
Jira ticket
```

The resulting ticket was NRA-8975, "Integrate CALL-E with BOBEvo."

That's exactly the sort of moment I would celebrate with the team because it's concrete:

> "For the first time, something we said in a meeting travelled through AI and became engineering work."

---

## Chapter 13 | Sep-Oct 2026

### Agents start becoming an ecosystem

The architecture then progressed beyond individual agents again.

The team developed the AIOS service module and relay service/API, creating an orchestration layer capable of sitting between ASK NBNCo and multiple AI agents.

That is philosophically connected to what the team had first imagined nearly a year earlier:

specialist agents → orchestration → common interface → agents working through shared services

Meanwhile agentic testing had become measurable rather than experimental, including reported coverage metrics and growing test suites.

#### Behind the milestone

##### Challenge

Lots of useful agents can themselves become another fragmented tool landscape.

##### Learn

The long-term capability isn't one perfect AI agent. It is an ecosystem of specialised capabilities that can work together.

##### Pivot

Invest in relay/orchestration patterns and reusable AI services.

##### Unlock

An agentic engineering platform rather than isolated AI experiments.

---

## Chapter 14 | Nov 2026

### From experiment to an AI-enabled way of working

Today's direction brings many earlier ideas together.

The meeting-to-Jira capability can now take a transcript, understand the required work, propose ticket fields, allow human review, produce the structured input and use Playwright to complete the Jira interaction where direct write access remains unavailable.

That last point matters.

The team is still working around real enterprise constraints rather than pretending they don't exist.

And that is perhaps the best description of the entire year's journey.
