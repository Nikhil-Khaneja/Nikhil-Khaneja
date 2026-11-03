## Hi, I'm Nikhil 👋

I'm a software engineer working on **AI agents, GPU performance, and data systems**. I'm doing an M.S. in Data Intelligence at San José State University (graduating December 2027). Before that, I spent four years at Merkle (Dentsu) building data platforms and C++/Python backend services, and in summer 2026 I interned at MedLaunch Concepts, building LLM search and AWS data pipelines.

### In numbers

| Number | What it measures |
|---:|---|
| **1,527x** | faster CUDA C matrix multiply vs. a CPU loop, profiled with nvprof on a Tesla T4 · [gpu-performance-benchmarking](https://github.com/Nikhil-Khaneja/gpu-performance-benchmarking) |
| **448&nbsp;TFLOPS** | FP8 GEMM measured on an RTX 5090, alongside a full roofline study · [gpu-performance-benchmarking](https://github.com/Nikhil-Khaneja/gpu-performance-benchmarking) |
| **7.2x** | fused vs. naive attention, plus the exact sequence length where naive attention runs out of memory |
| **8** | FastAPI microservices with Kafka, Redis and LLM agents · [LinkedIn Simulation](https://github.com/Nikhil-Khaneja/Linkedin_Simulation_LLM_Agent_Microservices) |
| **50K+** | hospital documents behind the RAG search I built at MedLaunch |
| **4&nbsp;years** | at Merkle building data platforms and streaming services on AWS, GCP, Azure and Snowflake |

### Year by year

<details open>
<summary><b>2026 – now</b> · GPU and AI systems</summary>

| Project | What I built | Stack |
|---|---|---|
| [**CrewQuarters**](https://github.com/Nikhil-Khaneja/crewquarters) | Led a self-hosted AI-agent platform for NVIDIA GB10. It serves open-weight LLMs with vLLM, admits a model only if GPU memory and KV-cache budget allow, and runs agents in sandboxed containers. | Python, vLLM, CUDA, Docker, PostgreSQL |
| [**GPU Performance Benchmarking**](https://github.com/Nikhil-Khaneja/gpu-performance-benchmarking) | A CUDA C kernel profiled with nvprof, then an RTX 5090 study: roofline, FP32 → FP8 GEMM throughput, fused attention and a 20-minute sustained-load test. | CUDA C, PyTorch, nvprof |
| [**edge-vision-npu**](https://github.com/Nikhil-Khaneja/edge-vision-npu) | Two vision models trained from scratch (77.4% top-1 on ImageNet-20, 26.07 dB restoration PSNR), exported to ONNX and compiled to INT8 for a Mobilint NPU. | PyTorch, ONNX, INT8 |

</details>

<details>
<summary><b>2026</b> · MedLaunch Concepts · Software Engineer Intern, Data/AI</summary>

| What I built | Stack |
|---|---|
| Clara, a RAG LLM application that answers policy questions over 50K+ hospital documents, tuned against an evaluation set | Python, LLMs, AWS |
| A deterministic identity-resolution pipeline across 5 AWS Lambda services, replacing brittle fuzzy matching | Lambda, SQS, EventBridge, PyTest |
| A Glue ETL pipeline into MongoDB Atlas and cold-start fixes that brought search under 2.5 s | AWS Glue, MongoDB Atlas, CloudWatch |

</details>

<details>
<summary><b>2025 – 2026</b> · San José State University · M.S. Data Intelligence</summary>

| Project | What I built | Stack |
|---|---|---|
| [**LinkedIn Simulation**](https://github.com/Nikhil-Khaneja/Linkedin_Simulation_LLM_Agent_Microservices) | A distributed LinkedIn clone with 8 microservices, Kafka-first writes, Redis caching and LLM recruiter and career-coach agents (team project) | FastAPI, Kafka, Redis, MySQL, MongoDB, React |
| [**AKI Trajectory Analysis**](https://github.com/Nikhil-Khaneja/AKI_trajectory_Analysis) | Led the team; owned the Snowflake ingestion layer, dbt models and Great Expectations gates for a real-time kidney-injury pipeline on MIMIC-IV | Snowflake, dbt, Great Expectations, Kafka, Spark |
| Instructional Student Assistant | Taught 30+ graduate students distributed systems, concurrency and Kafka architecture | |

</details>

<details>
<summary><b>2021 – 2025</b> · Merkle (Dentsu) · Software Engineer I → II</summary>

| What I built | Stack |
|---|---|
| A reusable Data Load Framework that unified client configs across clouds and databases, adopted by most client teams | AWS, GCP, Azure, SQL Server, Snowflake |
| Migrated Informatica pipelines to SQL Server stored procedures, cutting cost and runtime | SQL Server, Tidal |
| A Kafka streaming pipeline for multi-currency deposit data, and latency work on a distributed customer-profile platform | Kafka, Spring Cloud Stream, Kubernetes |
| An automated purge and data-quality framework for daily Redshift pipelines | Amazon Redshift, Python, SQL |

</details>

<details>
<summary><b>2018 – 2021</b> · Mumbai University · B.E. Computer Engineering</summary>

| What I built | Stack |
|---|---|
| Web apps and a small ERP while learning the full stack | HTML, CSS, JavaScript, PHP, MySQL |
| [**VoltWise**](https://github.com/Nikhil-Khaneja/VoltWise), started as a Java bill generator in 2020; now an analytics engine on 2M meter readings that cuts a home's peak demand 53% with battery dispatch | Java, MySQL |
| 1st prize, Study Link Hackathon | |

</details>

SnowPro Core certified

### Find me

[LinkedIn](https://linkedin.com/in/khanejan) · San Jose, CA
