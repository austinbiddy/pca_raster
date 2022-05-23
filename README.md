# pca_raster

To construct a correlative SDM and eliminate associated variables, I used a principal component analysis (PCA) to distill variables based on eigenvalues.
Raster files were clipped, masked, and converted to ASCII files in ArcGIS prior to being imported in R. 
I imported 23 environmental variables, but for brevity and generality, only the word "layer" is adopted in the provided code. 
For my work, current and projected scenarios were used to build SDMs. 

I created this code because I noticed that few PCA R tutorials discussed rasters for unconstrained ordination analyses, but they have utility with selecting variables that are contributing to overall model variance, as determined by a PCA. 
