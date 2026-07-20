---
description: Browse Coworker Chat use cases and sample prompts, organized by area across data insights, audiences, experimentation, journeys, and platform operations.
title: Use Cases
---
# Use cases {#use-cases}

Below are use cases and sample prompts that practitioners are using in Adobe CX Enterprise Coworker Chat, organized by work area. Each prompt is built to be copied, adapted with your own data and context, and refined through conversation.

## Data Insights

| Use Case | Description | Skill(s) | Application | Sample Prompts |
|---|---|---|---|---|
| Pull CJA reports & metrics | Query CJA in real time to pull metrics, dimensions, segments, and data views | `cja` | Customer Journey Analytics (CJA) | "Show me page views for the last 30 days" · "List top segments in the master data view" |
| Comparative analysis | Compare metrics across channels, time periods, or segments side by side | `cja` | Customer Journey Analytics (CJA) | "Compare revenue by channel month over month" · "How does mobile vs desktop conversion look this quarter?" |
| Funnel analysis | Walk through multi-step conversion funnels with drop-off at each stage | `cja` | Customer Journey Analytics (CJA) | "Walk me through the checkout funnel" · "Show conversion funnel from PDP to purchase" |
| Forecasting | Project future metric values based on historical CJA data | `cja` | Customer Journey Analytics (CJA) | "Forecast sessions for the next 30 days" · "Are we on track to hit our revenue goal?" |
| Root cause analysis | Investigate why a metric changed: diagnose drops, spikes, and anomalies | `cja-root-cause-analysis` | Customer Journey Analytics (CJA) | "Why did conversions drop last week?" · "What caused the revenue spike on Jan 15?" |
| Executive summaries & KPI digests | Produce stakeholder-ready performance summaries, prescriptive recommendations, and slide deck outlines | `cja-executive-summary` | Customer Journey Analytics (CJA) | "Give me an executive summary of last month" · "Create a slide deck outline from this quarter's data" |
| AA ↔ CJA data validation | Compare, audit, and reconcile data between Adobe Analytics and Customer Journey Analytics | `aa-cja-validation` | Adobe Analytics + CJA | "Compare my AA report suite to my CJA data view" · "Validate page views between AA and CJA" |
| Operational time-series & causal analysis | Query and analyze historical time-series data for audiences, datasets, and journeys with causal attribution | `operational-stats-causal-analysis` | Adobe Experience Platform (AEP) | "Show audience size trends over the last 90 days" · "Why did my dataset row count spike on March 3?" |
| Marketing ML / Propensity models | Full ML lifecycle on AEP: dataset discovery, feature engineering, model training, evaluation, batch inference, and MLOps | `marketing-ml` | Adobe Experience Platform (AEP) | "Build a churn propensity model on my purchase dataset" · "Score customers for likelihood to convert" |
| Create custom CJA skills | Turn analytical patterns into reusable, repeatable skills that persist across sessions | `cja-skill-creator` | Customer Journey Analytics (CJA) | "Turn this weekly revenue analysis into a reusable skill" · "Save this as a skill for monthly funnel reporting" |

## Audiences

| Use Case | Description | Skill(s) | Application | Sample Prompts |
|---|---|---|---|---|
| Create audiences from natural language | Orchestrate step-by-step audience creation with user approval at each phase | `audience-creation-flow` | Adobe Experience Platform (AEP) | "Create an audience of users who purchased in the last 30 days" · "Build a segment for high-value loyalty members in California" |
| Build PQL definitions | Assemble audience definitions from XDM properties, behavioral events, or existing audiences; supports aggregation and time windows | `segment-definition-assembly` | Adobe Experience Platform (AEP) | "Create a PQL for people who viewed 3+ products but didn't purchase" · "Add a 7-day time window to my event condition" |
| Search & find audiences | Find audiences by ID, name, semantic search; detect duplicates and analyze overlap | `audience-search` | Adobe Experience Platform (AEP) | "Find all loyalty audiences" · "Is there a duplicate of my 'Holiday Shoppers' segment?" |
| Estimate audience size | Estimate profile reach for a PQL expression using AEP Preview API with polling | `audience-size-estimate` | Adobe Experience Platform (AEP) | "How large is this audience?" · "Estimate reach for this PQL expression" |
| Audience size waterfall | Decompose a PQL into sub-predicates and show how each condition contributes to final audience size | `audience-size-waterfall` | Adobe Experience Platform (AEP) | "Show me the waterfall for this PQL" · "Break down how each condition reduces the audience" |
| Discover XDM fields for targeting | Search fields by name, description, or data value; see where they live and where they're already used | `field-discovery` | Adobe Experience Platform (AEP) | "Which fields can I use to target loyalty customers?" · "Find fields related to purchase history" |
| Publish / save audiences | Persist audience definitions to AEP Segmentation Service with naming conventions and compliance checks | `audience-publish` | Adobe Experience Platform (AEP) | "Save this audience as a draft" · "Publish the audience with name 'Spring Sale Buyers'" |

## Experimentation

