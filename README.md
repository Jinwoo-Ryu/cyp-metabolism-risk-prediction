# cyp-metabolism-risk-prediction
Predicting CYP-mediated drug metabolism risk from a pharmacist's perspective
## Problem Statement
Cytochrome P450–mediated metabolism, particularly via CYP3A4,
is one of the leading causes of drug failure during clinical development.
Compounds with high metabolic liability often show reduced exposure,
drug–drug interactions, or unexpected toxicity.

As a pharmacist, this project defines clinically meaningful risk categories
for CYP-mediated metabolism and aims to predict high-risk compounds early
using machine learning models based on molecular structure.

The ultimate goal is not model accuracy alone,
but supporting better decision-making in early drug discovery.
## Risk Definition
In this project, CYP3A4 metabolic risk is defined based on in vitro inhibition potency.

Compounds with IC50 values below 1 μM are classified as high risk,
as such potency is commonly associated with clinically relevant
drug–drug interactions or rapid metabolic clearance.

This binary definition prioritizes minimizing false negatives,
since missing a high-risk compound in early discovery
can lead to costly late-stage failures.
## Project Scope
This project focuses on early-stage risk assessment
and does not aim to replace experimental validation.
## ADMET Context
This project focuses on the metabolism (M) component of ADMET,
specifically CYP3A4-mediated drug–drug interaction (DDI) risk.

In early-stage drug discovery, ADMET assessment is used not to achieve
perfect prediction accuracy, but to conservatively filter out compounds
with a high probability of late-stage failure.

By prioritizing sensitivity over specificity,
this approach aims to minimize false negatives,
where high-risk compounds could otherwise advance
into costly optimization or clinical stages.