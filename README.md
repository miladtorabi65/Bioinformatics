Putative Disease Gene Identification and Drug Repurposing for Steatohepatitis

Authors

Milad Torabi, Possenti FrancescaGroup 9Sapienza University, Bioinformatics and Network MedicineJanuary 16, 2025

Overview

Non-alcoholic steatohepatitis (NASH) is a complex liver disorder characterized by fat accumulation, inflammation, and hepatocellular injury. As the prevalence of NASH rises globally, there is an urgent need to identify putative disease genes and explore potential drug repurposing strategies. This project utilizes network science methods and bioinformatics algorithms to analyze NASH-related genes and repurpose existing drugs as potential therapeutic candidates.

Objectives

Identify putative disease-associated genes using PPI network analysis.

Utilize network-based algorithms (DIAMOnD, DIAble, Diffusion) to identify key genes related to NASH.

Integrate multi-omics data (proteomics and genomics) to explore disease mechanisms.

Implement drug repurposing strategies by screening approved drugs against the identified genes.

Provide insights into novel therapeutic avenues for NASH treatment.

Methodology

1. Data Collection

Protein-Protein Interaction (PPI) Network: Retrieved from BioGRID database.

Gene-Disease Associations (GDAs): Extracted from DisGeNET (Disease Code: C2711227).

2. Network Construction & Analysis

Built PPI network from BioGRID interactome.

Filtered data to include only human physical interactions.

Identified the largest connected component (LCC) within the network.

3. Disease Gene Identification

Applied DIAMOnD, DIAble, and Diffusion algorithms to identify putative disease genes.

Prioritized genes based on their connectivity and biological relevance.

4. Drug Repurposing

Mapped identified genes to known drug-target interactions.

Screened FDA-approved drugs for potential efficacy against NASH-related pathways.

Technologies Used

Python (pandas, numpy, networkx, matplotlib, seaborn)

BioGRID and DisGeNET databases for gene and interaction data

Graph-based algorithms for network analysis

Results & Impact

Identified key genes potentially involved in NASH pathogenesis.

Proposed existing drugs that may be repurposed for NASH treatment.

Contributed to advancing bioinformatics-driven approaches for liver disease research.
