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
- > done?

## figure 5
figure panels
- [x] (a,b) ESCs first
- [x] (f) add dots for states on all outside x-y-axes and add label "states"
- [x] (h) try log scale
supplementary figure
- [ ] (a) add [counts per cell] to y-axis label
- [ ] (b) (low priority) change order of states
- [ ] (b) shift all legends/color bars to one side (right)
- [x] (b/c) call ECT/MES/END
- [x] (c/d) shorten labels
- [x] (e) background cell clusters one shade darker grey
- [ ] (g) axis labels
- [ ] (h) add title or make more coherent with g (add box around each germ layer?)
- [x] (h) try log scale?
- [x] (h) try to consider min counts and see if this helps

- [ ] improve volcano plot aesthetics

## figure 6
- [ ] check what are the overlapping genes
- [ ] send deseq gene lists to Peter

figure panels
Part I
- [x] (a) remove pluripotency + ESC deseq results
- [x] (a) add numbers in volcano lineplots
- [x] (a) add UMAP with compared groups
- [x] (Sa) remove GO results for pluripotency + ESCs
- [x] (b) make VENN diagram to show genes changing (1) only in RNA, (2) in RNA+K27, (3) in all 3
- [x] remake histograms for state changes and for stdev cutoff
- [ ] remake line plots too for the following sets:
      - [ ] full gene set
      - [ ] RNA + K27 changing
      - [ ] all 3 changing
      - [ ] for both stdev and state changes
      [x] filter: select only the 1st instance of change
- [x] boxplot: show filtered and unfiltered gene sets

Part II
- [x] separate sources/targets in active vs repressed networks
- [x] use barplots in supplement for pos/neg sources and extract their targets from net

part III
- [ ]  make histograms underneath the same line plots
- [x] remove pluripotency row

for Peter:
- [x] Make dotplot of state changes for diff expressed genes
- [ ] make dotplot for regulation of diff genes in other lineages
- [x] 6 - show dotplot of state changes for these genes > chromatin layer does not change as much


## manuscript:
- [ ] figure 6 caption
- [ ] figure S6 caption
- [ ] figure 6 main text
- [ ] add to methods: diff gene analysis
- [ ] add to methods: TF activity
- [ ] discussion
- [ ] Peter: check main text
- [ ] Peter: check fig6 text
- [ ] Peter: add methods sections
