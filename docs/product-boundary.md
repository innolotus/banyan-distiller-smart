# Banyan Distiller Smart Product Boundary

## Product Role

Banyan Distiller Smart is the model-assisted and Ivy-assisted semantic distillation tool for the Banyan product line.

It creates richer Banyan Knowledge Packs from external information while preserving the same `.banyanpack` contract used by standard Banyan Distiller.

Banyan Distiller Smart may use Ivy-0 as an execution kernel for controlled distillation workflows, but it is still a Banyan packaging tool. It should not become a general Ivy execution product, chat UI, or enterprise workflow engine.

## InnoLotus AI Product Model

- **LLM**: reasoning and solution generation provider.
- **Ivy**: execution and problem-solving platform.
- **Banyan**: proven memory, evidence, storage, trace, and provenance brain.
- **NeuronHub**: reserved for later definition.

Short form:

> LLM reasons. Ivy acts. Banyan remembers and proves.

## Banyan Distiller Smart Owns

- Model-assisted semantic extraction from source material.
- Ivy-assisted distillation workflow within the packaging boundary.
- Review queues for accepting, rejecting, or editing distilled knowledge.
- Facts, procedures, policies, entities, relations, citations, confidence, and provenance metadata extraction.
- `.banyanpack` generation compatible with Banyan Lite, Pro, and Ent.

## Banyan Distiller Smart Does Not Own

- General-purpose Ivy execution runtime.
- Chat UI or agent conversation shell.
- Enterprise workflow orchestration beyond distillation review workflows.
- Long-term memory serving or evidence storage runtime.
- Customer-specific business process automation.
- NeuronHub product semantics until NeuronHub is separately defined.

## Relationship To Ivy

Ivy is used here as an execution kernel or assistant for semantic distillation, not as the product owner.

The boundary is:

- Ivy helps plan, extract, classify, and validate knowledge during distillation.
- Banyan Distiller Smart owns the distillation workflow and `.banyanpack` output.
- Banyan nodes own mounting, serving, retrieval, evidence, and memory lifecycle.

## Alignment Actions

1. Keep Ivy usage scoped to distillation tasks.
2. Keep output compatible with the standard `.banyanpack` contract.
3. Keep chat and general user interaction work in Ivy-Chat.
4. Keep enterprise workflow automation in Ivy-Work.
5. Keep long-term memory storage and serving in Banyan nodes.
