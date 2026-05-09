# Banyan Distiller Smart

Banyan Distiller Smart converts external information into Banyan Knowledge Packs using Ivy-assisted execution and a small local model for knowledge distillation.

Banyan is the proven memory brain in the InnoLotus AI stack. Ivy is the execution and problem-solving platform. Banyan Distiller Smart may use Ivy to improve distillation quality, but it remains a Banyan packaging tool and does not own general Ivy execution runtime, chat UI, or enterprise workflow orchestration.

See [`docs/product-boundary.md`](./docs/product-boundary.md) for the product boundary.

## Scope

This is the smart edition of Banyan Distiller. It should provide higher-quality semantic extraction while keeping the output compatible with the same `.banyanpack` format used by Banyan Core.

Initial responsibilities:

- Integrate Ivy-0 as a controlled distillation execution kernel: https://github.com/labacacia/Ivy-0
- Run a small model to transform source material into structured Banyan-native knowledge.
- Extract facts, procedures, policies, entities, relations, citations, and confidence metadata.
- Produce portable `.banyanpack` artifacts.
- Support review queues so users can accept, reject, or edit distilled knowledge before packaging.

## Relationship To Banyan Distiller

Banyan Distiller is the standard deterministic extraction and packaging tool. Banyan Distiller Smart adds model-assisted distillation on top of the same Knowledge Pack contract.

## Relationship To Ivy

Ivy helps plan, extract, classify, validate, and review knowledge during distillation. Banyan Distiller Smart owns the distillation workflow and `.banyanpack` output. General-purpose execution, chat interaction, and enterprise workflow automation belong to Ivy-0, Ivy-Chat, and Ivy-Work respectively.

## Relationship To Banyan

Banyan Core mounts, recalls, and unmounts Knowledge Packs. Banyan Distiller Smart creates richer packs from external information.
