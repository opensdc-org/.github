<div align="center">

# OpenSDC

**Open Scientific Data Compression**
**开放科学数据压缩社区**

[**Website**](https://opensdc-org.github.io/) · [**Benchmark & Leaderboard / 评测与榜单**](https://opensdc-org.github.io/benchmark/) · [**Benchmark Code / 评测代码**](https://github.com/opensdc-org/OpenSDC-Bench)

[English](#english) · [中文](#中文)

</div>

---

## English

OpenSDC is an open community for **high-performance scientific data compression**. We develop, maintain, and benchmark error-bounded lossy and lossless compressors for HPC and AI-for-Science workloads, with first-class support for a wide range of CPU, GPU, and accelerator architectures.

Scientific simulations, large instruments, and AI models now produce data far faster than storage, I/O, and networks can absorb. OpenSDC aims to make compression a dependable building block of scientific data management: **high ratio, high throughput, strict error control, and portable across platforms.**

### OpenSDC-Bench: open, fair, reproducible benchmarking

Alongside compression software, OpenSDC provides **[OpenSDC-Bench](https://github.com/opensdc-org/OpenSDC-Bench)**: an open-source scientific data compression benchmarking system bringing together evaluation code, scientific datasets, comprehensive metrics, and regularly updated leaderboards. Compare compression ratio, speed, and scientific fidelity across datasets and error bounds under a shared, transparent protocol—helping users choose suitable compressors and developers improve their methods.

**[Explore the leaderboard](https://opensdc-org.github.io/benchmark/)** · [Evaluation code](https://github.com/opensdc-org/OpenSDC-Bench) · [Datasets](https://github.com/opensdc-org/OpenSDC-Bench/tree/main/datasets) · [Contribute a method, metric, or result](https://github.com/opensdc-org/OpenSDC-Bench/blob/main/CONTRIBUTING.md)

### Compression software

#### General-purpose compressors

| Project | Description | Publication |
|---|---|---|
| [**Falcons**](https://github.com/opensdc-org/Falcons) | Error-bounded lossy compressor optimized for parallel scientific applications on x86, ARM, and accelerator platforms | PPoPP '27 ([arXiv](https://arxiv.org/abs/2610.41209)) |
| [**CAIEC**](https://github.com/opensdc-org/CAIEC) | Learning-based compression with co-optimized model inference and entropy coding | Coming soon |
| [**PRISM**](https://github.com/opensdc-org/PRISM) | GPU-based progressive lossy compression for on-demand, precision-aware data retrieval | [PPoPP '26](https://doi.org/10.1145/3774934.3786438) (Best Paper Nominee) |
| [**MANS**](https://github.com/opensdc-org/MANS) | Efficient and portable ANS entropy coding for multi-byte integer data on CPUs and GPUs | [SC '25](https://doi.org/10.1145/3712285.3759825) |
| [**ClustraComp**](https://github.com/opensdc-org/ClustraComp) | Storage framework for grouping similar file chunks before lossless compression with LZ4 or Zstandard | NPC '26 |

#### Domain-specific compressors

| Project | Domain | Description | Publication |
|---|---|---|---|
| [**PhotonZip**](https://github.com/opensdc-org/PhotonZip) | Light sources | Compression software package for light source (synchrotron) data | NPC '26 ([arXiv](https://arxiv.org/abs/2611.04138)) |
| [**SolarZip**](https://github.com/opensdc-org/SolarZip) | Solar physics | Efficient and adaptive compression framework for solar EUV imaging data | [A&A '25](https://www.aanda.org/articles/aa/full_html/2025/10/aa55193-25/aa55193-25.html) |

Contributions of both **general-purpose** compressors and **domain-specific** compressors (e.g., climate, cosmology, microscopy, genomics) are welcome.

### Principles

- **Open** – Permissive open-source licenses (BSD-3-Clause / MIT); anyone can use, modify, and contribute.
- **Portable** – Designed to run efficiently on diverse hardware, not tied to a single vendor.
- **Reproducible** – Every claim backed by public benchmarks and scripts.
- **Community-driven** – Transparent review: every pull request receives a timely, reasoned response.

### Get involved

- Read our [Contributing Guide](https://github.com/opensdc-org/.github/blob/main/CONTRIBUTING.md).
- Open an issue or pull request in any project repository.
- Contact: taodingwen@ict.ac.cn, jinyang.liu@sjtu.edu.cn

---

## 中文

OpenSDC 是一个面向**高性能科学数据压缩**的开放社区，致力于研发、维护和评测面向高性能计算与科学智能（AI4S）场景的误差可控有损压缩与无损压缩软件，并对多种 CPU、GPU 及加速器体系结构提供一流支持。

科学模拟、大科学装置和 AI 模型产生数据的速度，已远超存储、I/O 与网络的承载能力。OpenSDC 希望让压缩成为科学数据管理中可靠的基础组件：**高压缩比、高吞吐、严格误差控制、跨平台可移植。**

### OpenSDC-Bench：开放、公平、可复现的评测系统

除压缩软件外，OpenSDC 还提供 **[OpenSDC-Bench](https://github.com/opensdc-org/OpenSDC-Bench)**，集成开源评测代码、科学数据集、多维评测指标和持续更新的榜单。在统一、透明的协议下，比较不同压缩方法在不同数据集与误差界上的压缩率、速度和科学数据保真度，帮助用户选择适合自身数据的压缩软件，帮助开发者理解性能差异并优化方法。

**[查看评测与榜单](https://opensdc-org.github.io/benchmark/)** · [评测代码](https://github.com/opensdc-org/OpenSDC-Bench) · [数据集](https://github.com/opensdc-org/OpenSDC-Bench/tree/main/datasets) · [贡献方法、指标或结果](https://github.com/opensdc-org/OpenSDC-Bench/blob/main/CONTRIBUTING.md)

### 压缩软件

#### 通用压缩器

| 项目 | 简介 | 发表 |
|---|---|---|
| [**Falcons**](https://github.com/opensdc-org/Falcons) | 面向并行科学应用的误差可控有损压缩器，针对 x86、ARM 及加速器平台深度优化 | PPoPP '27（[arXiv](https://arxiv.org/abs/2610.41209)） |
| [**CAIEC**](https://github.com/opensdc-org/CAIEC) | 模型推理与熵编码协同优化的学习型压缩 | 即将发表 |
| [**PRISM**](https://github.com/opensdc-org/PRISM) | 基于 GPU 的渐进式有损压缩框架，支持按精度需求按需检索数据 | [PPoPP '26](https://doi.org/10.1145/3774934.3786438)（最佳论文提名） |
| [**MANS**](https://github.com/opensdc-org/MANS) | 面向多字节整型数据的高效可移植 ANS 熵编码，支持 CPU 与 GPU | [SC '25](https://doi.org/10.1145/3712285.3759825) |
| [**ClustraComp**](https://github.com/opensdc-org/ClustraComp) | 基于相似文件块分组的无损压缩存储框架，支持 LZ4 和 Zstandard | NPC '26 |

#### 领域专用压缩器

| 项目 | 领域 | 简介 | 发表 |
|---|---|---|---|
| [**PhotonZip**](https://github.com/opensdc-org/PhotonZip) | 光源 | 面向光源数据的压缩软件包 | NPC '26（[arXiv](https://arxiv.org/abs/2611.04138)） |
| [**SolarZip**](https://github.com/opensdc-org/SolarZip) | 太阳物理 | 面向太阳极紫外（EUV）成像数据的高效自适应压缩框架 | [A&A '25](https://www.aanda.org/articles/aa/full_html/2025/10/aa55193-25/aa55193-25.html) |

欢迎贡献**通用压缩器**，也欢迎贡献面向气象气候、宇宙学、显微成像、基因组等领域的**专用压缩器**。

### 社区原则

- **开放**：采用 BSD-3-Clause / MIT 等宽松开源许可证，任何人均可使用、修改和贡献。
- **可移植**：面向多样化硬件高效运行，不绑定单一厂商。
- **可复现**：所有性能结论均有公开基准与脚本支撑。
- **社区驱动**：评审公开透明，每个 PR 都会得到及时、有理由的回复。

### 参与方式

- 阅读[贡献指南](https://github.com/opensdc-org/.github/blob/main/CONTRIBUTING.md)。
- 在任意项目仓库提交 Issue 或 Pull Request。
- 联系方式：taodingwen@ict.ac.cn、jinyang.liu@sjtu.edu.cn
