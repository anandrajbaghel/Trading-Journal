<div align="center">

# 📈 Trading Journal 📊

A comprehensive web application designed to empower traders through meticulous tracking and insightful analysis of their trading activity.

</div>

<br>

<div align="center">
<img width="960" alt="{E32B815D-DA26-470A-926E-E3ECEF2CC30F}" src="https://github.com/user-attachments/assets/1211104c-7499-4ecd-b908-f1c5758c067b" />
</div>

<br>

## ✨ Key Features

*   **📝 Multiple Entries Per Day:** Record all your trades, regardless of volume, within the same day.
*   **📊 Interactive Data Visualization:**
    *   📈 **Profit/Loss (P/L) Graphs:** Visualize daily and cumulative P/L trends.
    *   ⏱️ **Customizable Time Ranges:** Analyze performance over 7, 15, 30, 60 days; 3 and 6 months; 1 year; and all-time.
    *   🥧 **Win/Loss Pie Charts:**  Understand your win/loss ratio and value distribution at a glance.
*   **⚙️ Efficient Trade Management:**
    *   ✅ **Detailed Trade Capture:** Record comprehensive trade information (see "Trade Entry Fields" below).
    *   🗑️ **Flexible Data Management:** Delete specific trades easily.
    *   💾 **JSON Data Export/Import:** Securely back up or restore your trading data.
*   **📅 Date Navigation:** Quickly jump to any trade day in your journal history.
*   **💡 Inspirational Quotes:** Start each day with motivational quotes for discipline and focus.

<br>

## 🚀 Getting Started

1.  🚀 Launch the App
2.  ✍️ Start adding your trades after each trading session.
3.  🔍 Use the filters and date navigation for performance analysis.

<br>

## 📝 Trade Entry Fields

The following comprehensive fields are available for recording detailed information about each trade:

*   **📊 Setup Information:**
    *   `setupType`: Trading setup type (e.g., Breakout, Reversal).
    *   `entryReason`: Rationale for entering the trade.
    *   `entryPrice`: Entry price of the asset.
    *   `slPrice`: Stop-loss price.
    *   `targetPrice`: Target profit price.
    *   `riskToReward`:  Calculated risk-to-reward ratio.
    *   `positionSize`:  Position size based on your trading strategy.
    *   `confidenceLevel`:  Confidence in the trade setup (scale of 1-10).
    *   `emotionalState`: Your emotional state at the time of entry (e.g., Calm, Excited).
    *   `leverage`:  Leverage used in the trade.
*   **📈 Trade Details:**
    *   `tradeId`: Unique identifier for each trade.
    *   `date`: Trade entry date.
    *   `time`: Trade entry time.
    *   `market`:  Market traded (e.g., Stocks, Forex, Crypto).
    *   `marketCondition`: Market conditions during the trade.
    *   `asset`: Specific asset traded (e.g., AAPL, EUR/USD, BTC).
    *   `direction`: Long or Short.
    *   `fees`: Any fees associated with the trade.
*   **🚪 Exit Information:**
    *   `exitDate`: Trade exit date.
    *   `exitTime`: Trade exit time.
    *   `exitReason`: Reason for exiting the trade.
    *   `exitPrice`:  Exit price of the asset.
    *   `profitLoss`:  Calculated profit or loss of the trade.
    *   `tradeDuration`:  Duration of the trade.
    *   `followPlan`: Whether the trading plan was followed.
    *   `deviation`: Deviation from your trading plan.
    *   `lessonLearned`: Key takeaway from this specific trade.
*   **🧐 Post-Trade Analysis:**
    *   `emotionsDuringTrade`:  Emotions experienced during the trade.
    *   `takeTradeAgain`:  Would you repeat this trade setup in the future?
    *   `doDifferently`: What changes might improve the outcome of a similar trade?

<br>

## 🗄️ Data Storage

All trading data is stored locally in your browser's local storage. This means:

*   🔒  Your data is saved within your browser.
*   ⚠️  Clearing browser local storage will erase your journal data.
*   ✅  **Use the export/import functionality to backup and restore data**.

<br>

## ⚠️ Disclaimer

This Trading Journal is a personal analysis and tracking tool. It does not offer financial advice. Always manage risk and make informed trading decisions based on your own due diligence.

<br>

##  🤝 Contributing

Contributions are highly welcome! Fork the project, add your ideas, and create a pull request.

<br>
