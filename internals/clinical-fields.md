This file was generated on 2020-02-11 14:51:52.990740

# Subject Fields

## Demographic

### Age
The age of the subject in years.
```
age
```

### Gender
The gender of the subject.
```
sex
gender
```

## Clinical

### Stage
The tumor stage of the subject.
```
stage
m stage
metastasis stage
```

### RECIST
The RECIST classification of the subject.
```
recist
```

### Raw Investigator Response
The response of the subject encoded by the investigator.
```
raw investigator response
raw response
```

### IPOP Response - Two Type
The response of the subject encoded as a two-type variable.
```
two-type response
ipop two-type response
```

### IPOP Response - Three Type
The response of the subject encoded as a three-type variable.
```
three-type response
ipop three-type response
```

# Sample Fields

## Clinical

### Treatment Status
The treatment status at the time the sample was taken.
```
treatment status
pre on
```

### Cancer Type
The type of cancer of the sample.
```
cancer type
type of cancer
```

### Cancer Type Detailed
The detailed type of cancer of the sample.
```
cancer type detailed
detailed cancer type
detailed type of cancer
```

### Sample Type
The type of sample.
```
sample type
type of sample
```

### Sample Class
The class of sample.
```
sample class
class of sample
```

### Gene Panel
The gene panel taken using the sample.
```
gene panel
```

### Sample Cover
The cover of the sample.
```
sample cover
```

### Tumor Purity
The tumor purity of the sample.
```
tumor purity
```

### Oncotree Code
The OncoTree code of the sample.
```
oncotree
oncotree code
```

### MSI Score
The microsatellite instability score of the sample.
```
msi score
```

### MSI Type
The microsatellite instability type of the sample.
```
msi type
```

### Institute
The institute associated with the sample.
```
institute
```

### Somatic Status
The somatic status of the sample.
```
somatic status
```

## DNA

### Mutation Count
The number of non-synonmous single-nucleotide variants (SNV) detected and validated by an internal pipeline of the sample.
```
mutation count
number of mutations
```

### Mutation Count with Synonymous Mutations
The number of non-synonmous single-nucleotide variants (SNV) detected and validated by an internal pipeline of the sample.
```
mutation count syn
```

### Indel Count
The number of insertions and deletions (indels) detected and validated by an internal pipeline of the sample.
```
indel count
```

### Tumor Mutation Burden
The normalized number of non-synonmous single-nucleotide variants (SNV) detected and validated by an internal pipeline of the sample. To normalize the mutation count, the number of non-synonmous SNVs is divided by 30.
```
tmb
tumor mutation burden
mutation burden
```

### Tumor Mutation Burden with Synonymous Mutations
The normalized number of single-nucleotide variants (SNV) detected and validated by an internal pipeline of the sample. To normalize the mutation count, the number of SNVs is divided by 30.
```
tmb syn
tumor mutation burden syn
mutation burden syn
```

### Tumor Mutation Burden of Indel Mutations
The normalized number of insertions and deletions (indels) detected and validated by an internal pipeline of the sample. To normalize the mutation count, the number of indels is divided by 30,
```
tmb syn
tumor mutation burden syn
mutation burden syn
```

### Log Tumor Mutation Burden
The logarithm (base10) of the normalized number of non-synonmous single-nucleotide variants (SNV) detected and validated by an internal pipeline of the sample. In the instance that the non-synonmous SNV count is 0, this field is set to the logarithm of 1/30 (base 10).
```
log tmb
log tumor mutation burden
log mutation burden
```

### Log Tumor Mutation Burden Syn
The logarithm (base 10) of the normalized number of single-nucleotide variants (SNV) detected and validated by an internal pipeline of the sample. In the instance that the SNV count is 0, this field is set to the logarithm of 1/30 (base 10).
```
log tmb syn
log tumor mutation burden syn
log mutation burden syn
```

### Log Tumor Mutation Burden Indel
The logarithm (base 10) of the normalized number of insertions and deletions (indels) detected and validated by an internal pipeline of the sample. In the instance that the number of indels is 0, this field is set to the logarithm of 1/30 (base 10).
```
log tmb indel
log tumor mutation burden indel
log mutation burden indel
```

