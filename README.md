# Experimental Physics & Data Analysis

Selected laboratory reports and Excel-based analyses from **University of Michigan — PHYSICS 391: Introduction to Modern Physics Laboratory**.

This repository is a curated portfolio version of the original coursework folder. It preserves selected student-created work while excluding course manuals, assignment instructions, rubrics, and other instructor-provided materials. Reports here are redacted copies of the original course reports; lab partner names were removed for privacy.

## Overview

The projects in this repository emphasize experimental data analysis, quantitative modeling, curve fitting, parameter estimation, statistical reasoning, scientific visualization, and technical writing. The analysis work was originally completed primarily in Microsoft Excel, including spreadsheet formulas, charts, least-squares fits, and Solver-based nonlinear fitting where documented in the reports.

## Selected Experiments

| Experiment | What It Shows |
| --- | --- |
| [Blackbody Radiation](blackbody-radiation/) | Analyzed lamp voltage/current and photodiode measurements to test Stefan-Boltzmann behavior and Planck spectral trends. The original Excel analysis estimates a temperature-power exponent near 4 and an inferred solar temperature of about 6608 K. |
| [Photoelectric Effect](photoelectric-effect/) | Measured photocurrent versus retarding voltage for three laser wavelengths with and without a neutral-density filter. The report uses stopping-voltage fits to estimate Planck's constant and to test intensity independence. |
| [Electron Diffraction](electron-diffraction/) | Measured electron diffraction ring diameters at multiple accelerating voltages. The spreadsheet fits diffraction angle versus inverse square root of voltage to estimate graphite lattice spacings and compare them with expected crystal-plane values. |
| [Hydrogen/Deuterium Spectroscopy](hydrogen-deuterium-spectroscopy/) | Processed Balmer-series spectra for hydrogen and deuterium discharge tubes. The analysis estimates Rydberg-fit slopes and examines the small H-alpha isotope shift between hydrogen and deuterium. |
| [Hall Effect and Semiconductor Conductivity](hall-effect-semiconductors/) | Measured Hall voltage versus current and temperature-dependent germanium conductivity. The report infers negative carrier sign and estimates a germanium band gap from an Excel nonlinear fit. |
| [High-Temperature Superconductivity](high-temperature-superconductivity/) | Observed the Meissner effect and measured resistance-temperature behavior for BSCCO and YBCO samples. The report estimates a superconducting transition near 110 K and discusses persistent current observations. |
| [Radioactivity](radioactivity/) | Measured alpha, beta, and gamma attenuation using Geiger-counter data. The analysis estimates alpha range cutoff, beta absorber range, and a gamma attenuation coefficient from an exponential fit. |

## Methods & Tools

- **Data analysis:** Microsoft Excel spreadsheets with formulas, charts, matrix calculations, least-squares fits, and Solver where documented.
- **Experimental methods:** optical spectroscopy, Hall voltage measurement, Geiger counting, electron diffraction, blackbody lamp measurements, and superconducting transition measurements.
- **Quantitative skills:** parameter estimation, curve fitting, uncertainty/error discussion, comparison with accepted or reference values, and interpretation of deviations.
- **Communication:** redacted lab reports, extracted report figures, and a student presentation on quantum probability and entanglement.

## Repository Structure

- `*/report-redacted.docx` — sanitized copies of original student lab reports.
- `*/analysis.xlsx` — original Excel analysis workbooks, renamed for clarity.
- `*/figures/` — figures and instrument photos extracted from the original reports.
- `blackbody-radiation/data/` — raw text data files associated with the blackbody experiment.
- `presentations/` — student-created presentation file.
- `docs/source-manifest.json` — source-path mapping from the original coursework folder.
- `docs/curation-notes.md` — selected/excluded file decisions, privacy notes, and claims needing user review.

## Academic Integrity Notes

- This repository does **not** include course manuals, syllabi, assignment instructions, solution materials, or instructor slides.
- It does **not** repackage Excel analyses as Python projects.
- It does **not** claim ownership of course-provided programs or manuals.
- New README text is portfolio documentation written after the course; original course outputs are preserved separately as redacted reports and analysis files.
