# Contributing to OpenSDC / 贡献指南

Thank you for your interest in OpenSDC! We welcome contributions of all kinds: bug reports, new compressors, platform ports, performance optimizations, benchmarks, documentation, and translations.

感谢你对 OpenSDC 的关注！我们欢迎各种形式的贡献：问题反馈、新压缩算法、平台移植、性能优化、评测数据集与脚本、文档与翻译。

---

## 1. Ways to contribute / 贡献方式

| Type | How |
|---|---|
| Bug report / 问题反馈 | Open an issue with steps to reproduce, platform, compiler, and dataset. 提交 Issue，注明复现步骤、平台、编译器和数据集。 |
| Feature or platform port / 新功能或平台移植 | Open an issue first to discuss the design, then submit a PR. 先提 Issue 讨论设计，再提交 PR。 |
| New compressor / 新压缩器 | Propose it in the [`community`](https://github.com/opensdc-org/community) repository; accepted projects get their own repository under OpenSDC. 在 `community` 仓库提交提案，通过后在 OpenSDC 下新建仓库。 |
| Benchmarks / 评测 | Add datasets, scripts, or results to `sdc-bench`. 向 `sdc-bench` 贡献数据集、脚本或结果。 |

## 2. Pull request workflow / PR 流程

1. Fork the repository and create a branch from `main`. Fork 仓库并从 `main` 新建分支。
2. Keep each PR focused on one change. 每个 PR 只做一件事。
3. Make sure the project builds and all tests pass on at least one supported platform. 至少在一个支持的平台上编译通过并通过全部测试。
4. For performance changes, include before/after numbers, the hardware, and the dataset. 性能相关修改请附上修改前后数据、硬件环境与数据集。
5. For changes to compression output, report compression ratio and error metrics (e.g., max error, PSNR) and confirm the error bound is respected. 涉及压缩结果的修改，请给出压缩比与误差指标（如最大误差、PSNR），并确认满足误差界。
6. Sign off your commits (`git commit -s`) to certify the [Developer Certificate of Origin](https://developercertificate.org/). 提交时签署 DCO（`git commit -s`）。

## 3. Review policy / 评审规则

- Every PR is acknowledged by a maintainer within **7 days**. 每个 PR 将在 **7 天内**得到维护者回复。
- Reviews focus on correctness, error-bound guarantees, performance, portability, and code quality. 评审关注正确性、误差界保证、性能、可移植性和代码质量。
- If a PR is not accepted, maintainers will explain the reason and, where possible, suggest a path forward. 若 PR 未被接受，维护者会说明理由，并尽可能给出修改建议。
- Platform-specific optimizations are welcome as long as they do not break other supported platforms. 只要不影响其他已支持平台，欢迎提交面向特定平台的优化。
- A PR is merged after approval by at least one maintainer of the repository. PR 需至少一位该仓库维护者批准后合并。

## 4. Coding guidelines / 代码规范

- Follow the existing style of the repository (a `.clang-format` file is provided where applicable). 遵循仓库现有代码风格（如有 `.clang-format` 请使用）。
- Add or update tests for new functionality. 新功能请补充或更新测试。
- Document public APIs and new configuration options. 公共接口和新增配置项请写明文档。
- Do not commit large datasets; link to them instead. 不要提交大型数据集，请提供下载链接。

## 5. License / 许可证

All contributions are released under the **BSD 3-Clause License**. By submitting a contribution, you agree that it may be distributed under this license. If your contribution is derived from third-party code, keep the original copyright notice and license, and state the source in your PR.

所有贡献均以 **BSD 3-Clause 许可证**发布。提交贡献即表示你同意按此许可证分发。若贡献基于第三方代码，请保留原版权声明与许可证，并在 PR 中注明来源。

## 6. Code of Conduct / 行为准则

We are committed to a welcoming and respectful community for everyone, regardless of nationality, institution, or background. Please be constructive and professional in all interactions. Report concerns to taodingwen@ict.ac.cn or jinyang.liu@sjtu.edu.cn.

我们致力于建设一个开放、相互尊重的社区，不论国籍、单位或背景。请在所有交流中保持建设性和专业性。如有问题请联系 taodingwen@ict.ac.cn 或 jinyang.liu@sjtu.edu.cn。

## 7. Contact / 联系方式

- Issues and discussions: in the relevant repository / 在对应仓库提 Issue 或 Discussion
- Email / 邮箱: taodingwen@ict.ac.cn, jinyang.liu@sjtu.edu.cn
