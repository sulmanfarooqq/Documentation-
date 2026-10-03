# Flow Vello — Three-Person Operating Workflows

## 1. Company Revenue + Delivery
```mermaid
flowchart TD
 A[Revenue Lead A] --> P[Qualified Prospect]
 P --> D[Discovery]
 D --> Q{Qualified?}
 Q -->|No| N[Nurture / Close]
 Q -->|Yes| S[Scope + Proposal]
 S --> DP[Deposit / Agreement]
 DP --> B[Delivery Lead B]
 B --> C[Product + QA Lead C]
 C --> T[QA / Acceptance]
 T -->|Fail| B
 T -->|Pass| DEMO[Client Demo]
 DEMO --> H[Handoff]
 H --> PR[Proof / Referral / Repeat]
 PR --> A
```

## 2. Daily Ownership
```mermaid
flowchart LR
 A[Revenue A] -->|Pipeline / Calls / Proposals| REV[Revenue]
 B[Delivery B] -->|Build / Integrate / Deploy| DEL[Delivery]
 C[Product + QA C] -->|Test / Review / Proof| QA[Quality]
 REV --> SYNC[Daily Company Sync]
 DEL --> SYNC
 QA --> SYNC
```

## 3. Client Project Gate
```mermaid
flowchart TD
 SCOPE[Approved Scope] --> DEP[Deposit]
 DEP --> PLAN[B Technical Plan]
 PLAN --> BUILD[Implementation]
 BUILD --> QA[C QA]
 QA -->|Fail| FIX[B Fix]
 FIX --> QA
 QA -->|Pass| ACC[Acceptance]
 ACC -->|Change Request| A[A Scope Decision]
 A --> CHANGE[Re-scope / Re-price]
 ACC -->|Accepted| HAND[Handoff]
```

## 4. Hiring Gate
```mermaid
flowchart TD
 SOLD[Work Sold] --> CAP[Capacity Pressure]
 CAP --> REP{Repeatable Task?}
 REP -->|No| SCOPE[Fix Scope / Process]
 REP -->|Yes| DOD{Definition of Done?}
 DOD -->|No| DOC[Document SOP + QA]
 DOD -->|Yes| ECON{Economics Support Hire?}
 ECON -->|No| PRIOR[Prioritize / Reprice]
 ECON -->|Yes| HIRE[Contractor / Specialist]
 HIRE --> QA[Team QA]
 QA --> DOC2[Update SOP]
```

## 5. Critical Ownership Rule
- Revenue: A
- Delivery: B
- Quality/Systems: C
- Company-wide priorities: one named DRI per decision

Never use "everyone owns it" for an outcome.