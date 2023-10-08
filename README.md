# TReS
## Introduction

## Workdir
- TReS/data/DGE_rs/ : save the DGE results and processed DGE results;
  >including:
  > - ALV_DE.csv
  > - BALF.csv
  > - EXP.csv
- TReS/data/TWAS_rs/ : save the TWAS results and processed TWAS results;
  >including
  > - blood.txt ()
  > - lung.txt
  > - lymphocytes.txt
  > - spleen.txt
- TReS/data/LINCS2_beta/ : save the compound signatures downloaded from LINC2 database and processed annotation files;
  >including:
  > - siginfo_beta.txt (Metadata for level 5 signatures, can be downloaded from LINCS2)
  > - compoundinfo_beta.txt (metadata for compounds, can be downloaded from LINCS2)
  > - beta_immuncelline_revised.txt (immune cell lines, can be downloaded from LINCS2)
  > - level5_beta_trt_cp_n720216x12328.gctx (level 5 compound signatures, can be downloaded from LINCS2)
- TReS/data/drugbank/ : save the drugbank vocabulary file;
- TReS/data/compound_d_immune/ : save the revesal distance computed by us;

## Tool
Predixcan(https://www.nature.com/articles/ng.3367, https://github.com/gamazonlab/MR-JTI/blob/master/model_training/predixcan/)
