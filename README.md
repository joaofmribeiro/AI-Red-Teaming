**Overview**


This repository focuses on exploring and testing AI Red Teaming using PyRIT (Python Risk Identification Tool for Generative AI) — an open-source framework developed by Microsoft for systematically identifying safety, security, and misuse risks in generative AI systems.

The goal of this project is to demonstrate responsible, repeatable, and auditable AI risk testing, not to bypass safeguards in production systems.

**What Is AI Red Teaming?**
AI Red Teaming is the practice of intentionally stress-testing AI systems to uncover:

- Unsafe or harmful outputs
- Policy non-compliance
- Prompt injection vulnerabilities
- Jailbreak susceptibility
- Privacy or data leakage risks
- Robustness gaps across languages, formats, and contexts

Unlike traditional security testing, AI red teaming focuses on model behavior, not infrastructure exploitation.

**What Is PyRIT?**

PyRIT (Python Risk Identification Tool for Generative AI) is a framework designed to:

- Automate adversarial prompt testing
- Systematically vary prompts using converters
- Evaluate model responses using scorers
- Generate structured, auditable risk evidence
- Support enterprise AI governance and compliance

PyRIT is model-agnostic and can be used with commercial APIs, open-source models, or internal LLM deployments.



**Citing PyRIT**

cff-version: 1.2.0
message: "If you use this software, please cite it as below."
authors:
- family-names: "Microsoft, AI Red Team"
title: "PyRIT: The Python Risk Identification Tool for generative AI"
doi: https://doi.org/10.48550/arXiv.2410.02828
date-released: 2024-02-21
url: "https://github.com/Azure/PyRIT"

