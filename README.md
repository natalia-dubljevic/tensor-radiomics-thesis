# tensor-radiomics-thesis
Supplemental code for the thesis "Tensor Radiomics: Applications of Multi-Quantized Features to Oncologic PET/CT Images".

* conventional_baseline: This trains and tests on conventional pipelines using single-flavour features
* tr_flavour_concatenation: This trains and test the flavour concatenation TR implementation using the same pipelines as the baseline
* tr_flavour_combination: This trains and test the flavour combination TR implementation using mostly the same pipelines as the baseline. PCA as a dimensionality reduction technique is dropped for interpretability.
* tr_net: Trains and tests TR-Net
