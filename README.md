# TReD
## Introduction

## Workdir
- TReS/data/DGE_rs/ : save the DGE results and processed DGE results;  
  >prestored:
  > - ALV_DE.csv (derived from the study of Brian L. Le et al)
  > - BALF.csv (derived from the study of Brian L. Le et al)
  > - EXP.csv (derived from the study of Brian L. Le et al)
- TReS/data/TWAS_rs/ : save the TWAS results and processed TWAS results;  
  >prestored:
  > - twas_blood.txt (generated by PrediXcan)
  > - twas_lung.txt (generated by PrediXcan)
  > - twas_lymphocytes.txt (generated by PrediXcan)
  > - twas_spleen.txt (generated by PrediXcan)
- TReS/data/LINCS2_beta/ : save the compound signatures downloaded from LINC2 database and processed annotation files;  
  >prestored:
  > - siginfo_beta.txt (Metadata for level 5 signatures, can be downloaded from LINCS2)
  > - compoundinfo_beta.txt (metadata for compounds, can be downloaded from LINCS2)
  > - beta_immuncelline_revised.txt (immune cell lines, can be downloaded from LINCS2)
  > - level5_beta_trt_cp_n720216x12328.gctx (level 5 compound signatures, can be downloaded from LINCS2)
- TReS/data/drugbank/ : save the drugbank vocabulary file (drugbank vocabulary_5.1.10.csv, load from drugbank);  
- TReS/data/compound_d_immune/ : save the revesal distance computed by us;  

## Tool
Predixcan(https://www.nature.com/articles/ng.3367, https://github.com/gamazonlab/MR-JTI/blob/master/model_training/predixcan/)
