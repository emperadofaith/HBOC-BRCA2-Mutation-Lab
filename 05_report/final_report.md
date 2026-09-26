**Disease Background**

BRCA2 (BRCA2 DNA Repair Associated) is a gene that helps repair damaged DNA and maintain genomic stability. Pathogenic mutations in BRCA2 impair DNA repair, increasing the risk of developing certain cancers, particularly breast and ovarian cancer, as well as prostate and pancreatic cancers. BRCA2-related cancer risk can be inherited in an autosomal dominant pattern, meaning a person with a pathogenic variant has a 50% chance of passing it to each child.

**The Gene and its Normal Protein Function**

The BRCA2 (BRCA2 DNA Repair Associated) gene, located on chromosome 13q13.1, is a tumor-suppressor gene that provides instructions for producing the BRCA2 protein. Its normal function is to help repair damaged DNA, particularly DNA double-strand breaks, through the homologous recombination repair pathway. BRCA2 works closely with the RAD51 protein to ensure accurate DNA repair and maintain genomic stability. By preventing the accumulation of DNA mutations, BRCA2 helps maintain normal cell growth and reduces the risk of cancer development.

**Documented Mutation**
| Parameter                | Information                                                                                                                                 |
|--------------------------|---------------------------------------------------------------------------------------------------------------------------------------------|
| Gene                     | BRCA2                                                                                                                                       |
| Reference Transcript     | NM_000059.4                                                                                                                                 |
| Exact Variant            | NM_000059.4(BRCA2):c.10G>T (p.Gly4Ter)                                                                                                     |
| Nucleotide Change        | G>T position 10                                                                                                                            |
| Predicted Protein Change | p.Gly4Ter                                                                                                                            |
| Mutation Type            | missense / single nucleotide variant                                                                                                       |
| ClinVar Accession        | VCV000051063.27                                                                                                                            |
| Clinical Interpretation  | pathogenic                                                                                                                                  |
| Reference                | [Evidence-based Network for the Interpretation of Germline Mutant Alleles (ENIGMA)](https://www.ncbi.nlm.nih.gov/clinvar/submitters/504863/) |

**Hypothesis**

The c.10G>T mutation in the BRCA2 gene is hypothesized to disrupt normal BRCA2 protein function, potentially impairing DNA repair and genomic stability. Since the documented variant is classified as pathogenic, it may contribute to an increased susceptibility to BRCA2-associated cancers.

**Methods**

1. Sequence Retrieval: BRCA2 wild-type coding sequence was obtained through the NCBI database with reference transcript of NM_000059.4 .

2. Control Translation: The wild-type CDS was translated using the Galaxy translation tool in Frame 1 to obtain the predicted BRCA2 protein sequence.
3. Documented Mutation Engineering: The nucleotide at position 10 was changed from G  to T to reproduce the documented c.10G>T variant.

4. Mutant Translation: The modified CDS was translated using the same procedure as the wild-type sequence. The resulting protein was compared with the wild-type sequence to identify amino-acid changes, protein-length changes, and premature stop codons.

5. Artificial Mutation: A second single-nucleotide substitution was created at position 5, changing the codon from CCT to ACT. 

6. Sequence Alignment: Needle was used to compare the wild-type and mutant BRCA2 protein sequences and determine sequence identity, similarity, gaps, and amino-acid differences.

7. Workflow Management: Sequence processing, mutation construction, translation, and alignment were performed using Galaxy (https://usegalaxy.org/u/faith_emperado/h/emperado-hboc-gene-mutation-lab) and documented through GitHub.

**Results**

Documentation for WT

| Parameter                | Result       |
|--------------------------|--------------|
| CDS Length               | 10,257 bp    |
| Predicted Protein Length | 3,418 AA     |
| Start Codon              | ATG          |
| Stop Codon               | TAA          |
| Reading Frame            | +1           |
| First 10 Amino Acids     | MPIGSKERPT   |
| Last 10 Amino Acids      | DTITTKKYI    |

Documentation for mutation sample

| Parameter                 | Result                         |
|---------------------------|--------------------------------|
| Mutation                  | c.10G>T                        |
| Original Nucleotide       | G                              |
| Mutant Nucleotide         | T                              |
| Bases Affected            | 1                              |
| Bases Inserted            | 0                              |
| Bases Deleted             | 0                              |
| Bases Substituted         | 1                              |
| Mutation Type             | Missense                       |
| Mutant CDS Length         | 10,257 bp                     |
| Predicted Protein Length  | 2,987 AA                      |
| Reading Frame             | 1                              |
| Amino Acid Change         | p.Gly33Ter                     |
| Premature Stop Codon      | Present (Truncation at position 33) |


