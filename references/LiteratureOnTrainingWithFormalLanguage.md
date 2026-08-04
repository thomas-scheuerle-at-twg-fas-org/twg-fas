# Literature On Training With Formal Language

This file lists papers relevant to training language models with formal, procedural, code-like, or restricted language data. Each entry is deduplicated and limited to:

- topic description
- abstract-focused summary

## Formal Language And Procedural Pretraining

### [Between Circuits and Chomsky: Pre-pretraining on Formal Languages Imparts Linguistic Biases](https://aclanthology.org/2025.acl-long.478/)
- Topic: Pretraining language models on formal languages before natural language.
- Abstract summary: The paper studies which properties of formal languages transfer to natural-language modeling. It reports that transfer improves when the pretraining language encodes dependency structures aligned with linguistic structure and remains compatible with transformer computational limits.

### [Procedural Pretraining: Warming Up Language Models with Abstract Data](https://arxiv.org/html/2601.21725)
- Topic: Early-stage training with synthetic procedural data such as Dyck languages and simple algorithms.
- Abstract summary: The work evaluates whether a small amount of abstract procedural data can improve downstream performance and data efficiency. It reports strong gains in long-context recall and better pretraining efficiency compared with natural-language-only baselines.

### [Learning Syntax Without Planting Trees: Understanding Hierarchical Generalization in Transformers](https://arxiv.org/abs/2404.16367)
- Topic: Hierarchical syntax generalization learned from synthetic grammars.
- Abstract summary: The paper compares training objectives and their ability to induce hierarchical generalization. It reports that objective choice is critical, with language-model-style training showing substantially stronger hierarchical generalization than several alternative objectives.

### [Length Generalization Bounds for Transformers](https://arxiv.org/html/2603.02238v1)
- Topic: Formal limits of transformer length generalization on symbolic languages.
- Abstract summary: The paper gives theory for when finite-length training can or cannot guarantee correct behavior on longer inputs. It provides negative and positive results for different transformer-linked language classes.

### [What Formal Languages Can Transformers Express? A Survey](https://arxiv.org/pdf/2311.00208v3)
- Topic: Transformer expressivity for formal-language recognition and generation.
- Abstract summary: This survey synthesizes formal-language results on transformer capabilities and limitations, connecting automata theory, logic, and circuit viewpoints to practical questions about generalization and architecture.

## Code-Structured Data And Reasoning

### [On Code-Induced Reasoning in LLMs](https://arxiv.org/abs/2509.21499v1)
- Topic: How code and code-like structure affect reasoning performance.
- Abstract summary: The paper analyzes reasoning transfer from code-structured data across many controlled experiments. It reports that structural properties and representation format strongly influence reasoning gains, including effects from pseudocode and alternate programming-language syntax.

### [Not All Code Is Equal: A Data-Centric Study of Code Complexity and LLM Reasoning](https://arxiv.org/html/2601.21894v1)
- Topic: Code complexity as a training signal for reasoning.
- Abstract summary: The paper studies how structural complexity metrics in code data shape downstream reasoning outcomes. It reports that selecting suitable complexity ranges can outperform training on broad, unfiltered code mixtures.

## Restricted Natural-Language Mixtures

### [When Is Multilinguality a Curse? Language Modeling for 250 High- and Low-Resource Languages](https://aclanthology.org/2024.emnlp-main.236.pdf)
- Topic: Trade-offs in multilingual data mixtures under limited model capacity.
- Abstract summary: The study runs large-scale multilingual and monolingual experiments to quantify transfer and interference effects. It reports that moderate multilingual data can help low-resource languages, while larger mixtures can degrade performance due to capacity and data-allocation trade-offs.

### [ATLAS: Adaptive Transfer Scaling Laws for Multilingual Pretraining, Finetuning, and Decoding the Curse of Multilinguality](https://arxiv.org/abs/2510.22037)
- Topic: Scaling laws for multilingual transfer and performance balancing.
- Abstract summary: The paper introduces adaptive transfer scaling laws and analyzes cross-lingual transfer patterns across model and language scales. It provides a quantitative framework for choosing multilingual training mixtures.

### [The Role of Mixed-Language Documents for Multilingual Large Language Model Pretraining](https://arxiv.org/html/2601.00364v2)
- Topic: Effect of bilingual and mixed-language documents during pretraining.
- Abstract summary: The paper isolates mixed-language corpus components and measures capability impact. It reports that translation quality is highly sensitive to bilingual alignment data, while broader cross-lingual reasoning appears less sensitive.

