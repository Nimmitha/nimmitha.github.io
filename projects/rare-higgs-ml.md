---
layout: default
title: A blinded search for H → ZJ/ψ with machine learning
---

# A blinded search for H → ZJ/ψ with machine learning

## What it is
A search for a rare Higgs boson decay, H → ZJ/ψ, in Run-2 CMS data in the 4μ and 2e2μ final states. The Standard Model rate is very small, so the analysis tests for an enhanced rate. The analysis is blinded.

## What I did
- Developed the event selection
- Trained random-forest classifiers (TMVA; scikit-learn and XGBoost in exploratory studies) on simulated signal and data sidebands
- Validated the classifier on held-out samples, checked its correlation with the four-lepton mass, and retrained it 100 times with independent random seeds (2% model-variation uncertainty)
- Extended the mass-based approach to a two-dimensional likelihood combining the mass and the classifier score, using CMS Combine and the CLs method

## Result (blinded, expected)
The expected 95% confidence-level limit on the branching fraction improves from 2.2 × 10⁻³ using the four-lepton mass alone to 0.78 × 10⁻³ with the two-dimensional model. This is an expected sensitivity, not an observed limit or a published CMS result.

## Tools
Python, ROOT, TMVA, scikit-learn, XGBoost, CMS Combine, CRAB (private Run-3 signal simulation)
