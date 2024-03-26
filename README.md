# memBERT
Source code for the MemBERT paper is contained in this repository
The results are present in the results directory.  
We structure the source code and results into two directories.  
- slices
- structures

The slices directory contains the source code and results for the model trained without any metadata.
Similarly, the structures directory contains the source code and results for the model trained with metadata,i.e by 
extracting pointers, estimating the allocation sizes and creating a graph out of it.
We do five runs of the downstream task for both slices and structures based model.
The results of the downstream task are present within each corresponding subdirectory.
We compute the metrics on the latent space compression.
