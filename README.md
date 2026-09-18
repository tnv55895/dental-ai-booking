# ai appointment setter for dentists: booking after-hours consults and recalls without adding front-desk headcount

A new patient calls at 11:47 on a Tuesday about a cracked molar. Your front desk is checking out a family, the hygienist needs a schedule swap, and the phone rolls to voicemail. That patient is in pain, they will not wait, and the practice three lights down the road answers on the second ring.

That's the scenario everyone typing "ai appointment setter for dentists" is trying to fix. But the keyword hides two very different products: voice agents that pick up the phone and talk to patients, and text-channel setters that work through SMS, website chat and DMs. They solve different halves of the problem, cost different amounts, and only one of them is CloseBot. Picking the wrong category is the expensive mistake here, more expensive than picking the wrong vendor inside a category.

## Where dental demand actually goes missing

Most practices track phone volume, not channel-level leakage. The published estimates on missed calls are worth looking at, with the caveat that many come from companies selling the fix.

Dentina's own research page states that the average practice misses 32% to 38% of incoming calls, and puts each missed new-patient call at $250 to $350 in first-visit revenue. Peerlogic's breakdown of call data claims that of every 100 new-patient calls, only 68% get answered, and of the answered ones only 42% turn into appointments. Treat those as directional. The useful move is to pull your own numbers: how many calls go unanswered after 5 pm, how many web forms sit untouched until the next business day, how many Instagram DMs get a reply at all.

What those gaps have in common is timing. Patients research at night, message on weekends, and fill in forms during lunch. Inquiries sent to five practices at 8 pm tend to go with whoever replies first, and that is rarely the office with the best Google rating.

## The two products hiding behind one keyword

A voice AI receptionist answers the ringing line. It handles triage ("swelling," "knocked-out tooth," "severe pain"), books into the practice management system, and it is priced per location by vendors built only for dentistry. Review sites list Dentina AI at $299 to $399 per location per month billed annually, while Echo Booking publishes a flat fee starting at $499. That category is where you go if the phone is your leak.

A text-first AI setter works the other channels: SMS, website chat, WhatsApp, Facebook Messenger, Instagram DM and email. It qualifies the inquiry, answers routine questions, offers calendar slots and books the appointment without a human stepping in. This is what CloseBot does, and the company is explicit that phone calls are not part of it.

| Where the inquiry arrives | Voice AI receptionist | Text-first AI setter (CloseBot) |
| --- | --- | --- |
| Inbound phone call | Answers and books | Not handled |
| SMS / missed-call text-back | Sometimes | Yes |
| Website chat widget | Sometimes | Yes |
| Instagram / Facebook DM | Rarely | Yes |
| Email and web forms | Rarely | Yes |
| Emergency triage by keyword | Yes | Routing by urgency logic, escalation depends on your build |
| Typical pricing basis | Per location, per month | Per month plus message usage |

For a practice whose leads come through ads, Google Business messages and social, the text channel is where the money is leaking. For one that lives on the phone, a text-only setter will feel like it's solving a problem you don't have.

## What CloseBot is, in dental terms

CloseBot is a conversational AI agent builder for lead qualification, follow-up and appointment booking across text channels, with native integrations into GoHighLevel and HubSpot, plus custom CRM connections. You build agents visually in what the company calls Job Flows: instead of one long prompt, you drag modular objectives and conversation steps into a sequence, add a booking node connected to a calendar, and let the agent run.

The company reports over 1 million booked appointments across industries, 150,000+ daily messages, and more than 1,000 agencies on the platform. Those are vendor figures, not audited ones. The relevant part for a dental office is the workflow model: it can branch. A new-patient inquiry asking about implants can follow a different path than an existing patient asking about a hygiene recall, and each path can collect different fields before booking.

> CloseBot handles SMS, website chat and email. It does not answer phone calls. If your missed-call problem is literal ringing, pair this with a voice agent or an answering service.

