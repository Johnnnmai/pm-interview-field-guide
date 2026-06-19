# Product Scenarios Analysis

Based on 4,525 extracted product scenarios from 895 job descriptions.

Methodology note: I collected all product scenarios into a single file and used AI (Claude) to analyze and categorize them. This is not a quantitative analysis like the [skills analysis](02-skills.md) (see the [analysis notebook](../job-market/analysis.ipynb) for that) - it's based on the questions I asked and the patterns Claude identified in the data. It may be less precise, but I believe it's still representative of what's happening in the market.

## Summary

The product scenarios reveal what companies are actually building and shipping today. This is the real-world product landscape that Product Managers work on daily.

Total product scenarios extracted: 4,525

- Product-First roles: 3,177 scenarios (70.2%)
- Product-Support roles: 1,259 scenarios (27.8%)


## Problems Products Solve Today

Organized by the user problem, not the methodology.


### Prioritizing What to Build Next

696 mentions (15.4%)

Problem: Teams have more ideas than capacity. Stakeholders pull in different directions. Without structured prioritization, teams build the wrong things.

Product Solution: Prioritization frameworks (RICE, ICE, opportunity scoring) that connect user data to roadmap decisions.

Concrete examples:

- Analyze usage data and customer feedback to identify highest-impact features
- Build RICE scoring models to align engineering capacity with business goals
- Run discovery sprints to validate assumptions before committing resources
- Define metrics trees that connect feature launches to north star metrics
- Build business cases for new product investments with revenue impact models
- Orchestrate cross-team prioritization across multiple product areas
- Process hundreds of feature requests from enterprise customers at scale


### Understanding Customers at Scale

360 mentions combined (8.0%)

Problem: Companies have massive amounts of customer data - support tickets, usage analytics, NPS scores, interview transcripts. Teams cannot synthesize it fast enough. Intuition is not enough.

Product Solution: Structured discovery and customer insight programs that turn raw data into product decisions.

Concrete examples:

- Customer segmentation and persona development using behavioral data
- Support ticket pattern analysis to identify recurring pain points
- User journey mapping across multiple product surfaces
- Competitive win/loss analysis with sales team data
- Voice of customer programs with regular interview cadences
- NPS and CSAT tracking with automated insight extraction
- Cohort analysis revealing feature adoption patterns across segments


### Reducing Churn and Increasing Retention

312 mentions (6.9%)

Problem: Companies invest heavily in acquisition but lose customers through poor onboarding, missing features, or unmet expectations. Retention directly impacts unit economics.

Product Solution: Product-led retention strategies that identify at-risk users and intervene proactively.

Concrete examples:

- Building onboarding flows that drive activation within the first session
- Designing engagement loops that bring users back regularly
- Analyzing churn cohorts to identify common failure patterns
- Creating re-engagement campaigns triggered by usage drop-offs
- Optimizing pricing and packaging to reduce involuntary churn
- Building health scoring models that predict account risk


### Scaling Internal Operations

519 mentions (11.5%)

Problem: Enterprises have complex operations - compliance workflows, multi-team coordination, cross-product dependencies. These require product-level thinking to systematize.

Product Solution: Internal product platforms and operational tooling that reduce manual overhead.

Concrete examples:

- Early signal detection of emerging operational risks before they escalate
- Building compliant product workflows that meet enterprise regulatory requirements
- Industry-specific product solutions tailored to vertical needs
- Implementing multi-product strategies for platform organizations
- Automated compliance checking and audit trail generation
- Performance benchmarking and capacity planning dashboards
- Fraud detection and risk assessment product features


### Launching New Products Successfully

219 mentions (4.8%)

Problem: New products fail at high rates. Go-to-market execution, positioning, and initial adoption are major challenges.

Product Solution: Structured launch playbooks with staged rollouts and clear success criteria.

Concrete examples:

- Staged beta programs with defined success criteria and kill switches
- Go-to-market coordination across engineering, marketing, sales, and support
- Launch readiness checklists covering documentation, support, and monitoring
- Post-launch measurement frameworks with leading and lagging indicators
- Market entry strategies for new geographies and segments


### Making Data-Driven Decisions

163 mentions (3.6%)

Problem: Companies have data but cannot extract insights or make data-driven decisions quickly enough. Analysis paralysis or gut-feel decisions dominate.

Product Solution: Metrics frameworks and experimentation infrastructure that enable rapid, evidence-based decisions.

Concrete examples:

- Transform complex product data into clear dashboards and actionable insights
- Build metrics trees connecting feature-level metrics to business outcomes
- Design A/B experiments with proper statistical rigor and decision criteria
- Predictive models for user behavior and engagement forecasting
- Revenue attribution and impact quantification for shipped features


### Ensuring Product Quality

141 mentions (3.1%)

Problem: Products can launch with bugs, poor UX, or unintended edge cases. Quality directly impacts retention and brand trust.

Product Solution: Quality frameworks that catch issues before launch and monitor post-launch health.

Concrete examples:

