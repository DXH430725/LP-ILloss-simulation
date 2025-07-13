# LP-ILloss-simulation
Narrow Range LP Impermanent Loss Backtest with Rebalancing Costs
This Pine Script strategy simulates providing liquidity to a narrow price range (LP) in a volatile asset like BTC.



Key Features:
✅ Customizable range: Define the % width around the mid price (e.g., ±3%).
✅ Impermanent Loss estimation: As the price exits the range, all liquidity is effectively converted to one asset (USDC or BTC).
✅ Rebalancing logic: Each time the price leaves the range, the position is rebalanced back to a 50/50 allocation between the two assets.
✅ Average price basis: Rebalancing calculations use the average of the initial mid price and the exit price to better approximate gradual selling or buying as price moves through the band.
✅ Rebalancing friction: Simulates both fixed and percentage-based costs (e.g., gas fees and slippage).
✅ Equity simulation: Tracks the portfolio value over time to help evaluate long-term profitability of narrow LP strategies.
✅ Dummy entries: Automatically generates dummy trades to populate the TradingView Strategy Report for easier visualization (these trades do not affect the simulated equity).

This script is designed for research purposes and should be adapted to specific protocols or fee models as needed.
此 Pine Script 策略模拟为 BTC 等波动性资产的窄幅价格区间 (LP) 提供流动性。

主要特点：
✅ 可自定义区间：定义中间价附近的百分比宽度（例如 ±3%）。
✅ 无常损失估算：当价格超出区间时，所有流动性实际上都会转换为一种资产（USDC 或 BTC）。
✅ 再平衡逻辑：每次价格超出区间时，仓位都会重新平衡，两种资产的配置比例为 50/50。
✅ 平均价格基准：再平衡计算使用初始中间价和退出价的平均值，以便更好地模拟价格在区间内波动时逐渐卖出或买入的情况。
✅ 再平衡摩擦：模拟固定成本和基于百分比的成本（例如 Gas 费和滑点）。
✅ 股票模拟：跟踪投资组合价值随时间的变化，以帮助评估窄幅 LP 策略的长期盈利能力。
✅ 虚拟入场：自动生成虚拟交易，填充 TradingView 策略报告，以便于可视化（这些交易不会影响模拟净值）。

此脚本仅供研究之用，应根据需要根据特定协议或费用模型进行调整。
