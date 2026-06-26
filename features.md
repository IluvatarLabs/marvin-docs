# Features

Marvin is an autonomous research agent: give it a question, and it does the research work for you — end to end. This article covers what you can do with Marvin and what you'll see while using it. For a quick orientation, start with [getting started](getting-started.md); for the bigger picture of what Marvin is, see [what is Marvin](what-is-marvin.md).

## Autonomous runs

An autonomous run is the core of Marvin. You provide a research question or topic, and Marvin handles the rest — searching relevant literature, forming hypotheses, designing and running analyses, and delivering structured findings you can act on.

You start a run from the **Start Marvin** control. Before it begins, you set three things:

- **Length.** Choose a specific number of iterations, or select **Until STOP** to let Marvin decide for itself when the research is complete.
- **Compute.** Specify the resources Marvin may use — CPU cores and which GPU types to allow.
- **Budget.** Set a spend cap for the run. Marvin will not exceed it.

Once a run is going, you can step away. Watch it live in the UI, or come back later — everything is saved. You can stop a run at any time if you want to cut it short.

For a walkthrough of the run controls and where to find them, see [navigating the UI](navigating-the-ui.md).

## Persistent memory

Marvin remembers what it learns. Findings, literature, and the decisions behind them are preserved across your projects and across every run.

This means your research builds on itself rather than starting over each time. When Marvin returns to a topic you've explored before, it brings that prior context to the new work.

You can review the results of any past run at any point — nothing is discarded.

## Research findings

A finding is a structured result that comes out of a run. Each finding is made up of four parts:

- **The conclusion** — what was found.
- **The evidence** — the data, metrics, and literature behind it.
- **A confidence level** — how strongly the evidence supports the conclusion, expressed in plain language: *established*, *suggested*, *speculative*, *inconclusive*, or *refuted*.
- **What it means** — the interpretation, in context.

Findings are organized by project and by run, so you can trace any result back to where it came from. You can review them in-app and copy their contents to share or cite.

For concrete examples of the kinds of questions Marvin can investigate, see [what Marvin can do](what-marvin-can-do.md), and for step-by-step recipes, [how-to guides](how-to-guides.md).

## Project management

Projects organize your research by topic or goal. Every project has a mission and a set of specific goals that keep the work focused.

Within a project, runs produce iterations, and iterations produce findings — a clean hierarchy that lets you see how your understanding developed over time.

The **Time Machine** lets you navigate that history. Step forward and back through any past run or iteration and review it on its own, independent of the others. It's a full timeline of your project's thinking.

## Integrations

Marvin connects to academic literature databases out of the box, including **arXiv**, **Semantic Scholar**, **PubMed**, and more — so it can pull in relevant papers without any setup from you.

Cloud compute — CPU and GPU — is provisioned automatically for each run, based on the resources you allow.

Connecting your own data sources is **coming soon**. It's on the roadmap, but not available in the current release.

## Billing and plans

Marvin uses a two-part billing model. Your plan includes a monthly allowance of research capacity, and on top of that you have a wallet of top-up credits for when you need more.

Your current usage appears as a percentage bar in the sidebar, so you can see at a glance how much of your allowance you've used.

The **Free** tier gives you chat and literature lookup only — autonomous runs require a paid plan. Paid plans are **Academic**, **Pro**, **Team**, and **Enterprise**. The Enterprise plan supports BYOK (bring your own keys).

For the full breakdown of plans, capacity, and pricing, see [plans and billing](plans-and-billing.md). For common questions, [FAQ](faq.md); to reach us, [contact](contact.md).