- Pre-launch QA checklists covering functionality, performance, and edge cases
- Post-launch monitoring dashboards for error rates and user complaints
- Structured user acceptance testing programs with real customers
- Automated alerting on product health metrics degradation
- Bug triage and severity frameworks for rapid issue resolution


### Growing Revenue and Market Share

118 mentions (2.6%)

Problem: Products need to generate revenue. Growth requires experimentation, funnel optimization, and pricing strategy aligned with user value.

Product Solution: Growth product management with systematic experimentation and monetization.

Concrete examples:

- Conversion funnel optimization across acquisition, activation, and retention
- Pricing experiments and packaging strategy validation
- Revenue expansion programs with upsell and cross-sell triggers
- Market expansion playbooks for new segments and geographies
- Referral and viral growth loop design


### Personalizing User Experiences

128 mentions combined (2.8%)

Problem: Users want relevant experiences, not generic products. One-size-fits-all doesn't work at scale.

Product Solution: Personalization and recommendation strategies that adapt to user behavior and preferences.

Concrete examples:

- E-commerce recommendation systems driving higher conversion rates
- Content personalization based on user behavior and preferences
- Search optimization using user intent signals
- Dynamic pricing and packaging based on customer segments
- Customer segmentation driving targeted product experiences


### Improving Developer Experience

60 mentions (1.3%)

Problem: Developer productivity is limited by poor tooling, confusing APIs, and steep learning curves. Platform products need great DX.

Product Solution: Developer-focused product management with SDK design, documentation, and onboarding optimization.

Concrete examples:

- API design and versioning strategy for platform products
- Developer portal and documentation experience optimization
- SDK adoption metrics and developer satisfaction tracking
- Internal platform products improving engineering velocity
- Developer onboarding flow optimization


### Navigating Regulated Industries

38 mentions (0.8%)

Problem: Products in healthcare, finance, and legal must meet strict regulatory requirements. Generic product approaches fail in these domains.

Product Solution: Compliance-aware product management with regulatory expertise built into the product process.

Concrete examples:

- Healthcare products meeting HIPAA compliance requirements
- Financial products navigating SOX and PCI-DSS regulations
- Legal tech products adapting to jurisdiction-specific regulations
- Insurance products with automated compliance verification
- Privacy-first product design for GDPR and CCPA


## Domains Served

Based on the product scenarios, product management is applied across virtually all industries.

### Finance (340+ mentions)

- Fraud detection and risk products
- Underwriting and credit decision tools
- Trading and portfolio management platforms
- Claims processing automation
- Personalized financial planning products

### Healthcare (232+ mentions)

- Clinical decision support products
- Patient engagement and portal experiences
- Telehealth platform management
- Medical documentation and workflow tools
- Evidence-based treatment recommendation systems

### Cybersecurity (177+ mentions)

- Threat detection and alerting products
- Security operations center tooling
- Identity and access management platforms
- Compliance monitoring dashboards
- Risk assessment and scoring products

### Legal/Regulatory (157+ mentions)

- Contract lifecycle management products
- Legal research and document analysis tools
- Compliance monitoring platforms
- eDiscovery and case management
- Risk assessment products

### Education (181+ mentions)

- Personalized learning platform management
- Assessment and grading products
- Educational content delivery systems
- Student engagement and retention tools
- Course recommendation engines

### Manufacturing/Industrial (57+ mentions)

- Supply chain management platforms
- Quality control and defect tracking products
- Predictive maintenance dashboards
- Process automation tooling
- Inventory optimization systems

### Retail/E-commerce (40+ mentions)

- Product recommendation engines
- Search and discovery optimization
- Inventory and supply chain products
- Customer experience personalization
- Marketplace and platform products


## Key Insights

### 1. Prioritization is the Primary Product Challenge

The most common problem PMs solve is deciding what to build next. This is not glamorous - it's about reducing ambiguity, aligning teams, and making resource allocation decisions backed by data.

### 2. Customer Insight is Universal

Every domain has the same problem: too many signals, not enough synthesis. User research, analytics, and voice-of-customer programs solve this across healthcare, finance, legal, and enterprise products.

### 3. Retention Drives Business Outcomes

Retention and churn reduction are a top category because they directly impact revenue and unit economics. The ROI is clear: reducing churn costs less than acquiring new users.

### 4. Launching is Hard

A significant portion of product scenarios focus on go-to-market execution. This reflects the real challenge of getting products from prototype to successful market adoption.

### 5. Domain Specialization Matters

While fewer in number, products in regulated industries (healthcare, finance, legal) represent high-value PM roles where generic product management approaches are insufficient.


## Most Common Words in Product Scenarios

- customer: 505 mentions
- product: 490 mentions
- strategy: 399 mentions
- roadmap: 393 mentions
- metrics: 338 mentions
- growth: 291 mentions
- launch: 276 mentions
- business: 262 mentions
- user: 256 mentions
- enterprise: 245 mentions

The language emphasizes practical value: customer, product, strategy, roadmap, metrics - not just methodology.
