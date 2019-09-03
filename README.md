# Apoptosis_Evolution
Phylogenetic and statistical analyses of apoptotic gene repertoire evolution across Metazoa.

The analytical workflow that generated results and figures in the main text focused on genetic loci from the [KEGG human apoptosis pathway](https://www.genome.jp/kegg-bin/show_pathway?hsa04210) can be reproduced by running the R Markdown script `apoptosis-KEGGHomo.Rmd`.

Further analyses on additional apoptosis markers presented in the supplementary material (GeneGlobe and the *Drosophila* KEGG pathway) can be reproduced using `apoptosis-Global.Rmd`.

All input files required by the workflows are available in the `inputs/` directory.

Note: The initial execution of either workflow will begin with a time-consuming step (several minutes) to parse the OrthoFinder output and generate an R Object to the working directory that will be read into memory quickly during subsequent executions.
