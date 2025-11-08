# Contributing to MedSegTTABoard

感谢你对 MedSegTTABoard 的关注与贡献！以下为最小化摩擦的贡献流程与规范（中文为主，术语保留英文）。

## 快速开始
- Fork 本仓库，并创建分支：`git checkout -b feat/<short-name>` 或 `fix/<short-name>`。
- 保持提交信息遵循 Conventional Commits（例如：`feat: add CT pipeline configs`、`fix: link check false positive`）。
- 提交 PR 前请本地自查：
  - Markdown 规范：建议使用 `markdownlint`（CI 会二次检查）。
  - 外链可用性：尽量使用稳定 URL；CI 会做全面链接检查。
  - 图片：优先使用 PNG/SVG；体积控制在合适范围。
- 在 PR 描述中清晰说明：变更动机、主要修改点、是否影响文档/用户。

## 代码与文档风格
- Python（后续开源时）：遵循 PEP8；适度注释，避免冗余；严格区分评测与训练脚本。
- 文档：README/指南类文档使用英文（Chinese README 可附带），表格/链接保持易读性与稳定性。
- 资源：所有非必要的大文件不要直接入库；数据下载用链接，模型权重用发布页或外部存储。

## 目录约定（将随开源逐步完善）
- `fig/`：README 配图与示意图
- `scripts/`：自动化脚本（构建、评测、工具）
- `configs/`：基线/实验配置（规划中）
- `tools/`：评测与可复现工具（规划中）

## 许可证与版权
- 本仓库使用 MIT License（见 `LICENSE`）。
- 提交贡献即默认同意按 MIT 许可协议进行授权。

## 行为准则
- 彼此尊重、开放包容，欢迎不同观点。
- 禁止任何形式的人身攻击、歧视与骚扰。

## 联系与讨论
- 问题反馈与建议：请使用 GitHub Issues。
- 大改动或新特性提案：先开 RFC 类型的 Issue 以征求意见。

感谢你的贡献！
