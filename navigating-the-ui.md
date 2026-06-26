# Navigating the Marvin interface

Marvin is designed around a single principle: you set the direction, Marvin does the research. This article walks you through every part of the interface so you know exactly where things live and what you can do at each step.

If you're brand new, start with [getting started](getting-started.md) and [what is Marvin](what-is-marvin.md). To see what Marvin can actually investigate, read [what Marvin can do](what-marvin-can-do.md).

## The layout at a glance

The Marvin workspace is divided into three regions:

- **The sidebar (left)** is your home base for jumping between projects, checking system status, and managing your account and usage.
- **The top bar (center)** carries the project you're in, the button to start or stop a run, and the Time Machine control for moving through your project's history.
- **The main workspace** changes depending on what you're doing — browsing findings, watching a run in progress, or editing project settings. A tab strip along the top lets you switch between these views, and always includes a **Settings** tab for the current project.

You don't need to learn everything at once. Each section below covers one region and what you can do there.

## The sidebar

The sidebar is always available on the left edge of the window.

At the top is the **New Project** button. This is how you begin any new piece of research.

Below it is a **searchable list of your recent projects**. Type to filter by name, and click any project to open it. A link at the bottom of the list takes you to a full view of all your projects.

Under the project list, a **system health** indicator tells you whether Marvin's services are running normally. If something is degraded, you'll see it here before it affects your work.

A small **active Marvins counter** ("N/M active Marvins") tells you how many of your runs are currently running, out of your concurrent limit. It's a quick way to see what's in flight at a glance.

At the very bottom is a **usage bar** showing your monthly LLM usage as a percentage of your plan. Click it to open detailed usage and billing information. Beneath the usage bar sits your **account indicator** — your name, avatar, and plan badge. Click it to reach your account, billing, usage, and plan management views.

## Projects and creating a new project

A **project** is the container for a single line of research: one question, one set of goals, and everything Marvin produces while working on it. Findings, runs, and iterations all live inside a project.

To create one, click **New Project** in the sidebar. Marvin will walk you through a short setup:

1. **Name the project.** Give it something you'll recognize later.
2. **Describe what you're investigating.** This is your research question or set of hypotheses. Be as specific as you can — a sharper question leads to sharper research.
3. **Optionally, point Marvin at source material.** You can attach datasets or reference prior work you want Marvin to build on. This step is optional; Marvin can start from your question alone.

Once you submit that, Marvin drafts a plan back. The plan restates your question in its own words, names a focus, and lays out the goals it will work toward. Read it carefully — this is your chance to make sure Marvin understood you.

From here you have two choices:

- **Refine with Marvin.** Adjust the plan in conversation. Ask for a different emphasis, narrower scope, or different framing, and Marvin will revise.
- **Approve and launch.** Confirm the plan and bring the project into your workspace.

Nothing runs autonomously until you approve. Approving creates the project; it does not start a run on its own. For the broader capabilities Marvin brings to a project, see [what Marvin can do](what-marvin-can-do.md).

## Starting a run ("Start Marvin")

Once a project exists, you start research by clicking the **Start Marvin** button in the top bar — an indigo pill on the right side. A modal opens with the run's controls.

You set three things:

- **Iteration count.** Choose any number from 1 to 100, or flip the **Until STOP** toggle to let Marvin decide when the work is complete. With Until STOP on, Marvin runs until it reaches a natural stopping point or hits one of the limits below.
- **Compute resources.** A slider sets the maximum CPU cores Marvin may use, and a list lets you choose which GPU types to allow. Each GPU is shown with its VRAM and cost per hour, so you can balance speed against spend.
- **Run budget.** A dollar cap for this specific run, bounded by your available balance. Marvin will not start a run that would exceed the budget you set.

These settings are saved to the project, so the next run starts from the same configuration unless you change it.

While a run is active, the **Start Marvin** button turns into a red **Stop Marvin** button. Clicking it opens a confirmation modal before the run is halted, so you can't stop anything by accident.

