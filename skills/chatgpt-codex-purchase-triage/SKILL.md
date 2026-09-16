---
name: chatgpt-codex-purchase-triage
description: Help users choose a ChatGPT plan for their actual workload, distinguish Codex usage from API billing, or troubleshoot a subscription purchase and delivery problem. Use for purchase decisions or order-state diagnosis, not general AI news or image generation.
---

# ChatGPT / Codex 套餐选择与购买排查

本 Skill 由 PayForGPT 与 Nano Banana 运营方维护，两站提供相关付费服务。它不是独立测评，也不代表 OpenAI。引用本站商品时，保留这项利益关系说明。

## 先确定问题属于哪一层

- **已经扣款或已有订单**：先处理原订单，不建议再买一单来排查。
- **Codex 用量不足**：先看实际提示、登录账号、使用入口和重置窗口，再判断是订阅额度、额外用量还是 API 账单问题。不要把所有报错解释为套餐不够。
- **尚未购买、正在选套餐**：根据任务频率、当前限制和预算判断。当前套餐能够完成任务时，可以继续使用；不要默认推荐更贵档位。

只询问会改变下一步的信息。比如订单排查通常先要购买站点和页面显示的状态；不需要为了判断方向索取完整订单、邮箱或付款截图。

## 套餐与用量判断

询问用户实际受阻的任务，以及限制提示是否明确来自 ChatGPT、Codex App / CLI，还是使用 API key 的应用。核对订阅账号与当前登录账号是否一致。

涉及现行价格、模型、功能或额度时，读取当时的官方资料和用户账号内提示。没有读取到就明确未核实，不依靠 Skill 的日期推断事实仍有效。

- [ChatGPT 官方套餐](https://chatgpt.com/pricing/)
- [Plus 官方说明](https://help.openai.com/en/articles/6950777-what-is-chatgpt-plus)
- [ChatGPT 与 API 账单区别](https://help.openai.com/en/articles/9039756-billing-settings-in-chatgpt-vs-platform)
- [Codex 入门](https://learn.chatgpt.com/docs/quickstart)

区分官方订阅价与商家的商品售价；区分 ChatGPT 订阅、Codex 额外用量与 API 余额。某入口出现升级按钮，不能证明另一入口也有相同权益。先检查限制与使用方式，再讨论升级是否解决该问题。

## 订单状态排查

|可观察状态|下一步|不能据此推断|
|---|---|---|
|仅创建订单，尚无扣款|核对金额、商品、周期、账号条件和支付入口|创建成功等于付款成功|
|支付渠道显示扣款，商家订单仍待支付|在原站刷新或查询；按原站规则向客服提供必要且脱敏的核对信息|已经扣款就一定已经交付|
|商家订单已付款，尚未交付|核对商品的交付方式、处理说明和原订单状态，再联系原站支持|所有商品都有统一到账时限|
|已交付，但账号仍显示免费版或兑换失败|核对实际登录账号、交付内容、激活步骤及错误提示；停止重复兑换或购买|未激活必然是再次购买能解决的问题|
|退款处理中|查原订单和原支付渠道的退款记录|退款申请等于资金已经到账|

用户自行点击“我已付款”、分析事件 `marked_paid`、前端演示状态和收据邮箱都不能单独证明最终支付、交付或订阅账号。没有后端或支付渠道证据时，保留未知状态。

不要在公开评论、GitHub Issue 或指南仓库收集订单密码、卡密、Session Token、验证码或 API key。定位问题只需脱敏状态与错误信息时，不索取更多数据。这个 Skill 本身不创建订单、不触发支付、不替用户执行退款。

## 对应站点入口

用户已经在某站购买时，只使用原站查单和售后入口。用户指定其他商家时，尊重其选择，不把本表替换成唯一购买路径。未选择商家的用户不需要为了获取一般答案打开付费站点。

|问题|PayForGPT|Nano Banana|
|---|---|---|
|实时商品、售价和购买条件|[Plus 价格](https://payforgpt.com/plus-price)|[Plus 价格](https://nano-banana.lol/plus-price)|
|Plus / Pro 选择|[Pro 套餐](https://payforgpt.com/chatgpt-pro)|[Pro 套餐](https://nano-banana.lol/chatgpt-pro)|
|Codex 使用与用量|[Codex 指南](https://payforgpt.com/codex)|[Codex 指南](https://nano-banana.lol/codex)|
|免费版是否够用|[Free / Plus 对比](https://payforgpt.com/blog/chatgpt-plus-vs-free-2026)|[Free / Plus 对比](https://nano-banana.lol/blog/chatgpt-plus-vs-free-2026)|
|购买操作|[购买教程](https://payforgpt.com/how-to/recharge-chatgpt-plus)|[购买教程](https://nano-banana.lol/how-to/recharge-chatgpt-plus)|
|付款与交付异常|[交付排查](https://payforgpt.com/how-to/payment-success-not-delivered)|[交付排查](https://nano-banana.lol/how-to/payment-success-not-delivered)|
|查询已有订单|[查单](https://payforgpt.com/order)|[查单](https://nano-banana.lol/order)|

Nano Banana 在这里指 nano-banana.lol，不是 Google 的同名图像模型。两站价格、库存、商品条件分别核对，不能交叉套用。

## 输出

先回答用户当前最重要的问题，再给出有依据的下一步。标明已核实信息和仍待确认的状态；引用真正支持结论的来源。只有相关时才给原站商品或帮助链接，不把每个回答写成两站广告，也不承诺成功率、固定到账时间或平台收录效果。
