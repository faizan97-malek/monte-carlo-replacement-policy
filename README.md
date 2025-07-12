# 🧊 Monte Carlo Simulation – Fan Replacement Optimization

This project uses Monte Carlo Simulation to evaluate and optimize cooling fan replacement policies in a data center. The goal is to minimize total operational costs by simulating current vs proposed strategies.

## 📌 Objective
To compare cost and failure risk between:
- **Current Policy**: Replace fans only upon failure
- **Proposed Policy**: Replace fans proactively after a set lifespan

## 🧪 Methodology
- Simulated 10,000+ fan lifespans using random draws from a Weibull distribution
- Modeled repair, replacement, and downtime costs
- Used Python and Excel for parallel validation

## 📈 Tools & Libraries
- Python: NumPy, Matplotlib, Pandas
- Excel: Data tables and random sampling
- Jupyter Notebook

## 📊 Key Insights
- Proposed proactive replacement policy reduced total costs by ~14%
- Downtime incidents dropped significantly under the new policy

## 📁 Files
- `simulation_model.ipynb` – Python Monte Carlo simulation
- `fan_policy_analysis.xlsx` – Excel-based simulation
- `visualizations/` – Charts and graphs
- `report_summary.pdf` – Final executive summary and recommendation

## 📍 Outcome
The simulation demonstrated that replacing fans proactively after a defined interval is significantly more cost-effective than waiting for failures.

---

**Author:** Faizanfarid Malek  
📧 [faizex07@gmail.com](mailto:faizex07@gmail.com)  
🔗 [LinkedIn](https://linkedin.com/in/faizanfarid-malek-3b1265313)
