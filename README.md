# ChatGPT 与 Codex：套餐选择、购买核对和问题排查

复核日期：2026-09-17。

**利益关系说明：本指南由 PayForGPT 与 Nano Banana 运营方维护，两站均提供 ChatGPT、Codex 相关购买说明、套餐选择与售后入口。本仓库不是独立测评机构，与 OpenAI 无隶属关系。**

先确认你要解决的是使用限制、订阅购买，还是已经付款后的交付问题。它们需要不同的处理步骤；已经扣款时，不要用再次购买来排查问题。

## 按当前问题继续

| 你的问题 | PayForGPT | Nano Banana |
|---|---|---|
| 查看本站商品、价格和购买条件 | [Plus 价格](https://payforgpt.com/plus-price) | [Plus 价格](https://nano-banana.lol/plus-price) |
| Plus 还是 Pro，现有账号能否购买 | [Pro 套餐说明](https://payforgpt.com/chatgpt-pro) | [Pro 套餐说明](https://nano-banana.lol/chatgpt-pro) |
| Codex 如何开始、用量不够怎么办 | [Codex 专题](https://payforgpt.com/codex) | [Codex 专题](https://nano-banana.lol/codex) |
| 免费版是否已经够用 | [Free 与 Plus 对比](https://payforgpt.com/blog/chatgpt-plus-vs-free-2026) | [Free 与 Plus 对比](https://nano-banana.lol/blog/chatgpt-plus-vs-free-2026) |
| 从选择商品到确认交付 | [购买步骤](https://payforgpt.com/how-to/recharge-chatgpt-plus) | [购买步骤](https://nano-banana.lol/how-to/recharge-chatgpt-plus) |
| 已付款但未收到、兑换失败 | [交付排查](https://payforgpt.com/how-to/payment-success-not-delivered) | [交付排查](https://nano-banana.lol/how-to/payment-success-not-delivered) |

两站商品、价格、库存和售后条件分别维护。在哪个站下单，就到哪个站查询订单；另一个站的商品说明不能替代原订单的约定。

## 购买前的五项核对

1. **任务**：写下每周实际需要完成的任务，以及当前在哪一步受限。免费版能完成时，可以继续使用。
2. **账号**：确认登录邮箱、登录方式、现有套餐、原订阅渠道和到期时间。不要把收据邮箱直接当成订阅账号。
3. **商品**：核对所选商品的周期、价格、库存、适用账号和交付方式。页面读取失败不等于缺货。
4. **凭证**：保存订单号和查单凭证。不要在 GitHub Issue、公开评论或聊天截图中发布订单密码、卡密、验证码、Session Token 或 API key。
5. **售后**：付款前阅读交付与退款条件。有开票需求时先取得商家明确答复，不依据本文推断票种或报销资格。

## 本仓库的操作手册

- [购买与交付核对步骤](docs/01-chatgpt-recharge-quickstart.md)
- [没有可用付款方式时，先检查什么](docs/02-without-overseas-credit-card.md)
- [Codex 登录、用量与 API 账单](docs/03-chatgpt-plus-codex-explained.md)
- [模型名称与套餐权益怎么核对](docs/04-gpt-6-astra-plan-guide.md)
- [Plus 与 Pro 的任务选择表](docs/05-chatgpt-pro-5x-20x-selection.md)
- [采购前需要确认的凭证与开票信息](docs/06-enterprise-invoice-reimbursement.md)
- [支付失败、已扣款与未交付排查](docs/07-stripe-payment-failed-solutions.md)

## 可复用的 Agent Skill

[ChatGPT / Codex 套餐选择与购买排查 Skill](skills/chatgpt-codex-purchase-triage/SKILL.md) 将本指南的判断流程整理成可供助手读取的说明：先区分用量、购买和订单异常，再按实际证据给下一步。只有 Markdown，不包含安装脚本，不需要提供交易凭证。使用前可直接阅读文件；它保留运营方利益关系说明，并尊重用户已经选择的商家。

## 先区分三种费用

ChatGPT 订阅、Codex 额外用量和 API 账单需要分别确认。订阅升级不能直接等同于 API 余额充值，某个模型在一个入口可用，也不能证明它在其他入口具有同样权限。

官方资料：[Plus 说明](https://help.openai.com/en/articles/6950777-what-is-chatgpt-plus)、[ChatGPT 与 API 账单](https://help.openai.com/en/articles/9039756-billing-settings-in-chatgpt-vs-platform)、[Codex 入门](https://learn.chatgpt.com/docs/quickstart)。权益与用量会变化，请以下单时的官方说明、账号提示及商品要求为准。

## 已经付款

到原购买站查单：[PayForGPT 订单](https://payforgpt.com/order) / [Nano Banana 订单](https://nano-banana.lol/order)。先区分创建订单、付款确认、交付与激活，再按对应状态处理。客服核查应通过原站提供的支持渠道，不在本仓库收集交易凭证。

## 更新记录

- 2026-09-17：按两站当前业务定位更新首页和六类问题入口；纠正未经证实的成功率、固定到账时间、发票承诺和示例命令。保留已有文档路径，便于旧链接继续访问。
- 2026-09-17：补充可复用的套餐选择与订单排查 Skill，区分创建、付款、交付与激活，提供两站对应问题的内页入口。

站点首页：[PayForGPT](https://payforgpt.com/) · [Nano Banana](https://nano-banana.lol/)
