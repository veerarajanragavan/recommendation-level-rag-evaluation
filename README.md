# Recommendation-Level Evidence Retrieval and Provenance Evaluation for RAG over Versioned Medical Guidelines

## Overview

This repository contains the research artefacts for an offline experimental evaluation of recommendation-level evidence retrieval and provenance consistency in Retrieval-Augmented Generation (RAG) systems using versioned medical guidelines.

The study investigates whether recommendation-level evidence representation, context-enriched embeddings, and contextual reranking can improve retrieval relevance and evidence traceability.

## Research Experiments

- **E1:** Baseline semantic retrieval
- **E2:** Context-enriched embedding retrieval
- **E3:** Contextual reranking
- **E4:** Paired statistical comparison
- **E5:** Provenance consistency audit
- **E6:** Out-of-scope distance analysis

## Dataset

- 42 recommendation units
- 60 benchmark questions
- 6 contrastive questions
- 12 out-of-scope questions

## Research Scope

This project evaluates information retrieval and provenance consistency. It is not a clinical decision-support system, clinical validation study, or medical diagnostic tool.

## Repository Structure

- `data/` — Frozen benchmark and recommendation annotations
- `experiments/` — Experiment results and vector database artefacts
- `docs/` — Research methodology and reproducibility documentation
- `notebooks/` — Experimental notebooks
- `src/` — Reusable implementation code
