#  Real Estate Investment Advisor – AI-Driven Market & Property Analysis

![image](https://github.com/user-attachments/assets/086d75fc-e3c6-4433-b4d3-a8ca7dec7618)


This project is an intelligent real estate investment advisory system that automates data collection, financial evaluation, market analysis, and investment recommendation for U.S. residential properties using multi-agent collaboration powered by `crewAI`, `Langchain`, and `Groq's LLaMA-3`.

It simulates a professional real estate research and advisory team — all agents are domain experts collaborating to generate high-quality, real-time investment insights.

---

##  Key Features

- **Automated Data Collection**  
  Gathers property prices, rents, taxes, and demographic metrics across 10 U.S. cities from open real estate data sources (e.g., Zillow, Redfin, Census APIs).

- **Financial Metrics Computation**  
  Calculates ROI, cap rate, cash-on-cash return, and other real estate KPIs using collected data.

- **Macro & Micro Trend Analysis**  
  Analyzes economic trends like migration, job growth, and housing supply to assess long-term potential.

- **AI-Driven Investment Recommendations**  
  Identifies top 3 cities and properties to invest in, using combined insights from financial and market analysis.

- **Investor-Ready PDF Report**  
  Summarizes findings in a structured investor report with tables, charts, and professional language.

---

##  Agents Overview

| Agent Role | Responsibility |
|------------|----------------|
| **Property Data Researcher** | Fetches real-time property and economic data |
| **Financial Analyst** | Evaluates each property's financial viability |
| **Market Trends Analyst** | Studies real estate and economic indicators |
| **Investment Advisor** | Selects top 3 properties and cities for ROI |
| **Report Generator** | Produces the final investor presentation |

---

## Tech Stack

- **[crewAI](https://github.com/joaomdmoura/crewAI)** – Multi-agent task orchestration
- **[Langchain](https://www.langchain.com/)** – LLM agent reasoning framework
- **[Groq + LLaMA 3 70B Vision](https://groq.com/)** – High-performance LLM with vision
- **Open Real Estate APIs** – Zillow, Redfin, Census (via integration layer)
- **Python** – Core automation and task logic
- **NumPy, Pandas** – Data manipulation and computation

---

## How It Works

1. **Agents** are initialized with specific goals and domain backstories.
2. **Tasks** are defined in a sequential pipeline to:
   - Collect real estate data
   - Run investment calculations
   - Analyze market trends
   - Recommend cities/properties
   - Generate a professional report
3. **The Crew** is assembled and executed, simulating a real-world expert collaboration.

---

##  Sample Output

- 🔹 10 Cities analyzed
- 🔹 30+ property listings evaluated
- 🔹 ROI tables with key metrics
- 🔹 Market trends report (job growth, migration, housing supply)
- 🔹 Top 3 investment cities

---

##  Note

This project demonstrates how LLM agents can collaborate to perform **domain-specific analysis at scale**, and is especially suitable for:
- Investment firms
- Real estate research agencies
- PropTech startups
- Individual investors exploring AI-driven advisory

---

## License

MIT License – feel free to fork, modify, and use it for your own AI investment advisors.
