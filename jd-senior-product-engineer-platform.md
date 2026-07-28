# Senior Product Engineer — Platform

## About BlackHyve

We're building the system contractors use to run a profitable business. Construction is a $2 trillion industry, and the best contractors aren't 10% more profitable than average. They're 3 to 11x more profitable. The whole difference comes down to one discipline: tracking production against the bid, every day. The best operators do it religiously. Almost nobody else can, because the tools are spreadsheets, PDFs, and software built in the 1990s.

BlackHyve closes that gap. Pushing plans down to the field is the easy part, and everyone does it. The hard part is getting the truth back up: making it effortless for crews to capture what's actually happening on site, then turning that into something the office can act on before margin quietly disappears. The money's already in the bid; our customers are losing it every day and can't see where. We make the leak visible.

We're a small team of engineers, sales, and forward-deployed folks who all work close to the product and the customer. Our CTO is deep in product and AI; our CEO spent two decades building construction companies. Our pipeline is bigger than we can serve today, and one of the biggest reasons is integration. Customers won't move until BlackHyve talks to the systems they already run. We're hiring a Senior Product Engineer focused on Platform to own that.

## The role

You'll own how BlackHyve connects to the rest of the construction software world: the project-management ERPs and accounting systems our customers already live in (Foundation, Trimble Vista, Trimble Spectrum, Sage 300, COINS), plus platforms like Procore and Autodesk Construction Cloud. Your job is to get their data in and out of BlackHyve reliably, and to make connecting dead simple.

"Platform" is a focus, not a separate track. You're a Product Engineer. You'll ship customer-facing product alongside the rest of the team when priorities shift, and we'll pull you onto whatever's driving revenue that week. But integrations are your center of gravity, and over time, your subsystem to own.

You're not starting from zero. We're actively building Trimble Vista, Spectrum, and Procore connections right now, and there's an early connector pattern and a one-off Autodesk integration already in production. You'll plug into that, ramp fast, and start shipping. As you find your feet, you'll take over the integration surface: decide what to keep, what to rebuild, and set the architecture every future integration is built on.

This is a partner- and customer-facing role. You'll work with Procore's, Trimble's, and Autodesk's developer programs to get access and escalate when their APIs misbehave. You'll sit with a customer's IT or ops people to map their actual Sage instance and their cost-code structure — integrations are never truly generic, and someone has to understand what the fields mean. And when a deal hinges on "can you integrate with X?", you're the technical voice on the call. You'll still talk to customers and sit in on sales calls like everyone here does; for you, a lot of those conversations are about the seams between systems.

## What you'd ship in your first 3–6 months

We can't predict exactly which integration will be hottest in three months, but here's a representative sample of the work:

- **Ship integrations in your first weeks, not your first quarter.** We're actively building Trimble Vista, Spectrum, and Procore connections. You'll plug into that work, get up to speed fast, and start shipping partner integrations end-to-end: auth, sync, data mapping, and the failure handling that keeps them running when a partner's API has a bad day.
- **Take over the integration pattern and make it right.** We have an early connector pattern and an Autodesk integration live for one customer. As you ramp, you'll inherit that surface, decide what to keep and what to rebuild, and set the architecture every future integration is built on: sync, idempotency, retries, reconciliation, and observability.
- **Get messy ERP and accounting data flowing reliably.** With Foundation, Sage 300, COINS and the like, that means mapping their data models onto ours, working directly with customer IT to handle the real-world configuration, and keeping the pipes running in production.
- **Make connecting dead simple.** Turn one-off integrations into a repeatable, productized layer. This is the precursor to a possible BlackHyve integrations marketplace, and you'd have a defining hand in what it becomes.

## What we're looking for

