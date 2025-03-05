# tchic_figures
for easy sharing of jupyter notebooks to generate figures

## figure 1
- [x] all done!

## figure 2
- [x] all done!

## figure 3
- [x] all done!

## figure 4
figure panels
- [ ] (b) add scalebar values
- [ ] (e) add whitespace between sections
- [ ] (S4e) increase bar size for better visibility
- [ ] (S4l) make dots light/dark green?

## figure 5
- [x] set up anova test
- [x] determine gene states for all 3 lineages, all 3 marks
- [ ] organise genes according to where biggest change happens (which steps?)
- [x] specifying which gene groups are there? GO analysis - possibly Transcription factor activity inference (https://decoupler-py.readthedocs.io/en/latest/notebooks/dorothea.html)


figure panels
- [x] S5C: split per day and lineage
- [x] S5D: Make dotplot for epigenetic regulators. Check if it makes sense to split per celltype or per lineage/day
- [x] 5D: line plots - include all pseudobulks and plot on the same y-axis everywhere
- [x] 5E: transform into dotplot where the size is the quantity and the colour intensity is the percentage change
- [ ] Remainder for fig5: add volcano plots to supp, make a barplot of #changing genes for main
- [ ] 5D-S5E: UMAPS - find a nicer way to plot this (5D - thinner line, S5E - different colours for consistency with other figs)
- [ ] 5B: remove symbol legend - it is not used here
- [ ] 5C: change dots for symbols

## figure 6
- [x] integrate decoupler for TF activity inference. > see if we can make different levels of TF activities and see which level changes
- [ ] Calculate a delta transcriptome vs chromatin, to determine which one changes first

differential gene analysis - run DESEQ pseudobulks + scanpy default on the following comparisons:
- [x] mESC vs pluripotent
- [x] pluripotent vs 3 germ layers
- [x] endoderm vs pluripotent
- [x] ectoderm vs pluripotent
- [x] mesoderm vs pluripotent
- [x] compare different diff-exp analysis and pick the best one
- [x] Remove differentially expressed genes that are significant in >1 lineage
- [ ] check what are the overlapping genes

figure panels
- [x] remove figs 6a, S6a > they are already included in fig5
- [x] 6B - transpose: RNA/k4/K27 on y axis, lineages on x axis
- [ ] for deseq comparisons (ESCvP, PvECT, PvEND,PvMES):
- [x] 6A - Volcano plots of diff expresed genes
- [x] S6A - GO analysis, venn diagram of overlap between ect/mes/end
- [ ] 6B - Make dotplot of state changes for diff expressed genes?
- [x] 6C - show heatmaps/lineplots: which layer changes first?
Then: diff gene analysis for trajectory groups
- [ ] S6 - show UMAP of trajectory groups,
- [ ] S6 - show dotplot of top 5 genes,
- [ ] S6 - show venn diagrams of overlap between mes/ect
- [ ] 6 - show dotplot of state changes for these genes > chromatin layer does not change as much
- [ ] Make TF activity plots for diff expressed genes
- [ ] single-cell TF activity to identify regulatory layer + lower layer
- [ ] which one shows state changes?
- [ ] Make heatmaps/lineplots of different levels of TF regulators > which level is tight regulated in its own/in other lineages?
- [ ]
