# Rohit Chaturvedi: knowledge base

Source material for the portfolio voice agent. Every number here is one Rohit
has stated and can defend. Nothing in this file is estimated or inferred.

If a visitor asks something this document does not answer, the agent says so.
It never fills the gap with a plausible guess.

---

## Who he is

Rohit Chaturvedi. AGM Product Manager at Matrimony.com, which runs the Bharat
Matrimony platform. Based in Gurgaon. He builds AI products and writes build
logs for the decisions that mattered.

He leads and mentors four Product Managers and Analysts, and runs a monthly AI
quality review with the CPO and CEO.

Portfolio: https://chaturvedirohit.github.io/portfolio/
GitHub: https://github.com/chaturvedirohit
LinkedIn: https://www.linkedin.com/in/rohit-chaturvedi-340836168/

---

## Current role: Matrimony.com, March 2022 to present

Progressed PM to Senior PM to AGM, Product.

### Conversational search
Rebuilt a structured search of 40+ fields into agentic retrieval.
- 87.2% accuracy
- Cost per query down from $6.50 to $0.78 per 1,000
- Profile discovery up 20%
- Interests Sent up 12%

### Profile trust and validation
- 25,000+ profiles screened daily on a base of 5M+ active users
- Top-of-funnel completion held at 74 to 76%
- 500+ bad profiles caught per day
- Day-0 photo availability went from 31% to 49%
- End-to-end latency went from 1.72s to 1.20s
- Identity verification accuracy went from 40% to 70%

### AI customer experience
Built in-house after evaluating five enterprise AI vendors.
- Average handling time 6 minutes to 4.5 minutes
- CSAT 82% to 84%

### Growth
- Onboarding consolidated across six teams, $3M incremental annual revenue
- Install-to-registration 28% to 37% through continuous A/B testing
- Checkout drop-offs cut 23%

### Zero to one
- Built Elite Matrimony from scratch to an $8M+ annual business
- Leading a 0-to-1 Super App initiative benchmarked against six super-apps

### Voice AI platform
End-to-end ownership of an early-stage voice platform: speech-to-text,
text-to-speech and real-time orchestration. Currently in Beta. No published
numbers yet. If asked for results, say it is in Beta and numbers are not out.

---

## Previous roles

### ICICI Lombard, August 2020 to March 2022
Product Manager, IL TakeCare.
- Owned the app roadmap from inception to 1M+ downloads, joining insurance,
  healthcare access and wellness in one journey
- Led the Virtual Doctor telehealth feature for B2B and B2B2C clients,
  generating Rs 2.5 crore of new revenue in year one
- Shipped Know Your Health, an AI face-scan for health vitals, first in its
  segment. DAU up 15%
- Turned Play Store sentiment analysis into a prioritisation framework. App
  rating went 3.3 to 4.0 in four months

### Wipro, August 2015 to July 2018
Project Manager, Product and Accessibility Engineering.
- Started and led accessibility compliance across four Microsoft applications
  (Word, Excel, Skype, PowerPoint) against WCAG 2.1 and Section 508
- Defined test automation rules with engineering, improving accessibility issue
  detection by 15%

---

## How he works

Four principles, each from a real launch.

**Evaluate before you ship.** A 2,000-case golden dataset, a four-stage failure
taxonomy and a precision and recall gate come before any model goes live.

**Choose models on failure modes.** He picked a slower, more accurate model for
content safety because of how the faster one failed, not because of a published
latency number.

**Trace the error to its root.** Most failures are a few causes. One
entity-association rule explained 59% of precision errors, and fixing it moved
value precision from 95.1% to 98.0%. One Indic transliteration gap explained 71%
of recall misses, and aliasing took recall to 97.6%.

**Build or buy with a framework.** Five enterprise AI vendors compared before a
line was written, with the decision documented so it can be revisited.

His process: frame the problem, prototype the smallest version real data can
break, measure with evals and cost before and after launch, then write it down.

---

## Case studies he can discuss

**Choosing the slower model for content safety.** Two candidate models for
content-safety classification. The faster one looked better on paper. He
compared both on real failure modes from his own data and shipped the slower,
more accurate one. Published latency is not the same as how a model fails on
your data.

**One rule behind 59% of precision errors.** Precision errors and recall misses
measured against a 2,000-case golden dataset. A four-stage failure taxonomy
traced each failure to a root cause. One entity-association rule caused 59% of
precision errors: value precision went 95.1% to 98.0%. Indic transliteration
variants caused 71% of recall misses: recall reached 97.6% once aliased.

**A hallucinated field that survived across turns.** Ten manually confirmed
cases where a fabricated field persisted across conversation turns. He
redesigned the context architecture to re-validate every field against history
before persisting it. The post-fix result is not published yet.

---

## Toolkit

**AI evaluation:** golden datasets, failure taxonomies, LLM-as-judge, human
labeling, turn and trajectory scoring, regression suites, precision and recall
gates, shadow deployment.

**Agent systems:** multi-agent orchestration, tool calling, RAG, context
management, escalation policy, human-in-the-loop, multilingual voice agents.

**Observability and tools:** tracing, drift detection, benchmarking, cost
tracking, SQL, APIs, Tableau, Claude Code, Cursor, n8n, Jira, Confluence.

**Product:** roadmapping, prioritisation trade-offs, build versus buy,
executive communication, cross-functional leadership, go-to-market.

**Side project:** AgentProof, an open-source agent evaluation and observability
tool built solo with Claude Code: trace capture, trajectory scoring and
regression tracking.

---

## Credentials and recognition

MBA, Finance and Marketing, IIM Amritsar. B.Tech, Information Technology,
Dr. A.P.J. Abdul Kalam Technical University. Python and Power BI certified.

Maestro Award (Best Performer PM, FY25), Product Champion Award (FY25) and
Breakthrough Innovator Award (FY24) at Matrimony.com. Spotlight Performer
(FY22) at ICICI Lombard.

---

## What he is looking for

Problems: agentic systems, conversational AI and the reliability of ML in
production, where evaluation is part of the product.

He has not published his target team size, stage or scope. If asked, say he has
not specified and point the visitor at LinkedIn or email.

---

## Things this document does not cover

Do not answer these. Say you do not have that and offer email instead.

- Current or expected compensation
- Notice period or availability dates
- Anything about his personal life, family or location beyond "Gurgaon"
- Internal Matrimony.com information beyond the published numbers above
- Opinions about named competitors, colleagues or employers
- Voice AI platform results, which are not published yet
- Post-fix results for the hallucinated-field case study
