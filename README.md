# stat-learning

## DEseq2

edgeR in CRISPR screen 
* https://f1000research.com/articles/3-95/v2
* https://support.bioconductor.org/p/102648/

comparison of edgeR, DEseq2 and limma [link](https://www.biostars.org/p/284775/)

FDR method
* BH method
* [qvalue, Storey's method](https://youtu.be/T6J4b-WWebM?si=UEG6yu9141WKKQ-F)
  *  qvalue histogram and lamda estimate
  *  q(p) = mint; p<t FDR(t) (http://viiia.org/fdrFigs/?scale=1280)
  *  Storey's method can break down when a large proportion of the null hypotheses are false, doi: 10.1016/j.neuroimage.2012.07.040
  *  https://rpubs.com/jmr1990/eiccqvalue
