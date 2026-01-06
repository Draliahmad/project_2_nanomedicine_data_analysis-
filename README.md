
# Nanomedicine Formulation Data Analysis
## Graphical Abstract

## Graphical Abstract

<img src="graphical_abstract.png" width="900"/>

**Graphical Abstract | Nanomedicine formulation data analysis.**  
Summary of dataset, statistical analysis, key physicochemical relationships, and clinical relevance of nanostructured lipid carrier (NLC) formulations.

## Objective
To analyse nanostructured lipid carrier (NLC) formulation data using
data science techniques to understand relationships between
physicochemical properties and formulation performance.

## Dataset
Formulation data including particle size, PDI, zeta potential,
and encapsulation efficiency.

## Methods
- Data cleaning
- Descriptive statistics
- Correlation analysis
- PCA
- Regression analysis
## Results & Visualisations

### Correlation Heatmap
![Correlation heatmap of NLC formulation parameters](heatmap_correlation.png)
Figure 1 | Correlation matrix of nanostructured lipid carrier (NLC) formulation parameters.
The heatmap illustrates pairwise Pearson correlations between particle size, polydispersity index (PDI), zeta potential (ZP), and encapsulation efficiency (EE). Colour intensity reflects the strength and direction of associations, highlighting interdependencies between physicochemical properties that influence formulation performance.
### Particle Size vs Encapsulation Efficiency
![Particle size vs encapsulation efficiency](size_vs_EE.png)
Figure 2 | Relationship between particle size and encapsulation efficiency.
This scatter plot demonstrates the association between NLC particle size and drug encapsulation efficiency, revealing trends that suggest size-dependent effects on drug loading and formulation stability.
### PDI vs Encapsulation Efficiency
![PDI vs encapsulation efficiency](PDI_vs_EE.png)
Figure 3 | Influence of polydispersity index (PDI) on encapsulation efficiency.
The plot explores how formulation homogeneity, represented by PDI, impacts encapsulation efficiency. Lower PDI values indicate more uniform particle populations, which are generally associated with improved formulation consistency and performance
### Zeta Potential vs PDI
![Zeta potential vs PDI](ZP_vs_PDI.png)
Figure 4 | Association between zeta potential and polydispersity index.
This figure examines the relationship between surface charge and particle size distribution, providing insight into colloidal stability and electrostatic interactions governing NLC formulation behaviour.
## Key Findings
- Encapsulation efficiency showed a size-dependent trend, indicating the importance of nanoscale optimisation.
- Lower PDI values were associated with improved formulation consistency and performance.
- Zeta potential correlated with particle homogeneity, highlighting its role in colloidal stability.
## Clinical and Pharmaceutical Relevance
Understanding relationships between particle size, surface charge, and encapsulation efficiency is critical for optimising nanostructured lipid carriers intended for pulmonary and systemic drug delivery. Such data-driven optimisation supports the rational design of stable, reproducible, and clinically translatable nanomedicine formulations.

## Tools
Python, pandas, matplotlib, seaborn, scikit-learn
## Reproducibility
All analyses were performed using Python-based data science tools. Figures can be regenerated using the original dataset and analysis scripts following standard exploratory data analysis and statistical workflows.



Dr Ali Ahmad
MBBS, 
MSc (CMM),
MSc (DDD)
