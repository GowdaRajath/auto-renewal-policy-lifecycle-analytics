# Auto-Renewal Complaint Analysis Dimensions

## Purpose

This document defines the analytical dimensions used to evaluate auto-renewal and lifecycle-related complaints in a consistent, auditable way.

These dimensions are designed to distinguish between:
- Customer awareness and expectation gaps
- Communication timing and channel issues
- Process/system behaviours
- Agent intervention opportunities
- Preventable vs non-preventable outcomes

---

## Core Dimensions

### 1. Lifecycle Stage (from Policy Lifecycle Model)

Each complaint is mapped to a lifecycle stage:

- Pre-Renewal Period
- Renewal Point
- Cooling-Off Period
- Post-Renewal Period

This anchors analysis to timing risk and decision windows.

---

### 2. Complaint Reason (Primary)

Defines the primary driver of the complaint.

Examples:
- Amount taken without approval (perceived)
- Not aware of an active policy
- Documents not received (email/post)
- Duplicate policy
- Cancellation and refund dissatisfaction
- Agent escalation without clear necessity

---

### 3. Customer Awareness Level

Assesses whether the customer understood the renewal process and payment timing.

Values:
- Aware (understood renewal and payment timing)
- Partially aware (knew renewal existed but misunderstood timing/implications)
- Not aware (did not know renewal/payment would occur)

---

### 4. Communication Evidence

Captures whether communications were issued and via what channel.

Recommended fields:
- Renewal communication sent: Yes/No
- Channel: Email / Post / Mixed
- Customer reports receipt: Yes/No/Unknown
- Customer reports understanding: Yes/No/Unknown

This helps differentiate “sent” vs “received” vs “understood”.

---

### 5. Financial Surprise Indicator

Flags whether the complaint was triggered by unexpected payment.

Values:
- Yes (customer expresses surprise at payment)
- No
- Unknown

This dimension is particularly relevant at the Renewal Point and Cooling-Off Period stages.

---

### 6. Resolution Pathway

Captures what happened after contact.

Examples:
- Clarification provided and accepted
- Cancellation within cooling-off completed
- Refund requested / disputed
- Complaint escalated to formal handling
- Policy retained after discussion

---

### 7. Agent Intervention Opportunity

Assesses whether earlier or clearer intervention could reasonably have prevented escalation.

Values:
- High (clear opportunity for prevention)
- Medium
- Low
- Not applicable / Unknown

Examples of high opportunity:
- Customer requested escalation but clarification could resolve
- Lack of ownership or unclear explanation
- No proactive options offered

---

### 8. Preventability (Analyst Assessment)

Determines whether the complaint was reasonably preventable through changes in:
- Communication timing/clarity
- Channel strategy
- Agent guidance/behaviour
- Process prompts/checkpoints

Values:
- Preventable
- Partially preventable
- Not preventable

---

## Classification Principles

- Classify based on evidence and documented signals, not customer sentiment alone
- Anchor every case to a lifecycle stage for comparability
- Where multiple issues exist, identify one primary complaint reason
- Document assumptions (Unknown) rather than forcing a category

---

## Output of Dimensions

These dimensions enable:
- Stage-based complaint clustering (timing risk)
- Awareness vs compliance distinction (perception vs process)
- Identification of preventable drivers and intervention points
- Decision-ready insights for operational and policy teams
