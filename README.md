# DIKWP-INTENTFIELD²

**Definition-Free Intent Field, DIKWP×DIKWP Semantic Navigation and Problem-Kernel Discovery System**  
中文：**无定义意图场、网状语义空间突破与本质问题核发现系统**

## Why this system exists

DIKWP-INTENTFIELD² corrects a recurrent implementation drift: treating a familiar concept label as the inquiry object, pre-installing a concept registry or candidate semantic axes, and then asking DIKWP to enrich that concept. This package reverses the direction.

It starts from:

- a change someone intends to realize;
- conditions that must be preserved;
- outcomes that must be avoided;
- provenance-carrying traces from multiple observers;
- a co-equal DIKWP×DIKWP transformation mesh;
- unresolved residuals and counterfactual actions.

It does **not** produce a universal definition, a final category, an essence score, or an observer-free ontology.

## Core correction

1. There is no required top-level `concept` field.
2. Surface terms can be masked or renamed; the problem kernel should remain stable.
3. Intent is a revisable field, not a privileged P node or supreme controller.
4. All 25 ordered DIKWP×DIKWP transformations are present.
5. Routes are compared as a Pareto set; no single scalar truth score is emitted.
6. A “problem kernel” is an intent-indexed minimal intervention relation set, not a definition.
7. Unrepresented structure is emitted as an opaque `UAX-xxxx` residual coordinate with tests and rollback, not a newly named concept.
8. Every output retains observer, context, affected parties and provenance.

## Main modules

- `IntentSemanticMesh`: multi-observer semantic traces and transformations.
- `TransformRegistry`: all 25 DIKWP×DIKWP inquiry moves plus anti-definition guards.
- `TrajectoryExplorer`: cyclic, non-hierarchical route enumeration and Pareto filtering.
- `ConceptErasureEngine`: masks lexical anchors and compares route/kernel stability.
- `ProblemKernelMiner`: obstruction, preservation, discrimination and intent-revision relations.
- `ResidualAxisLab`: discovers unnamed residual coordinates without a hard-coded axis catalog.
- `ActionHypothesisCompiler`: compiles reversible experiments instead of final answers.
- `NoDefinitionAudit`: rejects concept registries, final definition language, scalar truth collapse and purpose monarchy.

## Quick start

```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -e '.[dev]'

python -m dikwp_intentfield2.cli analyze \
  examples/era_of_experience_intent_bundle.json \
  --out outputs

python -m unittest discover -s tests -v
```

Open `outputs/dashboard.html` after the run.

## Demonstration

The included synthetic demonstration asks how long-running AI systems may learn from real-world consequences without converting people, society or the environment into unauthorized optimization material. Two conflicting intent fields are supplied:

- rights-preserving, auditable real-world learning;
- faster feedback-to-update cycles.

The same semantic mesh is traversed under both intents. The output shows which relations persist, which change with the agenda, which residues remain unnamed, and which reversible experiments can distinguish routes.

## Boundaries

This is a research and design reference implementation. It does not define consciousness, life, experience, intelligence, fairness or any other concept. It does not certify scientific truth, authorize real-world experiments, replace domain experts or make high-impact decisions.