[👉 create a free CloseBot account and test it on your own inquiries](https://app.closebot.com/a?fpr=li87)

## Your Job Flows, and where the patient actually gets booked

Building a dental workflow in CloseBot looks roughly like this:

1. **Trigger.** A website form submission, an inbound SMS, an Instagram DM or a chat widget message starts the flow.
2. **Persona.** You define the tone. A family practice in a small town and a multi-location implant group should not sound the same.
3. **Qualification.** The agent asks the questions your front desk would: new or existing patient, which treatment (cleaning, exam, emergency, implant consult, ortho), which location, insurance, preferred times.
4. **Booking node.** Drag in the booking action and connect the calendar, either within a connected source by name or by calendar ID.
5. **CRM write-back.** Qualified details land on the contact record, tags fire, and your existing automations pick it up.
6. **Quiet hours.** Reply windows can be set per channel so follow-ups don't fire at 2 am and read like a robot.

Two practical notes. First, the calendar connection is where most builds succeed or fail; the docs have a troubleshooting article specifically because agents that can't see accurate availability stop booking. Second, unfamiliar patient questions get flagged in Smart FAQ rather than answered with a guess. You fill in the answer once and it sticks.

For practices on Dentrix, Eaglesoft or Open Dental rather than HighLevel, CloseBot does not ship a native PMS connector. Its healthcare page is direct about the workaround: you can build custom tools that let an agent book to any calendar with an API. That's real capability, but it's a build, not a toggle. Budget for it or hire a certified partner before promising your office manager anything.

## The HIPAA question, answered plainly

This is where dental buyers need to read the fine print rather than the homepage badge.

HIPAA compliance sits on the **Growth** plan only. It includes signed business associate agreements, quarterly audits, priority uptime and priority support, and it's custom-quoted rather than self-serve. If your agent handles patient information, that's the plan tier you need to be asking about.

A few specifics worth knowing before that sales call:

- CloseBot routes HIPAA accounts through Anthropic, and its help center states it does not allow "bring your own key" because of the security questions that raises.
- The company states it does not train AI models on your data.
- Support staff with account access are background-checked and US-based, per its healthcare page, and the trust center publishes audit details.
- The free plan is not a compliance answer. It's a testing environment.

If you're running the agent on general inquiry qualification with no clinical details, and your legal review agrees, a lower tier may work. Most dental conversations end up touching patient information quickly, so a practice that wants written coverage should be talking to sales about Growth rather than self-serving Core.

## Plans and pricing, all of them

CloseBot's pricing page currently presents three plans: Free, Core and Growth, with Core available on a Business track or an Agency track depending on whether you're using agents yourself or reselling them. The pricing page also shows a separate agency section for client re-billing.

| Plan | Who it suits | What's included | Price | Billing | Get it |
| --- | --- | --- | --- | --- | --- |
| **Free** | Testing agent quality on real inquiries before spending | 1 agent, 1 user seat, 100 messages/month, 1 MB knowledge storage, unlimited account connections; overage billed at $0.08 per message per the help center | $0 | Free forever under the message cap | [ start free, no card required](https://app.closebot.com/a?fpr=li87) |
| **Core (Business track)** | A practice or clinic group running its own agents | Message ceiling scalable from 500 up past 100K with message costs included in the base price, extra seats at $5 each, add-on storage, human support, 50+ extra templates on annual billing | $64/month; $53/month billed annually as $640/year | Month to month or annual, 7-day trial | [ check the current Core pricing](https://app.closebot.com/a?fpr=li87) |
| **Core (Agency track)** | Agencies building for dental clients | Same builder plus re-billing of all costs at your own markup, white-label client portal, 15+ templates, added agents for additional niches | From $64/month | Month to month or annual | [ see the agency-track setup](https://app.closebot.com/a?fpr=li87) |
| **Agency** | Agencies selling AI setters to multiple practices | Unlimited agents across unlimited sources, $0.012 per message billed to you and re-billable to clients, client wallets with Stripe payouts, markup control, white-label portal | $397/month, or roughly $331/month on annual billing | Month to month or annual | [ start the agency trial](https://app.closebot.com/a?fpr=li87) |
| **Growth** | Practices that need compliance paperwork on file | HIPAA compliance with signed BAAs, quarterly audits, 99.99% priority uptime, priority support, 50+ templates, custom volume | Custom quote | Custom | [ ask sales about the Growth plan](https://app.closebot.com/a?fpr=li87) |

Two details that change the math. Usage costs are separate from the base price in ways that matter: on business tiers, message costs are included up to your ceiling, and going over triggers a 2x overage rate drawn from a wallet. On the agency side, $0.012 per message is your cost and your markup is your margin, storage runs $0.006 per MB per day, and extra seats are $5 each. Annual billing saves roughly 17% and unlocks the 50+ template library, which the pricing page notes is otherwise unavailable on monthly plans.

One inconsistency to be aware of when you compare: the help center still lists business tiers by Job Flow count, $64 for 1 flow, $197 for 3, $297 for 10 and $397 for unlimited, while the pricing page now presents Core with a message-volume slider. Ask support which structure applies to your account before you budget from either page.

Paid plans come with a 7-day trial, there are no refunds, and plans run month to month with no contract. The free plan stays free as long as you stay under 100 messages.

## Which plan a dental buyer should actually pick

**Solo practice or single location.** Start on Free and run it against real inquiries, not test messages. You'll get a feel for whether the persona sounds like your office and whether the booking logic survives contact with real patients. If it works, Core on annual billing is the sensible landing spot, and the message ceiling depends on how much of your inbound is text-based.

**Multi-location group.** Core with a higher message ceiling, and one agent per niche if you're running different brands. Watch storage: 1 MB is roughly 1,000 pages of text, which is plenty for FAQs and policies, but multi-location groups often want more.

**Agency serving dental clients.** The Agency plan exists to make re-billing the default. CloseBot's own polling of agencies puts average billing at $500 per client per month, and the pitch is that the AI line item is where the margin comes from. Worth noting the same page admits agencies charge anywhere from $100 to $10,000+ per client, so the $500 is an average, not a benchmark to promise anyone.

**Compliance-first practices.** Growth, and start the paperwork conversation early. If your front desk or office manager has already told you that no patient data goes into a tool without a BAA, this is not a negotiation.

## Where it won't help, and who should look elsewhere

CloseBot does not answer the phone. If a practice's leak is voicemail, or patients who hang up before anyone picks up, a text-first setter doesn't close that gap. Pairing a voice agent with CloseBot is a legitimate architecture, and some builders do exactly that, but you're now buying two products.

There's a learning curve, and it's the most consistent criticism. G2's pros-and-cons summary flags setup complexity and trial-and-error, and posts in the GoHighLevel community include people who bounced off the builder on first contact. You can absorb that by hiring a certified partner, or by paying someone on staff to spend an afternoon learning the Job Flow builder. Either way, don't assume it's a 15-minute install.

And for practices that specifically want clinical-grade scheduling logic inside Dentrix, PMS write-back out of the box, insurance pre-checks during the call, or hands-off emergency escalation, a dental-native voice platform will usually be the better first purchase. CloseBot's strength is qualification and booking across text channels plus CRM write-back, and that's the job it should be judged on.

> Anything that touches patient scheduling on a large volume should be tested with real patients, real calendars and a clear rollback plan before you route every inquiry to it.

## How to tell whether it paid for itself

Set a baseline before you turn anything on, because "it feels like it's working" is not a dental metric. The numbers worth tracking:

- Time from inquiry to first response, split by channel and by hour of day
- After-hours and weekend appointments booked
- Recovered cancellations and recall appointments scheduled
- New-patient consults booked from web chat and social DMs
- No-show rate on AI-booked appointments versus front-desk-booked ones

If a practice is losing 30% of its calls and each first visit is worth a few hundred dollars, the arithmetic gets uncomfortable fast. But run it on your own data. The missed-call percentages floating around the dental marketing world are mostly published by the companies selling missed-call software, and your numbers will look like your practice, not like theirs.

If you want to see the builder before deciding anything, [👉 try CloseBot free for 7 days on any paid plan](https://app.closebot.com/a?fpr=li87) and point it at a form you already ignore after 5 pm. That's a more useful test than any demo.
