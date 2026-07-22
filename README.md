# RefundShield

RefundShield 是面向电商售后争议的 **pre-revenue MVP / 项目与概念**。
它把合成的订单、物流、聊天和图片证据整理为可追溯时间线，并生成确定性检查、证据缺口、回复草稿以及 HTML/PDF 报告。

[English README](README.en.md)

> 当前是本地可复现的合成演示，不是已经上线运营的 SaaS。

## 当前事实

| 项目 | 状态 |
| --- | --- |
| 年收入 | 0 |
| 年利润 | 0 |
| 付费客户 | 0 |
| 公开生产部署 | 否 |
| 演示数据 | 全部合成 |
| 发布资格 | `release_eligible=false` |
| 当前阶段 | Pre-revenue MVP |

## 产品演示

### 工作方式

![RefundShield 首页桌面截图](assets/home-desktop.png)

![RefundShield 首页移动截图](assets/home-mobile.png)

### 工作台与案件

![RefundShield 工作台](assets/workspace-desktop.png)

![RefundShield 案件分析](assets/case-desktop.png)

![RefundShield 案件移动端](assets/case-mobile.png)

### 报告输出

![RefundShield 报告预览](assets/report-desktop.png)

## 核心能力

- 证据编号、来源和原始文件指纹
- 订单、商品、聊天、物流和使用时间线
- 确定性规则、缺口识别和补证建议
- 中文/英文优先回复草稿
- HTML 与 PDF 报告
- 五类争议模板的本地合成演示
- 买方可在隔离环境中复现完整 demo seed

## 交付范围

完整源码、测试、迁移、依赖锁定文件、部署说明、技术文档、许可证清单和合成演示资产位于私有交付仓库：

**[RefundShield MVP Handoff](https://github.com/Lxsky-i/refundshield-mvp-handoff)**

交付仓库不包含真实客户数据、密钥、第三方账号、生产数据库或不可转让的 Provider 合同。

## 限制与边界

- 系统不判断买家是否欺诈，不提供法律意见，也不承诺争议结果。
- 真实 PostgreSQL、AI/OCR/visual Provider、生产外部服务、PITR、支付和公开部署不属于当前演示承诺。
- 名称、品牌、素材和第三方依赖的权属与许可证边界以交付仓库中的清单和正式协议为准。

## 联系与审查

有意查看源码或讨论一次性交接时，请通过 GitHub 个人主页联系，并先确认演示范围、转让清单、受限源码审查和正式协议条款。
