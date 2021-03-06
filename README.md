# Geometric Deep Learning Autonomously Learns Chemical Features That Outperform Those Engineered by Domain Experts
Patrick Hop, Brandon Allgood, Jessen Yu

https://pubs.acs.org/doi/10.1021/acs.molpharmaceut.7b01144

Numerate is open-sourcing the pre-processed AstraZenica-Chembl datasets used in our recent paper.

#### Human Intrinsic Clearance
This is the rate at which the human body removes circulating, unbound drug from the blood. This is one of the key in vitro parameters used to predict drug residency time in the patient.36 In drug discovery, this property is assessed by measuring the metabolic stability of drugs in either human liver microsomes or hepatocytes. This data set includes 1102 examples of intrinsic clearance measured in human liver microsomes following incubation at 37 °C.

#### Human Plasma Protein Binding
This assay measures the proportion of drug that is bound reversibly to proteins such as albumin and α-acid glycoprotein in the plasma. Knowing the amount that is unbound is critical because it is that amount that can diffuse into tissue or be cleared by the liver. 1640 compounds are measured, and regression targets are transformed using log(1 − bound), a more representative measure for scientists.

#### Thermodynamic Solubility
This measures the solubility of a solid starting material in pH 7.4 buffer. Solubility influences a wide range of properties for drugs, especially ones that are
administered orally. This data set contains 1763 examples.

#### Lipophilicity
This is a compound’s affinity for a lipophilic solvent vs a polar solvent. More formally, we use logD (pH7.4), which is captured experimentally using the octanol/buffer distribution coefficient measured by the shake flask method. This is an important measure for potential drugs, as lipophilicity is a key contributor to membrane permeability. Alternatively, highly lipophilic compounds are usually encumbered by low solubility, high clearance, high plasma protein binding, and so forth. Indeed, most drug discovery projects have a target range for lipophilicity. This data set is the largest of the three at 4200 compounds.

#### pKa-A1
This is the acid−base dissociation constant for the most acidic proton, which is an important factor in understanding the ionizability of a potential drug and has a strong influence over multiple different properties of interest, including permeability, partitioning, binding, and so forth. This is this smallest data set of the five with only 204 examples.

## References
https://www.ebi.ac.uk/chembl/doc/inspect/CHEMBL3301361

https://github.com/deepchem/deepchem