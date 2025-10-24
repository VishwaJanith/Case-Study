# Clinic Dispensary Simulation

## Project Overview
This project simulates patient flow in the **Clinic Dispensary at District General Hospital - Horana** using **SimPy** in a **Jupyter Notebook**. It analyzes key performance metrics such as **waiting times**, **queue lengths**, **pharmacist utilization**, and **patients served** under various staffing and workload scenarios. The simulation helps identify bottlenecks and test improvements to enhance hospital efficiency.

---

## Requirements

### Python Version
- **Python 3.8 or above**

### Required Libraries
Install the necessary dependencies using:

```bash
pip install simpy pandas matplotlib
```

---

## How to Run the Simulation

### Option 1: Run in Jupyter Notebook (Recommended)
1. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Open the `Clinic Dispensary.ipynb` file.
3. Run the notebook cells sequentially:
   - **Simulation section**: Generates the results table.
   - **Visualization section**: Generates charts for analysis.

### Option 2: Run as a Python Script
1. Convert the notebook to a Python script:
   ```bash
   jupyter nbconvert --to script "Clinic Dispensary.ipynb"
   ```
2. Run the script:
   ```bash
   python "Clinic Dispensary.py"
   ```

---

## Simulation Output Metrics
The simulation provides the following metrics to evaluate system performance:

| **Metric**            | **Meaning**                              |
|-----------------------|------------------------------------------|
| Patients Served       | Number of patients completed             |
| Avg Wait (min)        | Average waiting time in queue            |
| Avg Service (min)     | Time taken per patient                   |
| Avg Queue             | Average queue length                     |
| Utilization (%)        | Pharmacist workload level                |
| Throughput/hr         | Patients served per hour                 |

---

## Scenarios Studied
The simulation evaluates the system under different conditions:

| **Scenario**           | **Description**                                      |
|------------------------|-----------------------------------------------------|
| Base Case              | Current real-world system conditions                |
| More Counters          | Additional pharmacists added                        |
| Faster Pharmacists     | Improved service efficiency                         |
| Heavy Rush             | Patient overload on busy clinic days (e.g., Monday/Wednesday with 5–6 clinics) |

---

## Purpose of This Study
This simulation aims to assist the hospital in:
- Reducing long patient queues.
- Lowering waiting times.
- Balancing pharmacist workload.
- Testing system changes before real-world implementation.

---

## Visualizations
The project generates the following charts to analyze performance:
- **Average Waiting Time Across Scenarios**: Bar chart comparing wait times.
- **Queue Length vs. Wait Time**: Scatter plot showing relationships.
- **System Performance Trends Across Scenarios**: Line chart tracking trends.
- **Comparison of Key Metrics Across Scenarios**: Grouped bar chart for key metrics.

---

## Repository Structure
- `Clinic Dispensary.ipynb`: Main Jupyter Notebook containing the simulation and visualizations.
- `README.md`: This file, providing an overview and instructions.
- (Optional) `Clinic Dispensary.py`: Converted script for running outside Jupyter.

---

## Notes
- Ensure all dependencies are installed before running the simulation.
- For best results, use Jupyter Notebook to interact with the visualizations.
- The simulation is designed to be flexible, allowing modifications to test additional scenarios.
