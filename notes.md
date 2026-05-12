# Delivery Manager Prompts for IT Services Companies
## With Instructions, Do's & Don'ts

---

# 1. Incident RCA for Client

```text
You are a senior delivery manager preparing a client-facing RCA document for a production incident.

Your objective:
- Explain the incident clearly
- Maintain client confidence
- Demonstrate accountability
- Show preventive action planning

Include:
1. Executive summary
2. Incident description
3. Business impact
4. Timeline of events
5. Root cause analysis
6. Immediate mitigation steps
7. Permanent corrective actions
8. Preventive measures
9. Current status
10. Next steps

 Do's:
- Be transparent and factual
- Use professional enterprise language
- Focus on solutions and accountability
- Explain technical issues in simple business terms
- Keep the structure clean and executive-friendly
- Use concise paragraphs and bullet points
- Highlight preventive actions clearly

 Don'ts:
- Do not blame individuals or teams
- Do not use emotional or defensive wording
- Do not speculate without evidence
- Avoid excessive technical jargon
- Avoid vague explanations
- Do not overpromise future prevention guarantees

Incident details:
{incident_details}
```

---

# 2. Incident Status Update Email

```text
Draft a professional client-facing incident update email.

Include:
- Incident summary
- Current impact
- Actions completed
- Actions in progress
- Teams involved
- ETA if available
- Next update schedule

 Do's:
- Keep communication calm and reassuring
- Use concise and structured formatting
- Clearly distinguish completed vs ongoing work
- Mention ETA only if reasonably confident
- Maintain executive-friendly tone

 Don'ts:
- Do not create panic
- Do not provide uncertain timelines as commitments
- Avoid long technical explanations
- Avoid contradictory status statements
- Do not use casual language

Incident:
{incident}
```

---

# 3. Executive Escalation Response

```text
Act as a delivery head responding to a critical client escalation.

Generate:
1. Acknowledgement of concerns
2. Business impact summary
3. Leadership ownership statement
4. Immediate action plan
5. Recovery plan
6. Governance improvements
7. Long-term prevention measures
8. Reassuring closing statement

 Do's:
- Sound accountable and composed
- Show leadership involvement
- Focus on recovery and partnership
- Use executive-level communication style
- Keep messaging concise and action-oriented

 Don'ts:
- Do not become defensive
- Do not argue with the client
- Do not shift blame
- Avoid emotional responses
- Avoid excessive technical detail

Escalation details:
{escalation_details}
```

---

# 4. Weekly Delivery Status Report

```text
Generate a concise weekly delivery status report.

Include:
- Overall project health
- Completed milestones
- Upcoming milestones
- Risks and mitigations
- Dependencies
- Budget status
- Resource status
- Escalations
- Decisions required

 Do's:
- Use concise executive reporting style
- Highlight risks early and clearly
- Use measurable progress indicators
- Keep reporting balanced and factual
- Structure information for easy scanning

 Don'ts:
- Do not hide delivery concerns
- Avoid vague status updates
- Avoid overly optimistic language
- Do not overload with unnecessary detail
- Avoid inconsistent status reporting

Project details:
{project_data}
```

---

# 5. Project Risk Analysis

```text
Analyze the following project risks and generate a mitigation plan.

For each risk provide:
- Risk description
- Severity
- Probability
- Business impact
- Mitigation steps
- Contingency plan
- Suggested owner

 Do's:
- Prioritize risks logically
- Quantify impact where possible
- Recommend realistic mitigation plans
- Highlight operational and business impact
- Focus on preventive thinking

 Don'ts:
- Avoid generic mitigations
- Do not ignore low-frequency high-impact risks
- Avoid unrealistic contingency plans
- Do not leave ownership unclear

Project context:
{project_context}
```

---

# 6. Delivery Recovery Plan

```text
Create a recovery plan for a delayed software project.

Include:
- Current project health
- Root causes
- Critical blockers
- Scope prioritization
- Resource optimization
- Revised timelines
- Governance model
- Recovery milestones
- Stakeholder communication strategy

 Do's:
- Be realistic with timelines
- Focus on actionable recovery steps
- Prioritize business-critical deliverables
- Recommend governance improvements
- Highlight dependencies and blockers clearly

 Don'ts:
- Do not create unrealistic recovery schedules
- Avoid overcommitting resources
- Do not ignore technical debt
- Avoid superficial root cause analysis

Project details:
{details}
```

