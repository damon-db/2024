---
title: "Keynote & Talks"
weight: 4
theme: "damon-dark"
---

# Keynote & Invited Talks

## Keynote Talk
### NVMe and Data Systems: A Decade and Counting
#### Philippe Bonnet, IT University of Copenhagen

![Potrait of Philippe Bonnet](/img/philippe_bonnet.png)

**Abstract**: NVMe is synonymous with modern storage. It was introduced as a means to efficiently expose Solid-State Drives as PCIe 3.0 peripherals. With NVMe, I/Os were no longer the bottleneck. Initially, the challenge for operating system and database system designers was to accomodate radically faster storage devices. Then, SSDs evolved to meet a range of cost/performance requirements. Accordingly, NVMe 2.0 introduced new transport models, storage models and cross-layer optimizations. This diversity introduced new challenges. Today, NVMe passthru and Flexible Data Placement enable data systems designers to shape how data is stored, instead of designing their systems around the characteristics of opaque storage devices. Computational storage was supposed to further improve the ability of system designers to specialize storage devices to fit their workloads. However, device memory management became a challenge. We discuss the proposed standard and speculate on the role NVMe may play in future data systems, in a context where CXL emerges, PCIe 7.0 is being standardized and power consumption is the bottleneck.

<details>
  <summary>About the Speaker</summary>
Philippe Bonnet is professor at DIKU, the department of Computer Science of the University of Copenhagen. He contributed to the uFlip Benchmark, the Linux multiqueue block layer, the Linux framework for Open-Channel SSDs, the OX architecture for computational storage, the xNVMe library and Delilah, a prototype for eBPF offload on computational storage. Philippe is co-author of the book “Principles of Database and Solid State Drive Co-Design” with Alberto Lerner. He is currently trustee of the VLDB endowment and chair of the ACM EIG on Reproducibility and Replicability.
</details>

--- 

## Invited Talk

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
<a href="https://en.wikipedia.org/wiki/David_Patterson_(computer_scientist)">David Patterson</a> is a UC Berkeley Pardee professor emeritus, a Google distinguished engineer, and the <a href="https://riscv.org/">RISC-V International</a> Vice-Chair. His most influential Berkeley projects likely were <a href="https://en.wikipedia.org/wiki/Reduced_instruction_set_computer">RISC</a> (Reduced Instruction Set Computer) and <a href="https://en.wikipedia.org/wiki/RAID">RAID</a> (Redundant Array of Inexpensive Disks). His best-known book is <a href="https://www.amazon.com/Computer-Architecture-Quantitative-Approach-Kaufmann/dp/0128119055">Computer Architecture: A Quantitative Approach</a>. He and his co-author <a href="https://en.wikipedia.org/wiki/John_L._Hennessy">John Hennessy</a> shared the <a href="https://www.acm.org/media-center/2018/march/turing-award-2017">2017 ACM A.M Turing Award</a> and the <a href="https://www.nae.edu/266390/RISC-Chip-Innovators-Receive-the-2022-Charles-Stark-Draper-Prize-for-Engineering">2022 NAE Charles Stark Draper Prize for Engineering</a>. The Turing Award is often referred to as the “Nobel Prize of Computing” and the Draper Prize is considered a “Nobel Prize of Engineering.”
</details>

--- 

## Fresh Thinking Talk

### Effortless Locality Through On-the-fly Data Transformation
#### Manos Athanassoulis, Boston University

![Potrait of David Patterson](/img/manos_athanassoulis.jpg)

**Abstract**: What if we could access any layout and ship only the relevant data through the memory hierarchy by transparently converting rows to (arbitrary groups of) columns? We capitalize on the reinvigorated trend of hardware specialization to propose Relational Fabric, a near-data vertical partitioner that allows memory or storage components to perform on-the-fly transparent data transformation. By exposing an intuitive API, Relational Fabric pushes vertical partitioning to the hardware, which has a profound impact on the process of designing and building data systems. (A) There is no need for data duplication and layout conversion, making hybrid systems viable using a single layout. (B) It simplifies the memory and storage manager. (C) It reduces unnecessary data movement through the memory hierarchy allowing for better hardware utilization and, ultimately, better performance. In this talk, I will introduce the Relational Fabric vision and present our initial results on in-memory systems. I will also share some of the challenges of building this hardware and the opportunities it brings for simplicity and innovation in the data system software stack, including physical design, query processing, and concurrency control, and conclude with ongoing work for data transformation for general workloads including matrix and tensor processing.

<details>
  <summary>About the Speaker</summary>
Manos Athanassoulis is an Assistant Professor of Computer Science at Boston University, Director and Founder of the BU Data-intensive Systems and Computing Laboratory and co-director of the BU Massive Data Algorithms and Systems Group. His research is in the area of data management focusing on building data systems that efficiently exploit modern hardware (computing units, storage, and memories), are deployed in the cloud, and can adapt to the workload both at setup time and, dynamically, at runtime. Before joining Boston University, Manos was a postdoctoral researcher at Harvard School of Engineering and Applied Sciences. Manos obtained his PhD from EPFL, Switzerland, and spent one summer at IBM Research, Watson. Manos’ work is published in top conferences and journals of the community, like ACM SIGMOD, PVLDB, ACM TODS, VLDBJ, and others, and has been recognized by awards like “Best Demonstration” in VLDB 2023, “Best of SIGMOD” in 2017, “Best of VLDB” in 2010 and 2017, and “Most Reproducible Paper” at SIGMOD in 2016. Manos has been acting as a program committee member and technical reviewer in top data management conferences and journals for the past 12 years, having received the “Distinguished PC Member Award” for SIGMOD 2018 and SIGMOD 2023. He is currently an associate editor for ACM SIGMOD Record, co-chair of ACM SIGMOD 2023 Availability and Reproducibility, and co-chair of ICWE 2023 Industrial Track. His work is supported by several awards, including an NSF CRII award, an NSF CAREER award, a Facebook Faculty Research Award, multiple RedHat Collaboratory Research Incubation Awards, and a Cisco Research Award.
</details>