# No-Code Food Supply Chain Analytics Dashboard
### For Small and Mid-Market Distributors

Author: Sarah Onyeche Usoro
Tools: Microsoft Excel · Power BI Desktop · GitHub
Dataset: Simulated U.S. small/mid-market food distributor data (5 distributors, 6 products, 26 weeks)
Status: Demonstration project — framework in active development


 Dataset Disclosure
The data in this repository is entirely synthetic and was generated programmatically for demonstration purposes only. All four CSV files were produced using a Python random-number generator seeded for reproducibility. No real distributor, company, or operational system contributed data to this project. The five distributor names and six product categories are fictitious.


The numerical ranges used to generate the data are calibrated to reflect documented benchmarks from peer-reviewed literature and U.S. federal agency reports:
•  Waste rates (4–22%): calibrated from ReFED (2026) and Usoro et al. (IJSRA, 2026)
•  Temperature breach rates (~18%): calibrated from FDA FSMA cold chain compliance literature
•  Forecast error rates (8–38%): calibrated from CSCMP State of Logistics Report (2025)
•  On-time delivery rates (72–97%): calibrated from CSCMP mid-market distributor benchmarks


This project is a proof-of-concept demonstration showing that the analytical framework functions correctly and can be applied directly to real operational data from food distributors. It is not, and does not claim to be, an analysis of proprietary or real-world company data.


The Problem This Project Solves
The United States loses an estimated $380 billion worth of food every year to waste and spoilage — equivalent to 29% of the entire U.S. food supply (ReFED, 2026). Large retailers including Kroger, Walmart, and Sysco have achieved measurable food waste reductions of 15–30% through advanced analytics — but these tools remain inaccessible to small and mid-market distributors due to four structural barriers:


•  Capital limitations — enterprise analytics platforms cost $50,000–$500,000+ to implement
•  Data interoperability gaps — legacy systems do not share data across supply chain stages
•  Workforce skill deficits — 6 open supply chain analytics positions for every 1 qualified candidate (ASCM, 2025)
•  Inadequate rural digital infrastructure — limiting cloud-based tool deployment in underserved communities


This project demonstrates that Power BI and Excel, no-code tools that small businesses already have access to can replicate core enterprise analytics capabilities at near-zero additional cost, making data-driven supply chain management accessible to the operators who need it most.


What This Dashboard Tracks
•  Module 1: Waste & Inventory — Units wasted, waste %, revenue loss tracked weekly by product and distributor
•  Module 2: Cold Chain Monitor — Temperature breach rate and severity by product and distributor, with HIGH/MEDIUM/OK classification
•  Module 3: Demand Forecasting — Forecast vs actual demand comparison, error % by product, over/under ordering patterns
•  Module 4: Delivery Performance — On-time delivery %, late deliveries, average delay hours by distributor and region


Key Findings from the Demonstration Dataset
•  Average waste rate: 6.24% — above the 5% benchmark achieved by analytics-enabled large retailers
•  Cold chain breach rate: 18.4% — 497 breach events recorded out of 2,700 total temperature readings
•  Average forecast error: 22.7% — nearly double the 12% best-in-class benchmark for demand planning accuracy
•  Average on-time delivery: 83.7% — below the 85% industry performance threshold


These metrics reflect the documented performance gap between small and mid-market distributors operating without analytics tools and large enterprise retailers with dedicated analytics infrastructure. Closing this gap is the core objective of this framework.


Files in This Repository
•  data/inventory_waste.csv — 780 rows: weekly waste by product and distributor
•  data/cold_chain_events.csv — 2,700 rows: daily temperature readings with breach severity flags
•  data/demand_forecast.csv — 780 rows: forecast vs actual demand comparison by week
•  data/delivery_performance.csv — 130 rows: weekly on-time delivery KPIs by distributor and region
•  powerbi/FoodSupplyChain_Dashboard.pbix — Power BI dashboard file (4 pages, requires free Power BI Desktop)
•  docs/dashboard_screenshots/ — Screenshots of all 4 dashboard pages


How to Use This Project
•  Clone or download this repository to your computer
•  Open any CSV file in Microsoft Excel to explore the raw data
•  Download Power BI Desktop free at https://powerbi.microsoft.com/desktop
•  Open powerbi/FoodSupplyChain_Dashboard.pbix to view the completed 4-page dashboard
•  Connect Power BI to your own distributor data files to generate real operational insights


Connection to Peer-Reviewed Research
This project implements, in deployable no-code tools, the analytical frameworks documented in the following peer-reviewed publications:

•  Usoro et al. (2026). “Reducing Food Waste Through Predictive Analytics and Cold Chain Monitoring: A U.S. Retail Review.” International Journal of Science and Research Archive. DOI: https://doi.org/10.30574/ijsra.2026.18.3.0403
•  Usoro et al. (2026). “AI-Driven Risk Forecasting for Strengthening U.S. Food Supply Chain Resilience.” International Journal of Science and Research Archive. DOI: https://doi.org/10.30574/ijsra.2026.18.1.0143


A forthcoming fifth publication — “Unlocking Food Supply Chain Analytics: A No-Code Implementation Framework for Small and Mid-Market Distributors” — will formalize this demonstration project as a peer-reviewed, replicable implementation framework with outcomes data from field deployment.


This project is part of an active research program to expand data-driven supply chain capabilities to underserved segments of the U.S. food distribution industry.
Sarah Onyeche Usoro  ·  github.com/sarahusoro7  ·  2026