> **Free plan limits.** On the Free plan, runs are limited to a single iteration and the **Until STOP** toggle is unavailable. Autonomous, multi-iteration research requires a paid plan. The Free tier covers chat and literature lookup. See [plans and billing](plans-and-billing.md) for plan details.

## Monitoring a run

You don't need to babysit a run. Marvin works in the background, and the activity feed is there whenever you want to check in.

The feed has two modes:

- **Live** shows what Marvin is doing right now, streaming in as it happens.
- **History** lets you scroll back through everything that has happened in the project so far.

Marvin describes its progress in plain language as it moves through the stages of research — searching and reviewing literature, forming hypotheses, designing experiments, running them, analyzing results, and writing up findings. You'll see each stage announced as it begins, so you always know where the work stands without needing to interpret any internal process.

Failures are clearly flagged in the feed, with enough context to understand what went wrong. You won't have to hunt for errors.

A run can end in one of a few ways, and the feed and project card will tell you which:

- **Completed** — Marvin finished its planned iterations.
- **Reached a natural stopping point** — with Until STOP enabled, Marvin determined the work was done.
- **Paused** — the run halted for budget reasons or because it needs your guidance.

Banners make the outcome obvious, so you always know whether a run finished cleanly or needs your attention.

## Reviewing findings

Findings are the heart of what Marvin produces. A **finding** is a single claim, backed by evidence, that Marvin has concluded from the research.

Each finding has three parts:

- **The claim itself**, stated in plain language.
- **The metrics behind it** — effect sizes, significance, and the other measurements that support the claim.
- **A confidence level**, which tells you how strongly the evidence supports the claim. Marvin describes confidence in everyday terms — *established* (strongly supported), *suggested* (supported but not yet conclusive), *speculative* (an emerging pattern), *inconclusive* (not enough data yet), or *refuted* (contradicted by the evidence). Think of these as plain-language descriptors of how much weight to put on a result.

Every finding links to its **evidence** — the experiments and prior results behind it. Click through to see exactly why Marvin claims what it does. This chain of evidence is what makes a finding trustworthy rather than just an assertion.

From any finding you can:

- **Ask Marvin a follow-up.** Dig deeper, request a different analysis, or challenge the conclusion.
- **Export a citation.** Pull the finding out in a format you can use elsewhere.

Findings are searchable and filterable, so as a project accumulates results you can still find the ones that matter. For more on reading findings, see [features](features.md).

## Time Machine: revisiting past iterations

Research builds over time, and earlier states of a project are never lost. The **Time Machine** control sits in the center of the top bar and lets you move through your project's history iteration by iteration.

Use the controls to step forward and back, or jump directly to a specific iteration. The workspace then shows the project as it stood at that point — the findings known then, the questions still open. It's a way to retrace how an answer developed, not just see the final result.

If a later run revised an earlier finding, **both versions remain accessible**. You can compare what Marvin concluded at one point against what it concluded later, and see exactly what changed and when. Nothing is silently overwritten.

## Settings

Marvin keeps settings in two places, because account-level concerns and project-level concerns are different.

**Account & billing** lives behind your account indicator in the sidebar. From here you manage:

- Your **payment method**.
- Your **wallet balance** and any top-ups.
- Your **subscription**.
- **Plan management** — upgrade, downgrade, or review your plan.

For the full picture on plans, quotas, and billing behavior, see [plans and billing](plans-and-billing.md).

**Project configuration** lives in the **Settings** tab inside a project. This is where you shape how Marvin approaches this specific piece of research:

- The project's **mission and goals** — the question and objectives Marvin works toward.
- **Directives for Marvin** — guidance on approach, scope, or constraints you want Marvin to respect.
- **Run parameters** — maximum iterations, and compute and rigor settings such as significance thresholds and random seeds. These act as defaults whenever you start a run.
- A **danger zone** for deleting the project entirely.

Settings you change here carry forward into every subsequent run, so you can tune the project once rather than reconfiguring each time.

---

If this article didn't cover what you needed, the [features](features.md) reference and the [how-to guides](how-to-guides.md) go deeper, [faq.md](faq.md) answers common questions, and you can always [contact us](contact.md).
