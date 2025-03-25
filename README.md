# to do and deadlines
- Peter: finish checklists/figure aesthetics of figures 4 and 5, write bullet points for text of figures 4/5 in the manuscript
- Marloes: write manuscript until figure 5, try stdev cutoff and simplify figure 6

Current version of manuscript: everything can be found [here](https://drive.google.com/drive/folders/1-6IAZ8X184rGz3GzwJrszc_t1sO4ZMYN?usp=drive_link, "folder"), link to the manuscript itself is [here](https://docs.google.com/document/d/1p5outpuw4Un-rDOf8s5t8brp0EqJR14in3SULT3gqVY/edit?usp=sharing, "manuscript")

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
- [x] (f) use ECT/MES/END instead of ectoderm/mesoderm/endoderm
- [x] (b,c) re-order: mESC first
- [x] (d) replace top heatmap for RNA + K27
- [x] (e) add annot TSS
- [x] (f) add whitespace between sections, remove cutouts
- [x] (S4) 2 sub-panels b, make text sizes etc consistent
- [x] (S4) consistently say TSS instead of promoter (e, m)
- [x] (S4e) y-axis labels aren't centred
- [x] (S4g) remake to have same order of ECT/MES/END


## figure 5
figure panels
- [ ] (a,b) ESCs first
- [ ] (f) add dots for states on all outside x-y-axes and add label "states"
- [ ] (h) try log scale
supplementary figure
- [ ] (a) add [counts per cell] to y-axis label
- [ ] (b) (low priority) change order of states
- [ ] (b) shift all legends/color bars to one side (right)
- [ ] (b/c) call ECT/MES/END
- [ ] (c/d) shorten labels
- [ ] (e) background cell clusters one shade darker grey
- [ ] (g) axis labels
- [ ] (h) add title or make more coherent with g (add box around each germ layer?)
- [ ] (h) try log scale?
- [ ] (h) try to consider min counts and see if this helps

- [ ] improve volcano plot aesthetics

## figure 6
important:
- [ ] try to use stdev as a cutoff for state changes, use the step after mESCs as starting point.
- [ ] improve selection of differentially expressed genes (but how?)
- [x] integrate decoupler for TF activity inference. > see if we can make different levels of TF activities and see which level changes
- [x] Calculate a delta transcriptome vs chromatin, to determine which one changes first
differential gene analysis - run DESEQ pseudobulks + scanpy default on the following comparisons:
- [ ] check what are the overlapping genes


figure panels
- [ ] for deseq comparisons (ESCvP, PvECT, PvEND,PvMES):
- [x] 6A - Volcano plots of diff expresed genes
- [x] S6A - GO analysis, venn diagram of overlap between ect/mes/end
- [ ] 6B - Make dotplot of state changes for diff expressed genes?
- [x] 6C - show heatmaps/lineplots: which layer changes first?
Figure out state changes!
- [x] first: generate tables with +1 and -1 values for steps, where n = step and n-(n-1) = difference between steps
- [ ] make bar plots with RNA/K4/K27 for diff gene sets, to show where the biggest difference happens (underneath line plots? supp?)
- [x] make scatterplots of diff_step RNA vs diff_step K4/K27 (supp)
- [x] calculate delta between diff_step RNA and diff_step K4/K27 and plot this for all trajectories (boxplot/stripplot? violin?)

Then: diff gene analysis for trajectory groups
- [x] S6 - show UMAP of trajectory groups,
- [x] S6 - show dotplot of top 5 genes,
- [x] S6 - show venn diagrams of overlap between mes/ect
- [ ] 6 - show dotplot of state changes for these genes > chromatin layer does not change as much
- [ ] Make TF activity plots for diff expressed genes
- [ ] single-cell TF activity to identify regulatory layer + lower layer
- [ ] which one shows state changes?
- [ ] Make heatmaps/lineplots of different levels of TF regulators > which level is tight regulated in its own/in other lineages?
- [ ]
