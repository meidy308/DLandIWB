# Digital Leadership and Innovative Work Behavior (IWB) Knowledge Base

## Overview
This repository contains a structured, interlinked knowledge base for research on **Digital Leadership** and **Innovative Work Behavior (IWB)**. 

It is maintained using the **LLM Wiki pattern** (based on Andrej Karpathy's approach). In this workflow, an AI assistant maintains the markdown wiki pages, while the human user curates sources, asks questions, and guides the analysis.

> **Note**: Because this wiki relies heavily on internal `[[wiki-links]]` for navigation, it is best viewed using the **[Obsidian](https://obsidian.md/)** software.

## Repository Structure
- `raw/` - Immutable source documents (transcripts, articles, notes). Never modify these.
- `wiki/index.md` - table of contents for the entire wiki.
- `wiki/log.md` - append-only record of all changes.
- `wiki/summaries/` - One summary page per raw source document.
- `wiki/concepts/` - Concept, strategy, and framework pages.
- `wiki/syntheses/` - Comparison tables, decision frameworks, cross-cutting analyses.

## Workflow
1. **Adding Sources**: New research or sources are added to the `raw/` folder.
2. **Ingestion**: The AI assistant reads the source, discusses key takeaways, creates summary and concept pages, and interlinks them using `[[wiki-links]]`.
3. **Tracking**: All changes are tracked in the `wiki/index.md` and `wiki/log.md`.
4. **Analysis & QA**: The user can ask questions, and the AI will synthesize answers, citing specific wiki pages and sources.

## Disclaimer
The files in the `raw/` folder, `.obsidian/` folder, and other specific user resources are excluded via `.gitignore` to maintain a clean repository specifically focused on the curated wiki content.
