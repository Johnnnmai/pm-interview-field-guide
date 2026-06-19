# Interview Trends (2026)

Emerging patterns in product management interviews based on candidate experiences, job descriptions, and industry discussions.


## Market Data (2025)

- 62,000 tech layoffs in 2025 (including 9,000 at Microsoft), but layoffs became strategic restructuring rather than survival measures - companies now prioritize AI-fluent product talent [^interviewquery-2025]
- Tech job openings stabilized around 230,000 (up 22% from 2024 lows). Companies like Amazon and Apple hired more than they laid off [^interviewquery-2025]
- AI PM roles (AI Product Manager, Agentic PM, Growth PM) surged 240% in early 2025 [^interviewquery-2025]
- AI and product strategy interview questions tripled since 2023 [^interviewquery-2025]
- AI/product mentions in job postings increased across all roles: PMs 8% to 29.5%, Data Scientists 4% to 18.4%, Analysts and BI 3.8% to 15.8%, Technical PMs 6.7% to 13%, Platform PMs 3% to 9.7% [^interviewquery-2025]


## Patterns from Practitioners

Based on 130+ interview rounds reported by Janvi Kalra (46 companies) [^janvi-kalra], Deepthi Sudharsan (50+ rounds) [^deepthi-sudharsan], and a senior PM with 14+ YOE (~40 interviews) [^reddit-leetcode-2026]:

- Pure case study interviews are declining but not dead. ~70% of senior interviews had product design rounds instead. When analytical questions come up, they're practical (metric diagnosis, real-world data), not puzzle-based
- Three interview types dominate: product sense, product design, and execution interviews ("prioritize this roadmap given constraints")
- Product design shifted from "design a parking app" to AI-powered product design: scaling AI features, cost/quality trade-offs, responsible AI deployment, user trust, failure modes. See [Product Design](questions/04-ai-system-design.md) for details
- Project presentations are common: candidates present a past product launch, then get grilled on strategy decisions, trade-offs, what failed, what they'd change
- Data literacy and SQL fluency are becoming more important alongside product intuition
- In-person final rounds are coming back
- AI companies cluster into three types that affect interview focus: product companies (Cursor, Notion, Figma), platform companies (Stripe, Twilio, Datadog), and AI-native companies (OpenAI, Anthropic, Google, Meta)
- Interview focus varies by PM type: AI PMs get distinct product sense and strategy rounds plus AI-specific design; Growth PMs get more experimentation and funnel analysis; Platform PMs get more technical depth and API design


## "No Case Study" - Realistic Assessments

A growing number of companies explicitly reject traditional case study interviews in favor of realistic work:

- Clarium: "no abstract puzzles," context sent in advance
- Column Tax: "not textbook cases," interviews mimic real product work
- Phare Health: "not hypothetical scenarios"
- Doctolib: "Product Building Interview" tests practical product thinking, not frameworks
- Glass Health: realistic product simulation
- TensorOps: no live case, no take-home
- boam: real company product problems

For candidates, this means preparation should focus on building and discussing real products rather than memorizing frameworks.


## Framework Bias in Hiring

Some companies equate "product management" with specific framework knowledge, leading to rejections of more capable candidates. A PM with deep experience in data-driven product development, experimentation, and user research was rejected for not knowing a specific company's proprietary product framework - despite having stronger product instincts than what the role required. The community was split: [^reddit-langchain-rejected]

- "The company is not product-savvy enough to understand what real product management looks like" (355 upvotes)
- "Do you want a job? Learn the company's framework" - pragmatic view that popular methodologies are what companies hire for
- "You didn't fail the product interview. You failed the culture fit" - the best framing

For candidates: know what stage the company operates at (early-stage vs. growth vs. enterprise) and align your language accordingly. For companies: framework-specific requirements filter out candidates who may have deeper product expertise.


## Real-Time AI Cheating During Interviews

Real-time AI cheating is an increasing problem. Tools listen to the conversation, transcribe questions, and tell candidates what to say, and companies now explicitly address this in their hiring process.

This doesn't necessarily mean that they forbid using AI for preparation or case work.

- Marvell Technology: "candidates do not use AI tools (transcription apps or real-time answer generators) during interviews"
- Hudson River Trading: "use of AI tools is strictly prohibited... we evaluate the authenticity of candidate responses"
- Wolters Kluwer: "use of AI or third-party support during interviews will be grounds for disqualification"
- Wells Fargo: "you're required to directly represent your experiences during the hiring process"


## AI Surveillance During Remote Interviews

AI surveillance during remote interviews is an emerging concern: camera monitoring, browser extensions, and audio analysis tools are being deployed by employers. Most candidate experiences remain remote, but monitoring tools add a new layer of stress. This trend is partly driving the return of in-person interviews at top companies. [^reddit-datascience-2025]


