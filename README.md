# Geometric Deep Learning Autonomously Learns Chemical Features That Outperform Those Engineered by Domain Experts
Patrick Hop, Brandon Allgood, Jessen Yu
https://pubs.acs.org/doi/10.1021/acs.molpharmaceut.7b01144

## Datasets
Numerate is open-sourcing our pre-processed AstraZenica-Chembl datasets

#### Human Intrinsic Clearance


#### Human Plasma Protein Binding

#### Thermodynamic Solubility

#### Lipophilicity
This is a compound’s affinity for a lipophilic solvent vs a polar solvent. More formally, we use logD (pH7.4), which is captured experimentally using the octanol/buffer distribution coefficient measured by the shake flask method. This is an important measure for potential drugs, as lipophilicity is a key contributor to membrane permeability. Alternatively, highly lipophilic compounds are usually encumbered by low solubility, high clearance, high plasma protein binding, and so forth. Indeed, most drug discovery projects have a target range for lipophilicity.36 This data set is the largest of the three at 4200 compounds.

#### pKa-A1
This is the acid−base dissociation constant for the most acidic proton, which is an important factor in understanding the ionizability of a potential drug and has a strong influence over multiple different properties of interest, including permeability, partitioning, binding, and so forth. This is this smallest data set of the five with only 204 examples.