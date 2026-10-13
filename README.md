
# Engineering Document Quality Assurance — ChatGPT-Assisted Case Study

## Project Overview

This project demonstrates a structured, ChatGPT-assisted approach to reviewing engineering maintenance documentation. The review uses a fictional six-step centrifugal pump maintenance procedure for equipment P-101.

The objective is to identify documentation gaps, ambiguous instructions, missing acceptance criteria, safety-related omissions, and items requiring further verification.

**Project type:** AI-assisted engineering document QA case study  
**Domain:** Mechanical Engineering, Industrial Maintenance, Technical Documentation  
**Tools:** ChatGPT, GitHub, structured review prompts, PDF reports

## Objectives

- Identify missing information and ambiguous maintenance instructions.
- Trace findings to the relevant source-procedure steps.
- Recommend corrective actions and appropriate verification sources.
- Distinguish documentation gaps from confirmed real-world hazards.
- Compare a baseline review with a review using more explicit instructions.
- Document limitations and the need for qualified human verification.

## Methodology

### Run 1 — Fresh Baseline Review

A fresh review was prepared using the fictional maintenance procedure and a structured prompt. The report identifies documentation gaps and provides a findings register, checklist, unanswered questions, and safety limitations.

### Run 2 — Improved Review Instructions

A second review used more explicit instructions for finding traceability, priority rationale, confidence ratings, non-duplication, and verification planning.

### Comparison

The two available reports were compared to examine differences in finding coverage, structure, uncertainty handling, and verification planning. The comparison records observed differences rather than assuming that a higher finding count automatically means better quality.

**Execution transparency:** The reports were prepared in separate ChatGPT conversations with human-directed prompts. This repository documents a ChatGPT-assisted iterative review workflow. It does not demonstrate an independently deployed or autonomous AI agent, and no separate agent-platform trajectory has been captured.

## Key Results

- **Run 1:** 9 preliminary documentation findings.
- **Run 2:** 13 preliminary documentation findings.
- Run 2 adds more explicit priority rationales and confidence ratings.
- Run 2 provides a more structured verification plan and checklist.
- The comparison highlights the importance of traceability, uncertainty handling, and human review.

Finding counts are descriptive, not a standalone measure of quality. The findings require technical review to assess accuracy, overlap, and practical relevance.

## Repository Contents

| File | Description |
|---|---|
| `Run_1_Engineering_Document_QA_Report.pdf` | Fresh baseline review report |
| `Run_2_Engineering_Maintenance_Procedure_Quality_Review.pdf` | Review using improved instructions |
| `Run_1_vs_Run_2_Engineering_Document_QA_Comparison.pdf` | Updated comparison of the two review outputs |
| `Run_1_vs_Run_2_Comparison_and_Final_Capstone_Report.pdf` | Earlier comparison and capstone report |

## Review Criteria

The reviews consider:

- Energy isolation and verification requirements
- Safe access and risk-assessment references
- PPE requirements and applicable procedures
- Inspection methods and acceptance criteria
- Component damage and replacement criteria
- Reassembly, pre-start checks, and restart authorization
- Post-start monitoring and maintenance records
- Document control, unresolved questions, and verification needs

## Limitations and Safety

- The maintenance procedure is fictional and intended for training.
- The findings have not been independently validated against an OEM manual, site procedure, engineering drawing, or formal risk assessment.
- Priorities are preliminary reviewer judgments, not formal risk ratings.
- A gap in the supplied excerpt does not prove that a control is absent from the wider site maintenance system.
- The reports must not be used as operational maintenance instructions or as evidence of procedure approval.
- Qualified personnel must verify engineering and safety requirements before real-world use.

## Skills Demonstrated

- Engineering documentation review
- Technical writing and quality assurance
- Prompt design and instruction refinement
- Evidence traceability and structured reporting
- Comparative output evaluation
- Identification of uncertainty and verification requirements
- Safety-aware human oversight

## Project Links

- [GitHub Repository](https://github.com/sayooj-kp/engineering-document-qa-agent)
- [Portfolio Website](https://sayooj-kp.github.io)

---

**Summary:** This case study illustrates how structured prompts and human review can support engineering document quality assurance. It emphasizes traceable findings, careful handling of uncertainty, and transparent reporting of limitations.