- **Deep backend engineering.** You've built and operated APIs and data-sync systems in production. You'll work primarily in Laravel/PHP, and deep backend experience in any stack transfers, so we'll get you fluent fast. Your home needs to be the backend, though, not somewhere you're hoping to land for the first time here.
- **You build integrations that don't fall over.** You think in idempotency, retries, rate limits, partial failure, and reconciliation. You can map a foreign, badly-documented data model onto your own, reason about auth flows (OAuth2, API keys, SAML), and reverse-engineer behavior when the docs are wrong or absent.
- **A track record of shipping substantial product end-to-end.** Not "I led a team that shipped." You wrote the code, you talked to the people on the other side of the integration, you operated it in production.
- **Comfort in a small team.** We hire at this level for people who manage themselves and work shoulder-to-shoulder with other senior people. You figure out what needs doing without being asked, and you ship well inside a small group where collaboration is constant.
- **Cross-functional instinct.** Comfortable with a partner's dev-rel team, a customer's IT person, a sales call, and a code review, sometimes in the same day.
- **AI-native, or wanting to become AI-native fast.** You don't need to be a power user on day one, but you need to want to operate this way and have opinions about how AI changes how integration work gets built.
- **Construction or ERP-accounting familiarity is a strong plus, not a requirement.** Half the battle with Foundation, Vista, and Sage is understanding what the data *means*: cost codes, commitments, job cost, WIP. If you already know that world, great. If not, we can teach it faster than we can teach someone to build a bulletproof sync engine.
- **Taste.** You can tell the difference between "ships fast" and "ships sloppy."

## What makes this different

- **Real industry, real problems.** Construction is unsexy, which is why nobody's built this yet. The companies we sell to lose hundreds of thousands of dollars per project to problems we can actually solve. The work matters.
- **Integrations are a product surface, not a backlog.** Here, integration work unblocks the pipeline and points at a marketplace. You own it; you don't babysit it.
- **Small team, high autonomy, low theater.** No process layer cake, no two-week sprint ceremonies, no waiting on three approvals to ship. You'll work close to the CTO on technical direction and close to the CEO on customer interactions. Decisions get made by the people doing the work.
- **AI-pilled.** We treat AI as an amplifier, not a checkbox. We're rebuilding workflows around what's possible when an engineer + AI agents can ship what used to take a team of five.
- **Stage.** Past zero, with paying customers, real revenue, and growing pipeline, but still early enough that you'll have a defining hand in what BlackHyve becomes.
- **Ship daily.** We move fast and ship quality code to production every day.

## Career path

This role enters at Senior, but the ceiling is explicit: integrations are yours to own, and owning a subsystem end-to-end is Lead-level scope. On a team this size you'll stretch into that work quickly — setting the architecture, absorbing the rough edges, becoming the person the rest of the team relies on when they touch integrations. Promotion happens when you consistently operate at that scope, not after a calendar fires.

## Logistics

- **Work model:** Fully remote. We don't have an office. We get together in person at least once a year for an on-site.
- **Benefits:** Health insurance, paid time off, and an equipment stipend.
- **Compensation:** $95,000–$130,000 base salary in the US. Adjusted by location: US and major Canadian metros (Toronto, Vancouver, Montreal) at 100%; other Canada, Western Europe at 85%; rest of world at 60%. Our cash bands sit ~25% below comparable AI-pilled SaaS shops — we're transparent about it, we close the gap as we grow, and equity is part of the total-package conversation.
- **Equity:** There's an equity component at this stage of the company — specifics are part of the offer conversation, and we're happy to talk about it early.

## How to apply

Send your application to **apply@blackhyve.com** with:

- A cover letter.
- Two or three references we can talk to.
- Links to two or three things you've shipped that you're proud of, with a sentence on why each matters. If one of them is an integration or data-sync system you built, we especially want to see it.

## How we hire

We respect senior candidates' time.

1. **Application review.** We read what you sent: the cover letter, the ship links, the references. If there's a fit, we'll reach out within a week.
2. **Conversation with the CTO.** ~45 minutes. We dig into your work, your motivations, and your read on the problem space.
3. **Deep-dive on past work.** You walk us through one or two things you've shipped: the decisions, the tradeoffs, what you'd do differently.
4. **Join a working session.** Sit in on one of our team huddles and/or a shaping session and work through a real problem with us. We're not testing your code; we're seeing how you think about a problem.
5. **Conversation with the CEO.** ~45 minutes. Customer empathy, business fit, mutual gut-check.
6. **References and offer.** We talk to two or three of the people you sent us. If we're a fit, we make an offer.

Usually 2–3 weeks end-to-end.