### Neoantigen Count
The number of non-synonmous single-nucleotide variants (SNV) predicted to encode neo-antigenic peptides of a sample. The prediction is made by NetMHCPan and the length of amino acids is 9.
```
neoantigen count
```

### Neopeptide Count
The number of non-synonmous single-nucleotide variant-derived neopeptides predicted to encode neo-antigenic peptides of a sample. The prediction is made by NetMHCPan and the length of amino acids is 9.
```
neopeptide count
```

### Log Neoantigen Count
The logarithm (base 10) of the number of non-synonmous single-nucleotide variants (SNV) predicted to encode neo-antigenic peptides of a sample. See Neoantigen Count for more information. In the instance that the number of neoantigens is 0, this field is set to the logarithm of 1 (base 10), which equals 0.
```
log neoantigen count
```

### Log Neopeptide Count
The logarithm (base 10) of the number of non-synonmous single-nucleotide variant-derived neopeptides predicted to encode neo-antigenic peptides of a sample. See Neopeptide Count for more information. In the instance that the number of neopeptides is 0, this field is set to the logarithm of 1 (base 10), which equals 0.
```
log neopeptide count
```

### Aging Signature
The aging signature (Sanger signature 1) of the sample.
```
aging signature
```

### Smoking Signature
The smoking signature (Sanger signature 4) of the sample.
```
smoking signature
```

### UV Signature
The UV signature (Sanger signature 7) of the sample.
```
uv signature
```

### HLA-A Zygosity
The zygosity of HLA-A for the subject.
```
hla a zygosity
hla a
```

### HLA-B Zygosity
The zygosity of HLA-B for the subject.
```
hla b zygosity
hla b
```

### HLA-C Zygosity
The zygosity of HLA-C for the subject.
```
hla c zygosity
hla c
```

### HLA Zygosity
The composite zygosity of HLA at locus A, B and C for the subject.
```
hla zygosity
hla
```

### HLA-A Evolutionary Divergence
The evolutionary divergence of the HLA allele pair at locus A for the sample. This value is calculated by measuring the Grantham distance between the peptide-binding domains of the subject's two HLA-A alleles.
```
hla a evolutionary divergence
hed a
```

### HLA-B Evolutionary Divergence
The evolutionary divergence of the HLA allele pair at locus B for the sample. This value is calculated by measuring the Grantham distance between the peptide-binding domains of the subject's two HLA-B alleles.
```
hla b evolutionary divergence
hed b
```

### HLA-C Evolutionary Divergence
The evolutionary divergence of the HLA allele pair at locus C for the sample. This value is calculated by measuring the Grantham distance between the peptide-binding domains of the subject's two HLA-C alleles.
```
hla c evolutionary divergence
hed c
```

### Mean HLA Evolutionary Divergence
The mean of the evolutionary divergence of the HLA allele pair at locus A, B, and C for the sample. This value is calculated by measuring the Grantham distance between the peptide-binding domains of the subject's two alleles at locus A, B, and C, and taking the mean.
```
hla mean evolutionary divergence
mean hla evolutionary divergence
hed mean
mean hed
```

## CIBERSORT

### Naive B Cells (CIBERSORT - LM22)
The estimated absolute score of naive B cells as a result of the CIBERSORT analysis with the leukocyte gene signature matrix (LM22).
```
b cells naive lm22
naive b cells lm22
```

### Memory B Cells (CIBERSORT - LM22)
The estimated absolute score of memory B cells as a result of the CIBERSORT analysis with the leukocyte gene signature matrix (LM22).
```
b cells memory lm22
memory b cells lm22
```

### Plasma Cells (CIBERSORT - LM22)
The estimated absolute score of plasma cells as a result of the CIBERSORT analysis with the leukocyte gene signature matrix (LM22).
```
plasma cells lm22
```

### CD8+ T Cells (CIBERSORT - LM22)
The estimated absolute score of CD8+ T cells as a result of the CIBERSORT analysis with the leukocyte gene signature matrix (LM22).
```
t cells cd8 lm22
cd8 t cells lm22
```

### Naive CD4+ T Cells (CIBERSORT - LM22)
The estimated absolute score of naive CD4+ T cells as a result of the CIBERSORT analysis with the leukocyte gene signature matrix (LM22).
```
t cells cd4 naive lm22
naive cd4 t cells lm22
```

