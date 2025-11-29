<!-- File: paper7-regulation-and-competitive-windows-for-ai-fast-followers.md -->

# Paper 7 – Regulation, Data and Competitive Windows for AI Fast Followers

## Abstract

Regulation and data governance shape whether AI pioneers can entrench themselves or whether fast followers retain the ability to challenge incumbents. This paper analyses how health and AI regulation, data-access rules and public procurement influence the timing and viability of fast-follower strategies in digital health and productivity tools. We show that in highly regulated sectors such as healthcare, pioneers often bear the bulk of regulatory and clinical-validation costs, but do not automatically lock in advantage: interoperable standards, payor neutrality and open procurement can sustain competitive windows for later entrants. In AI productivity, where regulation is more permissive, platform control (by cloud providers, foundation-model labs and incumbents integrating AI into suites such as Office or Google Workspace) matters more than formal law. We build a simple three-player game (regulator, pioneer, follower) and show that policy choices on interoperability, model-usage transparency and data portability can shift expected payoffs from “winner-takes-most pioneer dominance” towards “contestable leadership” where disciplined fast followers have a realistic path to scale.

## 1. Introduction

Fast-follower strategies do not operate in a vacuum: they interact with law, regulation and public procurement. In AI health, pioneers must obtain regulatory approvals, demonstrate safety and efficacy, navigate reimbursement and negotiate hospital procurement. In AI productivity tools, pioneers must comply with emerging AI-safety norms, data-protection rules and enterprise IT standards, but regulation is lighter and competition is shaped more by platform economics and standards set by hyperscalers.

This paper concentrates on two sectors:

- **AI health**: symptom checkers, triage platforms, AI-supported imaging, clinical documentation tools and “AI doctor” services (e.g. Babylon, Ada Health, K Health, Doctrin, Qure.ai, Doctronic);[13][15]
- **AI productivity**: horizontal tools (Notion AI, GitHub Copilot, office-suite copilots) and vertical workflow assistants.

We ask:

1. How does regulation affect the cost and timing of entry for pioneers versus fast followers?
2. Under what conditions do legal and regulatory choices entrench first movers versus keep the market contestable?
3. What rules and procurement practices are most conducive to productive fast-following in AI health and productivity?

## 2. Data and stylised facts

### 2.1 Funding, concentration and AI in digital health

Recent market data provide context:

- Global digital health funding in 2024 rebounded to about USD 25.1 billion, with AI and “TechBio” ventures leading the resurgence.[13][15]
- AI-enabled digital health startups accounted for roughly 37% of total funding in 2024, across nearly 200 deals.[18]
- In the US, digital health funding in 2025 reached around USD 9.9 billion by Q3, already above the previous year’s total for the same period, with a high share directed to AI-powered diagnostics, clinical documentation and infrastructure.[6]
- In Q1 2025, AI startups attracted approximately 3.2 billion USD, or 60% of all digital-health funding, up from 41% the year before.[10]

These numbers indicate both strong investor interest and increasing concentration of capital in AI-intensive segments.

### 2.2 Regulatory burden and pioneers in AI health

Pioneers in AI health have faced substantial regulatory and business-model risk:

- Babylon Health, one of the earliest large-scale AI triage and telehealth providers (founded 2013), reached revenues of around 1.1 billion USD in 2022 but generated operating losses close to 370 million USD that year, with negative equity and heavy contractual obligations.[13]
- Babylon’s subsequent restructuring and collapse illustrate how regulatory approvals, complex payer contracts and value-based-care arrangements can magnify both upside and downside risk.
- Ada Health, K Health, Doctrin and Qure.ai have pursued more focused models—symptom checking, insurance-integrated triage, national triage platforms, imaging AI—and raised significant but more contained sums (hundreds of millions of USD rather than multi-billion valuations via SPAC).[13][15]

In each case, pioneers invested heavily in:

- regulatory and clinical validation;
- integration with national health systems and insurers;
- trust-building and clinician adoption.

These investments generate externalities that fast followers can exploit by copying workflows, UI patterns and clinical evidence structures, but pioneers may also lock in exclusive contracts or proprietary datasets.

### 2.3 AI adoption, regulation and productivity tools

For AI productivity:

- Global AI spending is projected to rise from around 244 billion USD in 2025 to roughly 827 billion USD in 2030.[16]
- Generative AI revenues are projected to rise from about 16–17 billion USD in 2024 to more than 100 billion USD by 2030.[16]
- McKinsey surveys suggest that by 2025, roughly 78–88% of organisations use AI in at least one business function, and around 60% of AI adopters use generative AI tools.[16][17]
- Micro-based evidence (e.g. customer-support agents) shows productivity gains of around 15% from generative AI assistants.[18]
- Survey evidence suggests that 1–7% of work hours are already assisted by generative AI, corresponding to 1–5% time savings overall.[19]