---

# 7. Difficult Client Response

```text
Draft a professional response to a frustrated client.

Goals:
- Acknowledge concerns
- Maintain professionalism
- Rebuild confidence
- Present corrective actions
- Reinforce partnership

 Do's:
- Show empathy professionally
- Use calm and respectful tone
- Focus on solutions
- Demonstrate accountability
- Reinforce collaboration mindset

 Don'ts:
- Do not sound defensive
- Do not dismiss concerns
- Avoid emotional or reactive wording
- Do not blame internal teams or client teams
- Avoid robotic language

Client message:
{client_message}
```

---

# 8. Steering Committee Summary

```text
Prepare a steering committee summary.

Include:
- Delivery status
- Financial health
- Risks and mitigations
- Strategic concerns
- Major achievements
- Leadership decisions needed
- Executive recommendations

 Do's:
- Focus on executive-level insights
- Highlight strategic impact
- Use concise reporting style
- Prioritize decision-oriented communication
- Keep language business-focused

 Don'ts:
- Avoid operational detail overload
- Avoid deep technical explanations
- Do not include unnecessary metrics
- Avoid cluttered reporting

Project/program details:
{details}
```

---

# 9. Scope Change Communication

```text
Create a professional client communication for a scope change request.

Include:
- Scope change summary
- Timeline impact
- Cost implications
- Resource implications
- Risk considerations
- Recommended options
- Suggested prioritization

 Do's:
- Clearly explain trade-offs
- Quantify impacts where possible
- Maintain collaborative tone
- Document assumptions clearly
- Recommend practical alternatives

 Don'ts:
- Do not approve scope informally
- Avoid vague effort estimates
- Do not ignore downstream impacts
- Avoid confrontational language

Requested scope:
{scope_request}
```

---

# 10. Resource Utilization Analysis

```text
Analyze the following resource allocation data.

Provide:
- Utilization summary
- Overloaded resources
- Underutilized resources
- Skill gaps
- Delivery risks
- Hiring recommendations
- Optimization opportunities

 Do's:
- Balance utilization with sustainability
- Highlight burnout risks
- Recommend cross-skilling opportunities
- Focus on delivery continuity
- Provide actionable optimization ideas

 Don'ts:
- Do not optimize only for utilization percentage
- Avoid unrealistic staffing assumptions
- Do not ignore skill mismatches
- Avoid recommending excessive overtime

Data:
{resource_data}
```

---

# 11. Sprint Delivery Health Analysis

```text
Analyze sprint delivery performance.

Provide:
- Velocity trends
- Sprint predictability
- Quality indicators
- Defect trends
- Bottlenecks
- Dependency risks
- Improvement recommendations

 Do's:
- Focus on continuous improvement
- Analyze quality alongside velocity
- Highlight recurring bottlenecks
- Keep analysis data-driven
- Recommend practical improvements

 Don'ts:
- Do not blame teams
- Avoid focusing only on velocity
- Do not ignore quality degradation
- Avoid generic Agile advice

Sprint data:
{sprint_data}
```

---

# 12. Team Performance Review Summary

```text
Generate a professional team performance review summary.

Include:
- Delivery achievements
- Collaboration quality
- Technical excellence
- Ownership assessment
- Leadership contribution
- Improvement areas
- Growth recommendations

 Do's:
- Keep feedback balanced
- Use evidence-oriented language
- Highlight strengths and growth areas
- Maintain professional HR-friendly tone
- Encourage development mindset

 Don'ts:
- Avoid personal criticism
- Avoid emotional language
- Do not exaggerate performance concerns
- Avoid vague feedback statements

Team details:
{team_details}
```

---

# 13. Vendor Evaluation

```text
Evaluate the following vendor/service partner.

Analyze:
- Delivery capability
- Technical expertise
- SLA adherence
- Communication quality
- Cost efficiency
- Governance maturity
- Operational risks
- Long-term suitability

 Do's:
- Use objective evaluation criteria
- Focus on measurable performance
- Compare against SLAs and commitments
- Highlight strategic risks
- Provide balanced assessment

 Don'ts:
- Avoid subjective bias
- Do not ignore governance concerns
- Avoid incomplete evaluation dimensions
- Do not make unsupported claims

Vendor details:
{vendor_info}
```