### Resting CD4+ T Cells (CIBERSORT - LM22)
The estimated absolute score of resting CD4+ T cells as a result of the CIBERSORT analysis with the leukocyte gene signature matrix (LM22).
```
t cells cd4 resting lm22
resting cd4 t cells lm22
```

### Activated CD4+ T Cells (CIBERSORT - LM22)
The estimated absolute score of activated CD4+ T cells as a result of the CIBERSORT analysis with the leukocyte gene signature matrix (LM22).
```
t cells cd4 activated lm22
activated cd4 t cells lm22
```

### Follicular Helper T Cells (CIBERSORT - LM22)
The estimated absolute score of follicular helper T cells as a result of the CIBERSORT analysis with the leukocyte gene signature matrix (LM22).
```
t cells follicular helper lm22
follicular helper t cells lm22
```

### Regulator T Cells (CIBERSORT - LM22)
The estimated absolute score of regulator T cells as a result of the CIBERSORT analysis with the leukocyte gene signature matrix (LM22).
```
t cells regulator lm22
regulator t cells lm22
```

### Gamma Delta T Cells (CIBERSORT - LM22)
The estimated absolute score of gamma delta T cells as a result of the CIBERSORT analysis with the leukocyte gene signature matrix (LM22).
```
t cells gamma delta lm22
gamma delta t cells lm22
```

### Resting NK Cells (CIBERSORT - LM22)
The estimated absolute score of resting NK cells as a result of the CIBERSORT analysis with the leukocyte gene signature matrix (LM22).
```
nk cells resting lm22
resting nk cells lm22
```

### Activated NK Cells (CIBERSORT - LM22)
The estimated absolute score of activated NK cells as a result of the CIBERSORT analysis with the leukocyte gene signature matrix (LM22).
```
nk cells activated lm22
activated nk cells lm22
```

### Monocytes (CIBERSORT - LM22)
The estimated absolute score of monocytes as a result of the CIBERSORT analysis with the leukocyte gene signature matrix (LM22).
```
monocytes lm22
```

### Macrophages M0 (CIBERSORT - LM22)
The estimated absolute score of M0 macrophages as a result of the CIBERSORT analysis with the leukocyte gene signature matrix (LM22).
```
macrophages m0 lm22
```

### Macrophages M1 (CIBERSORT - LM22)
The estimated absolute score of M1 macrophages as a result of the CIBERSORT analysis with the leukocyte gene signature matrix (LM22).
```
macrophages m1 lm22
```

### Macrophages M2 (CIBERSORT - LM22)
The estimated absolute score of M2 macrophages as a result of the CIBERSORT analysis with the leukocyte gene signature matrix (LM22).
```
macrophages m2 lm22
```

### Resting Dendritic Cells (CIBERSORT - LM22)
The estimated absolute score of resting dendritic cells as a result of the CIBERSORT analysis with the leukocyte gene signature matrix (LM22).
```
dendritic cells resting lm22
resting dendritic cells lm22
```

### Activated Dendritic Cells (CIBERSORT - LM22)
The estimated absolute score of activated dendritic cells as a result of the CIBERSORT analysis with the leukocyte gene signature matrix (LM22).
```
dendritic cells activated lm22
activated dendritic cells lm22
```

### Resting Mast Cells (CIBERSORT - LM22)
The estimated absolute score of resting mast cells as a result of the CIBERSORT analysis with the leukocyte gene signature matrix (LM22).
```
mast cells resting lm22
resting mast cells lm22
```

### Activated Mast Cells (CIBERSORT - LM22)
The estimated absolute score of activated mast cells as a result of the CIBERSORT analysis with the leukocyte gene signature matrix (LM22).
```
mast cells activated lm22
activated mast cells lm22
```

### Eosinophils (CIBERSORT - LM22)
The estimated absolute score of eosinophils as a result of the CIBERSORT analysis with the leukocyte gene signature matrix (LM22).
```
eosinophils lm22
```

### Neutrophils (CIBERSORT - LM22)
The estimated absolute score of neutrophils as a result of the CIBERSORT analysis with the leukocyte gene signature matrix (LM22).
```
neutrophils lm22
```

## ssGSEA

