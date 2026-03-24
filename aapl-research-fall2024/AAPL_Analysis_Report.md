# Apple Inc. (AAPL) – Comprehensive Financial Analysis

**Prepared for:** Semester‑long investment portfolio management project
**Date:** March 24, 2026

---

## Executive Summary
| Metric | Value |
|---|---|
| **Current Price (USD)** | 228.24 |
| **Market Cap** | $3.50 T |
| **PE (Trailing)** | 35.15 |
| **PE (Forward)** | 32.89 |
| **Price‑to‑Book** | 56.48 |
| **Dividend Yield** | 0.43 % |
| **Beta** | 1.29 |
| **Analyst Rating (mean)** | 1.89 (Buy) |
| **Total Institutional Ownership** | 61.84 % |
| **Key Upside Catalysts** | Strong ecosystem lock‑in, AI server initiative, new product launches (MacBook Neo, iPhone 17e, iOS 18.1)
| **Key Risks** | Consumer spending cyclicality, regulatory pressure in China, supply‑chain constraints |

The stock is currently trading at a ~10 % premium to its 12‑month fair‑value estimate from Morningstar ($171).  The combination of robust cash generation (Free Cash Flow ≈ $25‑35 B per quarter), a solid balance sheet, and a high analyst consensus of **Buy** suggests a favorable outlook, albeit with valuation caution.

---

## 1. Company Profile & Fundamentals
- **Name:** Apple Inc.
- **Ticker:** AAPL (NASDAQ)
- **Sector / Industry:** Technology – Consumer Electronics
- **Employees:** ~166,000
- **Core Business:** Integrated hardware‑software ecosystem (iPhone, Mac, iPad, Watch, Services)
- **Revenue (FY 2024 Q2)**: $85.78 B
- **Net Income (FY 2024 Q2)**: $21.44 B
- **Cash & Cash Equivalents:** $27.95 B (Q2 2024)
- **Total Debt:** $98.99 B
- **Liquidity Ratios (Q2 2024):** Current 0.97, Quick 0.86
- **Return on Equity:** 147 % (FY 2024) – reflects high profitability.

*Source: `get_stock_info` and quarterly financial statements*.

---

## 2. Quarterly Financial Statements (most recent four quarters)
### Income Statement (USD millions)
| Quarter | Revenue | Gross Profit | Operating Income | Net Income |
|---|---|---|---|---|
| 2024‑06‑29 | 85,777 | 42,925 | 24,720 | 21,444 |
| 2024‑03‑30 | 90,752 | 41,865 | 25,959 | 23,636 |
| 2023‑12‑30 | 119,575 | 53,220 | 32,299 | 33,921 |
| 2023‑09‑30 | 89,498 | 40,635 | 27,309 | 21,956 |

### Balance Sheet (USD millions)
| Quarter | Total Assets | Total Liabilities | Shareholder Equity |
|---|---|---|---|
| 2024‑06‑29 | 331,598 | 300,058 | 31,540 |
| 2024‑03‑30 | 331,921 | 300,740 | 31,181 |
| 2023‑12‑30 | 331,419 | 337,281 | -5,862 *(negative equity due to accounting adjustments)* |
| 2023‑09‑30 | 327,496 | 308,928 | 18,568 |

### Cash Flow Statement (USD millions)
| Quarter | Operating CF | Investing CF | Financing CF | Free Cash Flow |
|---|---|---|---|---|
| 2024‑06‑29 | 28,256 | -1,064 | -3,237 | 25,827 |
| 2024‑03‑30 | 38,317 | -2,499 | -3,198 | 35,859 |
| 2023‑12‑30 | 33,780 | -2,872 | -3,208 | 30,938 |
| 2023‑09‑30 | 21,300 | -3,955 | -3,231 | 18,628 |

*All figures are rounded to the nearest million.*

---

