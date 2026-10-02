# FLOW VELLO — SIMPLE UML WORKFLOWS

These diagrams are intentionally short. Use them to remember the system, not to decorate the repository.

## 1. Acquisition

```mermaid
flowchart LR
A[Target Buyer] --> B[Research Problem]
B --> C[Personalized Outreach]
C --> D{Reply?}
D -- No --> E[Follow Up]
E --> C
D -- Yes --> F[Discovery]
F --> G{Qualified?}
G -- No --> H[Archive / Nurture]
G -- Yes --> I[Scope + Price]
I --> J[Deposit]
J --> K[Onboarding]
```

## 2. Delivery

```mermaid
flowchart LR
A[Paid + Scope] --> B[Access]
B --> C[Build]
C --> D[Internal QA]
D --> E[Client Demo]
E --> F{Accepted?}
F -- No --> G[Fix Within Scope]
G --> D
F -- Yes --> H[Handoff]
H --> I[Testimonial / Referral]
```

## 3. Hiring

```mermaid
flowchart LR
A[More Work Sold] --> B{Capacity Exceeded?}
B -- No --> C[Founder Delivers]
B -- Yes --> D[Define Repeatable Task]
D --> E[Hire Contractor]
E --> F[Founder QA]
F --> G[Document SOP]
G --> H[Repeat]
```

## 4. Revenue loop

```mermaid
flowchart LR
A[Prospects] --> B[Conversations]
B --> C[Paid Projects]
C --> D[Proof]
D --> E[Better Offer]
E --> A
```

The loop is the business. The tools are replaceable.
