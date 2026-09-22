---
title: Ce que j'ai appris en construisant avec des LLMs (meetup)

event: Mindstone Lyon September AI Meetup
event_url: https://community.mindstone.com/events/mindstone-lyon-september-ai-meetup-2026

location: Lyon (Meetup Mindstone AI - Lyon)
address:
  street: Epitech, 2 Rue du Professeur Charles Appleton
  city: Lyon
  region: Auvergne-Rhone-Alpes
  postcode: '69007'
  country: France

summary: Un talk technique décortiquant le processus de construction d'un agent IA de correction de bugs, avec des retours d'expérience concrets issus de la 1ère place au Hackathon Dust/Qonto AI Agent 2025.
abstract: "Imaginez un monde où les membres non-techniques d'une équipe peuvent contribuer aux projets de développement sans attendre que les tickets passent dans le sprint. Notre Agent IA comble le fossé entre les deux équipes. Cassons les silos ! Ce constat, nous l'avons fait dans toutes les entreprises où nous travaillons. Les personnes non-techniques ne savent pas développer, ne connaissent pas nos outils (comme Cursor, Windsurf ou Roo Code), et doivent donc créer un ticket, attendre, attendre et encore attendre que ce ticket sorte du backlog pour entrer dans un sprint et tenter une résolution rapide. Dans ce talk, je partage comment mon équipe a construit un agent de correction de bugs en 6 heures avec smolagents (Hugging Face), LiteLLM et la plateforme Dust — et ce que j'en ai appris. L'agent permet à des utilisateurs non-techniques de décrire un bug en langage naturel, lit le code source, écrit la correction et ouvre une pull request pour qu'un développeur la relise. Enseignements clés : - Commencer ridiculement petit — on a choisi la correction de typos, pas la création d'applications - Des garde-fous, pas un accès direct — l'agent ouvre des PRs, il ne déploie jamais directement - 100 lignes pour prototyper, 5 heures pour intégrer — l'IA c'est la partie facile, la plomberie c'est le vrai travail - Connaître ses limites — lire tous les fichiers fonctionne pour un petit repo, les gros codebases ont besoin de RAG"

date: "2026-09-22T18:00:00Z"
date_end: "2026-09-22T20:30:00Z"
all_day: false

publishDate: "2026-09-01T00:00:00Z"

authors: [David Aparicio]
tags: [AI, IA, LLM, Hackathon]

featured: false

image:
  caption: 'Crédits: [**Mindstone**](https://community.mindstone.com/events/mindstone-lyon-september-ai-meetup-2026)'
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