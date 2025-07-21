## 📁 Supplementary Data Files

### `SD1`: Unconditional Sequence Generation  
This file contains a sample of 50 sequences unconditionally generated from the five independently trained models used in **Level 2 fine-tuning**.  
In total, 100 MaSp repeat sequences were generated from each model (500 in total), and this file includes a representative subset for reference.

---

### `SD2`: Model Self-Consistency Evaluation  
To evaluate self-consistency, each of the five Level 2 models was tested on the same set of 37 MaSp repeat instances (totaling **185 unique test cases**).  
Each test instance includes a natural MaSp repeat sequence along with its known mechanical property set.  
These properties were used as input conditions for sequence generation.  
The composition of this test set is detailed in the `SD2` file.

---

### `SD3`: BLAST-Based Similarity Comparison  
This dataset presents a comparison between **seven generated sequences** and their top two natural matches, referred to as `BLAST1` and `BLAST2`, based on BLAST results.  
Matches were selected based on the following metrices:

- **Query coverage**
- **Percent identity**
- **Sequence length similarity**

All included matches had statistically significant similarity scores:  
`E-value ≤ e⁻¹⁰`  
Details of the generated sequences, BLAST matches, and their sources are provided in the `SD3` file.

---
