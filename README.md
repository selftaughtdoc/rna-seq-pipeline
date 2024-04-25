# RNA-Seq Analysis Pipeline

This repository contains a Python script for an RNA-Seq analysis pipeline. The pipeline performs preprocessing, alignment, quantification, and differential expression analysis of RNA-Seq data.

## Usage

1. **Clone Repository**:

2. **Install Dependencies**:
- FastQC: https://www.bioinformatics.babraham.ac.uk/projects/fastqc/
- Trim Galore: https://www.bioinformatics.babraham.ac.uk/projects/trim_galore/
- HISAT2: http://daehwankimlab.github.io/hisat2/
- featureCounts: http://bioinf.wehi.edu.au/featureCounts/
- DESeq2: https://bioconductor.org/packages/release/bioc/html/DESeq2.html

3. **Run Pipeline**:
- Modify input parameters in the `rna_seq_pipeline.py` script.
- Execute the script:
  ```
  python rna_seq_pipeline.py
  ```

## License

This project is licensed under the MIT License 
