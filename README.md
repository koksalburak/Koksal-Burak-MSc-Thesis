> sessionInfo() 
R version 4.2.2 (2022-10-31)
Platform: x86_64-pc-linux-gnu (64-bit)
Running under: Ubuntu 22.04.2 LTS

Matrix products: default
BLAS:   /usr/lib/x86_64-linux-gnu/openblas-pthread/libblas.so.3
LAPACK: /usr/lib/x86_64-linux-gnu/openblas-pthread/libopenblasp-r0.3.20.so

locale:
 [1] LC_CTYPE=en_US.UTF-8          LC_NUMERIC=C                 
 [3] LC_TIME=en_US.UTF-8           LC_COLLATE=en_US.UTF-8       
 [5] LC_MONETARY=en_US.UTF-8       LC_MESSAGES=en_US.UTF-8      
 [7] LC_PAPER=en_US.UTF-8          LC_NAME=en_US.UTF-8          
 [9] LC_ADDRESS=en_US.UTF-8        LC_TELEPHONE=en_US.UTF-8     
[11] LC_MEASUREMENT=en_US.UTF-8    LC_IDENTIFICATION=en_US.UTF-8

attached base packages:
 [1] splines   parallel  grid      stats4    stats     graphics  grDevices utils    
 [9] datasets  methods   base     

other attached packages:
 [1] scDblFinder_1.15.1          future_1.33.0               NMF_0.26                   
 [4] cluster_2.1.4               rngtools_1.5.2              registry_0.5-1             
 [7] ggalluvial_0.12.5           CellChat_2.1.2              igraph_1.5.1               
[10] slingshot_2.6.0             TrajectoryUtils_1.6.0       princurve_2.1.6            
[13] ggbeeswarm_0.7.2            tradeSeq_1.12.0             limma_3.54.2               
[16] monocle_2.26.0              DDRTree_0.1.5               irlba_2.3.5.1              
[19] VGAM_1.1-9                  reshape2_1.4.4              ROCR_1.0-11                
[22] KernSmooth_2.23-22          fields_15.2                 viridisLite_0.4.2          
[25] spam_2.10-0                 patchwork_1.1.3             circlize_0.4.15            
[28] ComplexHeatmap_2.14.0       msigdbr_7.5.1               SCPA_1.6.2                 
[31] scran_1.26.2                pheatmap_1.0.12             biomaRt_2.54.1             
[34] DoubletFinder_2.0.3         data.table_1.14.8           magrittr_2.0.3             
[37] gridExtra_2.3               EnhancedVolcano_1.16.0      readxl_1.4.3               
[40] org.Mm.eg.db_3.16.0         pathview_1.38.0             DOSE_3.24.2                
[43] RColorBrewer_1.1-3          brew_1.0-8                  clusterProfiler_4.11.0.002 
[46] openxlsx_4.2.5.2            enrichplot_1.18.4           ggpubr_0.6.0               
[49] ggrepel_0.9.4               DESeq2_1.38.3               xlsx_0.6.5                 
[52] scater_1.26.1               scuttle_1.8.4               shiny_1.7.5.1              
[55] ensembldb_2.22.0            AnnotationFilter_1.22.0     GenomicFeatures_1.50.4     
[58] AnnotationDbi_1.60.2        AnnotationHub_3.6.0         BiocFileCache_2.6.1        
[61] dbplyr_2.4.0                harmony_1.1.0               Rcpp_1.0.11                
[64] RCurl_1.98-1.13             plotly_4.10.3               clustree_0.5.1             
[67] ggraph_2.1.0                sctransform_0.4.1           cowplot_1.1.1              
[70] scales_1.2.1                lubridate_1.9.3             forcats_1.0.0              
[73] stringr_1.5.0               dplyr_1.1.3                 purrr_1.0.2                
[76] readr_2.1.4                 tidyr_1.3.0                 tibble_3.2.1               
[79] ggplot2_3.4.4               tidyverse_2.0.0             SingleCellExperiment_1.20.1
[82] SummarizedExperiment_1.28.0 Biobase_2.58.0              GenomicRanges_1.50.2       
[85] GenomeInfoDb_1.34.9         IRanges_2.32.0              S4Vectors_0.36.2           
[88] BiocGenerics_0.44.0         MatrixGenerics_1.10.0       matrixStats_1.1.0          
[91] Matrix_1.6-1.1              Seurat_5.0.0                SeuratObject_5.0.0         
[94] sp_2.1-1                   

