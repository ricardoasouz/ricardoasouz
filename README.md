# Ricardo Alves de Souza

### Software & AI Engineer | ML Systems | Model Optimization | Edge & Embedded AI | Industrial Informatics Technician | Open-Source Contributor

📍 Dublin, Ireland

I am a Software and AI Engineer with an **MSc in Data Analytics**, a **BSc (Hons) in Information Technology**, and an **Industrial Informatics Technician qualification**.

My interest in technology started with an **8-bit MSX and cassette tape**, then grew through industrial informatics, electronics, digital logic, microprocessors, automation, technical support, software development, cloud systems, data engineering, and machine learning.

Today, I am particularly interested in the point where **AI meets real engineering**: efficient inference, model optimization, edge and embedded AI, reproducible ML pipelines, distributed systems, observability, and production-oriented infrastructure.

---

## Featured Engineering Work

### Intel OpenVINO Model Optimization

An independent, reproducible CPU inference study comparing **PyTorch FP32**, **OpenVINO FP32**, and **NNCF INT8 post-training quantization** using a pretrained ResNet18 model.

On the measured workload, INT8 reduced the OpenVINO model footprint by **3.94×** and produced a **7.46× mean-latency ratio improvement** versus OpenVINO FP32, while changing Imagenette Top-1 accuracy by only **-0.076 percentage points**.

The project includes:

* PyTorch to OpenVINO model conversion
* NNCF post-training quantization
* real-image calibration
* Imagenette validation
* latency and throughput benchmarking
* numerical consistency checks
* reproducible reports
* automated chart generation
* regression tests
* environment capture

**Stack:**
Python · PyTorch · torchvision · OpenVINO · NNCF · NumPy · pandas · matplotlib · pytest

→ [View project](https://github.com/ricardoasouz/openvino-model-optimization)

---

### Soft-Tissue Sarcoma Survival Analysis

Portfolio version of my **MSc Data Analytics dissertation**, investigating progression-free survival prediction in soft-tissue sarcoma using clinical and radiomic features.

The project implements an end-to-end medical imaging and survival machine learning pipeline covering:

* DICOM and RTSTRUCT mapping
* NIfTI conversion
* tumour segmentation masks
* PyRadiomics feature extraction
* patient-level feature aggregation
* clinical and radiomic data integration
* leakage-aware preprocessing
* Cox Proportional Hazards modelling
* DeepSurv neural survival modelling
* bootstrap evaluation
* Kaplan-Meier risk stratification

**Stack:**
Python · PyTorch · PyRadiomics · CoxPH · DeepSurv · scikit-learn · pandas · NumPy · DICOM · NIfTI

→ [View project](https://github.com/ricardoasouz/sts-survival-ml)

---

### AI Support Engineering Platform

An event-driven engineering reference platform for deterministic incident intake and asynchronous, retrieval-grounded AI analysis.

The platform combines:

* FastAPI
* PostgreSQL and pgvector
* transactional outbox pattern
* Apache Kafka
* local Ollama inference
* retrieval-augmented generation
* controlled AI tool execution
* explicit human review
* OpenTelemetry
* Prometheus
* Tempo
* Grafana
* Docker
* Kubernetes
* Helm

The architecture separates application, messaging, AI, retrieval, persistence, and observability concerns while preserving durable execution and auditability.

**Stack:**
Python · FastAPI · PostgreSQL · pgvector · Apache Kafka · Ollama · OpenTelemetry · Prometheus · Tempo · Grafana · Docker · Kubernetes · Helm

→ [View project](https://github.com/ricardoasouz/ai-support-engineering-platform)

---

## Merged Open-Source Contributions

Selected contributions accepted and merged into upstream open-source projects.

### Qualcomm ELD

* [#1849: Route assignment trace diagnostics to stderr](https://github.com/qualcomm/eld/pull/1849)

Fixed assignment trace diagnostics so linker trace output is consistently routed to `stderr`, with regression coverage for assignment and FILL/padding traces.

---

### PyTorch ExecuTorch

* [#22113: Extend CMSIS-Pack smoke test to Cortex-M](https://github.com/pytorch/executorch/pull/22113)

Extended the CMSIS-Pack smoke test to exercise the Cortex-M and CMSIS-NN path on ARMCM55, including a Cortex-M quantized operator and CMSIS-NN integration.

---

### Arm SDS Framework

* [#304: Fix mixed value type decoding in sds-convert](https://github.com/ARM-software/SDS-Framework/pull/304)

Fixed mixed-width binary data decoding where channel-by-channel parsing could misalign samples containing different numeric value sizes.

---

## Technical Focus

### Languages

Rust · C++ · Python · Node.js · Java

### AI, ML & Data

ExecuTorch · PyTorch · TensorFlow · OpenVINO · NNCF · scikit-learn · Apache Spark · pandas · NumPy · PyRadiomics · Deep Learning · Survival Analysis · Model Optimization · Quantization

### Backend & Distributed Systems

FastAPI · Flask · REST APIs · PostgreSQL · pgvector · Apache Kafka · SQL · NoSQL

### Infrastructure

Linux · Docker · Kubernetes · Helm · Jenkins · GitHub Actions · CI/CD · Cloud Architecture

### Observability

OpenTelemetry · Prometheus · Grafana · Tempo · Distributed Tracing · Structured Logging

### Cloud

AWS · Azure · Google Cloud · Firebase

### Engineering

Debugging · Root-Cause Analysis · Reverse Engineering · Systems Integration · Performance Analysis · Regression Testing · Reproducible Experimentation

---

## Areas I Am Exploring

I am especially interested in engineering problems involving:

* AI inference optimization
* model compression and quantization
* edge and embedded AI
* ML runtime systems
* PyTorch, OpenVINO and ExecuTorch ecosystems
* C++ inference infrastructure
* AI platforms
* distributed backend systems
* Kubernetes-based ML infrastructure
* performance engineering
* observability
* production machine learning systems

---

## Background

My journey into technology began long before AI became mainstream.

I started experimenting with computers on an **8-bit MSX using cassette tape storage**. During my qualification as an **Industrial Informatics Technician**, I studied electronics, digital logic, microprocessors, computer architecture, industrial computing, and automation.

That foundation led to years of hands-on work with computers, systems troubleshooting, technical support, and software technologies, followed by formal higher education in Information Technology and Data Analytics in Ireland.

Today I am combining that background with modern AI and software engineering, contributing to open-source projects involving model optimization, inference runtimes, embedded AI, compilers, linkers, and low-level systems software.

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

### Industrial Informatics Technician

**ETE João Baptista de Lima e Figueiredo**
Mococa, São Paulo, Brazil
1996

Technical training in:

Digital Electronics · Digital Logic · Microprocessors · Computer Architecture · Industrial Computing · Automation

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
