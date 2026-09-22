---
title: What I Learned Building With LLMs (meetup)

event: Mindstone Lyon September AI Meetup
event_url: https://community.mindstone.com/events/mindstone-lyon-september-ai-meetup-2026

location: Lyon (Meetup Mindstone AI - Lyon)
address:
  street: Epitech, 2 Rue du Professeur Charles Appleton
  city: Lyon
  region: Auvergne-Rhone-Alpes
  postcode: '69007'
  country: France

summary: Technical talk breaking down the process for building a bug-fixing AI agent, with real-life learnings and insights from the Dust/Qonto AI Agent Hackathon 2025.
abstract: "Imagine a world where non-technical team members can seamlessly contribute to development projects without waiting for tickets to move into the sprint. Our AI Agent bridges the gap between the two teams. Let's break down the silos! This comes from an observation we've made in all the companies where we work. Non-tech people can't develop, they don't know our tools (like Cursor, Windsurf or Roo Code) so they have to create a ticket, wait, wait and wait for that ticket to leave the backlog to get into a sprint and try a quick resolution. In this talk, I share how my team built a bug-fixing agent in 6 hours using smolagents (Hugging Face), LiteLLM, and the Dust platform — and what I learned along the way. The agent lets non-technical users describe a bug in plain language, reads the codebase, writes the fix, and opens a pull request for a developer to review. Key learnings: - Start absurdly small — we picked typo fixing, not app building - Guardrails, not access — the agent opens PRs, never deploys directly - 100 lines to prototype, 5 hours to integrate — the AI is the easy part, the plumbing is the hard part - Know your limits — reading all files works for small repos, large codebases need RAG"

date: "2026-09-22T18:00:00Z"
date_end: "2026-09-22T20:30:00Z"
all_day: false

publishDate: "2026-09-01T00:00:00Z"

authors: [David Aparicio]
tags: [AI, IA, LLM, Hackathon]

featured: false

image:
  caption: 'Image credit: [**Mindstone**](https://community.mindstone.com/events/mindstone-lyon-september-ai-meetup-2026)'
  focal_point: Right

links:
- icon: binoculars
  icon_pack: fas
  name: Description
  url: https://community.mindstone.com/events/mindstone-lyon-september-ai-meetup-2026
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

slides: "lyon2026_ai_mindstone_dust"
projects: ["dust_hackathon2025"]
---