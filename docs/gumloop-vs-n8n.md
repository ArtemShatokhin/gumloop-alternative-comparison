# Gumloop vs n8n: fixed workflows, hosted agents, and the open-source third route

Gumloop, n8n and an open-source system each automate work, in three different shapes. Kortix is the open-source AI Operating System, where open-ended agent work runs on real cloud computers inside a system a team owns. The useful question is which shape the job needs.

## n8n: the fixed workflow engine

n8n draws a workflow on a visual canvas and runs the same path on a schedule, a webhook or a chat. It runs on your own infrastructure with Docker, or in n8n Cloud, and it publishes its source on GitHub as fair-code; the self-hosted Community edition is free ([n8n.io](https://n8n.io)). One execution is a single run of the whole workflow, no matter how many steps are inside it, and that is the unit n8n bills ([n8n.io/pricing](https://n8n.io/pricing)). It fits the case where the steps are known in advance.

## Gumloop: the hosted builder

Gumloop is a hosted, no-code builder. You describe a task, an agent picks the tools, signs in to your apps and browses the web from Gumloop's own connections. There is no server to run, which is the point and also the limit: it is a hosted product with no self-hosted edition, billed by credits, with Pro from $37 per month ([gumloop.com/pricing](https://www.gumloop.com/pricing), checked October 2026).

## Kortix: the open-source system a team owns

Kortix keeps agents, skills, company memory and connectors as files in one git repo you own, and there is one isolated sandbox per session. Thousands of agents run in parallel on one config, each on its own cloud computer. Session work reaches `main` through a change request a person reads. Run it on Kortix Cloud, in your VPC, or on your own on-prem network, and self-host is free ([kortix.com](https://kortix.com)).

## When each wins

A fixed flowchart of steps points to n8n. A described task you are content to run in someone else's cloud points to Gumloop. Open-ended work where the configuration, the model and the infrastructure must be the team's own points to Kortix. The pricing and self-hosting article in this repository compares what each bill follows.
