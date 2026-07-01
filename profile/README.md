# BidScout 业务线

招投标/商机发现相关业务资产。

## Repository Map

| Repository | Visibility | Purpose |
|---|---:|---|
| [`BidScout`](https://github.com/Business-Unit-for-BidScout/BidScout) | private | BidScout 招投标/商机发现业务仓库。 |
| [`.github`](https://github.com/Business-Unit-for-BidScout/.github) | public | 组织 profile 和仓库地图。 |

## Scope

适合放在本组织：

- 招投标信息发现、线索筛选、商机分析和相关业务系统。
- BidScout 相关需求、数据处理、前后端和部署资产。

不适合放在本组织：

- Enterprise Service 的客户门户和服务交付资产，除非后续明确合并。
- 通用数据治理/RAG/BI 能力，这些归 Data Intelligence。

## Governance

- 具体业务代码、部署、需求和数据资产留在本业务组织。
- 跨 BU 的战略、组合、制度和决策进入 `President-Office`。
- 通用工程底座、RuoYi/Yudao clone/codegen 能力进入 `Business-Unit-for-Platform`。
- AI 平台产品和 AI infra 子域进入 `Business-Unit-for-AI-Platform`。
- 生产部署默认按多机模式设计，数据库/缓存不以 `127.0.0.1` 作为生产默认。

---

_Last updated: 2026-07-01_
