# TÜBİTAK 2209-A — Hydrogen Fuel-Cell Aviation Power Systems (Concept + TRL Roadmap)

Portfolio repository for our TÜBİTAK 2209-A team project on a **hydrogen fuel-cell electric power system** for a medium-class rotorcraft and a **Technology Readiness Level (TRL) analysis/roadmap**.

## Team
- Halime Nur Ateş (name shown on the official submission cover due to application format)
- Zehra Yağmur Soylu
- Oğuz Akpınar
- Melih Mergen

> **Authorship note:** Although the official submission document may display only the applicant/lead name on the cover page, the research, literature survey, analysis, modeling, and TRL roadmap work were carried out collaboratively by the full team listed above.

## Project Summary
Hydrogen has a high specific energy compared to batteries and is a strategic option for high-power rotorcraft missions.  
In this study, we propose and compare:
- **Hydrogen Fuel-Cell Electric** architecture (H₂ storage → PEMFC → power electronics → PMSM motors)
- **Hydrogen-fueled turboshaft** alternative (Brayton-cycle comparison perspective)

## Modeling Approach (as in the report)
- MATLAB/Simulink **lumped-parameter** simulation framework
- **70 MPa (700 bar) Type-IV tank** GH₂ behavior modeled with real-gas relations
- **Flight-envelope dependent** fuel flow regulation using control logic (mission phases: hover / climb / cruise)
- Thermal management analysis: cooling loops sized for major heat loads and their performance trade-offs
- Comparative efficiency discussion between PEMFC-based system and direct hydrogen combustion in a turboshaft

## Key Targets (high-level)
- Power system sizing for rotorcraft demand (continuous + peak power cases)
- GH₂ storage integration and volumetric/CG considerations
- Incremental time-step mission simulation (beyond simple Breguet range assumptions)
- Thermal management system sizing and related penalties/trade-offs
- TRL assessment and a 2030–2040 roadmap for major subsystems

## Files
- `docs/tubitak-2209a-h2-electric-trl.pdf` — Full TÜBİTAK 2209-A proposal/report (PDF)

## Notes (portfolio)
If you reference this work, please credit the full team listed above.