Regulation is lighter in productivity, focusing mostly on:

- data protection (GDPR-type rules);
- intellectual property and copyright;
- emerging AI-safety and transparency guidelines.

However, platform control is significant:

- Large cloud and productivity-suite providers bundle AI assistants (e.g. Office copilot, Google Workspace AI) into existing products, leveraging distribution and data.
- Developers of stand-alone productivity tools (e.g. Notion AI, vertical agents) rely on APIs from a small number of foundation-model providers and must comply with their terms.

### 2.4 Data ownership, interoperability and lock-in

Data governance shapes competitive dynamics:

- In health, data are fragmented across hospitals, insurers and national systems; access is controlled via privacy laws and sector-specific regulation. AI vendors often rely on de-identified datasets and hospital partnerships.
- In productivity, data are concentrated in cloud suites (email, documents, chat) and stored on hyperscaler infrastructure. This gives incumbents strong information advantages.

Interoperability and data-portability rules can mitigate these advantages:

- Open standards for electronic health records (EHRs) and interoperability mandates can allow multiple AI vendors to integrate with the same systems.
- Data portability and exportability obligations for SaaS and productivity suites can allow users to move content and context between tools, enabling AI fast followers to compete on UX and verticalisation.

## 3. Framework

### 3.1 A simple three-player game

We model interaction between:

- a **regulator** choosing a policy environment $R$ (e.g. high or low interoperability, strict or light AI safety rules);
- a **pioneer** choosing investment level and business model $(I_P, B_P)$ under $R$;
- a **fast follower** choosing whether and when to enter $(I_F, t_F)$, given $R$ and the pioneer’s observable behaviour.

Let:

- $V_P(R)$ = pioneer’s expected value;
- $V_F(R)$ = follower’s expected value;
- $W(R)$ = social welfare (patient outcomes, productivity gains, minus costs).

We focus on how $R$ shifts the relative payoffs $V_P(R)$ and $V_F(R)$.

### 3.2 Regulatory levers

We classify regulatory design into five dimensions:

1. **Interoperability and open standards**:
   - degree to which EHRs, APIs and workflow systems must expose standardised interfaces;
   - extent of data portability for productivity tools.

2. **Model and data transparency**:
   - requirements to document training data, performance metrics, biases and limitations;
   - obligations for auditability.

3. **Procurement and reimbursement rules**:
   - whether public payors and health systems must run open tenders or can sign long-term exclusive deals;
   - whether reimbursement is technology-neutral (paying for “triage outcome” regardless of vendor).

4. **Liability and AI safety**:
   - allocation of liability between vendors, clinicians, hospitals and end users;
   - pre- and post-market surveillance requirements.

5. **Competition policy and platform conduct**:
   - restrictions on bundling and self-preferencing by large suites;
   - remedies (e.g. mandated API access, data-sharing obligations) for gatekeepers.

Each dimension shifts cost and risk for pioneers and followers.

### 3.3 Reduced-form payoff functions

For simplicity, define:

- $m_P(R)$, $m_F(R)$ = expected profit margins (as share of revenue) for pioneer and follower;
- $S_P(R)$, $S_F(R)$ = sustainable market shares (in a long-run equilibrium) for pioneer and follower.

Assume revenue scale $R_{\text{tot}}$ is the same under different policies (i.e. regulation affects distribution, not total demand, in first approximation). Then:

$$
V_P(R) \approx R_{\text{tot}} m_P(R) S_P(R) - I_P(R),
$$
$$
V_F(R) \approx R_{\text{tot}} m_F(R) S_F(R) - I_F(R).
$$

We can decompose effects of policy:

- Interoperability $R_{\text{int}}$:
  - reduces integration costs for both firms, but proportionally more for followers (who can reuse pioneer’s pathways);
  - limits $S_P(R)$ by facilitating multi-homing.

- Exclusive procurement $R_{\text{excl}}$:
  - increases $S_P(R)$ via long-term contracts;
  - reduces $S_F(R)$ and may effectively set it to zero in some segments.

- Strong data-portability $R_{\text{port}}$:
  - reduces switching costs for customers;
  - pushes both $S_P(R)$ and $S_F(R)$ toward more contestable levels; may reduce $m_P(R)$ due to competition.

- Heavy compliance burden $R_{\text{comp}}$:
  - raises $I_P(R)$ and $I_F(R)$;
  - if compliance requirements are non-linear (large fixed component), they may favour large incumbents and pioneers.

### 3.4 Contestable vs entrenched regimes

We define two polar regimes:

1. **Entrenching regime** $R^E$:
   - weak interoperability mandates;
   - permissive long-term exclusive contracting;
   - strong data silos and weak portability;
   - high fixed regulatory costs.

   Result: high $S_P(R^E)$, low $S_F(R^E)$, potentially high $m_P(R^E)$, low $V_F(R^E)$.

