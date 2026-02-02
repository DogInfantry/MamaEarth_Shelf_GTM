# MamaEarth_Shelf_GTM
This repository contains the data analysis, Python simulations, and strategic framework designed to solve Mamaearth's "Mile-Wide, Inch-Deep" paradox.
The Core Problem: Mamaearth has prioritized Availability (being everywhere) over Authority (being the default choice). The brand suffers from portfolio bloat, where a wide array of low-velocity SKUs creates "shelf paralysis" for offline consumers and diminishes returns on marketing spend.
The Objective: Transition from a niche D2C bazaar model to a dominant FMCG leader by executing Strategic Assortment Rationalization. This involves cutting the "Long Tail" of products to focus exclusively on high-velocity "Hero" SKUs (e.g., Ubtan Range or Anti-Hairfall System) to drive shelf velocity and retailer ROI.

--------------------------------------------------------------------------------
📂 Repository Structure
├── data_analysis/
│   ├── ad_spend_efficiency.ipynb    # Analysis of Marketing Efficiency Ratio (Revenue vs. Spend)
│   ├── pareto_bloat.py              # Identification of the top 20% "Hero" SKUs driving 80% revenue
│   └── sku_velocity_gt.csv          # (Mock) General Trade velocity data
├── simulations/
│   ├── risk_model_gmroi.py          # Python simulation of Retailer ROI under "Shelf-Share Vacuum" scenarios
│   └── shelf_space_optimizer.py     # Planogram logic for "Yellow Wall" visual dominance
├── strategy_docs/
│   ├── 01_problem_diagnosis.md      # The "Ad-Spend Trap" and "Scale-Stage Crisis"
│   ├── 02_gtm_execution_plan.md     # 6-Month "Hero System" rollout plan
│   └── 03_trade_incentives.md       # Shift from Variety-based to Velocity-based margins
└── README.md

--------------------------------------------------------------------------------
📊 Key Data Insights
1. The Ad-Spend Trap
Our analysis confirms that the "Marketing Lever" is broken.
• Observation: In Q2 FY25, revenue declined (~₹462 Cr) despite sustained ad visibility.
• Metric: The Marketing Efficiency Ratio (Revenue generated per ₹1 Ad Spend) has stagnated. The brand is "shouting louder" just to stay in place.
2. The Pareto Bloat
• Insight: "Focus Categories" (Face Wash, Sunscreen, Serums) account for over 80% of revenues but occupy a fraction of the portfolio.
• Conclusion: The remaining 80% of SKUs are "rent-squatters"—occupying dead real estate and confusing consumers.

--------------------------------------------------------------------------------
💻 Simulation: The Risk Quantification Model
Located in simulations/risk_model_gmroi.py, this script models the "Availability Illusion" Risk. It tests the hypothesis that removing niche products will result in lost shelf space to competitors.
The Logic: Even if Mamaearth loses top-line revenue by delisting niche products, the Retailer's Return on Investment (GMROII) increases because they replace "dead" inventory with high-turnover Hero units.
Simulation Output:
--- RISK QUANTIFICATION RESULTS ---
Scenario: Delisting bottom 60% Long-Tail SKUs

1. Revenue Impact:
   Total Revenue Drop: -34.8% (Initial dip due to volume cut)

2. Retailer Efficiency (GMROII):
   ROI per shelf-inch: +389.1% INCREASE

CONCLUSION: 
Retailers make MORE profit per sq. ft. focusing on Hero SKUs. 
Economic incentive aligns with giving Mamaearth PRIME space, not LESS space.
[Ref: 15]

--------------------------------------------------------------------------------
🚀 GTM Strategy: Execution Plan
The project proposes two primary operational levers based on the analysis:
Lever A: Strategic Assortment Rationalization ("The Yellow Wall")
• Goal: Convert the confused shelf into a dominant billboard of the best-selling franchise (e.g., Ubtan).
• Phase 1 (The Purge): Issue "Stop-Ship" orders for the bottom 60% of SKUs in General Trade.
• Phase 2 (The Block): Implement 4 facings of Top 3 products to create visual dominance, rather than 1 facing of 10 products.
Lever B: The "Hero System" Play
• Goal: Solve the "decision friction" by grouping products into a solution-based routine (e.g., Anti-Hairfall: Shampoo + Conditioner + Oil).
• Shelf Architecture: Create a vertical block with "Step 1, Step 2, Step 3" signage to drive System Penetration rather than single-unit sales.

--------------------------------------------------------------------------------
📉 Success Metrics
We define success not by total revenue (which hides bloat), but by habit formation and efficiency.
1. Throughput Per Store (TPS): Tracking Units Sold per Week per Store of Hero SKUs.
2. System Penetration: The % of buyers purchasing 2+ Hero SKUs in a single transaction (for the System Play).
3. Marketing Efficiency: Improving revenue generated per ₹1 of ad spend.

--------------------------------------------------------------------------------
🛠 Usage
To run the risk simulation model:
# Clone the repository
git clone https://github.com/mamaearth-strategy/gtm-optimization.git

# Install dependencies
pip install pandas numpy

# Run the GMROII risk model
python simulations/risk_model_gmroi.py

--------------------------------------------------------------------------------
⚠️ Risks & Trade-Offs
• Deliberate Deprioritization: We are explicitly deprioritizing long-tail SKUs (body lotions, niche serums) in General Trade. Consumers seeking these must go online.
• Revenue Dip: We accept a short-term dip in "sell-in" revenue as retailers clear out non-performing inventory.
• Competitive Risk: Competitors may try to fill the "share of shelf" vacuum. We mitigate this by proving higher velocity per inch for retailers, incentivizing them to protect our space.

--------------------------------------------------------------------------------
