# Webinar 2: Defining the PM Role

- Date: February 24, 2026
- Host: [Alexey Grigorev](https://www.linkedin.com/in/agrigorev/)
- [Maven](https://maven.com/p/f0cada/defining-the-ai-engineer-role)
- [Recording on YouTube](https://www.youtube.com/watch?v=7NijlAdqk9U)
- [Slides](slides/ai-engineer-role.pdf)

## Description

PM job titles are inconsistent. This webinar examines 1,500+ current job descriptions and industry research to clarify what companies actually hire for, helping professionals transition from simply managing projects to driving product strategy at scale.

## Topics Covered

- Data analysis: scraping and processing job descriptions using LLMs to identify patterns
- Role classification: distinguishing between strategy-focused and execution-oriented PM positions
- Technical skills: analytics/SQL and cross-functional leadership fundamentals
- Product frameworks: prioritization frameworks (RICE, ICE) and product strategy requirements
- Production focus: shipping velocity versus product quality and evaluation methodologies
- Career strategy: actionable approaches for securing PM positions
- Industry trends: interview patterns and evolving skill expectations

## Key Findings

### Dataset

The analysis is based on approximately 895 job descriptions scraped from the Built In website in January 2026. Jobs were collected from five cities: Berlin, Amsterdam, London, Los Angeles, and New York. After removing duplicates and filtering out unrelated roles, each description was processed using an LLM to extract structured information: company details, position type (product-led, project-support, or technical PM), responsibilities, use cases, and skills categorized by type.

All data, scraping scripts, and analysis notebooks are in the [PM Field Guide repository](https://github.com/alexeygrigorev/ai-engineering-field-guide).

### Skills

70% of the positions were product-led roles. The remaining 30% were project-support roles or traditional project management positions relabeled as "product manager."

Product strategy is the number one skill pattern, mentioned in about 35% of product-led positions. 93% of PM roles require skills beyond just strategy.

Top skills from job descriptions:
- SQL/analytics is the dominant technical skill (82.5%), Python in second place (23.4%)
- Cloud platforms: AWS is the leader, but any cloud familiarity helps
- A/B testing, experimentation, and data pipelines are commonly expected
- Jira is the most popular tool mentioned, followed by Amplitude and Mixpanel
- 64% of roles require some technical knowledge - likely because product teams evolved from existing engineering teams
- Fine-tuning product-market fit is a niche skill (only ~25 out of 895 jobs mention it as primary)
- Evaluation and metrics are commonly required across positions

The key takeaway: a PM is first a strategic thinker, then a specialist. Just knowing how to write PRDs and run standups is not enough - you also need analytics, experimentation, stakeholder management, and cross-functional leadership skills.

### Responsibilities

Very common: building product strategy, shipping products (testing, QA, monitoring), evaluation and quality metrics, working with engineering teams (setting priorities, managing trade-offs), roadmap planning, user research.

Common: data analysis, cross-functional collaboration, platform and infrastructure decisions, building product vision.

Less common: hands-on technical work, self-hosting analytics. Most companies use external analytics platforms rather than building in-house.

## Q&A During the Webinar

### Data sample size and limitations

About 895 job descriptions. For these specific cities (LA, NY, Amsterdam, London, Berlin) and time period (January 2026), the sample is sufficient. Extrapolating to other regions like Asia or Africa would require more data, but New York sets the trends and Europe follows, so the patterns should generalize. The code is available in the repository for anyone who wants to reproduce the analysis with more cities.

### PM as a strategist who ships products

Yes, this is an accurate description. A PM is a strategic thinker with specialization in product, just like data engineers specialize in data and engineering managers in people leadership. They all need metrics, experimentation, stakeholder communication, and execution. An engineer can learn the core PM skills (product sense, prioritization, user research) in about 3-4 months and become a PM. For someone without an analytical background, it requires more effort because they also need to learn the data-driven decision-making skills.

### Context layer for product decisions

It depends on what "context layer" means. It could be: how you frame product problems, how you inject user data into decisions, selecting which metrics to track, using analytics, or maintaining product knowledge (docs or knowledge bases). All of this falls within the domain of product management.

### Data scientist with strong analytics transitioning to PM

Data scientists are well equipped for it. The mindset of tuning experiments, evaluating results, and making data-driven decisions is exactly what product management needs. Instead of training models yourself, you define product hypotheses and validate them with data, but the evaluation mindset is the same. Data scientists can start doing product work at their current workplace without switching titles. Take on more product ownership gradually.

### LeetCode interviews

This is changing but not everywhere. Some companies now allow coding agents and focus on walking through the solution. But many companies still use classical whiteboard interviews. The reasoning: "what if the internet is down, can you still think through technical problems?" Whether LeetCode is a good way to check that is debatable, but companies still do it for technical PM roles and it is not going away anytime soon.

### Differentiating PM and project manager

When I hear "product manager," I mean someone working with product strategy, user needs, and business outcomes, not just project timelines. Some companies jumped on the trend and renamed their project managers to product managers, but the role is still traditional project management. Sometimes the opposite happens too - a project coordination position has product strategy skills and responsibilities. The boundaries are blurry and some companies use the titles interchangeably.

### Are product jobs disappearing?

No. From a study analyzing 180 million job postings across years, product management is actually one of the top growing roles. You need PMs to set up processes so teams cannot ship broken products: quality gates, user testing, experimentation, metrics monitoring. PMs are safe.

Current AI tool pricing is heavily subsidized. If API costs become 10-100x higher, doing some product analyses by hand will make more sense again.

### Market for data analysts in product analytics and experimentation

Yes. Product analytics on the surface is just three steps: define metrics, build dashboards, run experiments. The complicated part is the analysis. You need proper metrics frameworks, and data needs to be clean and reliable. This is nothing but a data analytics job - moving data from source to insight. Data analysts have been doing this their entire career. Even with AI-powered analytics and automated dashboards, the underlying data is not going anywhere. Products need metrics, and those metrics need to be defined and maintained.

### Portfolio skills for masters students

Focus on what universities typically do not teach: product sense, experimentation, stakeholder management - the core PM skills. Also learn the full stack around product: analytics, user research, go-to-market strategy.

The way to add skills is through projects. Pick a project, implement it end to end, and each time focus on one area. For example: one project focused on building a metrics framework for a marketplace, another on A/B testing and experimentation, another on user research and product discovery. Build 5-6 small focused case studies rather than one large project. Spend 1-2 weeks on each.

### Course content for the next cohort

The [course on Maven](https://maven.com/alexey-grigorev/from-rag-to-agents) focuses on core product skills: product strategy, user research, experimentation, metrics, stakeholder management. Deep technical architecture is outside scope because the ideal profile is someone who already has analytical skills. Product design was added to the course despite personal preference for data-driven approaches, because there is demand. Making one single product work well with a few well-picked features is more important than complex multi-product systems.

### AI tools integration in industry

Very few product professionals do not use any AI assistants. It is pretty well integrated across data scientists, analysts, PMs, and engineers. It is a general productivity tool for product work - research, analysis, communication.

### Evaluating product performance

Create a ground truth dataset with expected user outcomes and success criteria. Run your product experiments, compare actual outcomes with expected outcomes, and compute success metrics across all cohorts. This is the standard evaluation approach.

### Securing a job at a product-led startup

Build case studies, yes. Cold outreach emails, probably not the most effective strategy.

Better approach: pick a domain by looking at companies hiring in your area. Read their product blogs to understand what problems they solve. Build 2-3 case studies in that domain using relevant data. At interviews, you have relevant things to discuss.

Instead of cold outreach, practice "learning in public" - share everything you learn on social media. People who work in the same domain will notice you. When you contact them later, it will not be cold outreach because they already saw your content. Also attend meetups and talk to people. If you are shy, speak at meetups instead - people come to you with questions.

## Q&A After the Webinar

### Technical skills in PM roles

From the analysis of 895 job descriptions:

- SQL/Analytics - 738 jobs (82.5%)
- Python - 209 jobs (23.4%)
- Business Intelligence - 133 jobs (14.9%)
- Data Visualization - 101 jobs (11.3%)
- A/B Testing - 88 jobs (9.8%)

SQL/analytics is the dominant technical skill. Python is in second place, which aligns with what we see in the field. BI tools and data visualization also appear frequently.

### PhD in research to product management

For a researcher, the core product analytics skills are easy. Running experiments, analyzing data, drawing conclusions - all of that is straightforward for someone with a research background.

The hard part for researchers is the business side: stakeholder management, prioritization, go-to-market. These are the areas that need the most attention.

For core PM skills beyond basic analytics:
- Experimentation design - approaching it the same way you design research studies
- Metrics monitoring - setting up proper success tracking for your products
- Evaluation - this should actually be easier for researchers since they already think in terms of metrics

For business skills:
- Stakeholder management - important to learn
- Go-to-market strategy - important to learn
- Basic financial modeling - knowing how to build a business case
- People management - can skip this initially, not essential

### Product security and compliance roles

I did not encounter separate product security roles in the data. But it would be interesting to investigate. All the scraping scripts are in the repository - if someone wants to repeat the analysis specifically for compliance-focused PM roles, it would not be too hard.

### Data analysts moving to product management

For data analysts, the core PM skills are exactly what you should focus on beyond analytics: product sense, stakeholder management, and prioritization. The transition is relatively fast - maybe 3-4 months and you are ready. You already have the analytical skills.

When job searching: "I am a data analyst, I know analytics, I can build dashboards and run experiments, and because I am a great analyst, I have an advantage over other PMs who do not have this skill."

### Are data scientist jobs safe?

Historically, to productionize a model, for every 1-2 data scientists you needed several engineers. With AI, this became even easier - any engineer who can run code can train an XGBoost model.

What makes data scientists valuable? ML and product management skills. They are also very good with experiments and evaluation. If data scientists want to move into product management, they should focus on the product strategy side and showcase their strong evaluation and metrics skills.

For example, search is very important and data scientists typically know how to evaluate ranking models. PMs may know less about this. That is the kind of edge data scientists have.

### Experimentation and testing in job descriptions

Experimentation is not always explicitly mentioned in job descriptions, but it is an important practice. It might fall under the metrics cluster, because sometimes when we do product evaluation, we can split our user base into segments - one segment as a control group. This is essentially a test that just looks and is configured a bit differently.

The reason experimentation might not appear explicitly: look at PM or business analyst job descriptions - do they often mention A/B testing? Not always. But all PMs run experiments. It is simply assumed as a best product practice.

I ran additional analysis on the job descriptions to verify this:

- 73% mention any quality practice (experimentation, metrics, monitoring, evaluation, user research)
- 52% mention metrics, monitoring, or evaluation specifically
- 26% mention experimentation explicitly ("A/B testing", multivariate tests, experiments)
- 0.4% mention specific frameworks by name (5 jobs out of 1,397)

Companies care about quality outcomes (metrics, monitoring, evaluation), not specific methodologies. RICE, lean startup, design thinking - all could be expected from any PM but almost never spelled out in job descriptions.

### Technical experience vs end-to-end product launches

Having an end-to-end product launch is always useful. Deep technical specialization is not a core PM skill, it is more of a niche strength. If we are talking about what is generally more valuable based on the data, broad product skills are more useful than niche technical depth.

### Do recruiters check your portfolio?

Recruiters themselves most likely do not check. Who will actually look is the hiring manager.

When I was hiring people, I did not have time to look in detail. Maybe 5-10 minutes before the interview I would open the resume, look at the portfolio link, and see what is there in general. I would not have time to read details. A case study would have to really interest me for me to want to look at the details.

That is why I invest a lot of attention in the summary - it is the most important part of the case study. I look at the summary to see what is described there, and that is usually it.

Organization plays a very important role. Links to data, to important findings right in the summary can be very helpful.

### What do hiring managers focus on?

As a hiring manager, what I want to see:
1. The case study solves a real problem - what it does, why it exists
2. A clear description so I can open the summary and immediately understand what is going on
3. Signs that the analysis is close to production quality: metrics, evaluation, clear recommendations

The more of these checkboxes I see, the better. Metrics add a plus, experimentation adds a plus, good analysis adds a plus, visuals, demos, presentations add a plus.

Does this mean every personal project must have evaluation or metrics? Of course not. Side projects are side projects. But if a case study solves a real problem and has multiple iterations invested in it, I will be interested in discussing it even without formal metrics.

### Portfolio quality

This is probably the most important part of your application. You need to make sure it is not too big and not too small, that it has all the important information but not too much.

For me the most important thing: the portfolio should describe the case study clearly, the project should solve a specific problem, and there should be a reasonable description so I can open the project and immediately understand what is happening. Everything else adds bonus points: having metrics described, having clear methodology, having good analysis, having visuals, demos, presentations.

### Two audiences for your portfolio

Write your portfolio for two different audiences:

1. The first audience is a peer reviewer (or another student) who has time to check everything and verify all criteria are satisfied. This motivates you to do thorough analysis, clearly and without cutting corners.

2. The second audience is a hiring manager. They have almost no time at all, and you need to convey the maximum amount of information in the shortest time.

You can also imagine this is your take-home case study and the hiring manager will read it. Try to guess what their internal checklist looks like and try to check all the boxes.

### How deeply do interviewers inspect case studies?

If we are talking about a hiring manager - there is no time to check in detail. I open it, look for 1-2 minutes, and that is probably it. In rare cases I might look at the methodology, maybe look at the metrics, check if proper analysis exists at all. I will not read every data point - I just open it, look if it is there.

But for take-home case studies, people will read more carefully. Some hiring managers actually verify the analysis. For take-home assignments, it is better to follow rigorous analytical practices: show your work, have clear methodology ideally.

### Commit history and contribution consistency

I have never in my life looked at commit history. And I do not think anyone will look at this. When I look at a project, I look at the project in its current state.

### End-to-end case studies vs exploratory analyses

The answer is obvious. No additional comments needed.

### Template-based vs original case studies

If someone tells me in an interview "this was a course, I just copied from there" - I immediately lose interest. If someone tells me they had an idea or a problem and they solved it using some approach - that is a huge plus.

Important distinctions:
- If it is a course with step-by-step instructions that you just repeat - everyone will have the same case study with the same analysis. Not much value in that
- If it is a course assignment where the problem is given but the analysis is yours - that is much more valuable
- If it is an original case study that you came up with and built from scratch - that has enormous value

The level of commitment is very different and it shows. When you were really involved in the task, you will have answers to questions because you lived through it, not just copied it.

### Production-level practices in personal projects

Companies do not expect production-level product practices in personal projects. That would be over-engineering - it would look forced. It is very hard to have real production-level problems in personal projects.

Clarity is more important - everything should be clean and understandable, solving your problem. But do not forget about basic best practices. We are not talking about millions of users - just a normal project that solves your specific task.

If you have a personal project that genuinely requires production-level infrastructure, you probably do not need a job - you already have one.

### Metrics and experimentation frameworks

Metrics and experimentation are pretty easy to implement, especially with AI assistants. You need to define success criteria regardless. And once you have metrics, wrapping them in a dashboard is a quick task.

Start with basic product metrics, then conversion funnels, then cohort analyses, then predictive models for user behavior.

### Using AI assistants in your portfolio

For me this is neutral. If you do not use an assistant, you are missing out. But I do not see a reason to specifically mention it.

If you want to be open about it, you can say at the end that the analysis was built using AI-assisted tools and indicate your contribution. If you discuss this with the hiring manager, the conversation might go into how exactly you used the assistant, how you gave instructions, how you made sure the analysis was correct. If your answer is "I gave a prompt and everything worked from the first try" - I will have questions. Because it never works from the first try.

Whether to write about it or not is your call. I see nothing wrong with writing it. I see nothing wrong with not writing it.

### Product analyst vs product manager

For me this is all semantics. I cannot say there is some huge difference. There is supposedly an industry opinion that an analyst is a level below in the sense that an analyst is more of an executor while a PM thinks more holistically. I think this is all semantics.

### PM vs engineer who does product thinking

The line is pretty thin. Most likely, from engineers the expectation is more of a generalist. While PM is probably a more focused role. But in practice, like duck typing in Python - if the methods are the same, there is essentially no difference regardless of what you call it.

### Job description quality and filtering

I did not have a filter for low-quality job descriptions when scraping data. The number of such descriptions is likely not zero. Some job postings exist just for show - to signal to investors that the company is actively hiring. I did not do any filtering for this.

### Technical understanding and analytical skills

Understanding technical systems and data infrastructure is useful for PMs. About 64% of PM roles require some technical knowledge. But if we look purely at core PM skills, the technical component is not always required.

However, at large scale, products become complex. You need to be able to do what the data team does but understand the trade-offs and costs. Typically this means: take the data, use it to inform product decisions, and build a product strategy that works within technical constraints. Such use cases exist especially at scale.

### Market pushing product thinking

Yes, this happens. There are stories where management sends down the order: "we need to show investors that we are product-led, so everyone start doing product thinking immediately."

If you are suddenly told to do product work but there is no real problem that product thinking solves: on one hand, this could be a good opportunity to learn something new. On the other hand, you can say "I think we have many other unsolved problems to focus on." It all depends on the specific situation.

### Project management jobs becoming product management

It would be interesting to verify whether many project management jobs are now relabeled as product management. I might try to run the same analysis but for project managers. Take New York as a representative city and see what is there.

### Analytics skills for data analysts and PMs

From the data: 31.4% of product-led roles mention analytics skills, 49.6% mention strategy skills, and 21.6% mention full-stack product (both). So it is more strategy-focused.

In general, PM is a full-stack role - the data confirms this. But the expectation is not that a PM will proactively do deep technical work. Each role has its specialization. Data analysts should work on analytics, designers on design. But if the need arises, it is fine.

### Top 3 projects for FAANG interviews

For FAANG specifically: they care more about product sense and product design than about case studies. Product sense you just have to practice, and product design you have to study. Pet projects do not help with either of these directly.

There is also product design for senior roles and above. Big companies ask about product strategy and go-to-market at senior levels.

### Entry-level PM positions

You can figure out the answer by analyzing the data. Collect the data, analyze it, draw conclusions, and based on those conclusions create a concrete learning plan.

Write about this - every day share what you learn, do learning in public, building in public. You will grow your network, people will notice you.

### Will PM replace traditional business analyst?

I do not think so completely. The overlap is large and right now there is more hype around product management. But this is temporary. Things will calm down and there will be more understanding of when to use product thinking and when not.

Product management is here to stay. But through the hype cycle, traditional business analysis is still needed and important. There are use cases you can optimize with data analysis, operational processes made with traditional methods because they need to be reliable.

Right now it is like data science 10 years ago - everyone wanted to do it but nobody understood what it was. Now there is understanding. The same will happen with product management.

### Is SaaS dead?

Of course not. Many services provide value that is hard to replicate. Stripe is not going anywhere. You can now vibe-code alternatives for some things, but not for everything.

Some things are becoming more commoditized - if you have a very specific use case and cannot find anything ready-made, you can now build it faster. But SaaS is definitely not dead.

### How to adapt to AI

If you are worried that AI will take your job, study automation tools and automate your own work. The 20 hours you invest in learning this will pay off within a couple of months at most.

For specific first steps: it depends on what you want to learn. If you do not have your own ideas, look at what others are doing, see what resonates, try to repeat it and adapt to your situation.

The key thing: do not fall into dopamine traps. Focus on what interests you personally and do not rush.

### Comparing PM roles: Product Ops, Platform PM, Growth PM

Product Ops is like DevOps - a set of practices about how you ship products efficiently. But there is a role called Product Ops Manager - usually they are the people who organize the platform so that PMs can ship products.

Growth PM and Platform PM could be the people who do the same but for specific areas. This might include running experiments (or not), but overall it is about organizing the process: setting up metrics, making it so that when you define a feature it deploys and monitoring automatically connects, you can collect user feedback and do evaluation based on those logs.

### Learning without formal frameworks

Yes, you can absolutely learn without formal PM frameworks. I even recommend not starting with frameworks. Start with the basics: understanding user problems, defining metrics. And only then start using a framework.

This is better because you understand what happens underneath. RICE is not a bad framework, though I would not use it as my only tool. You can definitely learn without it.
