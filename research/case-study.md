# Case Study: How Real Businesses Build Sales Funnels
## Research Project — Webinar Funnel from Zero | 100Hires Portfolio

> This case study is structured intentionally as a funnel itself.
> The sources move from theory → real cases → practitioners → B2B specific → build.
> Each layer narrows the focus until we arrive at something actionable for 100Hires.

---

## The Funnel of This Research

```
╔══════════════════════════════════════════════════════════════════╗
║         AWARENESS — What is a sales funnel?                      ║
║   YouTube: Gillian Perkins · Jason Whaling · MNTN · Udemy        ║
╚══════════════════════════════════════════════════════════════════╝
                              ↓ narrows
  ╔════════════════════════════════════════════════════════════╗
  ║       INTEREST — How do funnels actually work?             ║
  ║   OptimizePress (Apple, Amazon, Sephora, Lululemon cases)  ║
  ╚════════════════════════════════════════════════════════════╝
                              ↓ narrows
    ╔══════════════════════════════════════════════════════╗
    ║    CONSIDERATION — Who is building these?            ║
    ║   Fiverr practitioners: Shazeb · Nayem · Blessed     ║
    ╚══════════════════════════════════════════════════════╝
                              ↓ narrows
      ╔════════════════════════════════════════════════╗
      ║   INTENT — How does B2B specifically work?     ║
      ║   Belkins.io — 6 stage B2B funnel + benchmarks ║
      ╚════════════════════════════════════════════════╝
                              ↓ narrows
        ╔══════════════════════════════════════════╗
        ║   ACTION — How do I actually build this? ║
        ║   Alex Hormozi framework + n8n workflow  ║
        ╚══════════════════════════════════════════╝
                              ↓
          ╔════════════════════════════════════╗
          ║   OUTPUT: Working funnel for       ║
          ║   100Hires built in n8n            ║
          ╚════════════════════════════════════╝
```

---

## Stage 1 — Awareness: What Is a Sales Funnel?
### Sources: Udemy Blog, MNTN, Gillian Perkins (YouTube), Jason Whaling (YouTube)

The Udemy blog gives the clearest foundational definition. A sales funnel is not a single event — it's the full journey from a stranger first hearing about you to becoming a repeat customer. Udemy breaks it into distinct roles:

- **Lead** — anyone who becomes aware of you
- **Prospect** — a lead who has shown interest and is qualified to buy
- **Customer** — someone who purchased
- **Repeat customer / loyal fan** — someone who buys again or refers others

The key insight from Udemy that shapes this entire research: **you have two levers, not one.** Most people focus on getting more leads. But the smarter move is increasing the percentage of people who move from each stage to the next. Doubling your conversion rate at each stage is worth more than doubling your lead volume.

**Udemy's funnel stages:**
1. Awareness → Education → Evaluation → Engagement → Commitment → Purchase → Loyal Fan

**MNTN's 5-stage model** (from a real advertising platform) adds a stat worth noting: referred customers convert at 3-5x higher rates than other channels. This means the loyalty stage isn't the end of the funnel — it's the beginning of the next one.

**Gillian Perkins (YouTube)** provides the practical implementation: you can build a working funnel using MailerLite for free. Checkout page → email opt-in → sales page → email campaign → webinar. The webinar is optional but powerful.

**Jason Whaling (YouTube, 3hr crash course)** goes deeper with Systeme.io. His most valuable section starts at 2:36:42 — email automation — which maps directly to the n8n workflow documented in this repo.

**Key takeaway from Stage 1:** A funnel is a system, not a page. Every stage requires a different type of content and a different goal. The mistake most businesses make is treating their homepage as a funnel when it's actually just a brochure.

---

## Stage 2 — Interest: How Do Real Businesses Apply This?
### Source: OptimizePress Blog

OptimizePress builds funnel software for WordPress — they've seen thousands of funnels in production. Their article uses four real company examples to show how the funnel works at scale:

**Apple — Awareness Stage**
Apple doesn't run standard ads. They use product launches as global media events — news coverage, social mentions, cultural placement in films and TV shows. Every iPhone launch is awareness at scale, engineered to feel organic. The lesson for 100Hires: a single well-executed webinar can generate the same effect at a smaller scale if the content is genuinely valuable and shareable.

**Amazon — Interest Stage**
Amazon converts interest to consideration using personalized recommendations and "Frequently Bought Together." They show you what's relevant to you specifically, not a generic catalog. For a webinar funnel, this maps to segmented email sequences — showing different content to HR managers vs. founders vs. recruiting agencies after they register.

**Sephora — Desire Stage**
Sephora built a mobile app that lets customers virtually try on products before buying, eliminating the biggest friction point (will this look right on me?). For a B2B SaaS webinar, the equivalent is a live product demo inside the webinar — letting prospects "try" the product before they're asked to pay.

**Lululemon — Loyalty Stage**
The Sweat Collective loyalty program gives fitness professionals a 25% discount and community access in exchange for referrals and feedback. This turns customers into a sales force. For 100Hires, this could be a "power user" program — give your best customers early access to features in exchange for case studies and referrals.

**Key takeaway from Stage 2:** The best funnels are not about selling. They're about removing obstacles at each stage so the customer can move forward naturally. Apple removes the discovery obstacle. Amazon removes the relevance obstacle. Sephora removes the confidence obstacle. Lululemon removes the retention obstacle.