### Antigen Presenting Machinery Score 1 (ssGSEA - Hakimi)
The mRNA-based ssGSEA score for the antigen presenting machinery signature 1 of the sample. The score measures the rank of genes in the antigen presenting machinery signature 1 relative to all other genes.
```
apm1 hakimi
apm1 ssgsea
antigen presenting machinery 1 ssgsea
```

### Antigen Presenting Machinery Score 2 (ssGSEA - Hakimi)
The mRNA-based ssGSEA score for the antigen presenting machinery signature 2 of the sample. The score measures the rank of genes in the antigen presenting machinery signature 2 relative to all other genes.
```
apm2 hakimi
apm2 ssgsea
antigen presenting machinery 2 ssgsea
```

### Angiogenesis (ssGSEA - Hakimi)
The mRNA-based ssGSEA score for the angiogenesis signature of the sample. The score measures the rank of genes in the angiogenesis signature relative to all other genes.
```
angiogenesis hakimi
angiogenesis ssgsea
```

### B Cells (ssGSEA - Bindea)
The mRNA-based ssGSEA score for the B cell signature of the sample. The score measures the rank of genes in the B cell signature relative to all other genes.
```
b cells bindea
b cells ssgsea
```

### CD8+ T Cells (ssGSEA - Bindea)
The mRNA-based ssGSEA score for the CD8+ T cell signature of the sample. The score measures the rank of genes in the CD8+ T cell signature relative to all other genes.
```
cd8 t cells bindea
cd8 t cells ssgsea
```

### CTLA-4 (ssGSEA - Hakimi)
The mRNA-based ssGSEA score for the CTLA-4 signature of the sample. The score measures the rank of genes in the CTLA-4 signature relative to all other genes.
```
ctla4 hakimi
ctla4 ssgsea
```

### Cytotoxic Cells (ssGSEA - Bindea)
The mRNA-based ssGSEA score for the cytotoxic cell signature of the sample. The score measures the rank of genes in the cytotoxic cell signature relative to all other genes.
```
cytotoxic cells bindea
cytotoxic cells ssgsea
```

### Dendritic Cells (ssGSEA - Bindea)
The mRNA-based ssGSEA score for the dendritic cell signature of the sample. The score measures the rank of genes in the dendritic cell signature relative to all other genes.
```
dc bindea
dc ssgsea
dendritic cells ssgsea
```

### Eosinophils (ssGSEA - Bindea)
The mRNA-based ssGSEA score for the eosinophils signature of the sample. The score measures the rank of genes in the eosinophils signature relative to all other genes.
```
eosinophils bindea
eosinophils ssgsea
```

### Macrophages (ssGSEA - Bindea)
The mRNA-based ssGSEA score for the macrophages signature of the sample. The score measures the rank of genes in the macrophages signature relative to all other genes.
```
macrophages bindea
macrophages ssgsea
```

### Mast Cells (ssGSEA - Bindea)
The mRNA-based ssGSEA score for the mast cell signature of the sample. The score measures the rank of genes in the mast cell signature relative to all other genes.
```
mast cells bindea
mast cells ssgsea
```

### CD56bright NK Cells (ssGSEA - Bindea)
The mRNA-based ssGSEA score for the CD56bright NK cell signature of the sample. The score measures the rank of genes in the CD56bright NK cell signature relative to all other genes.
```
nk cd56 bright cells bindea
cd56bright nk cells ssgsea
```

### CD56dim NK Cells (ssGSEA - Bindea)
The mRNA-based ssGSEA score for the CD56dim NK cell signature of the sample. The score measures the rank of genes in the CD56dim NK cell signature relative to all other genes.
```
nk cd56 dim cells bindea
cd56dim nk cells ssgsea
```

### NK Cells (ssGSEA - Bindea)
The mRNA-based ssGSEA score for the NK cell signature of the sample. The score measures the rank of genes in the NK cell signature relative to all other genes.
```
nk cells bindea
nk cells ssgsea
```

### Neutrophils (ssGSEA - Bindea)
The mRNA-based ssGSEA score for the neutrophils signature of the sample. The score measures the rank of genes in the neutrophils signature relative to all other genes.
```
neutrophils ssgsea
neutrophils bindea
```

### PD1 (ssGSEA - Hakimi)
The mRNA-based ssGSEA score for the PD1 signature of the sample. The score measures the rank of genes in the PD1 signature relative to all other genes.
```
pd1 hakimi
pd1 ssgsea
```

