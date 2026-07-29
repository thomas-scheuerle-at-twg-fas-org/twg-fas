# Frequently Asked Questions (FAQ)

## What is VML?

VML (Vehicle Machine Language) is a proposed formal language for describing vehicle behavior in a way that can be interpreted, verified, tested, monitored, and executed by deterministic systems.

Instead of allowing natural language to directly influence safety-critical runtime behavior, VML acts as a formal intermediate representation between human intent and vehicle execution. Foundation models may help create VML specifications, but runtime systems operate only on formally defined VML artifacts.

References: [VML White Paper (PDF)](webadministration/webpage/docs/VML_whitepaper_v0_1.pdf), [TWG-FAS Index (HTML)](webadministration/webpage/index.html)

## Is VML meant to replace AI?

No.

VML is not intended to replace AI, machine learning, perception systems, planners, or foundation models.

VML aims to provide a formal representation of behavioral intent that can be shared between engineering, planning, verification, simulation, testing, and runtime monitoring. The goal is to standardize the behavior description layer, not the AI implementation itself.

Reference: [VML White Paper (PDF)](webadministration/webpage/docs/VML_whitepaper_v0_1.pdf)

## Why not simply use natural language?

Natural language is excellent for communication between humans but problematic for safety-critical runtime systems.

A statement such as:

> "Yield to pedestrians when necessary"

leaves many questions unanswered:

- What is a pedestrian?
- What does "necessary" mean?
- What risk threshold triggers yielding?
- What happens if yielding is impossible?

VML requires such concepts to be expressed explicitly and formally, making the behavior analyzable and testable.

Reference: [VML White Paper (PDF)](webadministration/webpage/docs/VML_whitepaper_v0_1.pdf)

## Can an LLM generate VML?

Yes.

A large language model can serve as a semantic compiler that translates natural language requirements, regulations, design intent, or spoken instructions into VML.

For example:

> "Turn left when it is safe"

may be transformed into a formal specification involving risk thresholds, traffic participants, and fallback obligations.

However, the generated VML is then processed by deterministic components such as parsers, type checkers, monitors, and verification tools. The output can therefore be validated independently of the model that generated it.

Reference: [VML White Paper (PDF)](webadministration/webpage/docs/VML_whitepaper_v0_1.pdf)

## Could a vehicle be controlled by voice using VML?

Potentially yes.

A voice-controlled assistant could translate spoken commands into VML.

Example:

Driver says:

> "Park near the entrance but avoid blocking pedestrians."

An AI assistant could convert that request into VML constraints and goals.

Before execution, the resulting VML would be checked for:

- Syntactic correctness
- Semantic validity
- Safety rule compliance
- Conflicts with existing obligations

Only validated VML would be accepted by the runtime system. This differs fundamentally from directly executing natural-language instructions.

## Does VML require training new AI models?

Not necessarily.

Current state-of-the-art language models already demonstrate an ability to understand formal languages and structured specifications.

For experimentation and prototyping, large models may be used with only prompt-based explanations of VML.

However, specialized models trained or fine-tuned on VML are likely to be:

- Smaller
- Faster
- Cheaper
- More reliable

than general-purpose models.

VML therefore does not require custom training, but dedicated training may significantly improve efficiency and quality.

## Could VML run on embedded devices?

Potentially yes.

One motivation for VML is that understanding unrestricted natural language is computationally expensive. A language model that only needs to translate intent into a constrained formal language can be substantially smaller than a model that must support unrestricted language understanding.

The formal runtime components themselves (parsers, monitors, rule engines, and verifiers) can be implemented using classical software techniques.

Reference: [VML White Paper (PDF)](webadministration/webpage/docs/VML_whitepaper_v0_1.pdf)

## Is VML a programming language?

Not in the traditional sense.

VML is better viewed as a behavioral specification language. It focuses on:

- Obligations
- Prohibitions
- Goals
- Temporal constraints
- Safety policies
- Probabilistic reasoning

It describes what behavior is allowed, required, or forbidden, rather than how algorithms should be implemented.

Reference: [VML White Paper (PDF)](webadministration/webpage/docs/VML_whitepaper_v0_1.pdf)

## Is VML a file format?

No.

VML is a language specification, not a file format.

The current draft uses a human-readable ASCII syntax for transparency, review, and engineering collaboration. However, VML does not currently prescribe how artifacts must be stored, transported, or exchanged.

