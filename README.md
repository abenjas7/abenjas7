# Diogo Borges

Computer Science graduate interested in Artificial Intelligence, software engineering, automation, and data-driven systems.

I like building systems that are not only functional, but also understandable: clear data flow, visible outputs, reproducible evaluation, and enough documentation for another person to inspect the work without guessing how it was built.

## Main Projects

### AI / Computer Vision / Medical Imaging

#### [SPINAL-AI2024-BORGES-LIMA](https://github.com/abenjas69/SPINAL-AI2024-BORGES-LIMA)

Final-year engineering project on automated scoliosis assessment from spinal radiographs.

- Built and evaluated an interpretable landmark-based pipeline for vertebral geometry prediction and Cobb angle estimation.
- Compared complementary scoliosis representations: local vertebral landmarks and global centerline curvature.
- Studied late fusion between landmark/MLP estimates and centerline estimates, including cases where fusion improves or degrades the final prediction.
- Packaged the project for external review with reproducible commands, dataset instructions, model documentation, metrics summaries, and release artifacts.

My main contribution focused on the landmark-based branch: vertebral quadrilateral prediction, geometric post-processing, Cobb endpoint selection, MLP-based angle regression, and error analysis. The centerline branch was developed by my project teammate Daniel Lima.

Reviewer links: [case study](https://github.com/abenjas69/SPINAL-AI2024-BORGES-LIMA/blob/main/docs/PORTFOLIO_CASE_STUDY.md) | [model card](https://github.com/abenjas69/SPINAL-AI2024-BORGES-LIMA/blob/main/MODEL_CARD.md) | [dataset guide](https://github.com/abenjas69/SPINAL-AI2024-BORGES-LIMA/blob/main/DATASET_ACCESS.md) | [model weights](https://github.com/abenjas69/SPINAL-AI2024-BORGES-LIMA/releases/tag/models-v1)

### Automation / Network Engineering

#### [clean_switch](https://github.com/abenjas69/clean_switch)

Python automation tool for collecting and analysing Cisco switch information.

- Connects to Cisco IOS switches through SSH with Netmiko.
- Parses command output with TextFSM/NTC templates and internal fallbacks.
- Generates Excel reports with dashboards, KPIs, VLANs, Port-Channels, CDP/LLDP information, and raw command outputs.
- Stores JSON snapshots for historical comparison and supports topology crawl through network neighbours.

### Full-Stack / Algorithms

#### [Nim Game frontend](https://github.com/abenjas69/nimgame) + [Nim Game API](https://github.com/abenjas69/api_nim)

Web implementation of a Nim game with a React frontend and Flask backend.

- Frontend built with React, Axios, and Tailwind CSS.
- Backend exposes game state and move endpoints through a REST API.
- Computer move logic uses Nim/XOR-based strategy and validates game rules server-side.

## Technical Areas

Python | JavaScript | React | Flask | REST APIs | TensorFlow/Keras | Computer Vision | Model Evaluation | Data Processing | Automation | Networking | Git/GitHub

## Current Direction

Preparing for MSc-level work in Artificial Intelligence while continuing to build practical software projects across machine learning, automation, APIs, and data-driven engineering.
