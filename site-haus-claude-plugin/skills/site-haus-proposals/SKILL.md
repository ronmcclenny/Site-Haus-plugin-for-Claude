---
name: site-haus-proposals
description: Write a client proposal in the user's Site Haus account as a draft they can review and send. Use when the user asks for a proposal, quote, scope or pitch for a client.
---

# Client proposals in Site Haus

A proposal is not a project. It is a title, an intro, a design and sections that the client reads on a private link, then accepts and pays for.

## Tools
`list_proposals`, `get_proposal`, `create_proposal`, `update_proposal` and `get_proposal_preview`.

## How to write one
- Write it for this one client: name their business, goals and audience. Use concrete deliverables, a timeline that fits them and pricing that adds up. Avoid stock phrases and stock section titles.
- Ask for anything you need to price it honestly (scope, deadline, budget) instead of inventing numbers.
- Call `get_guidelines` first: it holds the exact section types, layout options and design fields the proposal accepts.
- Give each proposal its own look rather than the same template, then call `get_proposal_preview` and refine it.

## What you cannot do
- Proposals are created as drafts. You cannot send one to a client: tell the user to review it and press **Send** in Site Haus.
- An accepted proposal is locked. You cannot change it.
