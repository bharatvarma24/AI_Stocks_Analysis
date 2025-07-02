# AI_Stocks_Analysis
📈 AI Companies Stock Behavior Analysis: Clustering & Portfolio Insights

🚀 Project Motive
With the AI revolution reshaping industries, many public companies are aggressively investing in AI:

NVIDIA is powering generative AI compute infrastructure.
Microsoft is deeply integrated with OpenAI and Copilot.
Meta is focusing on LLaMA and foundational AI models.
Oracle and IBM are enhancing AI-powered cloud and enterprise solutions.
Investors interested in AI often face the challenge:

Which AI-heavy companies offer strong returns without unjustified risk, and how can we segment and structure an AI-focused investment portfolio systematically?
This project answers this question with clean data, clustering, and actionable portfolio insights.

🔍 Approach & Methodology

1️⃣ Data Collection
Collected daily stock prices (2021–present) for 15 leading AI-investing companies using yfinance:

NVDA, MSFT, META, AMZN, AAPL, GOOGL, PLTR, ORCL, IBM, TSM, AMD, INTC, TSLA, CRM, BABA.
2️⃣ Metric Computation
Calculated:

CAGR (%): Long-term compounded annual growth.
Annualized Volatility (%): Risk representation.
Sharpe Ratio: Risk-adjusted return with 4% risk-free rate.
3️⃣ Visualization
Scatter plots of CAGR vs. Volatility for risk-return insight.
4️⃣ Clustering using KMeans
Applied KMeans clustering on CAGR and Volatility to group companies into 4 actionable investment clusters.

5️⃣ Portfolio Allocation
Created pie and bar charts recommending weight allocations per cluster for practical AI investing.

📊 Enhanced Results & Interpretations

🟩 Cluster 0 (40%): Low/Moderate Risk, Good Return
Companies: IBM, ORCL, MSFT, AAPL, GOOGL
✅ AI Context:

IBM is leveraging Watsonx for enterprise AI workflows.
ORCL integrates generative AI into cloud services.
MSFT invests in OpenAI, Copilot in Office and Azure.
GOOGL develops Gemini models, AI-enhanced Search.
AAPL integrates AI for on-device ML and health insights.
✅ Interpretation:
Stable AI investors with solid returns and manageable risk, forming the core backbone of an AI-focused portfolio.

🟥 Cluster 1 (5%): High Risk, Low/Negative Return
Companies: TSLA, AMD, BABA, INTC
✅ AI Context:

TSLA with AI for Full-Self Driving and Dojo supercomputer.
AMD expanding MI300X chips for AI training.
BABA focusing on Tongyi Qianwen and AI cloud.
INTC developing AI accelerators but lagging in market share.
✅ Interpretation:
Volatile with poor historical returns, these are speculative AI plays, recommended for minimal exposure.

🟧 Cluster 2 (30%): High Risk, High Return
Companies: NVDA, PLTR
✅ AI Context:

NVDA is the backbone of AI compute, dominating GPU markets.
PLTR offers AI-powered enterprise data integration and AIP for business workflows.
✅ Interpretation:
Aggressive growth drivers in AI, suitable for investors seeking high-risk, high-reward opportunities in their portfolio.

🟨 Cluster 3 (25%): Moderate Risk, Modest Return
Companies: META, TSM, AMZN, CRM
✅ AI Context:

META invests heavily in open-source LLaMA models and generative AI.
TSM manufactures cutting-edge chips enabling AI compute.
AMZN integrates AI in AWS Bedrock and retail operations.
CRM adds AI copilots into customer relationship workflows.
✅ Interpretation:
Balanced exposure to companies deeply investing in AI with moderate returns and risk, ideal for diversification.

✅ Actionable Portfolio Plan

📊 Recommended Allocation:

40% → Cluster 0: Core stable AI investments.
30% → Cluster 2: Aggressive AI growth.
25% → Cluster 3: Diversification.
5% → Cluster 1: Speculative exposure.
This systematic allocation ensures growth capture while managing volatility.

📌 Summary

Through:
✅ Clean data collection
✅ Calculation of CAGR, Volatility, Sharpe
✅ KMeans clustering
✅ Actionable visualization and allocation

this project translates the complex AI investing landscape into a structured, data-driven strategy for portfolio construction.

You now understand:

Which AI-heavy companies align with different risk-return profiles.
How to allocate effectively for your risk tolerance and growth goals.
How to leverage data-driven methods to guide investment decisions in the AI sector.
