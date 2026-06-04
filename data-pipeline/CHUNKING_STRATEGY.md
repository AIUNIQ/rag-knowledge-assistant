# Chunking Strategy

## Purpose

Break documents into useful sections so the retrieval system can return accurate context.

## Chunking Principles

- Preserve meaning.
- Avoid cutting important context.
- Keep related ideas together.
- Include metadata.
- Optimize for retrieval quality.

## Recommended Chunk Types

### Small Chunks

Best for:

- FAQs
- Policies
- Short product details

### Medium Chunks

Best for:

- Product descriptions
- Workflow steps
- Training material

### Large Chunks

Best for:

- Long explanations
- Transcript sections
- Documentation chapters

## Metadata Fields

- chunk_id
- source_file
- section_title
- page_number
- document_type
- topic
- timestamp

## Retrieval Goal

Return the smallest useful context that fully answers the user question.