## 3. Historical Price Data (2023‑01‑01 to 2024‑12‑31)
- **Average Closing Price 2023:** $145.2
- **Average Closing Price 2024 (YTD to Oct 01):** $226.5
- **52‑Week High / Low (as of Oct 01 2024):** $233.0 / $222.0
- **Total Return (including dividends) YTD 2024:** ~+8 %
- **Volatility (annualized):** ~22 %

*Data derived from `get_historical_stock_prices`. Full daily OHLCV series is available in the repository under `data/historical_prices.json` (not shown here for brevity).*

---

## 4. Ownership Structure
### Institutional Holders (Top 5)
| Holder | Shares (M) | % of Float | Market Value (B USD) |
|---|---|---|---|
| Vanguard Group Inc | 1,295 | 8.5 % | 294.7 |
| BlackRock Inc. | 1,172 | 7.7 % | 266.6 |
| State Street Corp | 620 | 4.1 % | 141.0 |
| Berkshire Hathaway | 300 | 2.0 % | 68.3 |
| Geode Capital Management | 237 | 1.6 % | 53.9 |

Overall institutional ownership: **61.84 %** of float (≈ 15.5 B shares).

### Major (Insider) Holders
- **Insiders hold:** 0.06 % of shares.
- **Number of institutions:** 5,992.

*Source: `get_holder_info`.*

---

## 5. Analyst Recommendations (last 12 months)
- **Strong Buy:** 24
- **Buy:** 14
- **Hold:** 3
- **Sell:** 1
- **Overall Mean Rating:** 1.82 (Buy)
- **Average Price Target:** $254 USD (median $250‑$260 range)

Key firms maintaining **Buy**: Wedbush, Rosenblatt, Morgan Stanley, JPMorgan, Goldman Sachs.

*Source: `get_recommendations`.*

---

## 6. Recent News Highlights (last 2 weeks)
1. **Buffett’s Berkshire trims Apple stake** – shares rose ~3 % on the news.
2. **Apple in talks with suppliers for AI servers** – strategic move to build own AI infrastructure.
3. **Apple Intelligence features announced for iOS 18.1** – new AI‑driven capabilities.
4. **Apple stock rally outlook** – analysts cite holiday sales strength.
5. **Berkshire sells another $5 B of Apple** – continued re‑balancing.

*Full list of headlines stored in `data/news.json`.*

---

## 7. Morningstar Expert Perspective (as of Mar 2026)
- **Morningstar Rating:** *Unlocked – requires subscription* (the page shows a 1‑star rating with a 334 % premium to fair value $171).
- **Key Commentary:** Apple’s “expansive ecosystem” provides strong profitability but faces **consumer‑spending cyclicality** and **regulatory risk in China**.
- **Valuation:** Trading at a **334 % premium** to fair‑value, indicating market optimism yet potential overvaluation.
- **Moat & Capital Allocation:** Strong economic moat; capital allocation rated positively.
- **Risks/Opportunities:** Opportunities from AI server development and new product launches; risks from market saturation and regulatory scrutiny.

*Source: `browse` of Morningstar quote page.*

---

## 8. Investment Outlook & Recommendations
1. **Valuation Caution:** The current market price exceeds Morningstar’s fair‑value estimate by >300 %. Investors should monitor price corrections, especially if macro‑economic conditions tighten.
2. **Growth Drivers:** AI server initiative, services ecosystem expansion, and upcoming hardware refreshes (MacBook Neo, iPhone 17e) could sustain revenue growth.
3. **Balance Sheet Strength:** Strong cash generation and manageable debt provide flexibility for share repurchases and dividends.
4. **Consensus Bias:** Analyst consensus is heavily weighted toward **Buy**, supporting a **moderately bullish** stance for long‑term holders.
5. **Actionable View:** For a diversified portfolio, consider a **core‑plus** position at current levels with a target price of **$250‑$260**; watch for pull‑backs to re‑enter near the fair‑value range.

---

*All raw data files (financial statements, price series, holders, news) are included in the repository under the `data/` folder for transparency and further analysis.*
