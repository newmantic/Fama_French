# Fama_French

The Fama-French Three-Factor Model is an extension of the Capital Asset Pricing Model (CAPM) that improves upon CAPM by considering additional factors that explain the differences in returns between diversified portfolios. While CAPM uses a single factor (market risk), the Fama-French model includes three factors:

Market Risk Premium (R_m - R_f): The excess return of the market portfolio over the risk-free rate.
Size Factor (SMB: Small Minus Big): The difference in returns between small-cap stocks and large-cap stocks.
Value Factor (HML: High Minus Low): The difference in returns between high book-to-market stocks (value stocks) and low book-to-market stocks (growth stocks).



Market Risk Premium (R_m - R_f):
This factor represents the return earned by taking on market risk. It is calculated as the difference between the return of the market portfolio (R_m) and the risk-free rate (R_f).
Market Risk Premium = R_m - R_f

Size Factor (SMB):
SMB stands for "Small Minus Big." It measures the return difference between small-cap and large-cap stocks. Historically, small-cap stocks have tended to outperform large-cap stocks, and this factor captures that effect.
SMB = R_small - R_large
Where:
R_small is the return of a portfolio of small-cap stocks.
R_large is the return of a portfolio of large-cap stocks.

Value Factor (HML):
HML stands for "High Minus Low." It measures the return difference between value stocks (high book-to-market ratio) and growth stocks (low book-to-market ratio). Value stocks have historically outperformed growth stocks, and this factor captures that effect.
HML = R_high - R_low
Where:
R_high is the return of a portfolio of high book-to-market stocks.
R_low is the return of a portfolio of low book-to-market stocks.



The Fama-French model expresses the expected return of an asset as a function of its sensitivity to the three factors:
E(R_i) = R_f + β_{iM} \times (R_m - R_f) + β_{iSMB} \times SMB + β_{iHML} \times HML
Where:
E(R_i) is the expected return of asset i.
R_f is the risk-free rate.
β_{iM} is the sensitivity (beta) of asset i to the market risk premium (R_m - R_f).
β_{iSMB} is the sensitivity of asset i to the size factor (SMB).
β_{iHML} is the sensitivity of asset i to the value factor (HML).
SMB is the size premium.
HML is the value premium.



Market Beta (β_{iM}):
This is similar to the beta in the CAPM model. It measures the sensitivity of the asset's returns to the overall market returns. A higher beta indicates greater sensitivity to market movements.

Size Beta (β_{iSMB}):
A positive size beta (β_{iSMB}) indicates that the asset behaves more like small-cap stocks, which tend to have higher returns. A negative size beta indicates that the asset behaves more like large-cap stocks.

Value Beta (β_{iHML}):
A positive value beta (β_{iHML}) indicates that the asset behaves more like value stocks (high book-to-market ratio). A negative value beta indicates that the asset behaves more like growth stocks (low book-to-market ratio).
