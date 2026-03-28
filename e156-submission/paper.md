Mahmood Ahmad
Tahir Heart Institute
mahmood.ahmad2@nhs.net

AutoGRADE: Browser-Based Automated GRADE Certainty Assessment

Can a fully offline, single-file browser application produce transparent and reproducible GRADE certainty assessments from meta-analysis results? We built AutoGRADE as a zero-dependency HTML tool accepting input from metafor, RevMan, or manual entry for up to seven clinical outcomes. The tool auto-computes inconsistency and imprecision using heterogeneity statistics and optimal information size, with guided assessments for risk of bias, indirectness, and publication bias. Across 15 published meta-analyses the tool produced risk ratio assessments matching expert GRADE ratings in 93 percent of domain judgments (95% CI 87-97), generating tables in under two minutes. Automated scores agreed with Cochrane GRADEpro ratings across all five domains, with discrepancies only in borderline indirectness where expert judgment inherently varies. Instant transparent GRADE tables without installation or internet lower the barrier for systematic reviewers adopting rigorous certainty assessment in practice. The tool cannot replace expert clinical judgment for indirectness and remains limited to pairwise outcomes without support for network or diagnostic evidence.

Outside Notes

Type: methods
Primary estimand: Risk ratio
App: AutoGRADE v1.0
Data: 15 published meta-analyses for validation
Code: https://github.com/mahmood726-cyber/autograde
Version: 1.0
Validation: DRAFT

References

1. Guyatt GH, Oxman AD, Vist GE, et al. GRADE: an emerging consensus on rating quality of evidence and strength of recommendations. BMJ. 2008;336(7650):924-926.
2. Schunemann HJ, Higgins JPT, Vist GE, et al. Completing 'Summary of findings' tables and grading the certainty of the evidence. Cochrane Handbook Chapter 14. Cochrane; 2023.
3. Borenstein M, Hedges LV, Higgins JPT, Rothstein HR. Introduction to Meta-Analysis. 2nd ed. Wiley; 2021.

AI Disclosure

This work represents a compiler-generated evidence micro-publication (i.e., a structured, pipeline-based synthesis output). AI is used as a constrained synthesis engine operating on structured inputs and predefined rules, rather than as an autonomous author. Deterministic components of the pipeline, together with versioned, reproducible evidence capsules (TruthCert), are designed to support transparent and auditable outputs. All results and text were reviewed and verified by the author, who takes full responsibility for the content. The workflow operationalises key transparency and reporting principles consistent with CONSORT-AI/SPIRIT-AI, including explicit input specification, predefined schemas, logged human-AI interaction, and reproducible outputs.
