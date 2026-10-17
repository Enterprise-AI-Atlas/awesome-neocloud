# Awesome Neocloud

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](./CONTRIBUTING.md)

A curated, research-oriented registry of resources for understanding the **Neocloud** ecosystem — the specialized, GPU-centric cloud providers built for modern AI workloads.

This list is for engineers, architects, investors, and researchers who want to compare AI-native cloud providers, track the NVIDIA Cloud Partner landscape, and understand how Neoclouds differ from traditional hyperscalers.

**Inclusion criteria:** Resources must help someone research or evaluate Neocloud providers, AI-native infrastructure, GPU-as-a-Service, or the NVIDIA Cloud Partner ecosystem. See [CONTRIBUTING.md](./CONTRIBUTING.md) for the full quality bar.

---

## Contents

- [What is a Neocloud?](#what-is-a-neocloud)
- [NVIDIA Cloud Partners & Reference Architecture](#nvidia-cloud-partners--reference-architecture)
- [Leading Neocloud Providers](#leading-neocloud-providers)
- [GPU Cloud Ratings & Benchmarks](#gpu-cloud-ratings--benchmarks)
- [Market Analysis & Research](#market-analysis--research)
- [Financials, IPOs & Funding](#financials-ipos--funding)
- [Energy & Sustainable Neoclouds](#energy--sustainable-neoclouds)
- [Sovereign & Regional Neoclouds](#sovereign--regional-neoclouds)
- [Software for Building Neoclouds](#software-for-building-neoclouds)
- [Related Atlases](#related-atlases)
- [Contributing](#contributing)
- [License](#license)

---

## What is a Neocloud?

A **Neocloud** is a cloud provider purpose-built for AI and high-performance computing workloads, typically offering GPU-as-a-Service (GPUaaS), bare-metal clusters, and AI-native infrastructure. Unlike general-purpose hyperscalers, Neoclouds optimize for the density, networking, and power requirements of training and inference at scale.

- **[Neoclouds: The Specialized Cloud Providers Powering AI's Next Leap](https://thirdruntime.com/2025/05/18/neoclouds-the-specialized-cloud-providers-powering-ais-next-leap/)** `Analysis` — Definition and comparison of CoreWeave, Nebius, Lambda, and Together AI.
- **[The rise of Neocloud in the AI landscape](https://www.jll.com/en-us/insights/the-rise-of-neocloud-in-the-ai-landscape)** `Analysis` — JLL market overview, including ~190 operator ecosystem and 82% five-year revenue CAGR estimate.
- **[Neoclouds roll in, challenge hyperscalers for AI workloads](https://www.networkworld.com/article/4011187/neoclouds-roll-in-challenge-hyperscalers-for-ai-workloads.html)** `Analysis` — NetworkWorld breakdown of CoreWeave, Lambda, Crusoe, and Nebius.

---

## NVIDIA Cloud Partners & Reference Architecture

NVIDIA partners with a global ecosystem of cloud providers that deliver the NVIDIA accelerated computing platform. The **NVIDIA Cloud Partner (NCP)** reference architecture and **Reference Platform NCP** program are the main frameworks for building AI-native clouds on NVIDIA hardware.

- **[NVIDIA Cloud Partners](https://www.nvidia.com/en-us/data-center/gpu-cloud-computing/partners/)** `Official` — Global directory of NCPs, including Reference Platform partners.
- **[NVIDIA Cloud Accelerator / NCP Software Reference Guide](https://docs.nvidia.com/ncx/ncp-software-reference-guide/latest/introduction.html)** `Official` — Northstar reference architecture for IaaS, CaaS, and PaaS layers.
- **[NVIDIA Unveils Reference Architecture for AI Cloud Providers](https://blogs.nvidia.com/blog/ai-cloud-providers-reference-architecture/)** `Official` — June 2024 announcement of the NCP reference architecture.
- **[NVIDIA Partner Network Locator](https://marketplace.nvidia.com/en-us/enterprise/partners/)** `Official` — Searchable partner directory.
- **[Reference Platform NVIDIA Cloud Partner](https://www.nvidia.com/en-us/about-nvidia/partners/)** `Official` — Description of the NPN Reference Platform specialization.

### Reference Platform NCPs (selected)

- **[CoreWeave](https://coreweave.com/)** `Official` — GPU cloud for training and inference at scale.
- **[Crusoe Cloud](https://crusoecloud.com/)** `Official` — Energy-optimized AI cloud platform.
- **[GMI Cloud](https://www.gmicloud.ai/)** `Official` — U.S.-based full-stack GPU infrastructure and inference services.
- **[Lambda](https://lambdalabs.com/)** `Official` — AI developer cloud for ML/AI teams.
- **[Nebius](https://nebius.com/)** `Official` — Full-stack AI cloud with NVIDIA Reference Platform status.
- **[Voltage Park](https://www.voltagepark.com/)** `Official` — Large-scale GPU cloud provider.
- **[Yotta Data Services](https://www.yotta.com/)** `Official` — Indian cloud and AI cloud solutions provider.

---

## Leading Neocloud Providers

A non-exhaustive list of providers commonly tracked as Neoclouds. Research each before committing production workloads — pricing, availability, and financial stability vary significantly.

### North America / Global

- **[CoreWeave](https://coreweave.com/)** `Provider` — Kubernetes-native AI cloud with early access to NVIDIA GPUs; public company (CRWV).
- **[Lambda Labs](https://lambdalabs.com/)** `Provider` — Developer-focused GPU cloud and on-prem hardware; strong Jupyter/Slurm/K8s support.
- **[Nebius](https://nebius.com/)** `Provider` — Full-stack AI cloud with strong European footprint; public company (NBIS).
- **[Crusoe Cloud](https://crusoecloud.com/)** `Provider` — AI cloud powered by low-cost, stranded renewable energy.
- **[Together AI](https://www.together.ai/)** `Provider` — Inference, fine-tuning, and model hosting focused on open-source models.
- **[Vultr](https://www.vultr.com/)** `Provider` — Cloud compute provider with broad global footprint and NVIDIA GPU instances.

### Europe / EMEA

- **[Nscale](https://nscale.com/)** `Provider` — Large-scale AI infrastructure across U.S. and Europe, including Stargate Norway.
- **[Civo](https://www.civo.com/)** `Provider` — Kubernetes-focused cloud with GPU offerings.
- **[Nebul](https://nebul.com/)** `Provider` — Sovereign AI cloud provider recognized by Gartner.

### Asia-Pacific / Regional

- **[Yotta Data Services](https://www.yotta.com/)** `Provider` — Indian data-center and AI cloud provider.
- **[YTL](https://ytl.com/)** `Provider` — Southeast Asian infrastructure player building AI cloud capacity.
- **[Cassava](https://cassavatechnologies.com/)** `Provider` — African cloud and AI infrastructure provider.
- **[Claro](https://www.claro.com.br/)** `Provider` — Latin American telecom/cloud provider expanding into AI cloud.

---

## GPU Cloud Ratings & Benchmarks

Independent ratings and benchmark reports comparing GPU cloud providers.

- **[ClusterMAX 2.0](https://newsletter.semianalysis.com/p/clustermax-20-the-industry-standard)** `Rating` — SemiAnalysis review of 84 GPU cloud providers across performance, pricing, and operations.
- **[ABI Research: Profiling Seven Leading Neocloud Companies](https://www.abiresearch.com/blog/leading-neocloud-companies)** `Research` — Profiles of Nscale, Civo, CoreWeave, Crusoe, Lambda, Nebius, and Vultr.
- **[Compute Comparison](https://computecomparison.com/)** `Platform` — Live price comparison across 100+ GPU cloud and LLM inference providers, with historical pricing data and open data exports.

---

## Market Analysis & Research

Analyst and industry research on the Neocloud segment.

- **[Is Nvidia Competing With Its GPU Cloud Partners?](https://www.forbes.com/sites/karlfreund/2025/06/17/is-nvidia-competing-with-its-gpu-cloud-partners/)** `Analysis` — Forbes analysis of DGX Cloud Lepton and NVIDIA's cloud partner dynamics.
- **[NVIDIA and Nebius Partner to Scale Full-Stack AI Cloud](https://nvidianews.nvidia.com/news/nvidia-and-nebius-partner-to-scale-full-stack-ai-cloud)** `News` — NVIDIA's $2B investment in Nebius and expanded partnership.
- **[Nvidia's AI Cloud ecosystem reaches six continents](https://www.aichatdaily.com/ai-business/nvidia-s-ai-cloud-ecosystem-reaches-six-continents)** `News` — Summary of Exemplar Cloud tier expansion and regional partners.

---

## Financials, IPOs & Funding

Resources for tracking the business side of Neocloud providers.

- **[CoreWeave Investor Relations](https://investors.coreweave.com/)** `Official` — Public filings, earnings, and investor materials.
- **[Nebius Investor Relations](https://ir.nebius.com/)** `Official` — Public filings, earnings, and investor materials.
- **[CoreWeave, Nebius, Lambda: The Neocloud Companies Powering the AI Boom](https://chiraghasija.cc/posts/coreweave-nebius-neocloud-boom/)** `Analysis` — Comparative financial and growth metrics for CoreWeave, Nebius, and Lambda.
- **[Deep dive on the Neocloud GPU rental industry](https://www.useluminix.com/reports/industry-analysis/deep-dive-on-the-neocloud-gpu-rental-industry-coreweave-lambda-crusoe/source/0)** `Research` — Business models, contract structures, and revenue estimates.

---

## Energy & Sustainable Neoclouds

Providers and research focused on energy efficiency, stranded power, and sustainability.

- **[Crusoe Energy](https://crusoe.com/)** `Provider` — Converts stranded or wasted energy into digital infrastructure.
- **[Firmus](https://firmus.co/)** `Provider` — Sustainable data center and AI cloud infrastructure.
- **[IREN](https://www.iren.com.au/)** `Provider` — Australian renewable-energy-powered HPC and AI infrastructure.

---

## Sovereign & Regional Neoclouds

Providers focused on data residency, sovereignty, and regional AI capacity.

- **[Nebul](https://nebul.com/)** `Provider` — Sovereign AI cloud for European organizations.
- **[Nscale](https://nscale.com/)** `Provider` — European and U.S. AI infrastructure with large-scale capacity builds.
- **[Yotta Data Services](https://www.yotta.com/)** `Provider` — India-focused cloud and AI cloud provider.
- **[Cassava](https://cassavatechnologies.com/)** `Provider` — African cloud and AI infrastructure.

---

## Software for Building Neoclouds

Open-source and vendor software used by Neoclouds to build multi-tenant AI clouds.

- **[NVIDIA Cloud Accelerator / NCP Software Reference Guide](https://docs.nvidia.com/ncx/ncp-software-reference-guide/latest/introduction.html)** `Official` — NVIDIA's reference for building AI cloud services.
- **[NVIDIA Base Command Manager](https://www.nvidia.com/en-us/data-center/base-command-manager/)** `Official` — Cluster provisioning and workload management for NVIDIA GPU clusters.
- **[DGX Cloud Lepton](https://www.nvidia.com/en-us/data-center/dgx-cloud/)** `Official` — NVIDIA's aggregated access layer for partner GPU clouds.
- **[RunPod](https://www.runpod.io/)** `Platform` — Serverless GPU cloud platform used by many GPU-as-a-Service providers.
- **[Vast.ai](https://vast.ai/)** `Marketplace` — Peer-to-peer GPU rental marketplace.

---

## Related Atlases

| Topic | Repository |
|---|---|
| Compare GPU cloud providers broadly | [awesome-gpu-cloud](https://github.com/Enterprise-AI-Atlas/awesome-gpu-cloud) |
| NVIDIA agentic skills & MCP servers | [awesome-nvidia-agentic-skills-mcp](https://github.com/Enterprise-AI-Atlas/awesome-nvidia-agentic-skills-mcp) |
| NVIDIA Base Command Manager | [awesome-nvidia-base-command-manager](https://github.com/Enterprise-AI-Atlas/awesome-nvidia-base-command-manager) |
| Local LLMs | [awesome-local-llms](https://github.com/Enterprise-AI-Atlas/awesome-local-llms) |

---

## Contributing

Please read [CONTRIBUTING.md](./CONTRIBUTING.md) before submitting additions.

Run `./scripts/validate-links.sh` before opening a pull request.

---

## License

This registry is released under [CC0 1.0 Universal](./LICENSE). Use it freely.

---

**Disclaimer:** This repository is independently curated and is not affiliated with or endorsed by NVIDIA, CoreWeave, Nebius, Lambda, or any other provider listed.