| Use Case | Description | Skill(s) | Application | Sample Prompts |
|---|---|---|---|---|
| Browse & list experiments | Get an overview of your experiments program; list, filter, and count experiments, and look up raw results, insights, and optimization opportunities for individual experiments | `experiment-explorer` | Adobe Experience Platform (AEP) | "Show me my running experiments" · "How many A/B tests are active?" |
| Analyze experiment performance | Analyze performance reports, health checks, portfolio rundowns, and win/loss briefs | `experiment-analysis` | Adobe Experience Platform (AEP) | "How is my checkout experiment performing?" · "Is my homepage test healthy?" |
| Design next experiments | Recommend what to test next, design blueprints, recover from failed tests, build roadmaps | `experiment-strategist` | Adobe Experience Platform (AEP) | "What should I test next?" · "Design an experiment to improve mobile checkout conversions" |
| Retrieve experiment context & learnings | Search past experiments by topic, retrieve hypotheses, outcomes, and ingest external CSVs | `experiment-context` | Adobe Experience Platform (AEP) | "What do we know about experiment X?" · "Have we tested this hypothesis before?" |
| Browse Target activities | List, inspect, and audit Target activities, audiences, offers, mboxes, and properties | `target-browse` | Adobe Target | "List my Target activities" · "Show me all paused A/B tests" |
| Analyze Target performance | Retrieve raw conversion rates, lift, confidence, revenue, and orders for Target activities | `target-analyze` | Adobe Target | "Show conversion lift for my homepage test" · "What's the revenue data for activity X?" |
| Create / update Target activities | Create, update, and configure Target activities, offers, audiences, and generate QA links | `target-design` | Adobe Target | "Create an A/B test with two HTML offers" · "Update the traffic split to 50/50" |
| Guided Target activity setup | End-to-end guided workflow through requirements, prerequisites, creation, QA, and activation | `target-setup` | Adobe Target | "Walk me through setting up a complete A/B test" · "Help me create my first experiment" |
| VEC visual editing | Visual Experience Composer authoring: WYSIWYG DOM modifications against a live page URL | `target-vec` | Adobe Target | "Create a VEC A/B test for the homepage" · "Change the hero headline in the visual editor" |
| Target program health & audit | Analyze the Target environment for risks, misconfigured tests, stale activities, and optimization opportunities | `target-intelligence` | Adobe Target | "Audit my Target environment" · "Find risky or misconfigured tests" |
| Target winning patterns & strategy | Mine Target history to reveal winning patterns, effective strategies, and recommend next tests | `target-strategist` | Adobe Target | "What testing patterns produce the best lift for us?" · "Which audiences respond best?" |

## Journeys

| Use Case | Description | Skill(s) | Application | Sample Prompts |
|---|---|---|---|---|
| Create journeys from natural language | Orchestrate journey creation in AJO from a text prompt or an uploaded image/flowchart | `journey-create` | Adobe Journey Optimizer (AJO) | "Create a welcome journey that sends an email after signup, waits 3 days, then sends a follow-up" · "Build a journey from this uploaded flowchart image" |
| Analyze journey conflicts | Detect audience overlap, schedule collisions, and deduplication issues between active journeys | `journey-analyze-conflict` | Adobe Journey Optimizer (AJO) | "Does my cart abandonment journey conflict with any other journeys?" · "Check for audience overlap between my active journeys" |

## Foundational Elements

| Use Case | Description | Skill(s) | Application | Sample Prompts |
|---|---|---|---|---|
| Product knowledge & documentation | Answer how-to, conceptual, troubleshooting, and best-practice questions from official Adobe docs | `product-knowledge` | All Applications | "How do I set up a streaming destination?" · "What's the difference between batch and streaming segmentation?" |
| Query AEP/AJO entities | Primary entry point for questions about your platform entities; routes to KG, field discovery, or APIs as needed | `operational-insights` | Adobe Experience Platform (AEP) + Adobe Journey Optimizer (AJO) | "How many datasets do I have?" · "Show me all active journeys" · "List my destinations" |
| Knowledge Graph queries | Aggregate counts, cross-entity joins, relationship lookups, and metadata exploration via single SQL queries | `knowledge-graph` | Adobe Experience Platform (AEP) + Adobe Journey Optimizer (AJO) | "Which audiences use this dataset?" · "Show relationships between schemas and datasets" |
| AEP/AJO/CJA API operations | Direct API gateway for mutations, real-time state checks, and entity types not in the Knowledge Graph | `cxo-api` | AEP / AJO / CJA | "Delete dataset X" · "Check the status of my batch ingestion job" |
| Entity resolution & linking | Semantic and lexical search to resolve entity mentions to actual AEP entities and discover XDM fields | `entity-linking` | Adobe Experience Platform (AEP) | "Resolve 'Holiday Shoppers' to an actual audience" · "Find the dataset named 'Web Events'" |
| Build personal context | Generate a personalized user profile from your AEP, CJA, and/or Workfront activity logs | `build-my-context` | AEP / CJA / Workfront | "Build my context from AEP and CJA activity" · "Who am I in this org?" |
| Distill org context | Extract organization-wide knowledge from a document into the shared org-context wiki | `distill-org-context` | All Applications | "Distill this doc into the org wiki" · "Add this file to the org context" |
| Distill user context | Extract personal working context from a document into your user-context wiki | `distill-user-context` | All Applications | "Add this file to my user context" · "Extract my working context from this doc" |
| Manage custom skills | Save, modify, or delete user-owned reusable skills that persist across sessions | `manage-skill` | All Applications | "Save that workflow as a skill" · "Delete my weekly report skill" · "Turn this into a reusable skill" |
