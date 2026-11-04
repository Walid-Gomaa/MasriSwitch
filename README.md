# MasriSwitch
## A Benchmark for Evaluating LLMs on Egyptian Arabic–English Code-Switching and Arabizi

**Institution:** Egypt-Japan University of Science and Technology (E-JUST), Egypt

**Principal Investigator:** Prof. Walid Gomaa

**Co-Principal Investigator:** Prof. Ahmed Fares

**Project Status:** Proposed research — dataset development has not yet started.

**Funding Application:** Amazon Research Awards (ARA) — Multilingual and Contextual AI Evaluation, Fall 2026.

### 1. Project Overview

MasriSwitch aims to develop an open benchmark and evaluation framework for assessing the performance, robustness, and fairness of large language models (LLMs) when processing Egyptian Arabic–English code-switching and Arabizi (Arabic written using Latin characters and numerals).

Egyptian Arabic speakers frequently combine Arabic and English in everyday communication, particularly in education, technology, and professional settings. These linguistic patterns are not adequately represented in many existing multilingual AI benchmarks.

The project will investigate how code-switching, dialectal expressions, and script variation affect LLM accuracy, instruction following, and conversational reliability.

### 2. Research Objectives

The project has five main objectives:

1. Develop a new, human-validated benchmark of approximately 4,000 evaluation prompts.
2. Evaluate existing LLMs on Egyptian Arabic–English code-switching, dialectal expressions, and Arabizi.
3. Quantify performance differences across equivalent linguistic variants.
4. Investigate practical techniques for improving model robustness and reducing linguistic disparities.
5. Release the benchmark, evaluation software, and experimental results openly.

### 3. Planned Dataset

The MasriSwitch dataset will be created primarily from original linguistic scenarios designed by the research team and validated by native Egyptian Arabic speakers.

The benchmark will include approximately 4,000 prompts derived from around 800 underlying scenarios, with controlled variations across:

- English
- Modern Standard Arabic (MSA)
- Egyptian colloquial Arabic
- Egyptian Arabic–English code-switching
- Arabizi and mixed-script writing

The scenarios will cover question answering, instruction following, and multi-turn conversational tasks drawn from realistic educational, technical, administrative, and everyday situations.

Each example will be accompanied by relevant language and task annotations, reference answers or evaluation criteria, and human validation where appropriate.

### 4. Data Sources and Provenance

**The primary dataset will be newly created as part of the MasriSwitch research project. It is not derived from an existing proprietary or commercial dataset.**

Planned sources include:

- Original scenarios authored by the E-JUST research team.
- Linguistic variants prepared by native Egyptian Arabic speakers.
- Voluntary linguistic contributions from consenting participants.
- Human annotations and validation by trained evaluators.

The project does not plan to scrape private communications or collect personal conversations from social media platforms.

Any supplementary publicly available resources will be documented with their original URLs, provenance information, and applicable licenses before inclusion.

This repository serves as the project's public documentation and planned distribution location. No dataset has been released at this stage.

### 5. Evaluation Methodology

The project will evaluate multiple existing pretrained LLMs using metrics such as:

- Task accuracy and answer correctness.
- Semantic consistency across linguistic variants.
- Robustness to code-switching and transliteration.
- Instruction-following performance.
- Language-dependent performance disparities.
- Human-assessed response quality.

Evaluation experiments are planned using AWS services, including Amazon Bedrock and Amazon SageMaker.

No new foundation model will be trained as part of the project.

### 6. Research Ethics and Privacy

The project will follow applicable E-JUST research ethics requirements.

Human contributors will be informed about the research purpose, data collection procedures, and intended public release. Informed consent will be obtained where required.

The publicly released benchmark will exclude personally identifiable information. Research data will be reviewed before release to ensure privacy protection and compliance with applicable licensing requirements.

### 7. Open-Source Release

The intended licenses are:

- **Dataset and annotations:** Creative Commons Attribution 4.0 International (CC BY 4.0).
- **Evaluation code and software tools:** Apache License 2.0.

Public release is subject to verifying participant permissions, third-party rights, and any necessary institutional approvals.

The project intends to publish the benchmark and evaluation tools through GitHub and Hugging Face, together with documentation supporting reproducible experiments.

### 8. Planned Deliverables

- MasriSwitch multilingual benchmark dataset.
- Human-validated annotations and evaluation guidelines.
- Open-source evaluation and scoring toolkit.
- Comparative analysis of multilingual LLM performance.
- Research publications and publicly available experimental results.

### 9. Project Timeline

**Proposed duration:** 12 months, April 2027 – March 2028, subject to funding and institutional approvals.

### 10. Contact

**Prof. Walid Gomaa**

Department of Computer Science and Engineering

Egypt-Japan University of Science and Technology (E-JUST)

Egypt

**Email:** walid.gomaa@ejust.edu.eg

---

*MasriSwitch is currently a proposed research project. Its datasets, software, experiments, and deliverables described above represent planned work and are not yet available.*
