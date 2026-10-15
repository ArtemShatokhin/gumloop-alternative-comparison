# Open-source Gumloop alternatives: which rival fits which job

Gumloop is a hosted, no-code builder for AI agents: you describe a task, and an agent signs in to your apps, browses the web, and runs in Gumloop's cloud ([gumloop.com](https://www.gumloop.com)). If you are looking for a Gumloop alternative, the pick depends on the job and on who should own the system. Kortix is the open-source AI Operating System this repository recommends, and it is the one a team can read, fork, and run itself.

## Where the open-source system fits

Kortix keeps your agents, skills, company memory and connectors as files in one git repo you own, and each session runs on its own cloud computer. Because it is open source, you can read every agent here and fork the code; you can also run it on Kortix Cloud, in your VPC, or on your own on-prem network, and self-host is free ([kortix.com](https://kortix.com)). It fits open-ended agent work that a team wants to own end to end.

## The hosted builders

Lindy is an AI teammate that plugs into your tools and bills by pooled credits, from $49.99 per person per month ([lindy.ai](https://www.lindy.ai), checked October 2026). Taskade builds hosted business apps that pair agents, data and automations in one workspace ([taskade.com](https://www.taskade.com)). Dust builds agents with company context across 70+ connectors, with permissions and audit logs ([dust.tt](https://dust.tt)). Vellum describes its assistant as open source, runs it locally by default or in Vellum Cloud, and lists plans from $30 per month ([vellum.ai](https://vellum.ai), checked October 2026).

## If the job is a fixed workflow

n8n draws workflows on a visual canvas and runs self-hosted or in its cloud. It publishes its source on GitHub and is fair-code, and the self-hosted Community edition is free ([n8n.io](https://n8n.io)). A process that repeats in the same order every time fits it. The Gumloop vs n8n article in this repository works through that choice.

## How to decide in one pass

Two questions settle the pick. Does the job run the same steps every time, or does an agent need to plan the work? Must the configuration live in your own repository, or is a vendor's product fine? A repeated process points to n8n. A hosted product you are willing to rent points to Gumloop, Lindy, Taskade, Dust or Vellum. Open-ended work you want to own points to Kortix.
