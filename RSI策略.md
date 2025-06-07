
## RSI策略教程

TPBOT 的 RSI 策略专为 Solana MEME 币市场设计，基于相对强弱指数（RSI）指标，通过 1 分钟或 5 分钟 K 线分析，当 RSI 值低于 30 时自动买入，结合用户自定义的止盈参数，帮助您精准捕捉 USDC/MEME 交易对的买卖点，实现科学化交易。本教程将指导您通过 Telegram 机器人（TPBOT）创建、配置和管理 RSI 策略，让您轻松成为"科学家"，在 MEME 币市场中实现高效收益！

**步骤 1：准备工作**

确保TP BOT钱包已创建：按照新手教程中的步骤，通过 TPBOT 创建您的 Solana 钱包。我们的平台采用 AES-256-GCM 加密、TLS1.3 协议和 HSM 硬件安全模块，确保私钥全生命周期安全，服务器永不触碰明文。

加入 Telegram 社区：搜索 TPBOT：`@Trade_Plus_Sol`
👉[点击这里进入](https://t.me/follow_step_bot?start=OFC25N6V)或
👉[点击这里获取支持](https://t.me/+yerC-XZv8sthN2Nl)

准备资金：确保您的 Solana 钱包中有足够的 USDC 用于交易和 SOL 用于支付 Gas 费用。建议新手从少量 USDC（如 10 USDC）开始测试。

**步骤 2：创建 RSI 策略**

进入 TPBOT：打开 Telegram，输入 `/start` 或点击"策略"按钮，进入策略选择界面。

选择 RSI 策略：

在策略菜单中选择"RSI 策略"（手续费 0.5%，Gas 费以 SOL 支付），适合基于 USDC/MEME 交易对的趋势交易。

配置策略参数：

交易对：输入代币地址（CA）

资金量：输入用于 RSI 策略的 USDC 金额（例如 20
USDC）。建议设置合理资金规模以分散风险。

K 线周期：选择 1 分钟或 5 分钟 K 线（1 分钟适合超短线交易，5 分钟适合稍长趋势）。

RSI 买入触发点：默认设置为 RSI < 30（可手动调整，例如 RSI < 25 以更严格筛选买入点）。

止盈参数：设置卖出时的盈利目标（例如 3% 或 5%），由用户自定义。

滑点和优先费：可选择默认参数或自行设置，TPBOT 默认启用滑点保护以降低交易成本。

Gas 费用：确保钱包中有足够 SOL 用于支付交易的 Gas 费用（由 Solana 网络自动收取）。

**步骤 3：运行与监控**

启动策略：返回策略主页，点击"策略运行"（绿色表示运行，红色表示未运行）。

消息推送：开启消息推送后，TPBOT 将实时通知每笔买入和卖出的价格、RSI 值及收益。

**步骤 4：进阶技巧与社区支持**

优化策略：根据 Telegram 社区讨论的 MEME 币热点，选择高波动 USDC/MEME 交易对以提高 RSI 策略效率。

参考 TPBOT 提供的 AI 驱动市场信号（即将推出，详见我们的发展路线），优化 RSI 参数设置。

尝试不同 K 线周期（1 分钟 vs. 5 分钟）以匹配市场节奏，1 分钟更适合快速波动，5 分钟更适合稳定趋势。

社区学习：👉[加入 Telegram 社区](https://t.me/+yerC-XZv8sthN2Nl)，参与RSI 策略分享和交易竞赛，学习其他"科学家"的经验。

**步骤 5：关闭策略**

如需关闭策略，可选择：

关闭策略并不清仓：暂停策略但保留持仓。

清仓：终止策略并卖出所有持仓。

**图文步骤：**

**步骤1：创建RSI策略 点击策略**

[//]: # (![]&#40;images/image39.png&#41;)
<img src="https://raw.githubusercontent.com/tpbot-admin/tpbot-admin.github.io/master/images/image39.png"  alt="image-16" style="width:800px;height:600px" />

选择RSI策略

[//]: # (![]&#40;images/image40.png&#41;)
<img src="https://raw.githubusercontent.com/tpbot-admin/tpbot-admin.github.io/master/images/image40.png"  alt="image-16" style="width:800px;height:600px" />

**步骤2：输入代币地址(CA） 新建策略**

[//]: # (![]&#40;images/image41.png&#41;)
<img src="https://raw.githubusercontent.com/tpbot-admin/tpbot-admin.github.io/master/images/image41.png"  alt="image-16" style="width:800px;height:600px" />

**步骤3：策略配置 选择RSI
K线周期，选择1分钟或者5分钟K线（1分钟适合超短线交易，5分钟适合稍长趋势）**

[//]: # (![]&#40;images/image42.png&#41;)
<img src="https://raw.githubusercontent.com/tpbot-admin/tpbot-admin.github.io/master/images/image42.png"  alt="image-16" style="width:800px;height:600px" />

**步骤4：设置单笔投入金额 如：20U**

[//]: # (![]&#40;images/image43.png&#41;)
<img src="https://raw.githubusercontent.com/tpbot-admin/tpbot-admin.github.io/master/images/image43.png"  alt="image-16" style="width:800px;height:600px" />

**步骤5：设置单笔止盈间隔 如6%**

[//]: # (![]&#40;images/image44.png&#41;)
<img src="https://raw.githubusercontent.com/tpbot-admin/tpbot-admin.github.io/master/images/image44.png"  alt="image-16" style="width:800px;height:600px" />

**步骤7：启动策略**

返回策略主页，点击"策略运行"（绿色表示运行，红色表示未运行）。

[//]: # (![]&#40;images/image45.png&#41;)
<img src="https://raw.githubusercontent.com/tpbot-admin/tpbot-admin.github.io/master/images/image45.png"  alt="image-16" style="width:800px;height:600px" />

