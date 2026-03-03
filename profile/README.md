# OpenBWC

> Open-source tools for ethical analysis of body-worn camera footage

[![Research](https://img.shields.io/badge/Stage-Research%20%26%20Development-orange.svg)]()
[![Website](https://img.shields.io/badge/Website-openbwc.org-blue)](https://openbwc.org)

---

## Mission

**Accurately interpret Police BWC footage by employing open source ML, CV, & NLP technologies, resulting in identifiable behavioral patterns among police & civilians, analyzed in an interdisciplinary setting.**

## Vision

**Improve policing through evidence-based recommendations sourced from BWC footage by leveraging AI in an ethical and unbiased manner.**

---

## The Challenge

**99% of Body-Worn Camera footage is never reviewed.** The vast majority of policing captures officers simply doing their jobs—a reality that stays hidden due to privacy laws and massive data volume.

This creates a critical gap: without systematic analysis, we miss opportunities to understand effective policing practices, identify training needs, and build evidence-based policy.

---

## About

OpenBWC is a research initiative developing open-source artificial intelligence tools to analyze police body-worn camera (BWC) footage. We combine computer science, social science, and criminal justice expertise to create interpretable, bias-audited analysis systems that serve the public interest.

### What Makes Us Different

- **Open Source** - Transparent methods, auditable code, no vendor lock-in
- **Ethics First** - Bias minimization built into every layer
- **Research-Grade** - Confidence scoring and uncertainty quantification
- **Interdisciplinary** - Computer science + social science + criminal justice
- **Academic Rigor** - Peer-reviewed methods and findings

---

## Research Focus

### Core Research Questions

1. **Behavioral Patterns** - What communication and interaction patterns emerge in police-civilian encounters?
2. **De-escalation** - What verbal and non-verbal techniques correlate with successful de-escalation?
3. **Use of Force** - What precursors can be identified before force escalation?
4. **Training & Policy** - How can AI-assisted analysis inform evidence-based training and policy recommendations?

### Methodology

Our interdisciplinary approach integrates:
- **Machine Learning & NLP** - Multi-model transcription with confidence scoring
- **Computer Vision** - Visual analysis of BWC footage
- **Speaker Diarization** - Identifying who spoke when, even with overlapping speech
- **Social Science Methods** - Qualitative and quantitative analysis frameworks
- **Continuous Bias Auditing** - Algorithmic fairness monitoring throughout the pipeline

---

## TrustScript Pipeline

Our core technology is **TrustScript**, a multi-model pipeline for processing BWC footage with interpretable confidence scores.

### Key Features

- **Multi-Model Fusion** - Combines ASR systems for robust transcription
- **Confidence Quantification** - Every word tagged with multi-source confidence scores
- **Overlap Handling** - Speaker re-identification for concurrent speech
- **Research-Grade Output** - Detailed metadata for reproducibility and auditing
- **Human-in-the-Loop** - Prioritized review based on confidence scores


## Ethics & Bias Minimization

We take algorithmic fairness seriously. Our multi-level bias mitigation strategy includes:

### Technical Safeguards
- **Continuous Auditing** - Regular fairness testing across demographic groups
- **Performance Monitoring** - Track model accuracy and calibration by subgroup
- **Transparency** - All confidence sources documented and interpretable

### Research Safeguards
- **Interdisciplinary Review** - CS + social science + ethics oversight
- **Privacy Protection** - Anonymization and secure data handling
- **Stakeholder Engagement** - Input from law enforcement, communities, and experts

### Methodological Safeguards
- **Stratified Sampling** - Ensure diverse representation in analysis
- **Counterfactual Reasoning** - Test alternative explanations
- **Open Documentation** - Publish methods, limitations, and findings

> **We do not build predictive policing tools.** Our work is descriptive and analytical, focused on understanding what happened, not predicting future behavior.

---

## Partnership

We collaborate with the **Rochester Police Department (RPD)** in Rochester, New York, through a research partnership that balances transparency with privacy protections.

Our partnership is governed by:
- Institutional Review Board (IRB) oversight
- Memorandum of Understanding with clear data use terms
- Privacy-first data handling protocols
- Community stakeholder engagement

---


## Academic Contributions

### Research Outputs (Planned)
- **Technical Papers** - TrustScript methodology and benchmarks
- **Ethics Framework** - Bias minimization in policing AI research
- **Policy Recommendations** - Evidence-based guidance for law enforcement
- **Open Datasets** - Annotated data for research community (privacy-protected)

### Educational Mission
- Training future researchers in ethical AI development
- Advancing interdisciplinary research methods
- Contributing to public understanding of AI in criminal justice

---

## Project Status

**Current Phase:** Active Research & Development

### Recent Milestones
- TrustScript core pipeline developed
- Multi-model transcription with confidence scoring
- Speaker re-identification for overlapping speech
- Bias auditing framework established
- GroundTruth annotation interface prototype



## Repository Structure

*(This section will be populated as we release code)*

```
openbwc/
├── trustscript/          # Core processing pipeline
├── groundtruth/          # Annotation interface
├── bias-auditing/        # Fairness monitoring tools
├── notebooks/            # Research notebooks and examples
├── docs/                 # Documentation
└── papers/               # Research publications
```

---

## Contributing

We welcome contributions from researchers, developers, and domain experts. Areas where we need help:

- **Audio Processing** - Improving robustness to noisy BWC environments
- **Bias Auditing** - Developing fairness metrics for policing contexts
- **Social Science** - Qualitative analysis frameworks
- **Documentation** - Making our work accessible
- **Use Cases** - Identifying ethical applications

**Coming Soon:** Contribution guidelines and code of conduct

---

## Licensing & Open Source Philosophy

Open-source transparency is a core pillar of OpenBWC. We believe that tools used in the analysis of public infrastructure, particularly in criminal justice, must be auditable, reproducible, and transparent to maintain public trust.

### Our Commitment

Every tool, model, and framework produced by the OpenBWC initiative will be released under an **Open Source Initiative (OSI) approved license**. This ensures that our work remains a public good, free from vendor lock-in and accessible for independent audit.

### Multi-License Architecture

Because OpenBWC is a multi-disciplinary toolkit—ranging from high-level research interfaces to low-level systems code—we may utilize different licenses to best suit each component's use case:

* **Core Logic & Frameworks:** Components like our pipeline will be licensed under the [AGPL](https://www.google.com/search?q=LICENSE), prioritizing maximum permissive reuse for the research community.
* **Infrastructure & Tooling:** Supporting tools, such as the **OpenBWC Project Guide** or **GroundTruth** annotation prototypes, may be released under licenses that encourage community contribution while protecting the integrity of the core research.
* **Research Outputs:** While code is open-source, specific **Open Datasets** and **Peer-Reviewed Methodologies** will be released under appropriate open-access licenses (such as Creative Commons) that balance transparency with strict privacy and Institutional Review Board (IRB) protections.

> **Note:** As we transition from active R&D toward a stable release in **October 2026**, specific license files will be added to each sub-repository within the `openbwc/` organization to provide definitive legal clarity for each module.

---


## Contact & Resources

- **Website:** [openbwc.org](https://openbwc.org)
- **Publications:** [openbwc.org/publications](https://openbwc.org/publications.html)
- **GitHub:** [github.com/OpenBWC](https://github.com/OpenBWC)

---

## Acknowledgments

- **Rochester Police Department** - Partnership and data access
- **RIT Faculty & Students** - Research collaboration
- **Department of Justice** - Grant support
- **Open Source Community** - Tools and frameworks that make this work possible

---

## Important Notes

### What This Project Is
- Research tool for understanding police-civilian interactions
- Open-source alternative to proprietary BWC analysis systems
- Framework for ethical AI in criminal justice contexts

### What This Project Is NOT
- Predictive policing or risk assessment tool
- Surveillance technology
- Replacement for human judgment
- Production-ready commercial software (yet)

### Responsible Use
We are committed to ensuring our tools are used ethically. Our research is designed to:
- Improve police training and accountability
- Inform evidence-based policy
- Advance academic understanding
- Protect civil rights and privacy

**Misuse Notice:** This technology should not be used for mass surveillance, predictive policing, or any application that violates civil rights.

---

## Learn More

- [Visit our website](https://openbwc.org) - Learn about our mission and approach
- [Read our publications](https://openbwc.org/publications.html) - Academic papers and research findings
- [Technical Documentation](docs/technical.md) - Coming soon
- [Ethics Framework](docs/ethics.md) - Coming soon

---

## Support This Work

If you're interested in supporting ethical AI research in criminal justice:
- **Star this repository** to follow our progress
- **Share** our work with researchers and policymakers
- **Engage** in discussions about AI ethics
- **Collaborate** - reach out if you have relevant expertise

---

<div align="center">

**Building transparent, ethical AI for a more just society**

[Website](https://openbwc.org) • [Publications](https://openbwc.org/publications.html) • [GitHub](https://github.com/OpenBWC)

</div>
