# Prompt Design Strategy

## Objective

Design prompts that maximize retrieval accuracy while minimizing hallucinations.

## System Prompt Principles

* Use retrieved knowledge as the source of truth.
* Do not invent information not present in retrieved context.
* Ask clarifying questions when context is insufficient.
* Separate facts from assumptions.
* Escalate when confidence is low.

## Example RAG Prompt Flow

User Question

↓

Retrieve Relevant Chunks

↓

Inject Context

↓

Generate Grounded Answer

↓

Validate Response

↓

Return Answer

## Prompt Goals

* Accuracy
* Relevance
* Consistency
* Explainability
* Reduced hallucinations

