---
title: "Keynote & Talks"
weight: 4
theme: "damon-dark"
---

# Keynote & Invited Talks

## Keynote
### NVMe and Data Systems: a Decade and Counting
#### Philippe Bonnet, IT University of Copenhagen

![Potrait of Philippe Bonnet](/img/philippe_bonnet.png)

**Abstract**: NVMe is synonymous with modern storage. It was introduced as a means to efficiently expose Solid-State Drives as PCIe 3.0 peripherals. With NVMe, I/Os were no longer the bottleneck. Initially, the challenge for operating system and database system designers was to accomodate radically faster storage devices. Then, SSDs evolved to meet a range of cost/performance requirements. Accordingly, NVMe 2.0 introduced new transport models, storage models and cross-layer optimizations. This diversity introduced new challenges. Today, NVMe passthru and Flexible Data Placement enable data systems designers to shape how data is stored, instead of designing their systems around the characteristics of opaque storage devices. Computational storage was supposed to further improve the ability of system designers to specialize storage devices to fit their workloads. However, device memory management became a challenge. We discuss the proposed standard and speculate on the role NVMe may play in future data systems, in a context where CXL emerges, PCIe 7.0 is being standardized and power consumption is the bottleneck.

<details>
  <summary>About the Speaker</summary>
Philippe Bonnet is professor at DIKU, the department of Computer Science of the University of Copenhagen. He contributed to the uFlip Benchmark, the Linux multiqueue block layer, the Linux framework for Open-Channel SSDs, the OX architecture for computational storage, the xNVMe library and Delilah, a prototype for eBPF offload on computational storage. Philippe is co-author of the book “Principles of Database and Solid State Drive Co-Design” with Alberto Lerner. He is currently trustee of the VLDB endowment and chair of the ACM EIG on Reproducibility and Replicability.
</details>

--- 

## Invited Talks

### Computer Architecture in Flux: The Central Processing Unit Is No Longer Central
#### David Patterson, University of California Berkeley

![Potrait of David Patterson](/img/dave_patterson.jpg)

**Abstract**: We start with a review of the instability of modern hardware, given the 
- slowing of Moore's Law, 
- the end of Dennard scaling, and 
- the rise of the demand for AI cycles versus traditional applications.

Data is becoming more critical than compute due to its increasing cost and slowing capacity curves for memory and storage. Data location and movement are now central to cost and performance. To build robust systems in light of these changes, we must shift the focus of hardware and software design from processing to the memory, storage, and network components.

<details>
  <summary>About the Speaker</summary>
David Patterson is a UC Berkeley Pardee professor emeritus, a Google distinguished engineer, and the RISC-V International Vice-Chair. His most influential Berkeley projects likely were RISC (Reduced Instruction Set Computer) and RAID (Redundant Array of Inexpensive Disks). His best-known book is Computer Architecture: A Quantitative Approach. He and his co-author John Hennessy shared the 2017 ACM A.M Turing Award and the 2022 NAE Charles Stark Draper Prize for Engineering. The Turing Award is often referred to as the “Nobel Prize of Computing” and the Draper Prize is considered a “Nobel Prize of Engineering.”
</details>

--- 

#### Manos Athanassoulis, Boston University

