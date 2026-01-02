**AI Red Teaming with PyRIT**

Overview
This repository focuses on AI Red Teaming using PyRIT (Python Risk Identification Tool for Generative AI) — an open-source framework developed by Microsoft for systematically identifying safety, security, and misuse risks in generative AI systems.

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


@misc{munoz2024pyritframeworksecurityrisk,
      title={PyRIT: A Framework for Security Risk Identification and Red Teaming in Generative AI Systems},
      author={Gary D. Lopez Munoz and Amanda J. Minnich and Roman Lutz and Richard Lundeen and Raja Sekhar Rao Dheekonda and Nina Chikanov and Bolor-Erdene Jagdagdorj and Martin Pouliot and Shiven Chawla and Whitney Maxwell and Blake Bullwinkel and Katherine Pratt and Joris de Gruyter and Charlotte Siska and Pete Bryan and Tori Westerhoff and Chang Kawaguchi and Christian Seifert and Ram Shankar Siva Kumar and Yonatan Zunger},
      year={2024},
      eprint={2410.02828},
      archivePrefix={arXiv},
      primaryClass={cs.CR},
      url={https://arxiv.org/abs/2410.02828},
}