The standard focuses on semantics and language constructs, while implementations may choose different containers or encodings as long as the normative meaning is preserved.

Design principle: **Container neutrality.**

In short: **VML defines meaning, not storage.**


## Is VML similar to LTL (Linear Temporal Logic)?

VML builds upon ideas found in formal methods, including temporal logic, deontic logic, ontologies, probabilistic reasoning, and runtime verification.

However, VML is intended as an engineering language for real automotive systems rather than as a pure academic logic formalism. Its goal is to integrate multiple behavioral concerns into a single practical representation.

Reference: [VML White Paper (PDF)](webadministration/webpage/docs/VML_whitepaper_v0_1.pdf)

## How does VML support safety?

VML introduces deterministic semantics, explicit rules, monitor semantics, type checking, and verification interfaces.

A VML specification can be:

- Inspected by engineers
- Reviewed by auditors
- Analyzed by formal tools
- Monitored during runtime
- Tested in simulation

This makes behavioral intent transparent and traceable.

References: [VML White Paper (PDF)](webadministration/webpage/docs/VML_whitepaper_v0_1.pdf), [TWG-FAS Index (HTML)](webadministration/webpage/index.html)

## How is VML different from a planner cost function?

Traditional planners often encode many decisions inside large cost functions. This can make behavior difficult to interpret.

VML separates:

- Hard constraints
- Obligations
- Prohibitions
- Goals
- Optimization objectives

This allows behavior to be expressed explicitly while still supporting optimization-based planning.

Reference: [VML White Paper (PDF)](webadministration/webpage/docs/VML_whitepaper_v0_1.pdf)

## Is VML intended only for autonomous driving?

No.

While autonomous driving is a primary motivation, VML could potentially be applied to:

- Advanced Driver Assistance Systems (ADAS)
- Automated parking
- Robotics
- Industrial automation
- Autonomous logistics systems
- Other safety-critical autonomous platforms

The central concept is domain-independent: a formal representation of behavioral intent.

## How does VML relate to AI Governance?

VML does not govern AI models themselves. Instead, it provides a transparent and inspectable description of behavioral intent.

This separation may help:

- Safety assessments
- Regulatory reviews
- Compliance processes
- Traceability requirements
- Certification activities

A governance framework can review the behavioral specification independently of the underlying AI implementation.

Reference: [VML White Paper (PDF)](webadministration/webpage/docs/VML_whitepaper_v0_1.pdf)

## Is VML an open standard?

That is the intention.

The TWG-FAS initiative proposes a vendor-neutral, openly developed standard, allowing multiple independent implementations and avoiding lock-in to any specific AI architecture, vendor, or vehicle platform.

## Why is TWG·FAS organized as an open, non-profit initiative?

TWG·FAS believes that the formal specification of behavior in safety-critical autonomous systems should not be controlled by a single company, vendor, or proprietary ecosystem.

A proprietary behavioral standard would create natural barriers to adoption. Automotive manufacturers, suppliers, tool vendors, researchers, regulators, and certification bodies are unlikely to build long-term safety processes around a language controlled by a single commercial entity. Broad adoption requires a vendor-neutral foundation that all stakeholders can trust.

More importantly, autonomous driving systems raise questions that extend beyond commercial interests. Society, regulators, and certification authorities must be able to understand and evaluate the behavioral logic that governs vehicle decisions. An open standard allows behavioral intent, safety policies, and verification artifacts to be reviewed independently, without requiring companies to disclose proprietary algorithms, model architectures, training data, or intellectual property.

This separation is fundamental. Companies should be able to protect their innovations while still providing transparent evidence of how safety-critical behavior is specified, verified, and monitored.

TWG·FAS therefore views openness not only as an engineering choice but as an ethical responsibility. A common, openly governed standard can promote transparency, independent verification, regulatory cooperation, scientific research, and public trust. By enabling scrutiny of behavioral specifications while preserving legitimate intellectual property, the initiative aims to support the safe and responsible development of future autonomous systems.

In this sense, openness is not merely a governance model—it is a contribution to safety, accountability, and the public good.

References: [TWG-FAS Index (HTML)](webadministration/webpage/index.html), [VML White Paper (PDF)](webadministration/webpage/docs/VML_whitepaper_v0_1.pdf)