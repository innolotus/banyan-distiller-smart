# Banyan Distiller Smart

Banyan Distiller Smart converts external information into Banyan Knowledge Packs using an embedded Ivy-0 runtime and a small local model for knowledge distillation.

## Scope

This is the smart edition of Banyan Distiller. It should provide higher-quality semantic extraction while keeping the output compatible with the same `.banyanpack` format used by Banyan Core.

Initial responsibilities:

- Bundle or integrate Ivy-0: https://github.com/labacacia/Ivy-0
- Run a small model to transform source material into structured Banyan-native knowledge.
- Extract facts, procedures, policies, entities, relations, citations, and confidence metadata.
- Produce portable `.banyanpack` artifacts.
- Support review queues so users can accept, reject, or edit distilled knowledge before packaging.

## Relationship To Banyan Distiller

Banyan Distiller is the standard deterministic extraction and packaging tool. Banyan Distiller Smart adds model-assisted distillation on top of the same Knowledge Pack contract.

## Relationship To Banyan

Banyan Core mounts, recalls, and unmounts Knowledge Packs. Banyan Distiller Smart creates richer packs from external information.
