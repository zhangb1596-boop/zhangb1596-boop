# 👋 Hi，我是张堡

**自动化 / AI 应用开发工程师** ｜ 泉州职业技术大学 · 软件工程（本科 2025 届）
专注把「官方开放平台 API + RPA + AI(MCP/Agent)」串成能落地的业务闭环。

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![RPA](https://img.shields.io/badge/RPA-影刀-FF6A00)](#)
[![飞书](https://img.shields.io/badge/飞书-lark--oapi-3370FF)](#)
[![MCP](https://img.shields.io/badge/MCP-Server-7C3AED)](#)
[![AI Agent](https://img.shields.io/badge/AI-Agent%20落地-10B981)](#)

---

## 📊 数字说话

| 26+ | 1 万+ /月 | 200+ | 8+ |
|:---:|:---:|:---:|:---:|
| 独立交付并在线的自动化 / AI 系统 | 金蝶 ERP 月同步单据量 | 覆盖 TikTok · Shopee · Lazada 店铺 | 服务部门（财务/运营/物流/采购/人事…） |

> 2 年跨境电商企业数字化落地经验：**有官方 API 就走 API 接入，没有就用 RPA 兜底，最后用 MCP 把数据喂给 AI**——这是我反复用的一条方法论。

---

## 🛠 技术栈

- **后端 / 工程化**：Python · FastAPI · APScheduler · SQLite / JSON 持久化
- **开放平台 API**：金蝶云苍穹 Open API ｜ 飞书(lark-oapi) ｜ TikTok Shop / Shopee / Lazada ｜ 巨量千川
- **AI 应用**：自建 **MCP Server**（把 ERP 业务数据标准化给 AI 用）· AI Agent 定时协同 · Vibe Coding 提效
- **RPA / 自动化**：影刀 RPA + Python 处理无 API 场景（网页模拟、PDF 解析、Excel 处理）

---

## 🚀 主打项目

### 1️⃣ 金蝶苍穹 ERP 数据同步管理平台（数据中台）
> Python + FastAPI + APScheduler + 飞书多维表 API，把金蝶 7 条业务线单据自动同步到飞书，替代人工导表。

- 接入 7 条业务线（采购订单 / 海运单 / 采购入库 / 销售出库 / 财务应付 / 暂估应付 / 采购付款），月同步单据 1 万+
- 封装金蝶 Open API：OAuth2 Token 自动刷新、分页遍历、三层字段映射校验，单批最大处理 271 条明细行
- 三种调度模式（interval / daily / multi_daily）+ 失败重试 + 7 天成功率看板
- 附带 **MCP Server** 出口，AI 工具可直接理解金蝶字段语义并作答
- 业务价值：单笔人工操作 15 分钟 → 一键触发 / 自动调度，响应效率提升 90%+

<!-- SHOT:01 数据中台管理端看板截图 -->

### 2️⃣ 出口报关单据自动追踪与对账系统
> 自建金蝶 MCP 数据源 + 柜号主键，把分散在 5 类单据里的报关数据自动聚合成一张对账表，最终落到飞书多维表。

- 「柜号主键 + 应付单双路径挂接」打通 5 类单据自动关联，替代人工 Excel 合并
- 发票匹配从人工模糊桥接 → 备注合同号正则提取 + 大小写不敏感精确匹配，可追溯
- 字段级来源溯源（双行表头 + 6 色单据标注）+ 缺失/未匹配自动预警
- 单次自动产出 23 个柜号、数百行明细与 3 张辅助对账 Sheet

<!-- SHOT:02 追踪表效果（双行表头+色标）截图 -->

### 3️⃣ 巨量千川广告数据同步与利润核算中台（已上线）
> 对接千川 Open API，把广告消耗、订单、计划数据同步下来，按计划 / 素材维度核算「消耗 − 收入 − 利润」。

- Token 自动续期、限流退避重试、增量断点续传、失败可视化告警
- 输出 ROI / 素材效果报表，支撑投放决策

<!-- SHOT:03 千川利润核算看板截图 -->

### 4️⃣ 跨境电商运营自动化矩阵（RPA · 200+ 店铺）
> 影刀 RPA + Python 批量交付财务 / 运营 / 物流高频流程，服务 200+ 店铺。

- 紫鸟自动提款、Shopee/TikTok 数据下载、差评自动删除、活动自动提报、利润测算
- 报关 PDF 智能拆分归档（JYJ / XM 合同号识别，模糊/翻转容错）
- BOSS 直聘自动打招呼等 26+ 个流程全部常态运行

<!-- SHOT:04 RPA 流程列表 / 运行看板截图 -->

---

## 📫 联系我

- 📧 Email：zhangb1596@gmail.com
- 🎯 求职方向：AI 应用开发 / 系统集成 / Python 自动化（RPA · API）
- 📍 现居：厦门
