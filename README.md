# Epileptic Neuronal Dynamics

## Overview
This project investigates epileptic neuronal activity using a computational neuroscience approach based on the Leaky Integrate-and-Fire (LIF) neuron model.

The notebook simulates and compares three neuronal network conditions:
- Normal neuronal activity
- Epileptic neuronal activity
- Treated epileptic activity

The project analyses how changes in neuronal excitability and connectivity affect firing behaviour and network dynamics. The work was developed as part of a university computational neuroscience assignment.

---

## Project Structure

```text
epileptic-neuronal-dynamics/
├── README.md
├── Epileptic_Neuronal_Dynamics.ipynb
├── report/
│   └── brain_project_report.pdf
└── images/
    └── neuronal_activity_visualization.png
```

---

## Objectives
The main objectives of the project are to:

- Simulate neuronal spiking behaviour using the LIF model
- Compare normal and epileptic network dynamics
- Analyse firing rate distributions across conditions
- Study temporal firing patterns using ISI analysis
- Investigate functional connectivity through spike correlation analysis
- Evaluate the effect of treatment on epileptic dynamics

---

## Computational Model

### Leaky Integrate-and-Fire (LIF) Neurons
The notebook implements a network of simulated LIF neurons to reproduce neuronal spiking activity over time.

The simulations model:
- Membrane potential dynamics
- External current inputs
- Synaptic interactions
- Spike generation and reset mechanisms

---

## Analyses Performed

### 1. Raster Plot Analysis
Raster plots are generated to visualise neuronal spike timing across the simulated network.

### 2. Inter-Spike Interval (ISI) Analysis
ISI histograms are used to analyse temporal firing behaviour and detect abnormal spiking patterns associated with epileptic activity.

### 3. Firing Rate Analysis
The notebook computes:
- Mean firing rates
- Firing rate distributions
- Comparative activity across conditions

### 4. Functional Connectivity Analysis
Pairwise spike correlations are computed to estimate functional connectivity within neuronal networks.

Correlation matrices are visualised to compare:
- Normal networks
- Epileptic networks
- Treated epileptic networks

---

## Technologies & Libraries

- Python
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Key Outcomes

- Simulated biologically inspired neuronal dynamics
- Compared activity patterns across multiple network conditions
- Visualised epileptic network behaviour using computational methods
- Analysed functional connectivity through spike correlation metrics
- Built a reproducible neuroscience simulation workflow

---

## Example Visualisations

The notebook includes:
- Raster plots
- ISI histograms
- Firing rate distributions
- Correlation heatmaps
- Comparative network activity visualisations

Example:

```markdown
![Neuronal Dynamics](images/neuronal_activity_visualization.png)
```

---

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/epileptic-neuronal-dynamics.git
cd epileptic-neuronal-dynamics
```

### 2. Install dependencies

```bash
pip install numpy matplotlib seaborn
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
Epileptic_Neuronal_Dynamics.ipynb
```

---

## Academic Context
This repository was developed for educational and research purposes as part of a university computational neuroscience project.
