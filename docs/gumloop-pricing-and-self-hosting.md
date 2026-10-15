# Gumloop pricing and self-hosting: what the open-source route changes

Gumloop, n8n and Zapier each bill in a different unit, and self-hosting an open-source system removes the subscription line entirely. Kortix is the open-source AI Operating System, it is free to self-host, and on its cloud it prices by seat plus pooled credits. Reading the three shapes side by side shows what each bill follows.

## What drives the Gumloop bill

Gumloop bills by credits. Pro starts at $37 per month and includes 20,000 credits per month, and model calls, tool calls and API pulls all spend them; Enterprise pricing is custom ([gumloop.com/pricing](https://www.gumloop.com/pricing), checked October 2026). The bill follows how much work the agents do.

## What drives the n8n bill

n8n bills by executions. One execution is a single run of the whole workflow, no matter how many steps are inside it, so a long workflow that would be thousands of operations elsewhere is still one execution ([n8n.io/pricing](https://n8n.io/pricing)). The self-hosted Community edition is free, and n8n Cloud starts at 24€ per month for 2,500 executions.

## What drives the Zapier bill

Zapier bills by tasks. Every step and every connector call inside a Zap uses tasks, and the whole account shares one pool. The Free plan carries 100 tasks a month, and the paid Professional plan starts at $19.99 per month ([zapier.com/pricing](https://zapier.com/pricing), checked October 2026).

## What self-hosting the open-source system changes

Kortix prices by seat plus pooled credits. The Free plan is $0 with 200 credits per month and 1 project, and the Team plan is $40 per seat per month with 2,500 credits per month per seat, pooled. Run it on Kortix Cloud, in your VPC, or on your own on-prem network, and self-host is free ([kortix.com/pricing](https://kortix.com/pricing)).

Running the open-source system yourself removes the subscription line. The commands come from the Kortix docs and README: install the CLI with `curl -fsSL https://kortix.com/install | bash`, then `kortix self-host start` to run the full stack on your own infrastructure as one Docker Compose stack. To build a project, `kortix init` scaffolds `kortix.yaml` with your agents and runtime config, and `kortix ship` pushes it up and brings it live.