## AI-Proctored Early Rounds

AI agents are starting to conduct early product screens.

- Eightfold.ai (Jan 2026): Round 1 was an AI-conducted screening interview - ~60 min, 2 product sense questions. The AI agent asked interactive follow-ups: edge cases, alternative approaches, metrics definition. "This round felt more like a conversational product discussion than a standard online assessment" [^eightfold-internship] [^reddit-eightfold]
- Coinbase: AI conducts initial screening interviews with simulated product scenarios
- Deepthi Sudharsan reports being interviewed by AI three times at US-based companies. The AI typically asks general or scenario-based questions; in rare cases uses RAG with the candidate's resume for targeted product questions [^deepthi-sudharsan]


## The "No AI Tools" Irony

Roles centered on building AI-powered products sometimes ban AI tools during case studies. Candidates report cognitive dissonance: the job requires AI product fluency, but the interview tests "raw" product thinking.

The Wolters Kluwer paradox: their AI PM roles require AI product tool proficiency (ChatGPT, AI agents) as mandatory skills, yet ban all AI during interviews.

Meanwhile, other companies lean into it:
- FlowFuse: AI tools "explicitly allowed and encouraged" during take-home case studies
- Miro: "AI-First Proficiency" as hiring criterion, expects familiarity with AI product tools


## Employers Using AI in Hiring

Many explicitly say that they use AI in the recruitment process:

- Coinbase: AI conducts initial screening interviews with simulated scenarios
- Foxelli Group: Ribbon AI asynchronous video interviews
- Block/TIDAL: "we may use automated AI tools"

Only 1 company (Viral Nation) explicitly states they do NOT use AI in recruitment.


## Encouraging or Evaluating AI Fluency

- FlowFuse: AI tools "explicitly allowed and encouraged" during take-home
- Toku: AI-native product development is "non-negotiable"
- Miro: "AI-First Proficiency" as hiring criterion, expects AI tool usage in product work
- TRM Labs: "AI fluency is a baseline expectation"
- BetterUp: "during our interview process, you'll have opportunities to showcase how you harness AI"
- Micron Technology: "candidates are encouraged to use AI tools to enhance their resume and/or application materials"


## Published AI Guidelines for Candidates

Many companies share guidelines on how candidates should use AI:

