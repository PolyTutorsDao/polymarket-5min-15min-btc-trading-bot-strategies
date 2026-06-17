# Polymarket 5-Min & 15-Min BTC Trading Bot Strategies

**Repository:** [PolyTutorsDao/polymarket-5min-15min-btc-trading-bot-strategies](https://github.com/PolyTutorsDao/polymarket-5min-15min-btc-trading-bot-strategies)

### Related repositories

| Repository | Description |
|---|---|
| [polymarket-5min-15min-btc-trading-bot-strategies](https://github.com/PolyTutorsDao/polymarket-5min-15min-btc-trading-bot-strategies) | **This repo** — strategy playbook for 5-minute and 15-minute BTC binary markets |
| [polymarket-15min-btc-trading-tools](https://github.com/PolyTutorsDao/polymarket-15min-btc-trading-tools) | Real-time terminal dashboard for 15-minute BTC Up/Down markets |
| [polymarket-trading-bot-crypto](https://github.com/PolyTutorsDao/polymarket-trading-bot-crypto) | Rust automation bot for 1-hour crypto Up/Down markets (BTC, ETH, SOL, XRP) |

**My Polymarket accounts:** [@coal234](https://polymarket.com/@coal234?tab=activity) · [@spiralgalaxy](https://polymarket.com/@spiralgalaxy?tab=activity)  
**我的 Polymarket 账户：** [@coal234](https://polymarket.com/@coal234?tab=activity) · [@spiralgalaxy](https://polymarket.com/@spiralgalaxy?tab=activity)

Polymarket Trading Bot & Arbitrage Bot — Trading Strategy Playbook  
Polymarket 机器人 — 交易策略手册 | Polymarket 交易机器人 & 套利机器人

<img width="1398" height="829" alt="image (3) (1)" src="https://github.com/user-attachments/assets/839d38ce-9e50-41ce-a8e7-8427a30b6470" />
<img width="1454" height="910" alt="Screenshot_2" src="https://github.com/user-attachments/assets/3c437b6a-9fd7-4e8b-af07-dd0d7c56a054" />

https://github.com/user-attachments/assets/57f70e56-7eb8-43c5-b0b8-b80e2739051b

https://github.com/user-attachments/assets/3cd89cf8-e96c-42b1-81c6-dba88cfe3e98

https://github.com/user-attachments/assets/4d0ad4aa-a5cd-4936-89d3-1892f62b6e5f

https://github.com/user-attachments/assets/af853a73-a5c5-4a8f-a8a7-15aa7b578fe0

https://github.com/user-attachments/assets/a42370dc-753d-4f4a-b2ee-e5baf750b1fb

https://github.com/user-attachments/assets/4dc4e9ef-1522-4e70-97fd-b6e3063a8d39

https://github.com/user-attachments/assets/816f497d-3954-400d-953d-b55c05f571cb

> **What is this?** A complete open-source **Polymarket bot** strategy playbook covering automated **Polymarket trading bot** and **Polymarket arbitrage bot** techniques for BTC, ETH, SOL, and XRP binary prediction markets.  
> Ready-to-deploy Python bots and documented signal logic for 5-minute, 15-minute, and 1-hour Polymarket markets.
>
> **这是什么？** 一份完整的开源 **Polymarket 机器人**策略手册，涵盖 BTC、ETH、SOL、XRP 二元预测市场的 **Polymarket 交易机器人**与 **Polymarket 套利机器人**技术，含 5 分钟、15 分钟及 1 小时市场的可部署 Python 机器人与信号逻辑。
>
> **Scope:** Strategies for Polymarket 5-minute Up/Down binary markets (BTC, ETH, SOL, XRP and correlated events).  
> All payoffs are binary: the winning side settles at **$1.00**, the losing side at **$0.00**.  
> Prices are expressed in US cents (¢) or dollars ($0.xx)
>
> **范围：** 针对 Polymarket 5 分钟二元涨跌市场（BTC、ETH、SOL、XRP 及相关事件）的交易策略。  
> 所有收益为二元结构：胜方结算价 **$1.00**，负方结算价 **$0.00**。价格以美分（¢）或美元（$0.xx）表示。

---

## 🤖 Polymarket Trading Bot & Arbitrage Bot — Available Now · 现已开放购买

I have built and am offering **two production-ready Polymarket trading bots** for crypto prediction markets (BTC, ETH, SOL, XRP — 5-minute, 15-minute, and 1-hour markets).  
Each bot is a fully automated **Polymarket bot** that connects to the Polymarket CLOB API, monitors live order books, and executes trades without manual intervention.  
The **Cross-Market** variant functions as a **Polymarket arbitrage bot**, exploiting lead-lag mispricings across BTC, ETH, SOL, and XRP simultaneously.

| Bot | Type | Description | 描述 |
|-----|------|-------------|------|
| **Momentum Bot** | Polymarket trading bot | Captures directional price momentum using multi-indicator signals (MACD, RSI, VWAP) to enter high-probability trending moves. | 基于多指标动量信号（MACD / RSI / VWAP）捕捉方向性行情，自动高概率入场。 |
| **Revert Bot** | Polymarket trading bot | Identifies overextended price dislocations and trades mean-reversion back to fair value — profits from market overreactions. | 识别价格严重偏离公允值的时机，自动交易均值回归，从市场过度反应中获利。 |
| **Cross-Market Bot** | Polymarket arbitrage bot | Routes lead-lag signals across BTC, ETH, SOL, and XRP markets to capture spread and arbitrage-style returns. | 跨资产套利机器人，利用 BTC / ETH / SOL / XRP 市场间的领先-滞后信号捕捉价差与类套利收益。 |

All bots support **5-minute, 15-minute, and 1-hour** Polymarket binary markets.

> **Interested? Contact me directly on Telegram:**  
> **👉 [@zostaffsmartx](https://t.me/zostaffsmartx)**

> **感兴趣？请直接通过 Telegram 联系我：**  
> **👉 [@zostaffsmartx](https://t.me/zostaffsmartx)**

---

## Table of Contents · 目录

| # | Strategy (EN) | 策略（中文） |
|---|--------------|-------------|
| 1 | [1¢ Buy — Ultra-Cheap Dislocation](#1-1¢-buy--ultra-cheap-dislocation) | 1 美分买入 — 极低价失衡捕捉 |
| 2 | [99¢ Sniper — Near-Resolution Strike](#2-99¢-sniper--near-resolution-strike) | 99 美分狙击 — 临近结算狙击 |
| 3 | [Low-Side Dual Reversion](#3-low-side-dual-reversion) | 弱势双边均值回归 |
| 4 | [Pre-Order Market — Queue Positioning](#4-pre-order-market--queue-positioning) | 预挂单 / 盘前布局 |
| 5 | [Cross-Market Bot — Spread & Hedge](#5-cross-market-bot--spread--hedge) | 跨市场机器人 |
| 6 | [Martingale & Anti-Martingale @ ~45¢](#6-martingale--anti-martingale--45¢) | 约 45¢ 马丁 / 反马丁 |
| 7 | [Fibonacci Strategy Bot](#7-fibonacci-strategy-bot) | 斐波那契策略机器人 |
| 8 | [Binary Momentum — MACD / RSI / VWAP](#8-binary-momentum--macd--rsi--vwap) | 二元动量（MACD / RSI / VWAP）|
| 9 | [Dump-Hedge — Sharp Move Arbitrage](#9-dump-hedge--sharp-move-arbitrage) | 急跌对冲 |

---

## About This Polymarket Bot Repository · 关于本 Polymarket 机器人仓库

**[polymarket-5min-15min-btc-trading-bot-strategies](https://github.com/PolyTutorsDao/polymarket-5min-15min-btc-trading-bot-strategies)** documents the algorithmic strategies behind a **Polymarket bot** designed for 5-minute and 15-minute BTC binary prediction markets.  
Whether you are building a **Polymarket trading bot** from scratch or extending an existing **Polymarket arbitrage bot**, the strategies here cover every major edge type: tail-price dislocations, mean reversion, momentum signals, cross-market arbitrage, and reactive hedging.

**Key features of the Polymarket bot strategies documented here:**
- Automated entry/exit logic compatible with the Polymarket CLOB API
- Signal generation using MACD, RSI, VWAP on binary token prices (5-second bars)
- Cross-asset arbitrage (BTC → ETH/SOL/XRP lead-lag) for a true Polymarket arbitrage bot workflow
- Martingale, anti-martingale, and Fibonacci sizing frameworks
- Regime filtering to prevent martingale use in trending markets

本仓库 **[polymarket-5min-15min-btc-trading-bot-strategies](https://github.com/PolyTutorsDao/polymarket-5min-15min-btc-trading-bot-strategies)** 记录了一个 **Polymarket 机器人**的算法策略，适用于 5 分钟与 15 分钟 BTC 二元预测市场。无论你是从零构建 **Polymarket 交易机器人**还是扩展现有的 **Polymarket 套利机器人**，这里涵盖了所有主要优势类型：尾部错价、均值回归、动量信号、跨市场套利及反应性对冲。

---

## Why Prediction Markets Offer Edge · 为什么预测市场存在可交易优势

Before diving into individual strategies, it helps to understand **where the edge comes from** in Polymarket 5-minute binary markets:

- **Thin books, stale quotes.** Market-makers often leave resting limit orders at prices they set minutes ago. Sharp moves in the underlying (BTC spot price) can render those quotes stale before they are cancelled, creating brief mispricings.
- **Binary terminal payoff.** Every contract pays exactly $0 or $1. A side trading at 2¢ needs only a ~2% probability of winning to be fair value. Markets routinely over- or under-price tails.
- **Short duration creates urgency.** With only 300 seconds per market, information decays fast and human reaction time becomes a measurable disadvantage — systematic bots can act in milliseconds.
- **Correlated underlyings.** BTC, ETH, SOL, and XRP often move together. Cross-market signals can predict a 5-minute outcome in one market before price has propagated to the other.

预测市场的优势来源：
- **盘口薄、报价滞后：** 做市商的挂单往往在现货价格急动后数秒内仍维持旧价，造成短暂错价。
- **二元终值：** 每张合约仅有 $0 或 $1 两种结果，尾部定价失当极为常见。
- **极短周期制造时间压力：** 5 分钟窗口内信息快速衰减，系统化机器人具有毫秒级反应优势。
- **资产联动：** BTC、ETH、SOL、XRP 走势相关，跨市信号可提前预判单一市场结果。

---

## Strategy Detail · 策略详解

---

### 1. 1¢ Buy — Ultra-Cheap Dislocation
### 1 美分买入 — 极低价失衡捕捉

> **One-line idea:** Pay 1–3¢ for lottery tickets on both sides; collect on reversals or volatility spikes.  
> **核心思路：** 以 1–3 美分在双边各买入"彩票仓"；在价格反转或波动放大时收割。

#### The Edge Case · 优势来源

A side trading at **1¢** implies the market believes that outcome has roughly a 1% probability of occurring in the next few minutes. However, in a 5-minute window driven by a volatile spot asset like BTC, **tail events are systematically underpriced**. Any 30-second candle that crosses the strike price in the final minute can flip the entire outcome — something the order book cannot price accurately in real time.

The strategy monetises three scenarios:

| Scenario | How it profits |
|----------|----------------|
| **Full reversal** | The side you bought at 1¢ wins outright and pays $1 — a 99× return. |
| **Mid-flight repricing** | The side climbs to 10–15¢ before expiry; you take profit at 10–15× your entry. |
| **Volatility spike** | Both sides momentarily reprice upward as the market becomes "live" again; sell both for a combined gain. |

#### Execution Detail · 执行细节

- **Entry:** Place resting limit bids at **1¢, 2¢, and 3¢** on **both** Up and Down simultaneously, once per market after a configurable delay (e.g. 30–60 s after open, giving the market time to find initial direction).
- **Sizing:** Small fixed notional per order (e.g. 5–20 shares). Because you are on **both** sides, one will almost certainly expire worthless — budget for that.
- **Take-profit tiers:** Partial sells as price climbs — e.g. sell 50% at 10¢, sell remainder at 15¢. This locks in multiples without needing the market to fully reverse.
- **Cancel unfilled:** In the last 30 s of the market, cancel any **unfilled** orders. Stale orders risk filling at bad times and expiring worthless without any chance to manage.
- **Kill switch:** Set a hard per-market notional cap. Because 1¢ orders can accumulate across many markets quickly, position concentration risk is real.

#### Risk · 风险

The dominant risk is **expected loss on the unfilled or losing side**. Over a large sample, only a fraction of 1¢ buys will ever fill *and* win. The strategy requires enough volume and market diversity to let the rare winners pay for the many losers. **Do not size up into losing streaks** — the edge is statistical, not deterministic.

---

### 2. 99¢ Sniper — Near-Resolution Strike
### 99 美分狙击 — 临近结算狙击

> **One-line idea:** Buy a side at 99¢ when the outcome is effectively decided but asks remain available; risk is a sudden flip.  
> **核心思路：** 在结果高度确定但卖单仍存时以 99¢ 买入；主要风险是意外反转。

#### The Edge Case · 优势来源

When BTC has drifted far from the strike with little time remaining, the winning side often still trades at 97–99¢ rather than jumping immediately to $1. This gap exists because:

1. **Liquidity providers fear last-second moves** and charge a spread even when the outcome seems certain.
2. **Automated fills are slow.** Settlement is not instantaneous — there is a window during which a 99¢ ask can be lifted for a near-risk-free 1¢ gain.

A 99¢ buy that settles at $1 earns **1¢ per share**. On 1,000 shares that is $10 — modest, but the trade can be executed in seconds with near-zero holding time.

#### Execution Detail · 执行细节

- **Entry conditions:**
  - Time remaining ≤ 60 s (the narrower, the safer).
  - Underlying is clearly on one side of the strike (e.g. BTC spot is $200 above the strike with 45 s left).
  - Ask price for the winning side is **≤ 99¢** (i.e. a fill is available below par).
- **Order type:** Market or aggressive limit (price the order at par or slightly below to ensure fill). Speed matters more than price at this stage.
- **Hold to settlement:** Because there is no time to actively manage, the plan is simply to hold to expiry and collect $1 per winning share.
- **Position sizing:** Can be larger than other strategies because the per-trade risk is low **when entry conditions are met strictly**. However, never bet your full account — slippage on a market order can push effective entry above 99¢ and eliminate the edge.

#### Tail Risk · 尾部风险

The catastrophic scenario: you enter at 99¢ with 30 s left, and BTC prints a 1% candle that crosses the strike **at the bell**. The winning side collapses to 0¢ and you lose 99¢ per share. This is rare but not negligible in volatile markets — hence the rule to trade only with **strict time and price conditions**, never mechanically.

---

### 3. Low-Side Dual Reversion
### 弱势双边均值回归

> **One-line idea:** When both sides are compressed below fair value (~35–45¢), bet on mean reversion to 50¢ or a late volatility burst — on both sides simultaneously.  
> **核心思路：** 双侧价格均受压至 35–45¢ 时，押注价格回归 50¢ 附近或尾盘波动放大，双边同时建仓。

#### The Edge Case · 优势来源

In a fair binary market with no information, both Up and Down should trade near **50¢** — together they must sum to $1. When both sides are trading at **35–45¢** simultaneously, the book is either:

- **Illiquid and wide:** Nobody is arbing the gap, so you can buy both at a discount.
- **Event-anticipating:** Participants expect a sharp move and nobody wants to be caught on either side — the temporary compression is itself tradeable.

Buying both at 40¢ costs **80¢** for a guaranteed $1 terminal payoff — a **locked 20¢ edge** *provided both orders fill*. The challenge is that one side may fill and the other may not before prices snap back.

#### Execution Detail · 执行细节

- **Setup:** Simultaneously post limit bids on **both** Up and Down, targeting total combined cost < $1 (e.g. 44¢ + 44¢ = 88¢ for a guaranteed $0.12 edge if both fill).
- **Fill management:** Track each side independently. If only one side fills and the other side's ask rises above breakeven, cancel the unfilled order and manage the single position (hold, take profit, or sell at market).
- **Reversion capture:** Even without full fill, a side bought at 40¢ that reprices to 50¢ generates a **25% return in minutes** — take partial profit at the midpoint.
- **Regime filter:** Only enter when both sides are truly compressed (e.g. max(Up ask, Down ask) ≤ 48¢). Avoid the strategy when one side is clearly dominant (e.g. 70¢ / 30¢ split).
- **Time gate:** Best applied early in the market window (first 60–120 s), when the midpoint has not yet been discovered. Avoid entering in the last 60 s where asymmetric fills become a larger problem.

#### Paired Risk Control · 配对风控

The "dual" in the name means **both legs are treated as a single trade**. If one leg fills at a bad price, the entire trade is re-evaluated — not just the unfilled leg. Notional exposure is measured as the sum of both sides, not each individually.

---

### 4. Pre-Order Market — Queue Positioning
### 预挂单 / 盘前布局

> **One-line idea:** Place limit orders on the *next* market window **before** it opens to capture the first liquidity when the new period starts.  
> **核心思路：** 在下一个窗口 **开市前** 预先挂出限价单，率先占据新市场的流动性优先级。

#### The Edge Case · 优势来源

Each 5-minute market is created fresh at UTC period boundaries. In the first 10–30 seconds of a new market, **the order book is empty** and whoever has a resting order already placed has **zero competition** for fills. Early fills consistently get better prices than participants who enter after the market has started finding equilibrium.

Pre-ordering is essentially **queue sniping at market creation** — analogous to placing a limit order on a new equity IPO before the open auction clears.

#### Execution Detail · 执行细节

- **Timing:** In the last 1–2 minutes of the **current** market, identify the slug of the **next** period and place limit bids on both Up and Down at your target price (e.g. 45¢ each).
- **Signal gate:** Only pre-order when the **current** market is "stable" — both sides trading between 35–65¢. If the current market is already heavily one-sided (e.g. 90¢ / 10¢), the next market may open in continuation mode, and a 45¢ pre-order on the losing side will be immediately adversely selected.
- **Post-fill management:**
  - If **both** sides fill below 50¢ combined, you have a locked arbitrage. When one side's price climbs to 90¢+, sell the **losing** side at whatever you can get (even 2–5¢ clears your cost basis) and hold the winner to $1.
  - If **only one side** fills, you have a naked directional bet. Manage it like any single-side position: hold if trending your way, cut if it moves against you through your danger threshold.
- **Mid-market variant:** A more aggressive version places orders in the **current** market (not just the next) when the same stable signal is met and sufficient time remains — essentially treating the current market as a dual-entry opportunity while simultaneously pre-ordering the next.

#### Why the Signal Filter Matters · 为什么信号过滤至关重要

Pre-ordering without a signal filter is dangerous because the order book for a future period is empty — your limit order will be the **best available price** and will be immediately filled by anyone who disagrees with you. The signal filter reduces adverse selection by only placing when the current market is balanced, indicating no strong directional bias entering the new window.

---

### 5. Cross-Market Bot — Spread, Hedge & Arbitrage (Polymarket Arbitrage Bot)
### 跨市场机器人 — 价差、对冲与套利（Polymarket 套利机器人）

> **One-line idea:** Link two or more related markets — same asset different horizons, or correlated assets — to extract spread, hedge, or arbitrage-style returns. This is the core **Polymarket arbitrage bot** strategy.  
> **核心思路：** 联动多个相关市场（同资产不同周期、或价格相关资产），做价差、对冲或类套利。这是核心的 **Polymarket 套利机器人**策略。

#### The Edge Case · 优势来源

Polymarket runs **simultaneous** 5-minute markets for BTC, ETH, SOL, and XRP. These assets are highly correlated on short timeframes. When BTC makes a sharp move up, ETH, SOL, and XRP typically follow within seconds. The cross-market bot monitors all four simultaneously and **routes signals from the faster-moving asset to trade the lagging asset's market** before prices adjust.

Additionally, for the same asset, markets at different strikes or different period starts can create **calendar spread** or **strike spread** opportunities when their implied probabilities drift out of sync.

#### Strategy Variants · 策略变体

**A — Correlation Signal (Lead-Lag)**  
Monitor BTC spot price movement. When BTC crosses its own strike cleanly, place aggressive orders on ETH or SOL in the same direction before those markets reprice. The lag between BTC leading and altcoins following is typically 5–30 seconds — enough to enter and profit.

**B — Paired Hedge**  
Hold simultaneous positions in two correlated markets with opposite risk profiles. Example: Long Up in BTC-5m (current period), Short (via Down buy) in ETH-5m (current period). If the two markets move together, the positions cancel; you profit from the **spread compression** rather than directional movement.

**C — Calendar Spread**  
Buy the current BTC-5m Down side at 40¢, simultaneously sell (buy the other leg of) the next-period BTC-5m Down at 52¢. You are long the current period's underpriced side and short the next period's overpriced side — a time-spread bet on mean reversion in implied probability.

#### Risk · 风险

Cross-market strategies carry **correlation breakdown risk**. When assets decorrelate (e.g. SOL flash crashes independently of BTC), the hedge leg fails and both positions lose simultaneously. Always model the **worst-case scenario as zero correlation** when sizing.

---

### 6. Martingale & Anti-Martingale @ ~45¢
### 约 45¢ 马丁 / 反马丁

> **One-line idea:** Around mid-prices (~45¢), either progressively add on adverse moves (martingale) or pyramid into strength and cut weakness (anti-martingale). Both require regime gating.  
> **核心思路：** 在中段价位（约 45¢）附近，亏损加仓（马丁）或顺势加码、逆势减仓（反马丁），须严格控制行情过滤与仓位上限。

#### Why ~45¢ Is the Arena · 为什么是约 45¢

At mid-prices, a binary market is essentially saying "50/50 — we don't know." This is where the **highest uncertainty** and therefore the most mean-reversion potential exists. Prices around 45¢ are also far enough from terminal values that there is room for multiple waves of price movement before expiry.

#### Martingale Variant · 马丁格尔变体

**Logic:** Buy at 45¢, if price drops to 38¢, buy more. If it drops to 30¢, buy again. Average down your cost basis with the expectation that price reverts above your average before expiry.

**Why it can work:** In a 5-minute binary, a side at 30¢ still has ~30% implied win probability. If the underlying hasn't made a decisive move, that probability may be understated — the market overreacted.

**Why it can blow up:** In a trending market (BTC making a sustained directional move), a 30¢ side can go to 5¢ and then 0¢ in seconds. Martingale on a binary during a strong trend is catastrophic. **Regime filtering is non-negotiable** — only apply martingale when the market is in a confirmed range/chop regime, not a trend.

**Hard rules for martingale:**
- Maximum 3 add-on levels.
- Total notional cap per market (e.g. no more than 5% of account).
- **Auto-liquidate** if the position drops below a hard stop (e.g. 15¢ sell price on average cost of 38¢).

#### Anti-Martingale Variant · 反马丁格尔变体

**Logic:** Buy at 45¢, if price moves to 52¢, add more (you are right, press the winner). If price drops from 45¢ to 38¢, cut the position (you are wrong, cut losses). This is the classic **trend-following / pyramiding** approach applied to binary mid-prices.

**Why it can work:** Winners tend to keep winning in short-duration markets where information is confirmed quickly. If a side moves from 45¢ to 52¢, that reflects real information — a market consensus is forming, and adding into that consensus has positive expected value in the continuation.

**Position management:**
- Add 50% of initial size when price confirms direction by ≥5¢.
- Add again when confirmed by another 5¢ move.
- Trail stop: if price ever retraces more than half the gain from entry, sell the adds but keep the original position.

---

### 7. Fibonacci Strategy Bot
### 斐波那契策略机器人

> **One-line idea:** Use Fibonacci retracement and extension levels — anchored to the swing high/low of a price window — to determine staged entry prices and take-profit targets.  
> **核心思路：** 以价格波段高低点为锚，计算斐波那契回撤与扩展位，分批建仓并设定止盈目标。

#### Applying Fibonacci to Binary Markets · 将斐波那契应用于二元市场

In traditional markets, Fibonacci levels (23.6%, 38.2%, 50%, 61.8%, 78.6%) are used to identify likely support/resistance during a retracement from a swing move. In a 5-minute binary market, **the "price" being analyzed is the Up/Down token price** (0 to $1), not the underlying BTC price.

**Swing anchor setup:**
1. Identify the high and low of the current binary token price over the first 60–90 seconds of the market.
2. Calculate Fibonacci retracement levels from that swing.
3. Place staged limit buy orders at the key retracement levels.

**Example:**
- Up token opens at 55¢, drops to 42¢ in the first 90 seconds.
- Swing: High = 55¢, Low = 42¢, Range = 13¢.
- Fibonacci retracements of the drop: 23.6% = 45¢, 38.2% = 47¢, 61.8% = 50¢.
- Place bids at 45¢, 47¢, and 50¢ with increasing size (or equal size, depending on confidence).

#### Extension Levels for Take-Profit · 扩展位作为止盈目标

Fibonacci extensions (127.2%, 161.8%, 200%) of the initial swing project likely **upside targets** if the retracement holds and the trend resumes.

- Extension 127.2%: 55 + 0.272 × 13 = **58.5¢** → partial take-profit.
- Extension 161.8%: 55 + 0.618 × 13 = **63¢** → full exit or trailing stop.

#### Binary Payoff Asymmetry · 二元收益不对称性

Unlike traditional assets, the maximum payoff is capped at $1 and minimum is $0. This means Fibonacci extension levels above $1 are irrelevant — any position running above 90¢ transitions into 99¢ Sniper mode (see Strategy 2). Treat $0.90–$0.99 as the effective "extension target" range regardless of what the Fibonacci math suggests.

---

### 8. Binary Momentum — MACD / RSI / VWAP
### 二元动量（MACD / RSI / VWAP）

> **One-line idea:** Stack three indicators — MACD for trend impulse, RSI for stretch/mean-revert filter, VWAP for intraday fair value — on the binary token price to generate high-conviction directional signals.  
> **核心思路：** 在二元代币价格上叠加 MACD（趋势动能）、RSI（过热/回调过滤）、VWAP（日内公允价值）三层指标，生成高置信度方向信号。

#### Indicator Roles · 各指标职能

**MACD — Trend Impulse (趋势动能)**  
Applied to the rolling binary token price (e.g. 5-second bars for a 5-minute market), MACD captures **momentum shifts**. A bullish MACD crossover on the Up token signals accelerating upward price pressure — the market is starting to "agree" that Up will win. A bearish crossover signals the opposite.

- Parameters: Fast EMA 3-bar, Slow EMA 8-bar, Signal 3-bar (adjusted for short timeframe).
- Signal: Enter Up when MACD line crosses above signal line and histogram turns positive.

**RSI — Stretch & Mean-Revert Filter (超买/超卖过滤)**  
RSI on 5-second bars measures whether the binary token price has moved too far too fast. In a binary market, an RSI above 75 on a 5-minute window often means the price is **overstretched and due for a pause or pullback** — a warning not to chase momentum. RSI below 30 flags potential mean-reversion entries.

- Use RSI as a **filter**, not as a primary signal. Only enter MACD momentum trades when RSI is in the 40–65 range (confirming momentum without being overbought).
- Use RSI extremes (< 25 or > 75) as **exit signals** — take profit or tighten stops.

**VWAP — Intraday Fair Value (日内公允价值)**  
VWAP of the binary token price within the 5-minute window provides a **volume-weighted fair value anchor**. Price above VWAP = buying pressure, below VWAP = selling pressure.

- Enter longs when token price is above VWAP and MACD confirms.
- Avoid new entries when price is extended more than 8–10¢ from VWAP (stretch risk).
- VWAP reversion: If price pulls back to VWAP during an established trend, it is a **reload opportunity** rather than a danger sign.

#### Multi-Indicator Confluence Scoring · 多指标共振评分

Rather than requiring all three signals simultaneously (which is too rare), score them:

| Signal | Score |
|--------|-------|
| MACD bullish crossover | +2 |
| RSI 40–65 (neutral zone) | +1 |
| Price above VWAP | +1 |
| MACD histogram increasing | +1 |

**Enter** when score ≥ 4. **Exit or reduce** when score drops below 2. This allows graduated position sizing rather than binary on/off.

---

### 9. Dump-Hedge — Sharp Move Arbitrage
### 急跌对冲 — 急跌后结构性套利

> **One-line idea:** When a sharp underlying move sends one side to near-zero, leg into the fallen side first; then hedge the other side when the combined pair cost clears your edge threshold.  
> **核心思路：** 识别急跌，先买入低价侧，再在组合成本达标时对冲另一侧，形成结构性锁利。

#### The Edge Case · 优势来源

A sudden BTC dump sends the Up token from 55¢ to **8¢** in ten seconds. The market is now pricing an 8% probability for Up. At the same time, Down has repriced from 45¢ to **88¢**. The book has moved violently and, critically, **not all stale quotes have been pulled yet**.

This creates a window (often 5–15 seconds) where you can:
1. Buy the collapsed **Up** token at 8–12¢ (ultra-cheap, leveraged on a potential reversal).
2. Buy the elevated **Down** token at a still-reasonable 85–88¢.

Combined cost: 10¢ + 86¢ = **96¢** for a guaranteed $1 payout = **4¢ locked edge** if both fill.

If only the Up leg fills at 10¢, you have a high-variance lottery ticket. If BTC reverses, that 10¢ position could run to 50¢ or beyond — a 5× in seconds.

#### Execution Detail · 执行细节

**Phase 1 — Dump Detection:**
- Monitor the underlying spot price (BTC, ETH, etc.) in real time via WebSocket.
- Trigger condition: Price drops ≥ X% in ≤ Y seconds (e.g. 0.3% in 10 s) AND Up token price drops below threshold (e.g. 20¢).

**Phase 2 — First Leg (Fallen Side):**
- Place a market or aggressive limit buy on the collapsed Up token immediately.
- Target entry: ≤ 15¢. Above 20¢, the expected value drops sharply.
- Size: Moderate — this leg has high variance if not paired.

**Phase 3 — Hedge Assessment:**
- After the first fill, calculate **combined cost** = Up fill price + Down current ask.
- If combined cost < 98¢ (giving at least 2¢ edge after fees), place the Down hedge immediately.
- If Down has already repriced to 99¢+, skip the hedge — you are now running the Up leg naked as a reversal play.

**Phase 4 — Position Resolution:**
- **Fully hedged (both filled under $1):** Hold both to expiry, collect $1, profit = $1 minus combined cost. No further action needed.
- **Single leg (Up only):** Apply take-profit tiers (e.g. sell 50% at 25¢, sell remainder at 40¢). If underlying continues to dump and Up goes below 5¢, cut losses at market.

#### Relationship to Other Strategies · 与其他策略的关联

Dump-Hedge is a **reactive** strategy — it waits for an event rather than placing orders in advance. It is the highest-adrenaline strategy in this playbook but also one of the highest positive-EV trades **when conditions are met** because it exploits the mechanical lag between spot price movement and book repricing in the binary market.

---

## Risk Management Summary · 风险管理总览

All strategies in this playbook share a common risk framework:

| Risk Control | Description |
|-------------|-------------|
| **Per-market notional cap** | Never exceed a fixed dollar amount (e.g. $50) on any single 5-minute market regardless of signal strength. |
| **Account drawdown kill switch** | If total unrealised + realised loss in a session exceeds X% of the session budget, halt all new entries. |
| **Adverse selection monitor** | Track fill rate by strategy. If a strategy fills only in losing conditions, pause and review. |
| **Cancel-unfilled discipline** | Any order with less than 20–30 s to expiry and no realistic fill path should be cancelled — stale orders are liabilities. |
| **Correlation breakdown buffer** | For cross-market strategies, always model the worst case as full decorrelation, not historical correlation. |
| **No martingale without regime gate** | Martingale-style adds are only permitted in confirmed range/chop conditions — never in trending markets. |

---

## Strategy Comparison Matrix · 策略对比矩阵

| Strategy | Direction | Edge Type | Variance | Complexity | Best Market Condition |
|----------|-----------|-----------|----------|------------|----------------------|
| 1¢ Buy | Both | Tail payoff | Very High | Low | Volatile, rangebound |
| 99¢ Sniper | One | Near-arb | Low | Low | Near expiry, clear winner |
| Dual Reversion | Both | Mean-revert | Medium | Medium | Both sides compressed |
| Pre-Order | Both | Queue priority | Medium | Medium | Stable current period |
| Cross-Market | Both | Lead-lag | Medium | High | High inter-asset correlation |
| Martingale ~45¢ | One | Mean-revert | Very High | High | Confirmed chop regime |
| Anti-Martingale ~45¢ | One | Momentum | Medium | High | Confirmed trend |
| Fibonacci | One | Level-based | Medium | Medium | Clear swing structure |
| MACD/RSI/VWAP | One | Multi-indicator | Medium | High | Moderate volatility |
| Dump-Hedge | Both | Reactive arb | High | High | Sharp spot move |

---

## Glossary · 术语表

| Term | Definition |
|------|-----------|
| **Binary market** | A market with exactly two outcomes; winner pays $1, loser pays $0. |
| **Up / Down token** | The two sides of a Polymarket 5-minute market. Up wins if spot price is above strike at expiry; Down wins otherwise. |
| **Strike** | The price level the underlying must be above or below for Up to win. |
| **CLOB** | Central Limit Order Book — Polymarket's order matching system. |
| **Take-profit tier** | A pre-set price level at which a portion of the position is sold to lock in gains. |
| **Adverse selection** | Being filled primarily when the counterparty has better information — a common hazard for resting limit orders. |
| **Regime** | The current market condition: trending (directional momentum) vs. ranging (oscillating around a midpoint). |
| **Notional cap** | Maximum total money at risk in a given market, strategy, or session. |
| **Kelly criterion** | A formula for optimal bet sizing based on edge and variance; most practical implementations use a fractional Kelly (e.g. 25%) to limit variance. |

---

## Disclaimer · 免责声明

> Trading prediction markets involves significant financial risk. All strategies described here are for **educational and research purposes only**. Past performance of any strategy does not guarantee future results. Prediction markets can move to 0 or 1 instantly and without warning. Never trade with capital you cannot afford to lose. Always test with simulation mode before deploying any live capital.
>
> 本文档中描述的所有策略仅供 **教育与研究目的**。预测市场交易存在重大财务风险，任何策略的历史表现均不代表未来收益。市场价格可能瞬间归零或涨至 1 美元。请勿使用无法承受损失的资金进行交易，上线前务必先在模拟模式下充分测试。

---

---

## Recommend VPS
> https://tradingvps.io/

---

## Tags · 关键词

`polymarket-5min-15min-btc-trading-bot-strategies` · `polymarket bot` · `polymarket trading bot` · `polymarket arbitrage bot` · `polymarket python bot` · `polymarket automated trading` · `polymarket 5min bot` · `polymarket 15min bot` · `polymarket BTC bot` · `polymarket ETH bot` · `polymarket prediction market bot` · `polymarket CLOB bot` · `crypto prediction market bot` · `binary market trading bot` · `polymarket momentum bot` · `polymarket mean reversion bot` · `polymarket cross-market arbitrage` · `polymarket MACD RSI VWAP bot` · `polymarket strategy` · `polymarket algo trading` · `polymarket ETH bot` · `polymarket prediction market bot` · `polymarket CLOB bot` · `crypto prediction market bot` · `binary market trading bot` · `polymarket momentum bot` · `polymarket mean reversion bot` · `polymarket cross-market arbitrage` · `polymarket MACD RSI VWAP bot` · `polymarket strategy` · `polymarket algo trading`
