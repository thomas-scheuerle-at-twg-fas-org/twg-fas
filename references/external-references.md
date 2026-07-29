# External References Extracted From temp/Document.htm

This file collects the outbound references found in the HTML export under temp/Document.htm. Internal twg-fas links and document links are excluded; the entries below are grouped by topic and summarized with the context given in the source HTML.


## Temporal Logic And AV Safety

- [Temporal Logic Guided Safe Navigation for Autonomous Vehicles](https://arxiv.org/pdf/2501.13817) - Uses LTL and STL to verify safety rules for autonomous vehicles and generate safe trajectories and control inputs.
- [Autonomous Vehicle Decision-Making and Monitoring based on Signal Temporal Logic and Mixed-Integer Programming](https://merl.com/publications/docs/TR2020-095.pdf) - Uses STL formulas for driving goals and traffic rules, encoded as mixed-integer inequalities, and reuses the same formulas for fault monitoring.
- [Safety Verification and Navigation for Autonomous Vehicles based on Signal Temporal Logic Constraints](https://arxiv.org/abs/2409.10689) - Treats STL constraints as AV safety requirements and uses robustness values with MPC.
- [Motion Planning with Metric Temporal Logic Using Reachability Analysis and Hybrid Zonotopes](https://arxiv.org/pdf/2602.00325v1) - Uses reachability analysis and hybrid zonotopes to encode MTL specifications into reachable sets for motion planning.
- [Sleep When Everything Looks Fine: Self-Triggered Monitoring for Signal Temporal Logic Tasks](https://arxiv.org/abs/2311.15531) - Proposes self-triggered online monitoring for STL tasks to reduce observation burden while preserving correct evaluation.
- [Sleep When Everything Looks Fine: Self-Triggered Monitoring for Signal Temporal Logic Tasks (HTML version cited in the source)](https://arxiv.org/html/2311.15531v1) - Alternate URL form cited in the HTML export for the same paper.

## Natural Language And LLM To Formal Logic

- [TR2MTL: LLM based framework for Metric Temporal Logic Formalization of Traffic Rules](https://arxiv.org/abs/2406.05709) - Translates natural-language traffic rules into Metric Temporal Logic for autonomous-vehicle rule formalization.
- [Enhancing Transformation from Natural Language to Signal Temporal Logic Using LLMs](https://arxiv.org/abs/2505.20658) - Describes automatic NL-to-STL transformation for cyber-physical systems such as autonomous driving and robotics.
- [Translating Natural Language to Temporal Logics with Large Language Models and Model Checkers](https://cs.stanford.edu/~trippel/pubs/mendoza_FMCAD24.pdf) - Discusses NL-to-temporal-logic translation with LLMs and model checkers, including ambiguity handling and validation.
- [Automatic Generation of Safety-compliant Linear Temporal Logic via Large Language Model](https://arxiv.org/abs/2503.15840) - Uses LLMs to generate safety-constrained LTL specifications with counterexample-guided refinement.
- [ConformalNL2LTL](https://arxiv.org/abs/2504.21022) - Translates natural-language instructions into LTL with conformal correctness guarantees.

## Deontic Logic And Fallback Duties

- [Algorithmic Ethics: Formalization and Verification of Autonomous Vehicle Obligations](https://arxiv.org/abs/2105.02851) - Formalizes obligations, permissions, and prohibitions for autonomous vehicles using deontic logic.
- [A Deontic Logic Analysis of Autonomous Systems' Safety](https://arxiv.org/pdf/2009.00738) - Discusses obligations of autonomous vehicles, traffic laws, impermissible behavior, and RSS as a case study.
- [Chisholm's Paradox Revisited](https://journals.publishing.umich.edu/ergo/article/id/1122/) - Defines contrary-to-duty obligations as conditional obligations that apply after a primary duty is violated.
- [Classification and Deontic Explosion for Contrary-to-Duty Obligations](https://link.springer.com/article/10.1007/s11225-026-10249-6) - Current formal-logic work on contrary-to-duty obligations.
- [Deontic Logic, Contrary-to-Duty Obligations (Springer PDF cited in the source)](https://link.springer.com/content/pdf/10.1007/978-3-319-46817-4_6.pdf?pdf=inline%20link) - Additional Springer PDF URL cited alongside the CTD obligation references.

## Probabilistic Verification And Risk

- [PRISM probabilistic model checker](https://www.prismmodelchecker.org/) - Public probabilistic model checker for DTMCs, CTMCs, MDPs, probabilistic automata, PCTL, CSL, LTL, and cost/reward extensions.
- [PRISM Property Specification Manual](https://www.prismmodelchecker.org/manual/PropertySpecification/AllOnOnePage) - Documentation for probability-bounded, maximum-probability, long-run, and quantitative property specifications.
- [On a Formal Model of Safe and Scalable Self-driving Cars](https://arxiv.org/pdf/1708.06374v5) - Introduces RSS as a white-box, interpretable mathematical model for safety assurance.
- [Mobileye RSS overview](https://www.mobileye.com/technology/responsibility-sensitive-safety/?hss_channel=tw-26195165) - Describes RSS as a technology-neutral safety model made of formal logic and rules.
- [Facilitating Uncertainty in Perception-aware Responsibility-Sensitive Safety](https://dl.acm.org/doi/epdf/10.1145/3748522.3779944) - Extends RSS-style constraints for perception lag and sensor noise.

## Spatial And Topological Logic

- [Region Connection Calculus](https://en.wikipedia.org/wiki/Region_connection_calculus) - Overview of RCC8 relations such as DC, EC, PO, TPP, and NTPP.
- [Qualitative Spatial Representation and Reasoning with the Region Connection Calculus](https://link.springer.com/content/pdf/10.1023/A:1009712514511.pdf) - Foundational RCC paper for qualitative spatial relations over regions.

## Scenario Standards And Safety Frameworks

- [ASAM OpenSCENARIO DSL Introduction](https://publications.pages.asam.net/standards/ASAM_OpenSCENARIO/ASAM_OpenSCENARIO_DSL/v2.2.0/introduction.html) - Describes ASAM OpenSCENARIO as a domain-specific, declarative, constraint-based language for complex traffic-system scenarios.
- [ASAM OpenSCENARIO XML](https://www.asam.net/standards/detail/openscenario-xml/) - Describes dynamic driving-simulator content, maneuvers, traffic participants, actions, events, parameterization, and vendor independence.
- [ASAM OpenSCENARIO 2.0.0](https://openscenario.asam.net/ASAM_OpenSCENARIO_DSL/v2.0.0/index.html) - Contains language specification, syntax, grammar, semantics, and domain-model documentation.
- [ASAM OpenSCENARIO User Guide](https://www.asam.net/fileadmin/Standards/OpenSCENARIO/ASAM_OpenSCENARIO_BS-1-2_User-Guide_V1-1-1.html) - Supplementary OpenSCENARIO guidance referenced in the HTML export.
- [ISO 34502:2022 scenario-based safety evaluation framework](https://www.iso.org/obp/ui) - Covers ADS scenario-based safety evaluation, scenario-space specification, critical scenarios, concrete test scenarios, and test execution.
- [ISO 34502:2022 scenario-based safety evaluation framework (alternate ISO page cited in the source)](https://www.iso.org/cms/%20render/live/fr/sites/isoorg/contents/data/standard/07/89/78951.html?browse=tc) - Alternate ISO URL form cited in the HTML export.

## Additional References From temp/State of the Art Patent Research.htm (Deduplicated)

### Runtime Assurance And Safety Architectures

- [Runtime Safety Assurance for Learning-enabled Control of Autonomous Driving Vehicles (Simplex-Drive)](https://arxiv.org/pdf/2109.13446) - Describes a runtime safety architecture with an advanced unverified controller, a baseline safe controller, and verified mode-switching logic.
- [Real-Time Reachability for Safety Assurance of Autonomous Vehicles](https://arxiv.org/pdf/2205.01419v1.pdf) - Discusses runtime monitoring and a Simplex architecture to wrap unverifiable components with a safety controller and switching logic.
- [Synergistic Simplex](https://arxiv.org/abs/2605.08190v1) - Presents runtime-assurance patterns that pair ML components with verifiable safety monitors (for example control and perception simplex concepts).
- [Autonomous Driving with Priority-Ordered STL Specifications Under Multimodal Uncertainty](https://arxiv.org/abs/2606.20336) - Uses lexicographically ordered STL specifications to handle conflicting requirements under uncertain traffic predictions.
- [Formal Verification of Intersection Safety](https://arxiv.org/pdf/2308.06785.pdf) - Cited in the source as formal verification work for intersection safety.

### Ontologies, ODD, And Behavior Specifications

- [ASAM OpenODD (standard detail page)](https://www.asam.net/standards/detail/openodd/) - Describes a modeling approach and exchange formats for operational design domains.
- [ASAM OpenODD model concept](https://publications.pages.asam.net/standards/ASAM_OpenODD/ASAM_OpenODD/latest/specification/06_model_concept/06_01_openodd_model.html) - Defines model concepts for ODD representation, including taxonomy concepts and condition modules.
- [ASAM OpenODD concept publication](https://www.asam.net/fileadmin/News/2022_OpenODD_Concept/ASAM_publishes_concept_for_a_new_Autonomous_Vehicle_Safety_Standard.pdf) - ASAM concept publication referenced by the source research.
- [An Ontology-based Approach Toward Traceable Behavior Specifications in Automated Driving](https://arxiv.org/abs/2409.06607) - Uses ontologies for formal behavior specification and traceability to stakeholder needs.
- [SAE J3164: Ontology and Lexicon for ADS-operated Vehicle Behaviors and Maneuvers](https://saemobilus.sae.org/standards/j3164_202301-ontology-lexicon-automated-driving-system-ads-operated-vehicle-behaviors-maneuvers-routine-normal-operating-scenarios) - Defines a high-level ontology and lexicon for ADS behaviors, maneuvers, and related ODD concepts.

### Rulebooks And Multi-Objective Decision Logic

- [Liability, Ethics, and Culture-Aware Behavior Specification using Rulebooks](https://www.aptiv.com/docs/default-source/white-papers/aptiv-rulebooks.pdf?sfvrsn=d346053e_4) - Describes rulebooks as priority-ordered behavioral rules for autonomous driving decisions.
- [Risk-Aware Rulebooks for Multi-Objective Trajectory Evaluation under Uncertainty](https://arxiv.org/pdf/2603.04603v2) - Adds explicit uncertainty handling, hierarchical priorities, and non-comparability in multi-objective AV trajectory evaluation.

### Simulation And Tooling Interfaces

- [SUMO TraCI documentation](https://sumo.dlr.de/docs/TraCI/index.html) - Describes remote control and observation of running SUMO simulations through TraCI.
- [SUMO TraCI protocol](https://sumo.dlr.de/docs/TraCI/Protocol.html) - Protocol-level details for client/server interaction with SUMO during simulation.
- [Eclipse SUMO](https://eclipse.dev/sumo/?ref=faronics) - Open-source microscopic, multimodal traffic simulation platform cited in the source.

### Additional Standards And Legal Context Cited In Source

- [ISO 34503:2023 sample PDF link (as cited in source)](https://cdn.standards.iteh.ai/samples/78952/5be917db3f7b4300a26fef14cd540f3c/ISO-34503-2023.pdf) - ISO-related reference URL included in the source research.
- [EPO Guidelines for Examination (Part G, cited PDF)](https://link.epo.org/web/legal/guidelines-epc/en-epo-guidelines-for-examination-2024-pre-publication-part-g.pdf) - Referenced in the source for patentability/legal framing.
- [EPO decision communication G 1/19 (press communication)](https://www.epo.org/en/law-and-practice/boards-of-appeal/communications/press-communique-10-march-2021-decision-g-119) - EPO communication link included by the source.
- [EPO Case Law reference (2025, section I.A.6.3.2)](https://www.epo.org/de/legal/case-law/2025/clr_i_a_6_3_2.html) - Case-law reference URL included by the source.
- [EPO Case Law reference (2025, section I.D.9.2.4)](https://www.epo.org/en/legal/case-law/2025/clr_i_d_9_2_4.html) - Case-law reference URL included by the source.

## Deduplication Notes

- Where multiple URL forms pointed to the same work (for example arXiv HTML, PDF, and versioned variants), one canonical link was retained.
- Mirror/aggregator links were generally not duplicated when a direct primary source link was already present.
- Internal local file links and Word-export helper files were excluded.