---

# 14. SLA Breach Analysis

```text
Analyze the following SLA breaches and generate a governance report.

Include:
- Breach summary
- Root causes
- Recurrence patterns
- Business impact
- Corrective actions
- Preventive controls
- Governance recommendations

 Do's:
- Focus on operational improvement
- Highlight recurring patterns
- Quantify business impact where possible
- Recommend preventive controls
- Maintain governance-focused tone

 Don'ts:
- Do not normalize SLA failures
- Avoid superficial root cause analysis
- Do not ignore process gaps
- Avoid vague corrective actions

Data:
{sla_data}
```

---

# 15. Leadership Briefing Note

```text
Prepare a concise leadership briefing note.

Audience:
CXO leadership

Include:
- Delivery status
- Strategic risks
- Financial impact
- Business concerns
- Immediate actions
- Leadership decisions required

 Do's:
- Keep communication concise
- Focus on strategic business impact
- Highlight decision points clearly
- Use executive communication style
- Prioritize clarity and brevity

 Don'ts:
- Avoid operational overload
- Avoid deep technical details
- Do not include unnecessary background
- Avoid ambiguous recommendations

Context:
{details}
```

---

# 16. Meeting Notes to Action Items

```text
Convert the following meeting notes into structured action items.

For each action include:
- Task
- Owner
- Priority
- Due date
- Dependencies
- Risks

 Do's:
- Assign clear ownership
- Keep actions specific and measurable
- Prioritize effectively
- Identify dependencies clearly
- Ensure follow-up readiness

 Don'ts:
- Avoid ambiguous action items
- Do not leave tasks ownerless
- Avoid missing critical follow-ups
- Do not create duplicate tasks

Meeting notes:
{notes}
```

---

# 17. Contract / SOW Obligation Analysis

```text
Analyze the following contract/SOW and identify:

- Delivery obligations
- SLA commitments
- Commercial risks
- Penalty clauses
- Compliance requirements
- Governance expectations
- Hidden assumptions
- Client expectations

 Do's:
- Focus on risk identification
- Highlight hidden obligations
- Analyze operational impact
- Identify legal and governance concerns
- Use structured corporate language

 Don'ts:
- Do not ignore assumptions or exclusions
- Avoid incomplete obligation analysis
- Do not miss renewal or termination clauses
- Avoid speculative legal interpretation

Contract:
{contract_text}
```

---

# 18. Client Sentiment Analysis

```text
Analyze the following client emails/messages.

Identify:
- Overall sentiment
- Trust level
- Escalation probability
- Hidden concerns
- Relationship health
- Recommended response strategy

 Do's:
- Detect subtle dissatisfaction indicators
- Analyze tone carefully
- Identify escalation warning signals
- Recommend relationship management actions
- Maintain balanced interpretation

 Don'ts:
- Do not assume positive sentiment blindly
- Avoid overreacting to isolated phrases
- Do not ignore recurring patterns
- Avoid emotional interpretation

Messages:
{messages}
```

---

# 19. AI PMO Assistant

```text
Act as an enterprise PMO assistant.

Based on the following project data:
- Identify risks
- Predict delays
- Highlight governance gaps
- Detect resource conflicts
- Recommend delivery improvements
- Suggest executive actions
- Identify budget concerns

 Do's:
- Correlate insights across projects
- Focus on governance maturity
- Highlight dependency risks
- Recommend realistic improvements
- Use portfolio-level thinking

 Don'ts:
- Avoid isolated project analysis only
- Do not ignore shared risks
- Avoid shallow recommendations
- Do not overestimate delivery confidence

Project data:
{project_data}
```

---

# 20. Multi-Project Portfolio Summary

```text
Generate an executive portfolio summary across multiple projects.

Include:
- Portfolio health
- RAG status
- Financial overview
- Shared risks
- Cross-project dependencies
- Resource conflicts
- Strategic concerns
- Recommended executive actions

 Do's:
- Focus on portfolio-level visibility
- Highlight strategic business impact
- Prioritize executive decision points
- Identify dependency chains clearly
- Maintain concise governance style

 Don'ts:
- Avoid excessive project-level detail
- Do not hide systemic risks
- Avoid inconsistent reporting formats
- Do not overload leadership with raw data

Portfolio data:
{portfolio_data}
```
