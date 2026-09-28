# Plans and Billing

Marvin keeps billing simple and transparent. You pay a monthly subscription that covers your autonomous research runs, and you can optionally add wallet credits for any usage beyond that. This article explains how it all fits together.

If you're new here, [getting started](getting-started.md) walks you through your first project, and [what is Marvin](what-is-marvin.md) explains what Marvin actually does.

---

## How billing works

Marvin uses a two-part model: a **subscription** plus an optional **wallet**.

Your subscription includes a **monthly research capacity** — a pool of usage that covers your autonomous runs each month. As long as you stay within that capacity, everything you run is included in your plan.

If you go beyond the monthly capacity, you have two options:

- **Use wallet credits** you've purchased ahead of time, or
- **Pay for the overage** on the card we have on file.

Overage is billed at **provider cost with zero markup**. We make our money on the subscription, not on your overruns.

This keeps your costs predictable: the subscription handles the bulk of your work, and the wallet or overage only kicks in when you push past it.

---

## Understanding your usage bar

The sidebar shows your research usage as a simple **percentage bar**:

> 42% used this month — resets July 1

That's it. You see how much of your monthly capacity you've used and when it resets. We deliberately don't surface raw token counts, per-run costs, or credit-unit math — the percentage is what matters for deciding whether to keep running or add credits.

For projects that run experiments, you'll also see a separate **compute bar** (more on that under [Compute](#compute)).

See [navigating the UI](navigating-the-ui.md) for a full tour of the sidebar and workspace.

---

## Spending caps

You can set a **spending cap** to bound your maximum monthly spend. A cap is a hard ceiling on how much you'll be charged beyond your subscription in a given month.

When you hit the cap, your runs **pause** — they don't fail, and they don't silently keep charging you. You'll be presented with three options:

- **Increase the cap** — raise the ceiling and continue.
- **Upgrade your plan** — move to a tier with more monthly capacity.
- **Add credits** — purchase wallet credits to fund the remaining work.

Caps give you a guaranteed "nothing surprises me" ceiling, which is especially useful for teams running shared budgets.

---

## Compute

Some Marvin projects dispatch real CPU and GPU jobs to run experiments. Each paid plan includes a **monthly compute allotment** for those jobs.

Compute is tracked separately from your research usage — it gets its own bar in the sidebar, so you can tell at a glance how much of your monthly compute you've used.

There is **no card-on-file overage for compute**. If you want to run more compute-heavy experiments than your plan includes, you buy credits explicitly. There are no surprise mid-run charges — compute only runs when you've funded it.

For an overview of what Marvin can run, see [what Marvin can do](what-marvin-can-do.md).

---

<a name="plans"></a>

## Plans

Marvin offers four tiers — Free, Academic, Pro, and Team — plus a custom Enterprise track. Here's how they compare.

### Free tier

The Free tier lets you explore Marvin at no cost.

- **No cost**, open signup
- **1 seat**
- Includes **chat** and **literature lookup**
- Does **not** include autonomous research runs

Free is great for trying the conversation and literature-search features and evaluating fit before committing. To run actual autonomous research, move to Academic or another paid plan.

### Academic tier

The Academic tier is our **real research tier** for students and academics — not just a trial.

- **$19/month**
- Requires an **academic email address** (for example `.edu`, `.ac.uk`, or a supported university domain)
- **Autonomous runs enabled**, with a reduced monthly capacity compared to Pro

If you have a qualifying academic email address, Academic gives you the full autonomous-research experience for $19/month. The monthly capacity is smaller than Pro, but the capability is identical — perfect for coursework, theses, and early-stage research.

### Pro and Team plans

Pro and Team are the standard paid tiers for individuals and growing teams.

| Plan | Seats | What you get |
|------|-------|--------------|
| **Pro** | 1–3 | Full autonomous runs, standard monthly capacity, wallet top-ups, compute allotment, spending caps |
| **Team** | 5–25 | Everything in Pro, larger monthly capacity, more seats, shared workspace and billing |

A few notes:

- **Pro scales 1 to 3 seats.**
- **Team starts at 5 seats** and scales up to 25. There is no 4-seat plan — if you need 4 concurrent seats, move to Team at 5.
- **Seats are concurrent projects, not people.** See [Seats](#seats) below.

### Enterprise and BYOK

Enterprise is for organizations that need custom terms, scale, or control.

- **Custom contracted seat counts** — no minimum, no maximum. We size the plan to your team.
- **Negotiated pricing** tailored to your volume and commitment.
- **Dedicated support and SLA**.
- **Bring Your Own Keys (BYOK)** — your organization provides its own LLM API keys and pays the provider directly. With BYOK, your usage flows through keys you control and bill for, on top of whatever contract we agree for the Marvin platform itself.

Enterprise is the right call when you need volume pricing, contractual SLAs, security reviews, procurement-friendly billing, or want to route LLM spend through your own provider accounts.

For everything Marvin can do across tiers, see [features](features.md).

---

<a name="seats"></a>

## Seats

A **seat** is one **concurrently running research project** — not one human user.

- The number of seats on your plan determines **how many projects can run at the same time**.
- The **total number of projects** on your account is **unlimited**. Create as many as you like.
- **Concurrency is what's metered.** A paused or completed project doesn't consume a seat.

This means a single researcher can juggle dozens of projects over time on a one-seat plan, as long as only one runs at a time. Teams that need parallel research across multiple projects at once add more seats.

For practical examples of running and queueing projects, see [how-to guides](how-to-guides.md).

---

## Adding credits (top-ups)

Wallet credits let you fund usage beyond your monthly capacity without hitting your card for overage.

**To add credits:**

1. Click the **account indicator** (your name and plan badge) in the sidebar, or the usage bar.
2. Pick the amount you want.
3. Confirm payment.

A few things worth knowing:

- **Credits never expire.** Buy them once and they stay until you use them.
- **Credits are drawn down first**, before any overage is charged to your card. Think of the wallet as a prepaid buffer that shields your card.
- **Prepay and postpay are both available.** Postpay — a card on file, invoiced monthly for any overage — is the self-serve default. Prepay is available for teams that prefer to fund the wallet up front, which is often friendlier for procurement.

Credits are shared across the seats on your account, so a team's wallet funds any member's runs.

---

## Need help choosing?

If you're unsure which tier fits — say, you're a lab deciding between Team and Enterprise, or a researcher wondering whether Academic's capacity is enough — we're happy to talk it through.

See [contact & support](contact.md) for how to reach us, and check the [FAQ](faq.md) for quick answers to common billing questions.
