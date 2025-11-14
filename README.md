# Cyber-Risk-Quantification-for-AML-Attacks
This repository has been created to provide additional data on AML attacks data

# Cyber Risk Quantification for Adversarial Machine Learning – Data Repository

This repository contains the input data and simulation outputs used in the study:

**"Cyber Risk Quantification for Adversarial Machine Learning Attacks"**

The Monte Carlo simulations were executed using **ModelRisk® (Vose Software)**.
This repository provides the full transparency package including:

### ✔ Input data for all four attack scenarios
- Ransomware  
- Evasion  
- Poisoning  
- Privacy attacks  

Each dataset includes:
- Threat Event Frequency (Poisson)
- Aggregated Vulnerability inputs
- Loss component distributions (Triangular min/mode/max)
- Simulation parameters (iterations, sampling method)

### ✔ Output graphs
- Annual Loss Exceedance distributions
- Tornado sensitivity charts

### ✔ ModelRisk resources
To enable full reproducibility:
- ModelRisk Quick Start Guide  
- Free License Manager (official)  
- Example workbook showing the risk model setup  

### ✔ Important note
This repository does **not** include the ModelRisk simulation engine.
Instead, it provides all necessary inputs and outputs so that the model
can be replicated by anyone using ModelRisk or an equivalent tool.

## Reproducing the Study
1. Install ModelRisk (free academic / trial license supported).
2. Open the workbook under `/modelrisk_workbooks/`.
3. Run 100,000 iterations.
4. Compare generated outputs with the charts in `/outputs/`.