loaded via a namespace (and not attached):
  [1] graphlayouts_1.0.2            pbapply_1.7-2                
  [3] lattice_0.22-5                rJava_1.0-6                  
  [5] vctrs_0.6.4                   fastICA_1.2-3                
  [7] mgcv_1.9-0                    blob_1.2.4                   
  [9] survival_3.5-7                spatstat.data_3.0-3          
 [11] later_1.3.1                   DBI_1.1.3                    
 [13] rappdirs_0.3.3                uwot_0.1.16                  
 [15] dqrng_0.3.1                   zlibbioc_1.44.0              
 [17] htmlwidgets_1.6.2             GlobalOptions_0.1.2          
 [19] leiden_0.4.3                  tidygraph_1.2.3              
 [21] promises_1.2.1                DelayedArray_0.24.0          
 [23] graph_1.76.0                  RSpectra_0.16-1              
 [25] fs_1.6.3                      fastmatch_1.1-4              
 [27] digest_0.6.33                 png_0.1-8                    
 [29] bluster_1.8.0                 qlcMatrix_0.9.7              
 [31] scatterpie_0.2.1              pkgconfig_2.0.3              
 [33] GO.db_3.16.0                  docopt_0.7.1                 
 [35] gridBase_0.4-7                spatstat.random_3.2-1        
 [37] DelayedMatrixStats_1.20.0     iterators_1.0.14             
 [39] statnet.common_4.9.0          reticulate_1.34.0            
 [41] network_1.18.1                beeswarm_0.4.0               
 [43] bslib_0.5.1                   GetoptLong_1.0.5             
 [45] xfun_0.41                     zoo_1.8-12                   
 [47] tidyselect_1.2.0              ica_1.0-3                    
 [49] gson_0.1.0                    rtracklayer_1.58.0           
 [51] rlang_1.1.2                   jquerylib_0.1.4              
 [53] glue_1.6.2                    ggsignif_0.6.4               
 [55] httpuv_1.6.12                 BiocNeighbors_1.16.0         
 [57] annotate_1.76.0               jsonlite_1.8.7               
 [59] XVector_0.38.0                systemfonts_1.0.5            
 [61] bit_4.0.5                     mime_0.12                    
 [63] Rsamtools_2.14.0              stringi_1.7.12               
 [65] spatstat.sparse_3.0-3         scattermore_1.2              
 [67] spatstat.explore_3.2-5        yulab.utils_0.1.0            
 [69] bitops_1.0-7                  cli_3.6.1                    
 [71] maps_3.4.1.1                  RSQLite_2.3.3                
 [73] KEGGgraph_1.58.3              timechange_0.2.0             
 [75] rstudioapi_0.15.0             GenomicAlignments_1.34.1     
 [77] nlme_3.1-163                  qvalue_2.30.0                
 [79] locfit_1.5-9.8                listenv_0.9.0                
 [81] miniUI_0.1.1.1                gridGraphics_0.5-1           
 [83] leidenbase_0.1.25             ggnetwork_0.5.12             
 [85] lifecycle_1.0.4               munsell_0.5.0                
 [87] cellranger_1.1.0              coda_0.19-4                  
 [89] codetools_0.2-19              vipor_0.4.5                  
 [91] lmtest_0.9-40                 xlsxjars_0.6.1               
 [93] xtable_1.8-4                  BiocManager_1.30.22          
 [95] abind_1.4-5                   FNN_1.1.3.2                  
 [97] farver_2.1.1                  parallelly_1.36.0            
 [99] RANN_2.6.1                    aplot_0.2.2                  
[101] sparsesvd_0.2-2               ggtree_3.6.2                 
[103] BiocIO_1.8.0                  RcppAnnoy_0.0.21             
[105] goftest_1.2-3                 future.apply_1.11.0          
[107] tidytree_0.4.5                ellipsis_0.3.2               
[109] prettyunits_1.2.0             ggridges_0.5.4               
[111] fgsea_1.24.0                  slam_0.1-50                  
[113] spatstat.utils_3.1-0          htmltools_0.5.7              
[115] yaml_2.3.7                    utf8_1.2.4                   
[117] interactiveDisplayBase_1.36.0 XML_3.99-0.15                
[119] withr_2.5.2                   fitdistrplus_1.1-11          
[121] BiocParallel_1.32.6           xgboost_1.7.5.1              
[123] bit64_4.0.5                   foreach_1.5.2                
[125] ProtGenerics_1.30.0           Biostrings_2.66.0            
[127] combinat_0.0-8                progressr_0.14.0             
[129] GOSemSim_2.29.1.001           rsvd_1.0.5                   
[131] ScaledMatrix_1.6.0            memoise_2.0.1                
[133] evaluate_0.23                 geneplotter_1.76.0           
[135] tzdb_0.4.0                    curl_5.1.0                   
[137] fansi_1.0.5                   fastDummies_1.7.3            
[139] tensor_1.5                    edgeR_3.40.2                 
[141] cachem_1.0.8                  org.Hs.eg.db_3.16.0          
[143] deldir_1.0-9                  HDO.db_0.99.1                
[145] babelgene_22.9                metapod_1.6.0                
[147] rjson_0.2.21                  rstatix_0.7.2                
[149] clue_0.3-65                   tools_4.2.2                  
[151] sass_0.4.7                    car_3.1-2                    
[153] ape_5.7-1                     ggplotify_0.1.2              
[155] xml2_1.3.5                    httr_1.4.7                   
[157] rmarkdown_2.25                globals_0.16.2               
[159] R6_2.5.1                      RcppHNSW_0.5.0               
[161] progress_1.2.2                KEGGREST_1.38.0              
[163] treeio_1.22.0                 shape_1.4.6                  
[165] statmod_1.5.0                 beachmat_2.14.2              
[167] sna_2.7-1                     BiocVersion_3.16.0           
[169] BiocSingular_1.14.0           carData_3.0-5                
[171] ggfun_0.1.3                   colorspace_2.1-0             
[173] generics_0.1.3                pillar_1.9.0                 
[175] Rgraphviz_2.42.0              tweenr_2.0.2                 
[177] HSMMSingleCell_1.18.0         GenomeInfoDbData_1.2.9       
[179] plyr_1.8.9                    dotCall64_1.1-0              
[181] gtable_0.3.4                  zip_2.3.0                    
[183] restfulr_0.0.15               knitr_1.45                   
[185] shadowtext_0.1.2              fastmap_1.1.1                
[187] doParallel_1.0.17             broom_1.0.5                  
[189] filelock_1.0.2                backports_1.4.1              
[191] hms_1.1.3                     ggforce_0.4.1                
[193] Rtsne_0.16                    polyclip_1.10-6              
[195] lazyeval_0.2.2                crayon_1.5.2                 
[197] MASS_7.3-60                   sparseMatrixStats_1.10.0     
[199] svglite_2.1.2                 viridis_0.6.4                
[201] compiler_4.2.2                spatstat.geom_3.2-7 
