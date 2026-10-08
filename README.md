# Awesome-Industrial-Equipment-Condition-Monitoring

## Top Industrial Equipment Condition Monitoring Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Vibration Analysis, Fault Diagnosis & Self-Hosted Condition Monitoring*  

**Last updated: October 2026**



This repository tracks notable **commercial condition monitoring platforms** and **open-source projects** that monitor equipment health through vibration, temperature, acoustic, and process data — from fully managed IIoT sensor platforms to self-hosted diagnostic frameworks and signal processing toolkits.



**Examples** include Amazon Monitron, Augury, Samsara Industrial IoT, Fluke Reliability eMaint, SKF Enlight, Emerson AMS Machine Works, ABB Ability Genix, Schneider Electric EcoStruxure, GE Digital APM, and SPM Instrument (the category leaders).



**Open-source emphasis**: Industrial condition monitoring is a strong open-source domain. **FD-REST** delivers a lightweight, containerized REST platform for real-time fault detection with DNN inference and automated reporting . **Rotary Insight** provides a unified framework for bearing fault diagnosis with REST-based inference and spectrogram visualization . **OpenConMo** from Aalto University enables reproducible vibration signal-based condition monitoring research with CWRU dataset integration . **ABRAVIBE** brings a comprehensive MATLAB/GNU Octave toolbox for vibration analysis and rotating machinery diagnostics . **pyOMA** and **oma-python** deliver production-grade Operational Modal Analysis for structural health monitoring . **machine-health** produces a single 0-100 health score per machine with full explainability and contributor breakdown . **JOR 4.0** applies recursive Bayesian evidence fusion with ISO 20816-3 compliance . **claude-stwinbox-diagnostics** bridges MEMS sensors to LLMs via MCP for conversational fault diagnosis . This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Amazon Monitron](https://aws.amazon.com/monitron/)**  

  **AWS's managed condition monitoring service** — end-to-end system for equipment monitoring using machine learning . **Includes sensors, gateway, and ML service** that detects abnormal machine behavior . **Best for AWS-native industrial monitoring** .



- **[Augury](https://augury.com/)**  

  **Machine health platform** — vibration, temperature, and magnetic data with AI diagnosis . **Best for rotating equipment monitoring** .



- **[Samsara Industrial IoT](https://www.samsara.com/)**  

  **Connected operations platform** — equipment monitoring, fleet telematics, and video safety . **Best for fleet and industrial operations** .



- **[Fluke Reliability eMaint](https://www.fluke.com/)**  

  **CMMS with condition monitoring** — maintenance management with vibration analysis integration . **Best for maintenance teams** .



- **[SKF Enlight](https://www.skf.com/)**  

  **Condition monitoring platform** — vibration sensors and analytics for rotating equipment . **Best for SKF ecosystem users** .



- **[Emerson AMS Machine Works](https://www.emerson.com/)**  

  **Machinery health management** — vibration analysis, balancing, and diagnostics for rotating equipment . **Best for process industries** .



- **[ABB Ability Genix](https://www.abb.com/)**  

  **Industrial analytics platform** — asset performance and condition monitoring . **Best for ABB ecosystem users** .



- **[Schneider Electric EcoStruxure](https://www.se.com/)**  

  **IoT-enabled architecture** — asset monitoring and predictive maintenance . **Best for Schneider ecosystem users** .



- **[GE Digital APM](https://www.ge.com/digital/applications/asset-performance-management)**  

  **Asset Performance Management** — predictive analytics and reliability for industrial assets . **Best for industrial enterprises** .



- **[SPM Instrument](https://www.spminstrument.com/)**  

  **Condition monitoring solutions** — vibration analysis and bearing monitoring . **Best for heavy industry** .



## Open-Source GitHub Projects



### Fault Detection & Diagnosis Frameworks



- **[FD-REST](https://github.com/Fraunhofer-IMS/FD-REST)**  

  **Lightweight RESTful platform for real-time fault detection and diagnosis in industrial systems**, open-source . **Integrates machine-learning-based fault detection into standard monitoring systems** . **Docker-based architecture with REST API** for on-premises deployment — maintains data security and integrity . **DNN-based inference** with user interface components for a complete predictive maintenance pipeline . **Automated report generator** produces standardized summaries for benchmarking and maintenance planning . **Model-independent** — can be adjusted to alternative architectures . **Planned enhancements**: multi-asset tracking, MQTT/OPC-UA/Modbus compatibility, explainability modules, and playback features . **Best for real-time industrial fault detection with on-prem deployment** .



- **[Rotary Insight](https://github.com/rotary-insight/rotary-insight)**  

  **Open-source framework for bearing fault diagnosis and health monitoring of rotary machinery using deep learning**, open-source . **Unified and modular environment** for processing time-series vibration data — automated preprocessing, segmentation, model training, and inference . **Supports multiple benchmark datasets** and integrates various deep learning architectures for consistent evaluation and comparison . **User-friendly interface and REST-based inference server** — upload data, perform fault classification, and visualize results through spectrograms and frequency-domain analysis . **Best for deep learning-based bearing fault diagnosis** .



- **[OpenConMo](https://github.com/Aalto-Arotor/openconmo)**  

  **Python library for vibration signal-based condition monitoring**, developed at Aalto University . **Objectives**: provide easy access to reproducing signal-based condition monitoring papers; enable comparison of AI/ML techniques with conventional signal processing tools . **Includes CWRU dataset downloader** and notebooks reproducing Smith & Randall results . **Measurement data formatted with location, fault type, depth, orientation, sampling rate, torque, and tags** . **Best for reproducible condition monitoring research** .



- **[Bearing-FDD](https://github.com/paolocalderaro/bearing-fdd)**  

  **Early detection and diagnosis tool for bearing faults in rotating machinery**, open-source . **Explainable and interpretable fault detection** using Monotonic Smoothed Stacked Autoencoder (MS2AE) — trained on healthy data only . **Multistage diagnostic procedure**: Dynamic Time Warping for baseline generation, kurtogram-guided bandpass filtering, and envelope analysis for fault signature extraction . **Determines fault type** (outer race, inner race, ball, cage) and **degradation stage** . **Best for explainable bearing fault diagnosis** .



### Vibration Analysis & Signal Processing Toolkits



- **[ABRAVIBE Toolbox](https://github.com/anderstorrence/ABRAVIBE)**  

  **MATLAB/GNU Octave toolbox for teaching and practicing vibration analysis and structural dynamics**, GPL licensed . **Comprehensive functionality**: simulation of mechanical models, time series analysis, spectral analysis, frequency response and correlation function estimation, modal parameter extraction, and rotating machinery analysis (order tracking) . **Fully free software platform** — can be used with GNU Octave . **Includes laboratory exercises** for structural dynamics teaching . **Best for vibration analysis education and research** .



- **[pyOMA](https://github.com/pyOMA-dev/pyOMA)**  

  **Open-source toolbox for Operational Modal Analysis (OMA) in Python**, developed at Bauhaus-Universität Weimar . **Used daily to analyze continuously acquired vibration measurements** of a structural health monitoring system since 2015 . **Supports various identification methods**: SSI-Cov-Ref, SSI-Data, Var-SSI-Ref, pLSCF, PRCE, ERA . **Features**: geometry processing, signal preprocessing, stabilization diagrams, mode shape plotting, multi-setup merging, uncertainty quantification . **Interactive GUI** via PyQt6 and Jupyter widgets . **3D mode-shape backend** via pyvista/VTK . **Applications**: bridges, towers/masts, wide-span floors . **Best for structural health monitoring and modal analysis** .



- **[oma-python](https://github.com/Dynoma/oma-python)**  

  **Open-source Operational Modal Analysis (OMA) algorithms for Python**, MIT licensed . **Estimate natural frequencies, damping ratios, and mode shapes from ambient vibration measurements** . **FDD (Frequency Domain Decomposition)** and **CovSSI (Covariance-driven Stochastic Subspace Identification)** . **TypedDict results** with complex and real mode shapes . **Best for ambient vibration-based modal identification** .



### Health Scoring & Fusion Engines



- **[machine-health](https://pypi.org/project/machine-health/)**  

  **One continuously updated 0-100 health score per machine, built from every sensor and the limits you already know**, open-source . **Four components**: **stability** (how far each channel has moved from baseline), **compliance** (whether your limits hold), **anomaly** (share of outlier readings), **availability** (missing readings and flatlined sensors) . **Weighted combination** (stability 0.30, compliance 0.30, anomaly 0.20, availability 0.20) into a score between 0 and 100 . **Full explainability** — points lost split by component and by channel, with violations detailed . **Fixed grades**: A ≥ 90, B ≥ 80, C ≥ 70, D ≥ 60, F below 60 . **Best for unified machine health scoring with reasoning** .



- **[JOR 4.0 Predictive Maintenance Fusion Engine](https://github.com/jamesorion6869/JOR_PYMC_V3_1)**  

  **Recursive Bayesian framework for industrial predictive maintenance with ISO 20816-3 compliance**, open-source research prototype . **Weighted evidence fusion with recursive posterior updating** — produces non-healthy probability (NHP) estimate and hysteresis-controlled alert state . **Vibration telemetry converted to structured evidence** via ISO 20816-3 (Criterion I zone boundaries, Criterion II rate-of-change) . **Operational context grounded in NEMA MG-1** Class F thermal and load limits . **Self-calibrating fusion engine** with validation tests for context stress, danger ramp, false-positive immunity, noise robustness, and long-duration stability . **Best for standards-based vibration severity monitoring** .



### LLM-Integrated Diagnostics



- **[claude-stwinbox-diagnostics](https://github.com/LGDiMaggio/claude-stwinbox-diagnostics)**  

  **Open-source condition monitoring copilot and predictive maintenance AI agent**, open-source . **Connects industrial MEMS vibration sensors to Claude via MCP (Model Context Protocol)** . **Transparent DSP pipeline** with standards-based severity checks (ISO 10816/20816) and conversational fault diagnosis . **Two MCP servers**: STWIN.box sensor acquisition and vibration analysis (FFT, envelope analysis, bearing fault detection) . **Three Claude Skills**: machine-vibration-monitoring, vibration-fault-diagnosis, operator-diagnostic-report . **Supported fault types**: bearing inner/outer race, rolling element, cage, unbalance, misalignment, mechanical looseness . **Hardware reference**: STEVAL-STWINBX1, but analysis server works with any vibration data source . **Best for LLM-assisted condition monitoring** .



### Additional Strong Open-Source Options



- **cbm_codes_open** (biswajitsahoo1111) — Data and code implementing common machine learning algorithms for machinery condition monitoring, 80 GitHub stars .

- **weibull-knowledge-informed-ml** (tvhahn) — Knowledge-informed machine learning on PRONOSTIA (FEMTO) and IMS bearing datasets for RUL prediction, 115 GitHub stars .

- **Rotating-machine-fault-data-set** (hustcxl) — Open rotating mechanical fault datasets collection, 718 GitHub stars .

- **cbm_codes_open** — ML algorithms for machinery condition monitoring .

- **IEEE published ESP32 + Raspberry Pi portable monitoring device** for EV induction motors using multi-sensor data .

- **TinyML-based Edge AI Predictive Maintenance System** for industrial rotating machinery using ESP32, FFT, and multi-sensor fusion .



**Frameworks for building custom industrial condition monitoring solutions**: Combine **FD-REST** for lightweight, containerized real-time fault detection with REST API and on-prem deployment . Use **Rotary Insight** for deep learning-based bearing fault diagnosis with REST inference and spectrogram visualization . Deploy **OpenConMo** for reproducible condition monitoring research with CWRU dataset integration . Integrate **ABRAVIBE** for comprehensive vibration analysis and rotating machinery diagnostics . Choose **pyOMA** or **oma-python** for Operational Modal Analysis and structural health monitoring . Use **machine-health** for unified 0-100 health scoring with full explainability . Integrate **JOR 4.0** for standards-based vibration severity monitoring with recursive Bayesian fusion . Choose **claude-stwinbox-diagnostics** for LLM-assisted conversational fault diagnosis . Note that true enterprise condition monitoring with managed infrastructure, industrial-grade sensors, and vendor-supported SLAs (Amazon Monitron, Augury, SKF Enlight) remains primarily commercial territory; open-source stacks provide strong fault detection, vibration analysis, and health scoring foundations that require integration for complete industrial condition monitoring deployments.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Industrial condition monitoring platforms handle sensitive operational data and may influence critical maintenance decisions. Self-hosted solutions require proper security hardening, access controls, and compliance with industrial safety standards (IEC 62443).

- **Open-source condition monitoring projects vary significantly in maturity** — FD-REST and Rotary Insight are production-oriented research tools ; claude-stwinbox-diagnostics is explicitly a proof of concept . Evaluate before relying on them for safety-critical maintenance decisions.

- **Vibration analysis requires domain expertise** — proper sensor placement, sampling rates, and signal processing parameters are critical for accurate fault detection . ISO 10816/20816 standards provide severity benchmarks but require careful application.

- **License considerations**: FD-REST is open-source ; Rotary Insight is open-source ; OpenConMo is open-source ; ABRAVIBE uses GPL ; pyOMA is open-source ; machine-health is open-source . Verify licensing against your use case before committing.

- The open-source ecosystem provides strong fault detection, vibration analysis, and health scoring foundations, but **managed infrastructure, industrial-grade sensors, and vendor-supported SLAs** remain primarily commercial offerings.



---



**Made for maintenance engineers, reliability professionals, and organizations seeking condition monitoring sovereignty.**

Let's make industrial equipment condition monitoring more open, transparent, and predictive.
