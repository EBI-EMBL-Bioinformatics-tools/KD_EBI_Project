# Keloid disease EBI Project
## Introduction
keloid disease (KD) is a condition characterized by abnormal scar tissue growth over a wound, believed to be caused by excessive production of collagen and its decreased degradation in affected tissues. KD can be triggered by both light and severe wounds and its incidence varies greatly among human populations, with black and Hispanic populations having an incidence rate many times higher than white (Caucasian) populations. 

It is well-established that KD has complex genetic and epigenetic causes. Several studies have shown links between certain loci and the appearance of keloids in different ethnic groups. For example: SNP rs873549 in chromosome 1 (1q41) in Japanese and Chinese people, SNP rs1511412 in FOXL2 across different Asian populations, and multiple SNPs in the NEDD4 gene in Egyptian, Chinese, and Japanese populations, while SNPs in the gene MYO1E were more strongly correlated with KD in African Americans. Moreover, different methylation patterns have been detected in KD tissues than normal tissues. Despite all this, the exact mechanism of keloid formation and its genetic causes remains unknown, with different studies showing different results across human populations. Current treatment of keloids is insufficient, with surgical removal often resulting in keloids reappearing, sometimes larger than before. We aim to use genetic variation between populations with high and low prevalence of KD to attempt to explain the causes of these differences and possible genetic causes of this disease. 
## SNPs and genes of interest
Based on the review by Liu et al (2022), we list here the most significant genes and variants associated with KD in different human populations. 

| Gene | Chromosome | SNP	| Population |  
|---------------|---------------|---------------|---------------|
| - | 1q41 | rs873549 | Japanese, Chinese |  
| FOXL2 |	3q22.3-23 |	rs1511412 |	Japanese, Chinese |
| MYO1E |	15q21.2-22.3 | rs747722 |	African American |
| MYO1E	| 15q21.2-22.3 | rs28394564 |	African American |
| NEDD4	| 15q21.3 |	rs8032158	| Egyptian, Japanese |

![image](https://github.com/NataliaDC16/KD_EBI_Project/blob/main/KD.png) 

La imagen tomada de [Florida Keloid Center](https://floridakeloidcenter.com/news/)

## European Nucleotide Archive (ENA)
We found that the ENA has some interesting projects associated with keloids, such as transcriptomic analysis of keloid tissue versus regular scar tissue. Many projects don’t have publicly available data yet. However, we found some transcriptomics projects that did. For example: project PRJNA764368. Other projects with publicly available data for keloids include: PRJEB50146, PRJNA751500, PRJNA734158 and PRJNA780889.

## European PMC

Search for information on keloid disease in European PMC using:

```plaintext
(TITLE:"keloid disease") AND (ANNOTATION_TYPE:"Gene") AND (FIRST_PDATE:[2019 TO 2024])
```
```plaintext
keloid disease in population AND (FIRST_PDATE:[2019 TO 2024]) AND (HAS_FT:Y)
```
```plaintext
(TITLE:"FOXL2") AND (ANNOTATION_TYPE:"Gene") AND (TITLE:"keloid disease" OR TITLE:"keloids" OR ANNOTATION:"keloid")
```
```plaintext
keloid disease AND (((SRC:MED OR SRC:PMC OR SRC:AGR OR SRC:CBA) NOT (PUB_TYPE:"Review")))
```
## European Variation Archive (EVA)
We conducted the searches using GRCh7, not GRCh8.

## Uniprot 
Based on our search in Uniprot, it’s clear that KD is mostly independent from changes in protein sequence. None of our 5 main variants result in changes to the protein sequence and are not listed in Uniprot. Therefore, we may conclude that KD is mostly the result of regulatory changes and not missense or nonsense variants.

## PDBe
The expression of the COMP and POSTN genes is associated with collagen deposition in the cellular matrix and has been found to be overexpressed in keloid tissue. 

PDBe contains one entry for human protein COMP with accession ID 3fby.
PDBe contains three entries for human periostin (POSTN) with acession IDs: 5yjg, 5yjh and 5wt7.

## InterPro 
We used InterPro to research the domains thought to interact with collagen and/or fibronectin in both proteins. 

For COMP information in entry: G3XAP6.
It is believed that COMP in pentameric formation catalyzes the formation of collagen structures using the N-terminal coiled-coil linker domain (Halász et al, 2007). This domain is found in the InterPro entry for COMP and is in the first 40 amino acids (position 1-40) of the protein. ID: IPR024665.

For POSTN information in entry: Q15063.
The EMI domain of this protein, believed to be the most important for interaction with collagen and fibronectin by Liu et al (2018). This domain is found between the amino acids 40 and 94 of the protein. ID:IPR011489.

## AlphaFold
```plaintext
COMP predicted structure with accession code: AF-P49747-F1-v4.
```
```plaintext
POSTN predicted structure with accession code: AF-Q15063-F1-v4.
```
```plaintext
Unconventinal myosin-le with accession code:Q12965.
```
## InterPro

Unconventinal myosin-le/lf, SH3 domain:IP035507.
Myosin head, motor domain:IPR001609.
Kinesin motor domain superfamily: IPR036961.
Class I myosin tail homology domain:IPR010926.