### PD-L1 (ssGSEA - Hakimi)
The mRNA-based ssGSEA score for the PD-L1 signature of the sample. The score measures the rank of genes in the PD-L1 signature relative to all other genes.
```
pdl1 hakimi
pdl1 ssgsea
```

### T Cells (ssGSEA - Bindea)
The mRNA-based ssGSEA score for the T cells signature of the sample. The score measures the rank of genes in the T cells signature relative to all other genes.
```
t cells bindea
t cells ssgsea
```

### Helper T Cells (ssGSEA - Bindea)
The mRNA-based ssGSEA score for the T helper cell signature of the sample. The score measures the rank of genes in the T helper cell signature relative to all other genes.
```
t helper cells bindea
t helper cells ssgsea
th cells ssgsea
```

### Central Memory T Cells (ssGSEA - Bindea)
The mRNA-based ssGSEA score for the T central memory cell signature of the sample. The score measures the rank of genes in the T central memory cell signature relative to all other genes.
```
tcm cells bindea
tcm cells ssgsea
t central memory cells ssgsea
```

### Effector Memory T Cells (ssGSEA - Bindea)
The mRNA-based ssGSEA score for the T effector memory cell signature of the sample. The score measures the rank of genes in the T effector memory cell signature relative to all other genes.
```
tem cells bindea
tem cells ssgsea
t effector memory cells ssgsea
```

### Follicular Helper T Cells (ssGSEA - Bindea)
The mRNA-based ssGSEA score for the T follicular helper cell signature of the sample. The score measures the rank of genes in the T follicular helper cell signature relative to all other genes.
```
tfm cells bindea
tfm cells ssgsea
t follicular helper cells ssgsea
```

### Gamma Delta T Cells (ssGSEA - Bindea)
The mRNA-based ssGSEA score for the gamma delta T cell signature of the sample. The score measures the rank of genes in the gamma delta T cell signature relative to all other genes.
```
tgd cells bindea
tgd cells ssgsea
gamma delta t cells ssgsea
```

### T Helper 1 Cells (ssGSEA - Bindea)
The mRNA-based ssGSEA score for the T helper 1 cell signature of the sample. The score measures the rank of genes in the T helper 1 cell signature relative to all other genes.
```
th1 cells bindea
th1 cells ssgsea
t helper 1 cells ssgsea
```

### T Helper 17 Cells (ssGSEA - Bindea)
The mRNA-based ssGSEA score for the T helper 17 cell signature of the sample. The score measures the rank of genes in the T helper 17 cell signature relative to all other genes.
```
th17 cells bindea
th17 cells ssgsea
t helper 17 cells ssgsea
```

### T Helper 2 Cells (ssGSEA - Bindea)
The mRNA-based ssGSEA score for the T helper 2 cell signature of the sample. The score measures the rank of genes in the T helper 2 cell signature relative to all other genes.
```
th2 cells bindea
th2 cells ssgsea
t helper 2 cells ssgsea
```

### Regulator T Cells (ssGSEA - Bindea)
The mRNA-based ssGSEA score for the regulator T cell signature of the sample. The score measures the rank of genes in the regulator T cell signature relative to all other genes.
```
treg cells bindea
treg cells ssgsea
regulator t cells ssgsea
```

### Activated Dendritic Cells (ssGSEA - Bindea)
The mRNA-based ssGSEA score for the activated dendritic cell signature of the sample. The score measures the rank of genes in the activated dendritic cell signature relative to all other genes.
```
adc bindea
adc ssgsea
activated dc ssgsea
activated dendritic cells ssgsea
```

### Immature Dendritic Cells (ssGSEA - Bindea)
The mRNA-based ssGSEA score for the immature dendritic cell signature of the sample. The score measures the rank of genes in the immature dendritic cell signature relative to all other genes.
```
idc bindea
idc ssgsea
immature dc ssgsea
immature dendritic cells ssgsea
```

### Plasmacytoid Dendritic Cells (ssGSEA - Bindea)
The mRNA-based ssGSEA score for the plasmacytoid dendritic cell signature of the sample. The score measures the rank of genes in the plasmacytoid dendritic cell signature relative to all other genes.
```
pdc bindea
pdc ssgsea
plasmacytoid dc ssgsea
plasmacytoid dendritic cells ssgsea
```

