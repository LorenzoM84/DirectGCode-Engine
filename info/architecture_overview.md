# Architecture Overview

DirectGCode Engine is organized around a modular workflow:

- Project and job management
- STEP import and analysis
- AI CAM generation
- Learned case retrieval
- Controller-specific adaptation
- Post-processing and export
- Simulation and validation

The architecture is intentionally modular in order to support future expansion of machining strategies, controller profiles and AI-assisted optimization.
