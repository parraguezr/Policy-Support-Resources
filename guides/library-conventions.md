---
type: Guide
title: How this knowledge base works
description: OKF structure, provenance and maintenance conventions.
status: draft
tags:
  - guides
  - policy-support
generated:
  by: codex/gpt-6
  at: 2026-09-22T19:13:02.722Z
sources:
  - id: s1
    resource: ../external-sources/openknowledge-overview.md
    title: openknowledge-overview
---



This local library follows the project's OKF v0.2 skill and uses OpenKnowledge's document tools.[^s1] Curated records are **draft**: source-backed agent synthesis awaiting human review, not an assertion that the underlying resources are drafts.

## Structure

| Folder / type | Meaning |
| --- | --- |
| projects / Project | The two user projects and suggested reading pathways |
| methods / Method | Reusable approaches and their requirements |
| initiatives / Initiative | Example programmes, portals and services |
| organizations / Organization | Hosts, developers, publishers and maintainers |
| data-sources / DataSource | Data-facing portals and views; not necessarily downloadable datasets |
| software / Software | Libraries, applications and explicitly labelled discovery leads |
| readings / Reading | Essays, papers, decks and collections |
| external-sources / Source | Original URL, capture scope, short excerpt or preserved PDF |
| guides / Guide | Editorial navigation, coverage and maintenance |
| assets | Local screenshots, rendered PDF pages and machine-readable manifests |

## Evidence contract

Separate three things: **what a source says**, **what was directly inspected**, and **suggested project use**. Source records preserve identity and limited capture; curated notes hold interpretation. A link to a source does not imply independent validation.

Concept documents have `type`, `title`, `description`, `status` and generation provenance. Source-backed notes pair `sources` IDs with Markdown footnotes. Relative links provide portable relationships. Root `index.md` declares `okf_version: "0.2"`; folder indexes remain navigation documents.

## Relationship vocabulary

Use **develops**, **hosts**, **publishes**, **maintains**, **part of**, **uses method**, **documents**, and **relevant to** with a linked target and supporting source. A suggested relevance link is editorial; an ownership or development claim needs evidence. “Listed in” does not mean “owned by.”

## Adding material

Use the folder's **resource** template in OpenKnowledge. Keep one durable identity per record; link variants and multiple sources to it. Preserve original URLs, retrieval scope, dates and version differences. Store permitted source media locally with caption, alt text, source and PDF page number.

Read and write Markdown through OpenKnowledge's CRDT tools. Run the project's audit after changes; investigate every selected validator's warnings. Use checkpoints for recovery.

## Access and rights

The TDR collection is private and remains local. Copyright and reuse rights remain with source owners; a local screenshot or PDF copy is not a licence to republish. Web excerpts are not full archives. No external publication or synchronization was requested.

[Coverage](source-register.md) · [Relationships](relationships.md) · [Build status](build-status.md).

## Sources

[^s1]: [Captured source: openknowledge-overview](../external-sources/openknowledge-overview.md).

[Browse guides](index.md) · [Library home](../index.md)
