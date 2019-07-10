# DataProcessinginMetagenomics
Data processing in metagenomics: Theoretical and applied perspectives on your decisions

The purpose of the code is to provide a tool enabling the assessment of the effect of data transformation, normalization and calculation of beta-diversity to analyze compositional ecology data. Typical data include metagenomics or 16S rRNA gene microbial community characterization.


The tool were applied to an example dataset provided in the "microbiome" bioconductor R package. The study investigates the association between diet and colon cancer in African Americans and rural Africans. 

Different subset of data were used for the analysis. 
Dataset2: Samples were part of the home environment (HE) study and the first time point. Representing a dataset with large differences in microbiome composition between the two groups (African Americans and rural Africans). 
Dataset3: Samples were part of the home environment (HE) study and African Americans. Representing a dataset with relatively smaller differences in microbiome composition between the two timepoints compared to dataset2. 
Dataset3: Samples were part of the home environment (HE) study and rural Africans. Representing a dataset with relatively smaller differences in microbiome composition between the two timepoints compared to dataset2. 

The analysis were both performed with and without the presence absence (PA) transformation.
