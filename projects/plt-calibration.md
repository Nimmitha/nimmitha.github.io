---
layout: default
title: Pixel Luminosity Telescope calibration and monitoring
---

# Pixel Luminosity Telescope calibration and monitoring

## What it is
The Pixel Luminosity Telescope (PLT) is a CMS detector built from silicon pixel sensors that measures luminosity bunch by bunch. I worked on its calibration and performance in the CMS luminosity group (BRIL) at CERN from April 2022 to November 2023, and afterwards.

## My own work
- Estimated backgrounds from track-slope distributions
- Tracked the detector's response over 2022–2023, separating radiation-driven drift from operating-point changes
- Devised a method that extracts the rate-dependent nonlinearity without a second luminometer as a reference; it reduced the effect by about a factor of two in 2022
- Built a framework that extracts PLT tracks per fill from the readout stream into a database
- Handled routine PLT monitoring and took CMS control-room shifts

## Team work
- Part of the BRIL team that sets CMS's absolute luminosity scale: fitted Run-3 van der Meer scan data, estimated beam-induced backgrounds, and performed online visible-cross-section calibrations of the luminometers
- Built an automated analysis chain that processes emittance-scan files as they arrive, replacing manual processing
- Maintained the shared calibration software (VdMFramework): fixes, features, physics updates
- Directed a student's development of an HTCondor tool for large-scale reprocessing and extended it

## Tools
Python, C++, ROOT, pandas, HTCondor, git (CERN GitLab)
