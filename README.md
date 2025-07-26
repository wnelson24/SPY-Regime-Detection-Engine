# SPY-Regime-Detection-Engine


A Python script that classifies current SPY market conditions using unsupervised machine learning (Hidden Markov Models). It outputs both:

- **Price Trend Regime** (e.g., Strong Bull, Sideways, Panic Selling)
- **Volatility Regime** (e.g., Complacent, Elevated, Risk-Off)

All with **confidence scores**. Perfect for traders who want to adapt strategies to changing market regimes.

---

## 🔧 How It Works

- Downloads 5 years of SPY data via `yfinance`
- Engineers market features (returns, momentum, volatility)
- Fits two Hidden Markov Models (HMMs):
  - One for **price regime**
  - One for **volatility regime**
- Prints out:
  - Descriptive labels for each regime
  - Confidence level for each
  - Combined strategic context

---

## 🧠 Example Output

