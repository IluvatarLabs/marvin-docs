# Getting Started with Marvin

Welcome to Marvin. This guide walks you through your first autonomous research run — from a blank project to structured, evidence-backed findings.

If you're new to the product, start with [What is Marvin?](what-is-marvin.md) for a one-page overview, then come back here.

---

## What you'll need

- **A Marvin account.** Sign up and log in.
- **A project.** Every run lives inside a project. You'll create your first one below.
- **A paid plan for autonomous runs.** On the Free plan you can chat with Marvin and look up literature, but autonomous research runs require an Academic, Pro, Team, or Enterprise plan. See [Plans and billing](plans-and-billing.md).

That's it. You don't need to write code, configure tools, or point Marvin at any specific dataset to get started.

---

## Quick start

You'll go from question to results in four steps.

### 1. Create a project

Click **New Project** in the sidebar. Marvin will ask you for three things:

- **A name** — what to call the project.
- **What you're investigating** — your research question, in plain language.
- **(Optional) Where to point Marvin** — datasets, prior work, or context you want Marvin to consider.

Marvin then drafts a plan: it restates your question in its own words, proposes a focus, and lays out the goals it will pursue. Read it over. If something's off, click **Refine with Marvin** and tell it what to change. When you're happy, click **Approve and launch**.

Marvin never starts working autonomously until you approve the plan.

### 2. Start a run

Inside your project, click **Start Marvin** in the top bar. You'll set three things:

- **Iteration count** — how many rounds of investigation Marvin should attempt. Pick any number from 1 to 100, or choose **Until STOP** to let Marvin run until it concludes or you stop it.
- **Compute resources** — a maximum number of CPU cores, and which GPU types Marvin is allowed to use.
- **Run budget** — a dollar cap for the entire run. Marvin stays within it.

Then launch. Marvin takes over from here.

### 3. Monitor the run

The **activity feed** shows Marvin working through your question in real time — searching literature, forming hypotheses, running analyses, and writing up findings. These are stages of work, shown as they happen, so you always know what Marvin is doing and why.

The feed has two views:

- **Live** — the current run, updating as Marvin works.
- **History** — past runs, so you can revisit what Marvin found earlier.

You can step away at any point. Nothing requires your attention while a run is in progress.

### 4. Review your findings

When a run finishes, results appear as **structured findings**, organized by run. Each finding includes:

- **A conclusion** — the answer Marvin reached.
- **The evidence** — the analyses, data, and sources behind that conclusion.
- **A confidence level** — how strongly Marvin stands behind the result, stated in plain terms.

Findings are linked to their sources, so you can trace any conclusion back to what it was built on.

---

## What is a run?

A run is Marvin researching your question autonomously and delivering structured findings.

You give Marvin a question. Marvin reads the relevant literature, forms hypotheses, runs analyses, and reaches conclusions — then hands you the results as structured findings, each tied to its evidence.

It's fully autonomous: set it up, launch it, and walk away. You don't drive Marvin step by step. You approve the plan up front, set your resource and budget limits, and Marvin takes care of the investigation.

---

## Example: your first research question

Say your question is:

> I want to understand the trade-offs between transformer and CNN architectures for time-series forecasting.

Here's what happens after you launch:

1. Marvin breaks the question into sub-questions — accuracy, training cost, data efficiency, latency, and so on.
2. It reads the relevant papers and compares methodologies.
3. It runs analyses to see where findings align and where they conflict.
4. It writes up structured findings: performance differences, compute trade-offs, and practical recommendations.

Each finding points back to the papers and analyses it came from, so you can verify the reasoning and follow up on anything that interests you.

---

## What's next?

- [What is Marvin?](what-is-marvin.md) — a high-level overview of what Marvin does.
- [What Marvin can do](what-marvin-can-do.md) — the full range of questions and tasks Marvin handles.
- [Navigating the UI](navigating-the-ui.md) — a tour of projects, runs, and the activity feed.
- [How-to guides](how-to-guides.md) — step-by-step recipes for common workflows.
- [Plans and billing](plans-and-billing.md) — picking the right plan and managing your run budget.

Still stuck? See the [FAQ](faq.md) or [contact us](contact.md).
