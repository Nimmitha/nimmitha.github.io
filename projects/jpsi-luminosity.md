---
layout: default
title: Luminosity from J/ψ counting
---

# Luminosity from J/ψ counting

## What it is
Luminosity is how an experiment turns counted events into a measured rate, and every cross-section measurement at the LHC depends on it. This analysis measures CMS's Run 3 luminosity from a different observable than the dedicated detectors: the rate of reconstructed J/ψ → μ⁺μ⁻ decays.

## What I did
- Extracted J/ψ yields from unbinned fits to the dimuon mass distribution
- Calibrated the rate to an absolute scale with emittance-scan data
- Corrected for pileup dependence and for gradual and sudden changes in detector response, using a tracker-based observable
- Evaluated the uncertainties and compared the result with other luminosity measurements over the same data-taking intervals
- Presented the progress to the CMS luminosity group and addressed review comments

## Status
Documented in CMS Analysis Note AN-25-127 (with S. Spanier), under review by the collaboration's luminosity group (BRIL). I do not quote numbers while the review is open.

## Tools
Python, ROOT, unbinned likelihood fits, brilcalc, git (CERN GitLab)
