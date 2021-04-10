# metabolomicsSCFM

Data, code, and figures from Dunphy et al

Code:
- dunphy_et_al_manuscript.Rmd -> Includes data processing and figure generation


figures_and_supplement: Includes all main and supplementary figures as well as supplementary data

Key Data Files:

1. Raw metabolomics data (raw peak areas)
- Laura_neg_mode_Final_051220.csv (negative mode)
- Laura_pos_Mode_Final_051220.csv (positive mode)

2. Metabolomics file names and metadata
- sample_key_ljd2.csv -> connects raw metabolomics files names to sample names
- metabolomics_metadata.csv -> information on each sample (replicate, name, collection date, batch, strain, CFU counts)
- additional_kegg_id.csv -> KEGG IDs not initially included in annotation found upon a curated pass of the database
