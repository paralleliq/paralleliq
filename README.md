# Paralleliq

**Find the productive capacity already inside your GPU fleet. Recover it before you buy more.**

GPU fleet efficiency and reliability for AI teams. Paralleliq finds idle GPUs, models on the wrong GPU tier, and the risk signals that turn into incidents. It prices each finding in dollars per month and keeps your team in control of every change.

Research consistently reports GPU utilization below 50%. Paralleliq estimates that about half of GPU capacity is wasted, and targets recovering 20–40% of that waste.

<p>
  <a href="https://paralleliq.ai/contact"><img src="https://img.shields.io/badge/Request%20Demo-22d3ee?style=for-the-badge&labelColor=04060d" alt="Request Demo" /></a>
  <a href="https://paralleliq.ai/get-started/self-serve"><img src="https://img.shields.io/badge/Lightweight%20Scan-0c1322?style=for-the-badge&labelColor=04060d" alt="Lightweight Scan" /></a>
  <a href="https://paralleliq.ai/gpu-waste-calculator"><img src="https://img.shields.io/badge/Estimate%20Your%20Waste-0c1322?style=for-the-badge&labelColor=04060d" alt="Estimate Your Waste" /></a>
</p>

## What it finds

- **Idle deployments:** GPUs allocated and billing, with no requests for a day.
- **Too many replicas:** more than the week's peaks need, autoscaled or fixed.
- **Oversized GPUs:** models on a bigger GPU tier than their traffic needs.
- **GPU hardware faults:** Xid errors, naming the node and the GPU.
- **Dark capacity:** GPUs no workload is using.

## How it works

Paralleliq reads operational metrics from your Kubernetes cluster through an OpenTelemetry collector (vLLM on NVIDIA GPUs). It judges each workload against a week of peaks and your latency targets with deterministic rules, and recommends the fix. Today your team approves every change, and every step is recorded in an audit log.

Model weights, prompts and responses never leave your environment.

## Open source

- **[piqc](https://github.com/paralleliq/piqc):** open-source GPU waste scanner for Kubernetes. Read-only, one command, a cost report in your terminal.
- **[ModelSpec](https://github.com/paralleliq/modelspec):** open declarative AI model specification. Captures execution, serving and orchestration intent in a runtime-agnostic, cloud-agnostic, machine-readable format.
- **[piqc-knowledge-base](https://github.com/paralleliq/piqc-knowledge-base):** production readiness standards for GenAI. Neutral, community-driven checklists for deploying LLMs, vLLM, GPU optimization, observability and governance.

## Contact

| | |
|---|---|
| **Website** | [paralleliq.ai](https://paralleliq.ai) |
| **Business inquiries** | [sam@paralleliq.ai](mailto:sam@paralleliq.ai) |
| **Founder & CEO** | Sam Hosseini |
| **Headquarters** | San Francisco, California |

<p>
  <a href="https://www.linkedin.com/company/paralleliq"><img src="https://img.shields.io/badge/LinkedIn-22d3ee?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=04060d" alt="LinkedIn" /></a>
  <a href="https://x.com/paralleliq"><img src="https://img.shields.io/badge/X-22d3ee?style=for-the-badge&logo=x&logoColor=white&labelColor=04060d" alt="X" /></a>
  <a href="https://www.crunchbase.com/organization/paralleliq"><img src="https://img.shields.io/badge/Crunchbase-22d3ee?style=for-the-badge&logo=crunchbase&logoColor=white&labelColor=04060d" alt="Crunchbase" /></a>
</p>

<sub>© Paralleliq · GPU fleet efficiency and reliability for AI teams</sub>