- Datadog: [Interviewing at Datadog AI Guidelines](https://careers.datadoghq.com/candidate-experience/interviewing-at-datadog-ai-guidelines/)
- Invisible Technologies: [AI Interview Guidelines](https://invisibletech.ai/ai-interview-guidelines) - AI OK for resumes and assessments, banned during live interviews (no AI-generated scripts), case studies allow AI as part of normal workflow if candidates explain their thought process
- Anthropic: [Guidance on Candidates' AI Usage](https://www.anthropic.com/candidate-ai-guidance)
- Zapier: [How to Collaborate with AI During Zapier's Hiring Process](https://zapier.com/l/jobs/ai-at-zapier)
- AssemblyAI: [Candidate AI Guidance](https://www.assemblyai.com/candidate-ai-guidance)
- SandboxAQ: [AI in Interviews](https://www.sandboxaq.com/ai-in-interviews)
- CDW: [AI Applicant Notice](https://www.cdwjobs.com/pages/ai-applicant-notice) - encourages AI for grammar checking, brainstorming, accessibility, and research, but requires the final product to "accurately reflect your own experiences, achievements, and voice"
- Oscar Health: [Guidelines for using AI when interviewing at Oscar](https://www.hioscar.com/careers/ai-guidelines) - AI OK for resumes and prep, but misrepresentation may lead to disqualification.


## In-Person Interviews Are Coming Back

In-person interview rounds increased from 24% (2022) to 38% (2025), driven by concerns about AI-assisted cheating during remote interviews. [^interviewquery-2025] More top companies are requiring in-person onsites. [^yuan-meng]


## AI Tools Allowed During Live Interviews

Some companies now explicitly allow AI tools during live product interviews:

- OpenAI: AI tools allowed during product rounds - candidates share screen and narrate reasoning. "The boundary is that you shouldn't dump the entire problem into ChatGPT and paste back the output. They're watching for reasoning and judgment" [^exponent-openai]
- PromptLayer: allows ChatGPT during live product design to observe how candidates think about AI product trade-offs [^promptlayer]
- Microsoft PM: Round 1 is AI-assisted product analysis, Round 2 is unassisted product design. The format explicitly tests both AI-augmented productivity and baseline product thinking [^reddit-csmajors-msft]
- Exponent mock interview: a senior FAANG PM conducts a combined product sense + design round where the candidate uses AI tools throughout. The interviewer evaluates HOW the candidate uses AI - prompting strategy, ability to verify and build on AI output, and whether they let AI make product decisions for them. Key interviewer warning: "Not understanding what the AI is going to do is the biggest pitfall. Relying on AI to make decisions for you." [^exponent-claude-code]


## PM Interviews Lack Standardization

The PM role is still evolving, and interviews reflect this. Janvi Kalra, who interviewed at 46 companies, found the process "all over the place" - combining product sense, product design, and execution assessments with no consistent format. "The market is trying to move away from traditional case studies but still asks them, so you end up having to prepare for everything." She hopes the industry moves toward product design, real project reviews, and data analysis - but "as an industry we haven't fully formed an opinion here" [^janvi-kalra] [^janvi-kalra-youtube]


## Junior vs. Senior Expectations Are Diverging

Product design interviews increasingly test seniority through depth of thinking rather than framework knowledge: [^interviewnode]

- Junior: Focus on user needs and basic product design
- Mid-level: Describe metrics trees, experimentation plans, and go-to-market strategies
- Senior: Design an evolving product ecosystem - user segmentation strategies, how metrics interact across features, how user feedback drives roadmap iteration, how competitive dynamics shape product positioning

"At senior levels, product design interviews aren't about frameworks, they're about foresight."


## Read the Room: AI Hype Can Backfire

An interviewer gave a borderline senior candidate a "soft thumbs down" because the candidate kept insisting AI could help with a product problem the team was working on - in a way that didn't make sense for the user segment. The takeaway: at senior levels, candidates are expected to demonstrate judgment about when AI solutions are and aren't appropriate. Knowing the latest AI tools is table stakes; knowing when NOT to use them signals maturity. [^reddit-datascience-llm-hype]


## The Bar Feels Higher

Because everyone uses AI tools daily, the focus has shifted:
- Explaining product strategy and trade-offs over memorization
- Demonstrating production thinking over framework recitation
- Showing how you reason about products with AI, not just raw product intuition

Candidates report that "can you write a PRD?" is no longer enough. The question is now "can you ship, scale, and measure products in production?"

InterviewQuery frames it as: "Knowledge is free - judgment isn't." The interview philosophy shifted from "Can you design a product?" to "Can you reason about the product that users actually need?" [^interviewquery-2025]


## Exploitative Take-Homes at Startups

Startups are increasingly using take-home case studies as low-cost product ideation, with scope that amounts to real strategy work. Community discussions highlight a growing pattern:

- A candidate was asked to build a complete go-to-market strategy for a new product vertical - community estimated thousands of dollars worth of consulting effort [^reddit-developpeurs]
- A real-estate startup asked candidates to build an end-to-end competitive analysis with pricing recommendations - vague scope with a 2-hour timeframe [^reddit-expdevs-takehome]
- Experienced PMs recommend declining any assignment that could constitute a deployable strategy document, and refuse take-homes sent before any human conversation

The trend is accelerating as AI tools make it easier to produce more in less time, raising scope expectations. "Founding PM" roles at startups often pair high expectations with exploitative screening processes.


## Emerging Interview Formats

Several new approaches are gaining traction, reported across multiple Hacker News threads:

- Product critique rounds: Candidates evaluate an existing product for UX issues, strategic gaps, and growth opportunities [^hn-code-review-1] [^hn-code-review-2] [^hn-code-review-3]
- Evaluating AI-generated product plans: Candidates receive an AI-generated PRD, then review and critique that document during the interview [^hn-ai-generated-1] [^hn-ai-generated-2]
- "AI delta" assessment: Candidates tackle a real product problem in 2-4 hours while evaluators assess what they add beyond what AI generates - strategic depth, user insight, edge case handling, go-to-market quality [^hn-ai-delta]
- Collaborative product sessions on real problems: 1-2 hours on an actual product challenge provides stronger signal than hypothetical case studies [^hn-code-review-3]
- Candidates using AI in live interviews often perform worse: Follow-up questions expose lack of depth. AI-generated product strategies often contain surface-level recommendations that the candidate cannot defend [^hn-ai-worse]
- Anti-cheating tooling: Tools like BlindSpots use adversarial examples (invisible pixel and audio modifications) to disrupt AI screenshot-based and audio-based cheating tools without invasive surveillance [^hn-blindspots]


## New Interview Round Types Emerging

Yuan Meng identifies several challenging rounds now appearing at top companies that didn't exist in earlier interview cycles: [^yuan-meng]

- Product Strategy at Scale: Detailed questions about platform effects, multi-sided marketplace dynamics, and portfolio prioritization (not just feature-level thinking)
- Multi-stakeholder Product Design: Building product solutions with incremental complexity and competing stakeholder needs
- AI Product Design: Designing AI-powered features with responsible AI constraints, evaluation frameworks, and user trust considerations
- Product Presentations: Job talk-style presentations defending product decisions and outcomes
- References becoming standard: Most top companies now require 2-3 references from recent managers/colleagues


## Sources

[^interviewquery-2025]: [InterviewQuery: PM Interview Trends 2025](https://www.interviewquery.com/p/ai-interview-trends-tech-hiring-2025)
[^janvi-kalra]: [Janvi Kalra / Pragmatic Engineer](https://newsletter.pragmaticengineer.com/p/from-software-engineer-to-ai-engineer)
[^janvi-kalra-youtube]: [Janvi Kalra / YouTube](https://www.youtube.com/watch?v=GEqJrKYnhbY)
[^deepthi-sudharsan]: [Deepthi Sudharsan: Inside PM Interviews](https://medium.com/@deepthi.sudharsan/inside-ai-interviews-stories-patterns-and-what-actually-matters-555684c38598)
[^reddit-leetcode-2026]: [Reddit r/leetcode - 2026 Interview Prep](https://www.reddit.com/r/leetcode/comments/1q06zz6/2026_interview_prep)
[^reddit-langchain-rejected]: [Reddit r/LocalLLaMA - Rejected for Not Knowing Framework](https://www.reddit.com/r/LocalLLaMA/comments/1ow3anq/rejected_for_not_using_langchainlanggraph/)
[^reddit-datascience-2025]: [Reddit r/datascience - State of Interviewing 2025](https://www.reddit.com/r/datascience/comments/1p1dklk/state_of_interviewing_2025_heres_how_tech/)
[^eightfold-internship]: [Inside Eightfold's PM Process](https://medium.com/@bhardwajtushar2004/inside-eightfold-ais-agentic-ai-internship-hiring-process-2026-f86dcb625aa8)
[^reddit-eightfold]: [Reddit r/developersIndia - Eightfold AI](https://www.reddit.com/r/developersIndia/comments/1pbaj11/need_advice_for_eightfoldai_agentic_ai_engineer)
[^exponent-openai]: [Exponent: What It's Like to Interview at OpenAI](https://medium.com/exponent/what-its-actually-like-to-interview-at-openai-in-2026-03a646c9436c)
[^promptlayer]: [PromptLayer: The Product Design Interview](https://blog.promptlayer.com/the-agentic-system-design-interview-how-to-evaluate-ai-engineers/)
[^reddit-csmajors-msft]: [Reddit r/csMajors - Microsoft PM](https://www.reddit.com/r/csMajors/comments/1nqfzhq/microsoft_swe_applied_aiml_summer_2026_redmond)
[^exponent-claude-code]: [Exponent: AI-Assisted PM Interview](https://www.youtube.com/watch?v=C6CdzcU7I18)
[^interviewnode]: [InterviewNode: Product Design Patterns](https://www.interviewnode.com/post/generative-ai-system-design-interview-patterns-you-should-know)
[^reddit-datascience-llm-hype]: [Reddit r/datascience - Failed Candidate for AI Hype](https://www.reddit.com/r/datascience/comments/15t69mt/failed_an_interviewee_because_they_wouldnt_shut/)
[^reddit-developpeurs]: [Reddit r/developpeurs - Build a Complete GTM Strategy](https://www.reddit.com/r/developpeurs/comments/1m84v47/on_ma_demand%C3%A9_de_construire_un_agent_llm_complet/)
[^reddit-expdevs-takehome]: [Reddit r/ExperiencedDevs - Take-Home Case Study Scope](https://www.reddit.com/r/ExperiencedDevs/comments/1nyzx77/is_this_type_of_takehome_assignment_becoming_the/)
[^yuan-meng]: [Yuan Meng: PM Interviews 2.0](https://www.yuan-meng.com/posts/mle_interviews_2.0/)
[^hn-code-review-1]: [HN: Product Critique Interviews](https://news.ycombinator.com/item?id=40363135)
[^hn-code-review-2]: [HN: Product Critique Interviews](https://news.ycombinator.com/item?id=42977039)
[^hn-code-review-3]: [HN: Collaborative Product Sessions](https://news.ycombinator.com/item?id=43108673)
[^hn-ai-generated-1]: [HN: Evaluating AI-Generated Product Plans](https://news.ycombinator.com/item?id=42268158)
[^hn-ai-generated-2]: [HN: AI-Generated Product Review](https://news.ycombinator.com/item?id=42977039)
[^hn-ai-delta]: [HN: AI Delta Assessment](https://news.ycombinator.com/item?id=46865130)
[^hn-ai-worse]: [HN: AI in Live Interviews](https://news.ycombinator.com/item?id=42909166)
[^hn-blindspots]: [HN: BlindSpots Anti-Cheating](https://news.ycombinator.com/item?id=45492686)