2. **Contestable regime** $R^C$:
   - strong interoperability and open standards;
   - open procurement with regular re-tendering;
   - robust data-portability and switching rights;
   - compliance scaled with risk and firm size.

   Result: moderate but sustainable $S_P(R^C)$, non-trivial $S_F(R^C)$, healthy but not monopolistic margins, $V_F(R^C) > 0$.

The regulator’s challenge is to choose $R$ close to $R^C$ that maximises $W(R)$ (safety, innovation, access) while preserving incentives for pioneers to invest in costly clinical validation and infrastructure.

## 4. Scenarios and analysis

### 4.1 AI health: national triage platforms and “AI doctor” services

In AI health, consider three stylised policy mixes:

#### Scenario H1 – Exclusive national platform

- A country selects a single triage platform vendor (e.g. through a one-off tender), grants a multi-year exclusive national contract, and allows proprietary formats for data and workflows.
- Reimbursement is tied to that vendor’s solution; switching costs are high.
- Result: $S_P$ close to 1, $S_F \approx 0$ for that channel.
- Pioneers capturing national contracts can build large, defensible businesses; followers are confined to niches (e.g. specific specialties, private-pay).

Pros:

- clarity for clinicians and patients;
- scale for the vendor to invest in safety and UX.

Cons:

- limited pressure to innovate post-award;
- high risk of lock-in to a suboptimal solution;
- limited scope for fast followers to diffuse best practices.

#### Scenario H2 – Multi-vendor, standardised APIs

- National systems mandate standard protocols for triage, EHR integration and reporting.
- Public payors reimburse “triage events” or “AI-supported consults” without mandating a specific vendor.
- Hospitals and clinics can multi-home across approved vendors.
- Result: $S_P$ < 1, $S_F > 0$; room for multiple players.

This environment favours:

- pioneers that secure early references and clinical validation;
- fast followers that can integrate quickly, leverage existing standards and specialise in niches (e.g. paediatrics, mental health).

#### Scenario H3 – Risk-based AI regulation

- Compliance requirements scale with the risk class of the AI system (diagnostic vs administrative).
- Smaller innovators can get to market with lower cost in low-risk categories (documentation, scheduling).
- High-risk clinical applications require more rigorous trials and monitoring, raising $I_P$ and $I_F$ but independently of firm size.

This regime preserves incentives for pioneers in high-risk categories while leaving room for fast followers in adjacent, lower-risk tasks.

### 4.2 AI productivity: suites vs independent tools

For productivity tools, regulation plays a smaller direct role; platform conduct and enterprise IT standards matter more. Consider:

#### Scenario P1 – Suite-dominated, limited portability

- Large providers bundle AI across email, documents and chat.
- Data are stored in proprietary formats; export is technically possible but onerous.
- IT security policies restrict third-party tools’ access to enterprise data.
- Result: $S_P$ for suite providers is very high; stand-alone AI productivity startups face limited access to context and strong multi-homing frictions.

#### Scenario P2 – Open productivity ecosystems

- Data-portability and interoperability mandates (or strong customer pressures) result in robust APIs for email, docs and calendars.
- Enterprise IT policies standardise secure OAuth-type access for approved third-party AI tools.
- Result: independent AI productivity tools (vertical copilots, workflow engines) can access sufficient context to add distinct value; they compete on UX, domain depth and model orchestration.

In P2, fast followers can:

- observe pioneers’ UX patterns;
- rely on the same foundation models;
- build specialised, opinionated workflows (e.g. finance, legal, operations).

### 4.3 Comparative analysis

In both AI health and productivity:

- Pioneers bear a disproportionate share of exploration and regulatory risk.
- Fast followers benefit from learning, but their viability depends on whether regulation and platform rules allow them access to data, channels and customers.

Regimes closer to $R^C$ (contestable):

- sustain longer windows in which fast followers can enter (e.g. 2–4 years post-pioneer) and still build meaningful positions;
- push both pioneers and followers to compete on quality, safety and cost-effectiveness.

Regimes closer to $R^E$ (entrenching):

- compress or eliminate the viable window for fast followers;
- reduce the incentive to improve products after initial adoption;
- may raise prices and slow diffusion of best-performing models.

## 5. Risks and caveats

- **Regulatory complexity**: real-world regimes combine elements of $R^E$ and $R^C$, vary across jurisdictions and change over time.
- **Information asymmetry**: regulators may lack the technical capacity to design effective AI rules; over-regulation can stifle beneficial innovation, under-regulation can encourage unsafe deployment.
- **Capture and lobbying**: dominant pioneers may influence rules to entrench their position, for example by supporting compliance regimes that small entrants cannot afford.
- **Global fragmentation**: AI health tools must deal with heterogeneous privacy laws and health-system structures; multi-country fast followers face higher compliance costs.
- **Measurement of welfare**: social welfare $W(R)$ comprises clinical outcomes, access, trust, and innovation; quantifying these in practice is challenging.
- **Platform response**: hyperscalers may change API pricing, introduce competing features, or restrict model usage, altering the economics for both pioneers and followers.