---

## Stage 3 — Consideration: Who Is Actually Building These Day-to-Day?
### Sources: Shazeb Qamar, Nayem Khan, Blessed Afolayan (LinkedIn)

The Fiverr practitioners give a ground-level view of funnel building — what actually gets built for real clients with real budgets.

**Shazeb Qamar** builds funnels for coaches, consultants, and small businesses. His most useful contribution is a warning list: the mistakes that kill funnels before they start. Over-complicating the funnel. Ignoring mobile. Neglecting analytics. Being pushy. Forgetting personalization. Every one of these is a trap for a first-time funnel builder.

His core principle: **keep it simple.** A 5-step funnel that works beats a 15-step funnel that confuses people. For 100Hires — whose prospects are busy founders and HR managers — simplicity is not a compromise, it's a strategy.

**Nayem Khan** treats every interaction as a micro-funnel. His insight: the query stage (first response to an inquiry) is where most conversions are won or lost. Speed and personalization matter more than price. A prospect who gets a personalized reply in 2 minutes is far more likely to convert than one who waits 2 days for a generic response. This maps directly to the n8n automation in this repo — the instant confirmation email sent within seconds of webinar registration is our "query stage."

**Blessed Afolayan** demonstrates funnel stacking — using multiple channels to feed into and reinforce the same funnel. LinkedIn content builds authority → drives traffic to a registration page → email sequence nurtures → retargeting ads recover the fence-sitters. Each channel does one job. Together they cover the full funnel. This is the exact multi-layer approach used in the funnel map documented in `/research/other/funnel-map.md`.

**Key takeaway from Stage 3:** Funnels are not a one-channel play. The practitioners who get results run awareness, nurture, and retargeting simultaneously — each layer catching the people who fell out of the previous one.

---

## Stage 4 — Intent: How Does B2B Specifically Work?
### Source: Belkins.io Blog

Belkins is a B2B lead generation agency. Their blog post on B2B sales funnels is the most valuable source in this research because it's the only one written specifically for B2B SaaS — not ecommerce, not coaches, not info products.

**Three things that make B2B funnels fundamentally different from B2C:**

1. **Longer sales cycles** — B2B averages 2 months to close. A webinar is not a one-shot close; it's a trust-building event that moves prospects forward.

2. **Multiple decision-makers** — 6-10 people involved in a typical B2B purchase. The webinar needs to equip the champion (the person who attended) to sell internally to blockers and influencers who weren't in the room.

3. **Non-linear buying journey** — B2B buyers research, compare, and evaluate simultaneously. They're not moving neatly from stage to stage; they're doing all of it at once. This is why the post-webinar sequence needs to handle objections, provide comparisons, and offer demos — not just follow up on the offer.

**Belkins' 6-stage B2B funnel:**
Awareness → Interest → Consideration → Intent → Evaluation → Purchase

The key addition compared to B2C models is the **Evaluation stage** — where buyers have all the information and just need a final nudge. This is where urgency (pricing deadline), ROI calculators, and customer testimonials do the most work.

**Belkins' benchmark:** A good B2B funnel conversion rate is 3-5%. This means for every 100 leads who enter the funnel, 3-5 become customers. For a webinar, this translates to: if 100 people register and 35 attend, and 3-5% of registrants convert — that's 3-5 new customers per webinar. At 100Hires' pricing of $2,388/year, one webinar with 100 registrants could generate $7,164-$11,940 in ARR.

**Key takeaway from Stage 4:** B2B funnels need to be built for a longer cycle, multiple stakeholders, and non-linear behavior. The webinar is the Intent-stage tool — used when buyers are actively comparing vendors and need a reason to choose you.

---

## Stage 5 — Action: How Do I Build This?
### Source: Alex Hormozi Framework + My n8n Workflow

Everything from the previous four stages feeds into the build. The Hormozi framework provides the structure. The n8n workflow (documented in `/research/other/my-n8n-workflow.md`) provides the automation.

**Hormozi's core principle applied to 100Hires:**
"Give the WHAT for free. Sell the HOW."

The webinar teaches *what* the best hiring systems look like. 100Hires sells *how* to implement them.


---

## What I Learned

- **Simplicity converts.** Every practitioner who showed real results — Shazeb, Nayem, Melissa Kwan, Hormozi — emphasized one thing: remove friction at every step. A complicated funnel is a leaky funnel.

- **Speed is a conversion lever.** The fastest response wins — in B2B, the vendor who responds first gets the meeting. In a webinar funnel, the confirmation email sent in seconds beats the one sent in minutes.

- **B2B funnels need an evaluation stage.** B2C funnels move fast. B2B moves slow. The post-webinar sequence needs to run for 5 days minimum, handle objections, provide proof, and create urgency — not just follow up once.

- **Automation makes personalization scalable.** The n8n workflow I built handles what a sales team of 3 would normally do — instant confirmation, timed reminders, attendance tracking, segmented follow-up, and lifecycle nurturing — automatically and at zero marginal cost per lead.

- **The funnel is never finished.** Every source — Belkins, Udemy, OptimizePress — emphasized measurement and iteration. The first webinar gives you data. The second webinar is where you actually start converting.

---

*Built by Prashanth | April 2026*
*Part of 100Hires Portfolio Project 
