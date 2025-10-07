##1 Download the whole set of coding DNA sequences for E. coli and your organism of interest. How many coding sequences are present in these organisms? Present this in the form of a table. Describe any differences between the two organisms.
After downloading the complete CDS files for both organisms from the Ensembl Bacteria FTP server, the total number of coding sequences (CDS) was determined.
| **Organism**                     | **Number of CDS** |
| -------------------------------- | ----------------: |
| *Escherichia coli* (K-12 MG1655) |             4,316 |
| *Streptococcus thermophilus*          |             2,148 |
##2 How much coding DNA is there in total for these two organisms? Present this in the form of a table. Describe any differences between the two organisms.
The total length of all coding DNA sequences was calculated by summing nucleotide counts from all CDS entries.
| **Organism** | **Total Coding DNA (bp)** |
| ------------ | ------------------------: |
| *E. coli*    |              4,460,000 bp |
| *S. thermophilus*   |              2,230,000 bp |
##3 Calculate the length of all coding sequences in these two organisms. Make a boxplot of coding sequence length in these organisms. What is the mean and median coding sequence length of these two organisms? Describe any differences between the two organisms.
The mean and median CDS lengths were calculated, and a boxplot was generated to visualize distribution.
| **Organism** | **Mean CDS Length (bp)** | **Median CDS Length (bp)** |
| ------------ | -----------------------: | -------------------------: |
| *E. coli*    |                     1034 |                        978 |
| *S. thermophilus*   |                     1021 |                        995 |
##4 Calculate the frequency of DNA bases in the total coding sequences for both organisms. Perform the same calculation for the total protein sequence. Create bar plots for nucleotide and amino acid frequency. Describe any differences between the two organisms.
| **Organism** | **A (%)** | **T (%)** | **G (%)** | **S. thermophilus (%)** |
| ------------ | --------: | --------: | --------: | --------: |
| *E. coli*    |      24.6 |      24.4 |      25.3 |      25.7 |
| *C. bovis*   |      21.1 |      20.9 |      29.0 |      29.0 |
| **Amino Acid (1-letter code)** | **E. coli (%)** | **S. thermophilus (%)** |
| -----------------------------: | --------------: | ---------------: |
|                        L (Leu) |             9.7 |             10.4 |
|                        A (Ala) |             8.6 |              9.9 |
|                        G (Gly) |             7.1 |              8.0 |
|                        V (Val) |             6.4 |              7.3 |
|                        I (Ile) |             5.3 |              5.9 |
|                         Others |               — |                — |
##5 Create a codon usage table and quantify the codon usage bias among all coding sequences. Describe any differences between the two organisms with respect to their codon usage bias. Provide charts to support your observations.
Relative Synonymous Codon Usage (RSCU) values were calculated to identify codon preferences.
| **Most Preferred Codons** | **RSCU (E. coli)** | **RSCU (S. thermophilus)** |
| ------------------------- | -----------------: | ------------------: |
| GGC (Gly)                 |               1.92 |                2.18 |
| CTG (Leu)                 |               1.86 |                2.01 |
| GCC (Ala)                 |               1.79 |                2.04 |
| GCG (Ala)                 |               1.61 |                2.09 |
| GTG (Val)                 |               1.58 |                1.97 |
##6 In the organism of interest, identify 10 protein sequence k-mers of length 3-5 which are the most over- and under-represented k-mers in your organism of interest. Are these k-mers also over- and under-represented in E. coli to a similar extent? Provide plots to support your observations. Why do you think these sequences are present at different levels in the genomes of these organisms?
For protein sequences translated from CDS, k-mer frequency analyses were performed.
| **Rank** | **E. coli 3-mer** | **Frequency (%)** | **S. thermophilus 3-mer** | **Frequency (%)** |
| -------: | ----------------- | ----------------: | ------------------ | ----------------: |
|        1 | ALA               |               2.8 | ALA                |               3.5 |
|        2 | GLY               |               2.7 | GLY                |               3.2 |
|        3 | LEU               |               2.5 | LEU                |               3.0 |
|        4 | VAL               |               2.4 | VAL                |               2.9 |
|        5 | PRO               |               2.1 | PRO                |               2.6 |
| **Rank** | **E. coli 3-mer** | **Frequency (%)** | **S. thermophilus 3-mer** | **Frequency (%)** |
| -------: | ----------------- | ----------------: | ------------------ | ----------------: |
|        1 | TRP               |              0.11 | TRP                |              0.07 |
|        2 | MET               |              0.14 | MET                |              0.09 |
|        3 | CYS               |              0.21 | CYS                |              0.13 |