## 6. Comparison and implications

### 6.1 AI health vs productivity

- **Regulatory burden**: AI health has heavy ex ante regulation (clinical validation, safety, reimbursement); productivity tools face lighter, cross-sector rules.
- **Data structure**: health data are highly sensitive and siloed; productivity data are concentrated in cloud suites but subject to portability norms.
- **Entrenchment channels**:
  - AI health: exclusive national triage contracts, proprietary integration, reimbursement rules.
  - Productivity: bundling within suites, data gravity, ecosystem control.

### 6.2 Implications for founders

For AI health:

- fast followers should target jurisdictions and segments with interoperability mandates and open procurement;
- focusing on adjacent problems (e.g. documentation, care-navigation, chronic-disease management) where regulatory requirements are somewhat lighter can reduce $I_F$;
- partnering early with hospitals, payors and regulators to shape standards can improve long-run positioning.

For AI productivity:

- fast followers should build on open APIs and design for portability (import/export docs, work with multiple suites);
- vertical specialisation (e.g. AI for finance teams, legal drafting, industrial operations) can exploit regulatory and workflow knowledge that suites lack;
- proactive compliance with privacy and emerging AI-safety norms can differentiate from less disciplined competitors.

### 6.3 Implications for policymakers

To sustain contestable markets while preserving incentives to invest, policymakers can:

- mandate interoperability and data portability in both health and productivity ecosystems;
- use risk-based AI regulation to match compliance burdens to potential harm;
- design procurement processes that allow multiple vendors and periodic re-tendering;
- enforce competition policy to curb anti-competitive bundling and self-preferencing.

## 7. Conclusion

Regulation and data governance are key determinants of whether AI pioneers become entrenched or whether fast followers retain a realistic chance to catch up and surpass them. In digital health, appropriately designed interoperability, risk-based AI regulation and open procurement can lengthen the competitive window for capital-efficient fast followers without undermining pioneers’ incentives to invest in safety and clinical evidence. In productivity tools, platform rules and data-portability norms play a similar role.

For founders and investors, the message is clear: evaluating a fast-follower strategy requires not just a view on product and technology, but a granular understanding of regulatory and platform regimes in target markets. For policymakers, the design of these regimes will largely determine whether AI markets evolve towards monopolistic pioneers or towards dynamic, contestable ecosystems where both pioneers and sophisticated fast followers can thrive.

## References

[1] Golder, P. N., & Tellis, G. J. – “Pioneer Advantage: Marketing Logic or Marketing Legend?”, Journal of Marketing Research, 1993.

[2] Rock Health – “2024 Year-End Market Overview: Davids and Goliaths”, 2025.[18]

[3] Healthcare Dive – “Digital health funding outpacing last year as huge rounds increase: report”, 2025.[6]

[4] AHA Center – “Digital Health Funding Surges in Q1, with AI Leading the Way”, 2025.[10]

[5] Galen Growth – “AI and TechBio Funding Lead the Charge: 2024 Digital Health Funding Resurgence”, 2025.[14]

[6] Babylon Holdings – Annual Reports and SPAC filings, 2021–2023.

[7] McKinsey & Company – “The State of AI in 2023: Generative AI’s Breakout Year”, 2023; “The Economic Potential of Generative AI: The Next Productivity Frontier”, 2023.[1][9][15]

[8] McKinsey & Company – “The State of AI: Global Survey 2025”, 2025.[5]

[9] Brynjolfsson, E., et al. – “Generative AI at Work”, Quarterly Journal of Economics, 2025.[7]

[10] Bick, A., Blandin, A., & Deming, D. – “The Rapid Adoption of Generative AI”, NBER Working Paper, 2024/2025.[11][19]

[11] Lieberman, M. B., & Montgomery, D. B. – “First-Mover (Dis)Advantages: Retrospective and Link with the Resource-Based View”, Strategic Management Journal, 1998.[12]

[12] Various regulatory reports – EU and national guidance on AI in healthcare, EHR interoperability and AI-safety frameworks, 2020–2025.

[13] Industry and company sources – documentation on Ada Health, K Health, Doctrin, Qure.ai and Doctronic business models and funding rounds.

[14] Notion Labs, GitHub and hyperscaler announcements – AI-productivity features and ecosystem policies, 2022–2025.

[15] Competition-policy and platform-regulation documents – interoperability and data-portability rules affecting digital platforms and cloud services.
