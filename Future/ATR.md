---
title: ATR
description: 
published: true
date: 2024-07-27T10:23:30.697Z
tags: 
editor: markdown
dateCreated: 2024-07-24T11:21:22.021Z
---

# ATR(Average True Range)
真实波幅是以下三个值中的最大值：
* 当前最高价与当前最低价的差值。
* 当前最高价与前一个收盘价的差值的绝对值。
* 当前最低价与前一个收盘价的差值的绝对值。
## 公式
- 计算TR（True Range）：
	- TR = max(当前最高价 - 当前最低价, |当前最高价 - 前一个收盘价|, |当前最低价 - 前一个收盘价|)
- 计算ATR（Average True Range）：
	- 选择一个周期（常用的是14天）。
	- 第一天的ATR是当天的TR。
	- 从第二天开始，ATR = [(前一天的ATR × (n-1)) + 当前的TR] / n，其中n是选定的周期天数。
## 应用
- 在交易中，控制风险是非常重要的。ATR可以帮助确定头寸大小，也可以帮助设定止损目标。例如在左侧交易，如趋势线底部，考虑到弱通道的反转概率大，有望测试通道起点，如果在通道底部挂单，期望反弹的话，在成交后如何确定止损位置？ 
	- 可以利用1-2倍的当前周期的ATR数值作为参考，例如NQ 5min的 ATR 在 RTH一般为20-40，可以选择最近的一段时间内的ATR，设定1-2倍的ATR作为止损目标位
  
- 在交易中，如何确定lot的大小？
	- 举例50k的账户，单比风险控制在0.5%-1%，也就是250-500$, 那么假设MNQ的1.5倍ATR是50 point, 且是你的止损目标, 那么根据一个点2$的波动，50点的止损就是100$。 由于目标单比风险的200-500，目标lot理论章应该是2-5个contract比较合适。
