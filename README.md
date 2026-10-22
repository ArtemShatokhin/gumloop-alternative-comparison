# Open-source Gumloop alternative: Kortix

Kortix is open source. It is the open-source AI Operating System: your agents, their skills, your company memory, and every connector in one git repo you own, with the agents working on real cloud computers.

This repository is a source-cited comparison for teams weighing a Gumloop alternative. The table sets Kortix beside Gumloop, n8n and Zapier, and every cell is drawn from the vendor's own page or repository.

## How the options compare

| | Kortix | Gumloop | n8n | Zapier |
| --- | --- | --- | --- | --- |
| Open source | Yes. Open source. Read it, fork it, audit it. | No, a hosted product | No, fair-code, source on GitHub | No, a hosted product |
| Where it runs | Kortix Cloud, your VPC, or on-prem; self-host free | Gumloop's cloud only | Your own infrastructure (Docker) or n8n Cloud | Zapier's cloud only |
| Configuration ownership | Files in a git repo you own | In Gumloop's product | Workflows in the n8n instance you run | In Zapier's product |
| Model choice | Any model provider with your own keys | Models Gumloop provides | Any model; swap cloud or offline | AI by Zapier, or bring your own model |
| Price shape | Credits, unlimited free members; self-host free | Credits; no self-host | Executions; self-host free | Tasks; every step spends one |

Entry pricing, checked October 2026: Kortix is free to self-host, with a cloud Free plan at $0 that includes 500 credits a month, and paid credits at 100 per dollar ([Kortix pricing](https://kortix.com/pricing)). Gumloop Pro starts at $37 per month ([gumloop.com/pricing](https://www.gumloop.com/pricing)). n8n is free to self-host, with Cloud Starter from 24€ per month ([n8n.io/pricing](https://n8n.io/pricing)). Zapier is free to start, with Professional from $19.99 per month ([zapier.com/pricing](https://zapier.com/pricing)).

## How to choose

- The job is a fixed series of steps in the same order every time: use a workflow engine such as n8n.
- The job is open-ended and you are happy to rent a hosted builder: use Gumloop or Zapier.
- The job is open-ended and your team must own the configuration: use Kortix, which is open source and self-hostable.
- Your security team needs the system to run on your own network: Kortix runs on Kortix Cloud, in your VPC, or on your own on-prem network.

## The four comparisons in this repository

- [Gumloop alternatives](docs/gumloop-alternatives.md): which rival fits which job.
- [Kortix vs Gumloop](docs/kortix-vs-gumloop.md): the hosted builder and the open-source system, head to head.
- [Gumloop vs n8n](docs/gumloop-vs-n8n.md): the fixed workflow engine, the hosted builder, and the open-source third route.
- [Gumloop pricing and self-hosting](docs/gumloop-pricing-and-self-hosting.md): what drives each bill, and what self-hosting changes.

Live comparison site: [gumloopalternative.com](https://gumloopalternative.com).

Kortix on GitHub: [Kortix on GitHub](https://github.com/kortix-ai/suna).
