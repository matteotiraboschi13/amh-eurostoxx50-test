# Data sources

This file summarizes the data used in the empirical analysis.

## Variables

- **EURO STOXX 50**: target stock market index used to compute daily returns.  
  Source: [FACTSET](https://my.apps.factset.com/workstation/navigator/company-security/price-history/183657)

- **Brent Oil**: oil price variable, used to capture external commodity-related shocks.  
  Source: [FRED - DCOILBRENTEU](https://fred.stlouisfed.org/series/DCOILBRENTEU)

- **Euro area spot rate 5Y**: interest rate variable used to represent the medium-term part of the euro area yield curve.  
  Source: [ECB - Euro area spot rate 5Y](https://data.ecb.europa.eu/data/datasets/YC/YC.B.U2.EUR.4F.G_N_C.SV_C_YM.SR_5Y)

- **Euro area spot rate 10Y**: interest rate variable used to represent the long-term part of the euro area yield curve.  
  Source: [ECB - Euro area spot rate 10Y](https://data.ecb.europa.eu/data/datasets/YC/YC.B.U2.EUR.4F.G_N_C.SV_C_YM.SR_10Y)

- **Euro area spot rate 30Y**: interest rate variable used to represent the very long-term part of the euro area yield curve.  
  Source: [ECB - Euro area spot rate 30Y](https://data.ecb.europa.eu/data/datasets/YC/YC.B.U2.EUR.4F.G_N_C.SV_C_YM.SR_30Y)

- **EONIA and €STR**: overnight interest rate variables used to construct a consistent short-term monetary policy proxy.  
  Sources: [ECB - EONIA](https://data.ecb.europa.eu/data/datasets/EON/EON.D.EONIA_TO.RATE) and [ECB - €STR](https://data.ecb.europa.eu/data/datasets/EST/EST.B.EU000A2X2A25.WT)

- **M2**: monetary aggregate used to construct the real money supply variable.  
  Source: [ECB - M2](https://data.ecb.europa.eu/data/datasets/BSI/BSI.M.U2.Y.V.M20.X.1.U2.2300.Z01.E)

- **HICP**: Harmonised Index of Consumer Prices, used to deflate M2 and construct the real money supply variable.  
  Source: [ECB - HICP](https://data.ecb.europa.eu/data/datasets/HICP/HICP.M.U2.N.000000.4D0.INX)

- **EER40**: euro effective exchange rate index against a basket of 40 trading partners, used to compute euro returns.  
  Source: [ECB - EER40](https://data.ecb.europa.eu/data/datasets/EXR/EXR.D.E03.EUR.EN00.A)

- **VSTOXX**: volatility index used to identify and contextualize periods of high uncertainty in the European stock market.
