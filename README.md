# Ricardo Alves de Souza

### Software & AI Engineer | ML Systems | Model Optimization | Cloud-Native Platforms | Open-Source Contributor

📍 Dublin, Ireland

I am a Software and AI Engineer with an **MSc in Data Analytics** and a **BSc (Hons) in Information Technology**, working across machine learning, model optimization, backend/platform engineering, cloud-native systems, and open-source software.

My interest in technology started with an **8-bit MSX and cassette tape**, then grew through electronics, microprocessors, industrial informatics, technical support, software development, cloud systems, data engineering, and machine learning.

Today, I am particularly interested in the point where **AI meets real engineering**: efficient inference, model optimization, edge and embedded AI, reproducible ML pipelines, distributed systems, observability, and production-oriented infrastructure.

---

## Featured Engineering Work

### Intel OpenVINO Model Optimization

A reproducible CPU inference study comparing **PyTorch FP32**, **OpenVINO FP32**, and **NNCF INT8 post-training quantization** using a pretrained ResNet18 model.

On the measured workload, INT8 reduced the OpenVINO model footprint by **3.94×** and produced a **7.46× mean-latency ratio improvement** versus OpenVINO FP32, while changing Imagenette Top-1 accuracy by only **-0.076 percentage points**.

The project includes:

- PyTorch → OpenVINO model conversion
- NNCF post-training quantization
- real-image calibration
- Imagenette validation
- latency and throughput benchmarking
- numerical consistency checks
- reproducible reports
- automated chart generation
- regression tests
- environment capture

**Stack:**  
Python · PyTorch · torchvision · OpenVINO · NNCF · NumPy · pandas · matplotlib · pytest

