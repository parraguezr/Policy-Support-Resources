---
type: Method
title: Bayesian belief networks
description: Represent conditional dependencies and probabilistic reasoning.
status: draft
tags:
  - methods
  - policy-support
generated:
  by: codex/gpt-6
  at: 2026-09-22T19:06:12.798Z
sources:
  - id: s1
    resource: ../external-sources/bayesian-belief-networks.md
    title: bayesian-belief-networks
---



Bayesian belief networks encode variables and conditional dependencies in a directed acyclic graph. Probabilities can be informed by observations, expert elicitation or both.[^s1]

## What it needs

A defined question, a defensible graph structure, variable states and conditional probability estimates. Updating evidence changes inferred probabilities under the model.

## Evidence and limitations

Ordinary Bayesian networks cannot contain feedback cycles. Expert probabilities introduce assumptions that need documentation and sensitivity checks; a diagram alone is not a fitted or validated model.

## Suggested project use

Consider only when a bounded decision needs quantified uncertainty and appropriate data or elicitation is feasible. It is a different analytical layer from displaying relationships extracted from documents.

## Relationships

Documented by [UNDP](../organizations/undp.md). Contrast feedback in [causal loop diagrams](causal-loop-diagrams.md) and emergent behaviour in [agent-based modelling](agent-based-modelling.md).

## Sources

[^s1]: [Captured source: bayesian-belief-networks](../external-sources/bayesian-belief-networks.md).

[Browse methods](index.md) · [Library home](../index.md)
