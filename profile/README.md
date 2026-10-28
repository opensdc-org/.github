<div align="center">

# OpenSDC

**Open Scientific Data Compression**
**开放科学数据压缩社区**

[English](#english) · [中文](#中文)

</div>

---

## English

OpenSDC is an open community for **high-performance scientific data compression**. We develop, maintain, and benchmark error-bounded lossy and lossless compressors for HPC and AI-for-Science workloads, with first-class support for a wide range of CPU, GPU, and accelerator architectures.

Scientific simulations, large instruments, and AI models now produce data far faster than storage, I/O, and networks can absorb. OpenSDC aims to make compression a dependable building block of scientific data management: **high ratio, high throughput, strict error control, and portable across platforms.**

### Projects

| Project | Description | Publication |
|---|---|---|
| [**Falcons**](https://github.com/opensdc-org/Falcons) | Error-bounded lossy compressor optimized for parallel scientific applications on x86, ARM, and accelerator platforms | PPoPP '27 |
| [**PRISM**](https://github.com/opensdc-org/PRISM) | GPU-based progressive lossy compression for on-demand, precision-aware data retrieval | PPoPP '26 (Best Paper Nominee) |
| [**MANS**](https://github.com/opensdc-org/MANS) | Efficient and portable ANS entropy coding for multi-byte integer data on CPUs and GPUs | SC '25 |
| [**CAIEC**](https://github.com/opensdc-org/CAIEC) | Learning-based compression with co-optimized model inference and entropy coding | Coming soon |
| [**PhotonZip**](https://github.com/opensdc-org/PhotonZip) | Compression software package for light source (synchrotron) data | NPC '26 |

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

### 项目

| 项目 | 简介 | 发表 |
|---|---|---|
| [**Falcons**](https://github.com/opensdc-org/Falcons) | 面向并行科学应用的误差可控有损压缩器，针对 x86、ARM 及加速器平台深度优化 | PPoPP '27 |
| [**PRISM**](https://github.com/opensdc-org/PRISM) | 基于 GPU 的渐进式有损压缩框架，支持按精度需求按需检索数据 | PPoPP '26（最佳论文提名） |
| [**MANS**](https://github.com/opensdc-org/MANS) | 面向多字节整型数据的高效可移植 ANS 熵编码，支持 CPU 与 GPU | SC '25 |
| [**CAIEC**](https://github.com/opensdc-org/CAIEC) | 模型推理与熵编码协同优化的学习型压缩 | 即将发表 |
| [**PhotonZip**](https://github.com/opensdc-org/PhotonZip) | 面向光源数据的压缩软件包 | NPC '26 |

### 社区原则

- **开放**：采用 BSD-3-Clause / MIT 等宽松开源许可证，任何人均可使用、修改和贡献。
- **可移植**：面向多样化硬件高效运行，不绑定单一厂商。
- **可复现**：所有性能结论均有公开基准与脚本支撑。
- **社区驱动**：评审公开透明，每个 PR 都会得到及时、有理由的回复。

### 参与方式

- 阅读[贡献指南](https://github.com/opensdc-org/.github/blob/main/CONTRIBUTING.md)。
- 在任意项目仓库提交 Issue 或 Pull Request。
- 联系方式：taodingwen@ict.ac.cn, jinyang.liu@sjtu.edu.cn