→ [View project](https://github.com/ricardoasouz/intel-openvino-model-optimization)

---

### Soft-Tissue Sarcoma Survival Analysis

Portfolio version of my **MSc Data Analytics dissertation**, investigating progression-free survival prediction in soft-tissue sarcoma using clinical and radiomic features.

The project implements an end-to-end medical imaging and survival-machine-learning pipeline covering:

- DICOM and RTSTRUCT mapping
- NIfTI conversion
- tumour segmentation masks
- PyRadiomics feature extraction
- patient-level feature aggregation
- clinical and radiomic data integration
- leakage-aware preprocessing
- Cox Proportional Hazards modelling
- DeepSurv neural survival modelling
- bootstrap evaluation
- Kaplan-Meier risk stratification

**Stack:**  
Python · PyTorch · PyRadiomics · CoxPH · DeepSurv · scikit-learn · pandas · NumPy · DICOM · NIfTI

→ [View project](https://github.com/ricardoasouz/sts-survival-ml)

---

### AI Support Engineering Platform

An event-driven engineering reference platform for deterministic incident intake and asynchronous, retrieval-grounded AI analysis.

The platform combines:

- FastAPI
- PostgreSQL and pgvector
- transactional outbox pattern
- Apache Kafka
- local Ollama inference
- retrieval-augmented generation
- controlled AI tool execution
- explicit human review
- OpenTelemetry
- Prometheus
- Tempo
- Grafana
- Docker
- Kubernetes
- Helm

The architecture separates application, messaging, AI, retrieval, persistence, and observability concerns while preserving durable execution and auditability.

**Stack:**  
Python · FastAPI · PostgreSQL · pgvector · Apache Kafka · Ollama · OpenTelemetry · Prometheus · Tempo · Grafana · Docker · Kubernetes · Helm

→ [View project](https://github.com/ricardoasouz/ai-support-engineering-platform)

---

## Open-Source Contributions

I contribute fixes, regression tests, debugging, and engineering improvements to upstream projects involving **AI inference, model optimization, compilers, linkers, embedded systems, and developer tooling**.

### OpenVINO

C++ graph-transformation and reshape-semantics fixes.

- [#38029 — Preserve zero-extent reshape semantics](https://github.com/openvinotoolkit/openvino/pull/38029)
- [#38096 — Fix reduce reshape elimination with keep_dims=false](https://github.com/openvinotoolkit/openvino/pull/38096)

Work includes reproducing ONNX failures, root-cause analysis, transformation fixes, regression tests, and validation against ONNX Runtime and OpenVINO test suites.

---

### NNCF

TorchFX / PT2E quantization work.

- [#4173 — Fix PT2E Mul weight detection for parameters](https://github.com/openvinotoolkit/nncf/pull/4173)
- [#4185 — TorchFX/PT2E QAT support](https://github.com/openvinotoolkit/nncf/pull/4185)

Areas covered include parameter classification, quantization insertion points, TorchAO integration, fake quantization, Q/DQ validation, and Quantization-Aware Training.

---

### Qualcomm AI Hub Models

- [#340 — Fix RoPE scaling factor propagation in Genie config](https://github.com/qualcomm/ai-hub-models/pull/340)

Preserves model-provided RoPE scaling values instead of relying on a fixed hardcoded configuration.

---

### Qualcomm ELD

Engineering work on Qualcomm's linker implementation.

- [#1849 — Route assignment trace diagnostics to stderr](https://github.com/qualcomm/eld/pull/1849)
- [#1850 — Pick up ARM e_flags from object files](https://github.com/qualcomm/eld/pull/1850)

Work includes ELF behaviour, ARM EABI compatibility, linker diagnostics, regression tests, and compatibility validation.

---

### PyTorch ExecuTorch

- [#22113 — Extend CMSIS-Pack smoke test to Cortex-M](https://github.com/pytorch/executorch/pull/22113)

Extends embedded inference validation to exercise the Cortex-M / CMSIS-NN path.

---

### Arm CMSIS-NN

- [#241 — Fix GCC optimization guards for Clang](https://github.com/ARM-software/CMSIS-NN/pull/241)

Improves compiler compatibility by preventing GCC-specific optimization attributes from being applied under Clang.

---

### Arm SDS Framework

- [#304 — Fix mixed value type decoding in sds-convert](https://github.com/ARM-software/SDS-Framework/pull/304)

Fixes mixed-width binary decoding where channel-by-channel parsing could misalign the data stream.

---

## Technical Focus

### Languages

Python · C++ · Java · JavaScript · Node.js · SQL · Bash

### AI, ML & Data

PyTorch · OpenVINO · NNCF · scikit-learn · Apache Spark · pandas · NumPy · PyRadiomics · Deep Learning · Survival Analysis · Model Optimization · Quantization

### Backend & Distributed Systems

FastAPI · Flask · REST APIs · PostgreSQL · pgvector · Apache Kafka · SQL · NoSQL

### Infrastructure

Linux · Docker · Kubernetes · Helm · CI/CD · Cloud Architecture

### Observability

OpenTelemetry · Prometheus · Grafana · Tempo · Distributed Tracing · Structured Logging

### Cloud

AWS · Google Cloud · Firebase

### Engineering

Debugging · Root-Cause Analysis · Systems Integration · Performance Analysis · Regression Testing · Reproducible Experimentation · Git · GitHub Actions

---

## Areas I Am Exploring

I am especially interested in engineering problems involving:

- AI inference optimization
- model compression and quantization
- edge and embedded AI
- ML runtime systems
- PyTorch / OpenVINO / ExecuTorch ecosystems
- C++ inference infrastructure
- AI platforms
- distributed backend systems
- Kubernetes-based ML infrastructure
- performance engineering
- observability
- production machine learning systems

---

## Background

My journey into technology began long before AI became mainstream.

I started experimenting with computers on an **8-bit MSX using cassette tape storage**, then studied electronics, digital logic, microprocessors, computer architecture, automation, and industrial informatics.

That foundation led to years of technical troubleshooting and systems support, followed by formal studies in Information Technology and Data Analytics in Ireland.

Today I am combining that background with modern AI and software engineering, while contributing to open-source projects involving model optimization, inference runtimes, embedded AI, and low-level systems software.

---

## Education

### MSc Data Analytics

**CCT College Dublin**  
2025

Main areas:

Machine Learning · Deep Learning · Data Mining · Data Visualization · Statistics · Cloud Computing · Research Methods · Applied Data Analytics

Dissertation focus:

**Radiomics-based survival prediction in soft-tissue sarcoma using CoxPH and DeepSurv**

---

### BSc (Hons) Information Technology

**CCT College Dublin**  
2023

Main areas:

Python · Java · Machine Learning · AI · Data Mining · SQL · NoSQL · Node.js · Cloud Architecture · Software Engineering · Strategic IT

---

### Technical Diploma in Industrial Informatics

**ETE João Baptista de Lima e Figueiredo**  
Mococa, São Paulo, Brazil  
1996

Digital Electronics · Logic Gates · Microprocessors · Computer Architecture · Industrial Computing · Automation

---

## Current Direction

I am building toward engineering roles where **machine learning meets systems engineering**.

That includes:

**Software Engineering · AI Engineering · ML Systems · Model Optimization · Edge AI · Embedded AI · ML Platform Engineering · AI Infrastructure**

I particularly enjoy engineering work that requires understanding a system deeply, reproducing a failure, identifying the root cause, validating the fix, and leaving behind regression coverage so the same problem does not return.

---

## Connect

**LinkedIn**  
[linkedin.com/in/ricardo-alves-de-souza](https://www.linkedin.com/in/ricardo-alves-de-souza/)

**GitHub**  
[github.com/ricardoasouz](https://github.com/ricardoasouz)

**Location**  
Dublin, Ireland
