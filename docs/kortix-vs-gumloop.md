# Kortix vs Gumloop: what a team owns, open source and self-hosted

Kortix and Gumloop both put AI agents to work, and they answer a different question. Kortix is the open-source AI Operating System, so the configuration is yours to read and change. Gumloop is a hosted, no-code builder for AI agents, so the configuration lives inside Gumloop's product and its cloud. The comparison comes down to what a team keeps once the work is done.

## The repository

In Kortix, a project is a git repo. Agents and skills are markdown, memory is files, and `kortix.yaml` declares the machine image, the connectors and the triggers. A person can `grep` the whole company, diff any change, and roll it back. In Gumloop, agents are built and stored in Gumloop's product, and each session is recorded for review inside that product ([gumloop.com](https://www.gumloop.com)).

## Self-hosting

Kortix runs on Kortix Cloud, in your VPC, or on your own on-prem network, and self-host is free ([kortix.com/pricing](https://kortix.com/pricing)). Gumloop's own site and pricing page document a hosted product, with no self-hosted edition ([gumloop.com/pricing](https://www.gumloop.com/pricing), checked October 2026).

## Model choice

Kortix is model-agnostic: any model provider with your own keys, or the ChatGPT plan you already pay for. Gumloop runs the models it provides inside its hosted product, so the model is part of what you rent along with the builder.

## Review of agent work

Session work in Kortix reaches `main` through a change request: merge is default-deny for agents, so a person reads the diff before it lands. Approval gates you set, off until you set them. Gumloop keeps a person in the loop as well, handing the live browser to you when a site needs a sign-in or an approval, and recording each step.

## What each is for

Kortix fits open-ended agent work a team wants to own: the configuration in its own repository, the system on its own network, and any model it chooses. Gumloop fits a team that wants a hosted builder with no server to run and no configuration to maintain. When the answer to "who owns this" has to be your team, Kortix is the open-source route; when the answer is "whoever hosts it", Gumloop is the simpler setup.
